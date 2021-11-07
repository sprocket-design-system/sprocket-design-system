# Project Setup

We want to only allow pushes to to repo that match conventional commits. Use the regex `^(?P<type>build|chore|ci|docs|feat|fix|perf|refactor|revert|style|test|¯\\_\(ツ\)_/¯)(?P<scope>\(\w+\))?(?P<breaking>!)?(?P<subject>:\s.*)?|^(?P<merge>Merge \w+)`
