# get-files-last-push-or-last-pullrequest-azure-repository
This script create a zip with the modified files in last push/pull request from Azure Repo or create a txt file that contains deleted files from last push/pull request from Azure Repo.

# Usage

Usage: `python3 get-modified-files-azure-repo.py -pat $PAT -ourl $organizationURL -pn $projectName -ri $repositoryID`

Arg `-pat` it's the key of Personal Access Token. Required.

Arg `-ourl` it's the Organization URL. It's like `https://dev.azure.com/organizationname/projectname/_git/repoid`. Required.

Arg `-pn` it's the Project Name. Required.

Arg `-ri` it's the Repository ID. It's like repo name. Required.

Arg `-pr` indicates whether the files will be searched in a pull request. Optional.

# Requirements
For the script to work, you need to download the following library: `azure-devops` using `pip install azure-devops`.
