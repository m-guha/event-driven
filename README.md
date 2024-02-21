# Event-driven workflows with Prefect


## GitHub issue filed -> webhook -> deployment run 

We created a webhook in the UI to get data when a GitHub issue is filed in this repo. 
The event's information will be passed into a the flow's paramaters in `flow.py` through an automation that was created via the UI and runs a deployment as its action.

## Use the API to interact with automations

### Use the Prefect Client convenience method to create an automation

Creating an automation is the only functionality exposed via the PrefecClient at the moment.
