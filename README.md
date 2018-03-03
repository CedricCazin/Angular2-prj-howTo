# Dev environment

* Create a GitHub Repo
* Protected master branch https://github.com/.../settings/branches
* Create a dev branch based on master
* Clone the dev branch locally

* Install IDE

* Install NodeJs (+ npm) https://nodejs.org/en/

# Angular2 App

* Command: npm install -g @angular/cli https://github.com/angular/angular-cli
* Command: go the the parent folder of our clone branch
* Command: ng new <project name>
* Commit (and push)

# prevent bad commit

* http://githooks.com/

* https://github.com/typicode/husky
* command: npm install husky@next --save-dev

```json
// package.json
{
  "husky": {
    "hooks": {
      "pre-commit": "<command>",
      "pre-push": "<command>",
      "...": "..."
    }
  }
}
```

* https://palantir.github.io/tslint/
* https://github.com/prettier/prettier
* https://github.com/marionebl/commitlint
* https://seesparkbox.com/foundry/semantic_commit_messages

# uning github hooks

* https://github.com/marketplace

# CI

* https://github.com/marketplace/category/continuous-integration

* https://travis-ci.org/
* https://circleci.com/
* https://jenkins.io/
* https://www.jetbrains.com/teamcity/
* https://codeship.com/
* https://www.atlassian.com/software/bamboo

# code coverage

* https://coveralls.io/
* https://github.com/marketplace/coveralls

# code quality

* https://app.codacy.com/
* https://github.com/marketplace/codacy

# code vulnerability

* https://snyk.io
* https://github.com/marketplace/snyk

# style

* https://sass-lang.com/
* http://lesscss.org/


