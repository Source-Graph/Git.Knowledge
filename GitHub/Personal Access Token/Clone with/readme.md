sch: https://www.google.com/search?q=github+clone+with+personal+access+token

Guide:
- https://www.shanebart.com/clone-repo-using-token/

# source:
- https://gist.github.com/magickatt/07ff02068f8cd2e4e558f20358b2082c
```
export GITHUB_USER=magickatt
export GITHUB_TOKEN=secret
export GITHUB_REPOSITORY=magickatt/ContainerisingLegacyApplicationsTalk
git clone https://${GITHUB_USER}:${GITHUB_TOKEN}@github.com/${GITHUB_REPOSITORY}
```

# Using a personal access token on the command line
Doc: https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#using-a-personal-access-token-on-the-command-line
