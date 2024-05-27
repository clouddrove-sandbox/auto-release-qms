# auto-release-qms


Once you commit your code with message convention, for example, feat: add some features, it will trigger the semantic-release. Default convention message with angular preset included:

**git commit -m "fix: bug fixed" -> bug fixes: patch release**

**git commit -m "feat: added new feature" -> feature: minor release**

**git commit -m "breaking change: Updated entries" -> break change: major release**

1. Once you push your code it will run GitHub Action and release your project.

2. Then it will create Release and CHANGELOG.md in the project.

