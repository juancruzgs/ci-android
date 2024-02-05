# CI Android

![development workflow](https://github.com/juancruzgs/ci-android/actions/workflows/development.yml/badge.svg)

Sample Android project to showcase the integration with different Continous Integration platforms.

### Supported CI platforms
- Github Actions

### Workflows

It currently runs the following steps when creating a pull request or a commit on **development**.
1. Run debug unit tests
2. Run linter (detekt)
3. Create debug APK
4. Upload the artifacts from the previous steps
