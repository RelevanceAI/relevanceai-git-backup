# github-template
Github template for backing up all your tools and agents.

1. Create a github repo.
2. Copy the `backup.yml` file to `.github/workflows/backup.yml`. You can edit the cron settings to change the backup schedule to be more/less frequent.
3. Copy the `backup.py` file to the root of your repo.
4. Go to Relevance AI and create API Key.
5. Go to your github repo and set the repository secret of `RELEVANCE_AUTH_TOKEN` and `RELEVANCE_REGION`.
6. Push the changes to your repo and the backup will start running.