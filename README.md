# Amplify Stop Jobs

The `amplify_stop_jobs` GitHub action for stopping previous Amplify deployments.

As this use the AWS SDK, credentials should be set beforehand on env variables.

## Usage

```yml
- uses: luisgreen/amplify_stop_jobs@main
  with:
    # Amplify Application ID
    # required: true
    appId: ''

    # Amplify Application branch to deploy
    # required: true
    branchName: ''

    # Region of the Amplify Application
    # required: true
    region:
```

## Sample

```yml
- uses: luisgreen/amplify_stop_jobs@main
  with:
    appId: 'asd8adsjasd9'
    branchName: 'master'
    region: 'us-west-2'
```
