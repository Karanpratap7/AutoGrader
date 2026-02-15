# High Level Architecture

```
Pull Request Created/Updated  
        ↓
GitHub Action Workflow Triggered
        ↓
Python Script Runs
        ↓
Fetch PR Diff via GitHub API
        ↓
Send Diff to OpenAI API
        ↓
Receive Structured Feedback
        ↓
Post Comment on PR
```