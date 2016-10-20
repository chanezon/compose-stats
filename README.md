# docker-compose stats

This scripts searches public Github repositories for docker-compose files and determines the usage of each directives in docker-compose files.

Before using it, get a Github API OAuth token at [https://github.com/settings/tokens](https://github.com/settings/tokens) and set the OAUTH_TOKEN environment variable with it. There is rate limiting for the GitHub API, but you can run it on smaller files with 30 lines of input, one every minute.

You need jq installed on your machine.

`export OAUTH_TOKEN=xxx`

`Usage:
./stats composeref.txt`
