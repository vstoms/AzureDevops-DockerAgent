# AzureDevops-DockerAgent
Running a self-hosted Azure DevOps agent in Docker

How to run:
docker run -e AZP_URL=<Azure DevOps instance> -e AZP_TOKEN=<PAT token> -e AZP_AGENT_NAME=mydockeragent vstoms/azuredevops-dockeragent:latest
