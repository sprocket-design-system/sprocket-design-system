# Project Setup

We want to only allow pushes to to repo that match conventional commits. Use the regex `^(?P<type>build|chore|ci|docs|feat|fix|perf|refactor|revert|style|test|¯\\_\(ツ\)_/¯)(?P<scope>\(\w+\))?(?P<breaking>!)?(?P<subject>:\s.*)?|^(?P<merge>Merge \w+)`

NX has been set up to use standalone config files. Meaning that each project will contain a project.json file opposed to a less maintainable workspace projects.json file. The command to do this was `nx g @nrwl/workspace:convert-to-nx-project --all`
