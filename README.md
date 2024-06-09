### About the function
This function is designed to be used within the Slack Workflow Builder. The function reads a slack message and then makes an API call to OpenAI to create a incident summary. The incident summary is then saved as an output variable. 

### Dependencies
1. The user will need to generate an OpenAI API token through https://platform.openai.com/api-keys

https://github.com/peoplesj/ai-summarize-function/assets/105441105/806a1021-84ca-418a-a589-b74e1a93de65

### Modify the function
Once the Slack CLI is installed and authorized within a Slack Workspace. Clone this repo to your local system using the Slack CLI command
```
slack create ai-summary-function --template <this github url>
```

