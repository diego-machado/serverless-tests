#A collection of projects from a serverless study

##01-envs
A cron job executed every minute do get a random commit message from http://whatthecommit.com/

- aws-sdk
- axios
- cheerio
- env-var

How to test:

```bash
sls deploy

sls invoke -f commit-message-scheduler --logger

sls invoke local -f commit-message-scheduler --logger
```
