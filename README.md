# AzureDevops Docker Linux Agent
Running a self-hosted Azure DevOps agent in Docker for Linux

How to run:

docker run -e AZP_URL=<Azure DevOps instance> -e AZP_TOKEN=<PAT token> -e AZP_AGENT_NAME=mydockeragent -e AZP_POOL=poolname vstoms/azuredevops-dockeragent:latest
