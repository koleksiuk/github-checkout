# Init
1. Clone repo
2. cd ./github-checkout
3. bundle install
4. `ln -s git-pr /usr/local/bin/git-pr`
5. `chmod +x /usr/local/bin/git-pr`

# Create Github token
1. Go to https://github.com/settings/tokens
2. Create token with repo privillege.
3. Copy token
4. Run git-pr to generate default config
5. Paste token into config key value

![image](https://cloud.githubusercontent.com/assets/5732023/20297939/6acd6250-ab13-11e6-90ae-262b6366074e.png)

# Usage

Fetch from default remote saved in git-pr-config:
`git-pr https://github.com/org/repo/pull/3`

Fetch from different remote:
`git-pr aaron https://github.com/org/repo/pull/3`
