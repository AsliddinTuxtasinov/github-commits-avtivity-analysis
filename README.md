___

# GitHub commits activity analysis
___

The purpose of this project is:
- Analyzing the number of commits in time and time interval

Mode of operation:
- `get_owner_and_repoName` uses this function to separate the github profile owner and repository name.
- `get_github_commits_api_url` and with this function we get github api url.
    - this simple `https://api.github.com/repos/ {owner} / {repo} / commits` returns this api.
- `get_commiter_and_message` This function returns` json` data consisting of comitter information and commit message.

At the end of the project there will be two graphs based on the data we have:
- The first is a `line graph` describing the relationship between time and the number of commits in the time interval
- The second is a `heatmap` describing the relationship between time and the number of commits in the time interval.