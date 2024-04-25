# modified-files-last-push-azure-repository
This script create a zip with the modified files in last push from Azure Repo.

# Usage

Usage: `python3 get-modified-files-azure-repo.py -pat $PAT -ourl $organizationURL -pn $projectName -ri $repositoryID`

Arg `-pat` it's the key of Personal Access Token.

Arg `-ourl` it's the Organization URL. It's like `https://dev.azure.com/organizationname/projectname/_git/repoid`

Arg `-pn` it's the Project Name.

Arg `-ri` it's the Repository ID. It's like repo name.

# Requirements
For the script to work, you need to download the following library: `azure-devops` using `pip install azure-devops`.
