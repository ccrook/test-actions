# test-actions

Trying out some stuff in github actions to get clear what events are triggered 
by some actions.

## Simple push

```
Run echo push branch event
push branch event
GITHUB env
GITHUB_WORKSPACE=/home/runner/work/test-actions/test-actions
GITHUB_PATH=/home/runner/work/_temp/_runner_file_commands/add_path_6b5fd193-efcb-42c7-a554-f502dfe72601
GITHUB_ACTION=__run
GITHUB_RUN_NUMBER=3
GITHUB_REF_TYPE=branch
GITHUB_ACTIONS=true
GITHUB_SHA=e42897bf71ddb81c5b33ec0c86ff77f8700323d2
GITHUB_REF=refs/heads/main
GITHUB_REF_PROTECTED=false
GITHUB_API_URL=https://api.github.com
GITHUB_ENV=/home/runner/work/_temp/_runner_file_commands/set_env_6b5fd193-efcb-42c7-a554-f502dfe72601
GITHUB_EVENT_PATH=/home/runner/work/_temp/_github_workflow/event.json
GITHUB_EVENT_NAME=push
GITHUB_RUN_ID=1849204845
GITHUB_ACTOR=ccrook
GITHUB_RUN_ATTEMPT=1
GITHUB_GRAPHQL_URL=https://api.github.com/graphql
GITHUB_SERVER_URL=https://github.com
GITHUB_REF_NAME=main
GITHUB_JOB=package
GITHUB_REPOSITORY=ccrook/test-actions
GITHUB_RETENTION_DAYS=90
GITHUB_ACTION_REPOSITORY=
GITHUB_BASE_REF=
GITHUB_REPOSITORY_OWNER=ccrook
GITHUB_HEAD_REF=
GITHUB_ACTION_REF=
GITHUB_WORKFLOW=Upload snap to packagecloud.io
===========================================
git branch
* main
===========================================
git tag
```

## tag and push --tag

```
Run echo push tag event
push tag event
GITHUB env
GITHUB_WORKSPACE=/home/runner/work/test-actions/test-actions
GITHUB_PATH=/home/runner/work/_temp/_runner_file_commands/add_path_a8f31b93-38ca-4b69-a0b6-d95f758b376c
GITHUB_ACTION=__run
GITHUB_RUN_NUMBER=2
GITHUB_REF_TYPE=tag
GITHUB_ACTIONS=true
GITHUB_SHA=e42897bf71ddb81c5b33ec0c86ff77f8700323d2
GITHUB_REF=refs/tags/tag
GITHUB_REF_PROTECTED=false
GITHUB_API_URL=https://api.github.com
GITHUB_ENV=/home/runner/work/_temp/_runner_file_commands/set_env_a8f31b93-38ca-4b69-a0b6-d95f758b376c
GITHUB_EVENT_PATH=/home/runner/work/_temp/_github_workflow/event.json
GITHUB_EVENT_NAME=push
GITHUB_RUN_ID=1849212023
GITHUB_ACTOR=ccrook
GITHUB_RUN_ATTEMPT=1
GITHUB_GRAPHQL_URL=https://api.github.com/graphql
GITHUB_SERVER_URL=https://github.com
GITHUB_REF_NAME=tag
GITHUB_JOB=package
GITHUB_REPOSITORY=ccrook/test-actions
GITHUB_RETENTION_DAYS=90
GITHUB_ACTION_REPOSITORY=
GITHUB_BASE_REF=
GITHUB_REPOSITORY_OWNER=ccrook
GITHUB_HEAD_REF=
GITHUB_ACTION_REF=
GITHUB_WORKFLOW=Upload snap to packagecloud.io
===========================================
git branch
* (HEAD detached at tag)
===========================================
git tag
tag
```


