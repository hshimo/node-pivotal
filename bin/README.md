# pivotal-cli

 Command line tool for node-pivotal

 This is not for production use.


## How to use

 just execute the command

```
% ./pivotal-cli
```

## How to setup default values

Setup shell variables.

```
export token="12345678a1bc12abc3abc1234567abc8"
export username="username"
export password="password"
export project_id="123456"
export story_id="12345678"
export member_id=""
```


## Commands

- quit
- help
- env
- getToken
- useToken
- getActivities
- getProjectActivities
- getProjects

## Requirement

- shell-mode
- prompt
- optimist

## TODO

- write unit test
- test commands
- show help
- command option validation
- change shell mode command names?
- format command's output

### implement shell mode commands

- addProject
- getMemberships
- getMembership
- addMembership
- removeMembership
- getIterations
- getDoneIterations
- getCurrentIteration
- getBacklogIterations
- getCurrentBacklogIterations
- getStories
- getStory
- addStory
- addStoryAttachment
- addStoryComment
- updateStory
- moveStory
- removeStory
- deliverAllFinishedStories
- getTasks
- getTask
- addTask
- updateTask
- removeTask

- setUsername
- removeUsername
- setPassword
- removePassword
- setToken
- removeToken
