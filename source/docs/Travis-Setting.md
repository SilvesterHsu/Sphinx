# Travis Setting
## Outline
* sign in Travis
* manage Travis settings

## Sign in Travis
You can register for an account on [Travis](https://travis-ci.org/) and bind to GitHub.
![Travis-Setting-01](img/Travis-Setting-01.jpg)

## Manage Travis Settings
1. Create a new repository by click `+` to choose the repository we pushed before.
![Travis-Setting-02](img/Travis-Setting-02.jpg)

2. After that we need to set this repository by entering into the settings section.
![Travis-Setting-03](img/Travis-Setting-03.jpg)

3. There are a few environmen variables we need to add.
![Travis-Setting-04](img/Travis-Setting-04.jpg)

`CUSTOM_DOMAIN` is optional, `GIT_EMAIL` is your GitHub email, `GIT_NAME` is your GitHub name
, `GITHUB_TOKEN` is the GitHub token we generated before.

Remember to disable the `Display value in build log` at the bottom
![Travis-Setting-05](img/Travis-Setting-05.jpg)
