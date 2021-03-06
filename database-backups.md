---
title: Database Backups - PaaS FAQ
---

# Database Backups
## Is my database getting backed up?
Yes! Nightly an automated backup task is performed against the database services in your Catalyze Environment. The backup files are encrypted and securely stored in cloud storage in Amazon's S3 service or Rackspace's Cloudfiles service.

## How do I check the status of a backup?
You can use the Catalyze CLI to check the status of the daily database backups. Please see the [Catalyze CLI Resource page](https://resources.catalyze.io/paas/paas-cli-reference/backup-list/) for more information about using the CLI.

## How can I get a copy of my backup?
You can download a copy of your database backup by using the `export` command in the CLI. You can read more about imports, exports, and backups by reading our [database import and export](https://resources.catalyze.io/paas/paas-faq/import-export/) FAQ article.
