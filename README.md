## Getting Started

This is a sample of how to upload files to  [DigitalOcean Spaces](https://cloud.digitalocean.com/spaces) using deploys a Functions and Static Site component on App Platform. 

**Note: Following these steps may result in charges for the use of DigitalOcean services.**

### Requirements

* You need a DigitalOcean account. If you don't already have one, you can sign up at https://cloud.digitalocean.com/registrations/new.

### Spaces Bucket
* [Create a new Space](https://cloud.digitalocean.com/spaces/new?) or use an existing one. 
* [Spaces API Keys](https://cloud.digitalocean.com/account/api/tokens)

When deploying the App, these environment variables are required in the Functions component. 

```
SPACES_ENDPOINT
SPACES_NAME
SPACES_KEY
SPACES_SECRET
```

# Deploying the App

Click this button to deploy the app to the DigitalOcean App Platform. If you are not logged in, you will be prompted to log in with your DigitalOcean account.

[![Deploy to DigitalOcean](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/digitalocean/sample-functions-file-upload/tree/main)

Using this button disables the ability to automatically re-deploy your app when pushing to a branch or tag in your repository as you are using this repo directly.
