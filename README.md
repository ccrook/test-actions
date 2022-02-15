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

## add commit, tag2, push --tag

```

Run echo push tag event
push tag event
GITHUB env
GITHUB_WORKSPACE=/home/runner/work/test-actions/test-actions
GITHUB_PATH=/home/runner/work/_temp/_runner_file_commands/add_path_f7ddeaf6-9283-40dd-86f2-6f743c35b034
GITHUB_ACTION=__run
GITHUB_RUN_NUMBER=3
GITHUB_REF_TYPE=tag
GITHUB_ACTIONS=true
GITHUB_SHA=9c5b1128c000c4c584ee4d77c986d5f779206f76
GITHUB_REF=refs/tags/tag2
GITHUB_REF_PROTECTED=false
GITHUB_API_URL=https://api.github.com
GITHUB_ENV=/home/runner/work/_temp/_runner_file_commands/set_env_f7ddeaf6-9283-40dd-86f2-6f743c35b034
GITHUB_EVENT_PATH=/home/runner/work/_temp/_github_workflow/event.json
GITHUB_EVENT_NAME=push
GITHUB_RUN_ID=1849237077
GITHUB_ACTOR=ccrook
GITHUB_RUN_ATTEMPT=1
GITHUB_GRAPHQL_URL=https://api.github.com/graphql
GITHUB_SERVER_URL=https://github.com
GITHUB_REF_NAME=tag2
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
* (HEAD detached at tag2)
===========================================
git tag
tag2
```

## ... followed by push

```
Run echo push branch event
push branch event
GITHUB env
GITHUB_WORKSPACE=/home/runner/work/test-actions/test-actions
GITHUB_PATH=/home/runner/work/_temp/_runner_file_commands/add_path_87c0481f-2224-41e5-adb5-4701d28c648c
GITHUB_ACTION=__run
GITHUB_RUN_NUMBER=4
GITHUB_REF_TYPE=branch
GITHUB_ACTIONS=true
GITHUB_SHA=9c5b1128c000c4c584ee4d77c986d5f779206f76
GITHUB_REF=refs/heads/main
GITHUB_REF_PROTECTED=false
GITHUB_API_URL=https://api.github.com
GITHUB_ENV=/home/runner/work/_temp/_runner_file_commands/set_env_87c0481f-2224-41e5-adb5-4701d28c648c
GITHUB_EVENT_PATH=/home/runner/work/_temp/_github_workflow/event.json
GITHUB_EVENT_NAME=push
GITHUB_RUN_ID=1849246702
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

## checkout -b branch and push

```
Run echo push branch event
push branch event
GITHUB env
GITHUB_WORKSPACE=/home/runner/work/test-actions/test-actions
GITHUB_PATH=/home/runner/work/_temp/_runner_file_commands/add_path_8143efa6-9a0b-429a-83ee-eedfa3395518
GITHUB_ACTION=__run
GITHUB_RUN_NUMBER=5
GITHUB_REF_TYPE=branch
GITHUB_ACTIONS=true
GITHUB_SHA=9c5b1128c000c4c584ee4d77c986d5f779206f76
GITHUB_REF=refs/heads/test
GITHUB_REF_PROTECTED=false
GITHUB_API_URL=https://api.github.com
GITHUB_ENV=/home/runner/work/_temp/_runner_file_commands/set_env_8143efa6-9a0b-429a-83ee-eedfa3395518
GITHUB_EVENT_PATH=/home/runner/work/_temp/_github_workflow/event.json
GITHUB_EVENT_NAME=push
GITHUB_RUN_ID=1849261679
GITHUB_ACTOR=ccrook
GITHUB_RUN_ATTEMPT=1
GITHUB_GRAPHQL_URL=https://api.github.com/graphql
GITHUB_SERVER_URL=https://github.com
GITHUB_REF_NAME=test
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
* test
===========================================
git tag
```
