# 1. Migrate version control manager in Cloud

Date: 2023-05-20

## Status

Accepted

## Context

DevOps team and infrastructure resources (Cloud).

## Decision

We will migrate our local GitLab and all data to the Сloud. We will set up a new GitLab instance, create back-up the current instance, transfer the files, and restore the backup to the new service. Check and test the new environment.

## Consequences

Cloud GitLab is ready-to-use.
There may be differences in Gitlab instances settings. At one point there will be 2 identical gitlab instances and we should use the new one as soon as possible so as not to lose new updates.
