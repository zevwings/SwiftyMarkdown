fastlane documentation
----

# Installation

Make sure you have the latest version of the Xcode command line tools installed:

```sh
xcode-select --install
```

For _fastlane_ installation instructions, see [Installing _fastlane_](https://docs.fastlane.tools/#installing-fastlane)

# Available Actions

## iOS

### ios patch

```sh
[bundle exec] fastlane ios patch
```

This does the following: 



- Runs the unit tests

- Ensures Cocoapods compatibility

- Bumps the patch version

### ios minor

```sh
[bundle exec] fastlane ios minor
```

This does the following: 



- Runs the unit tests

- Ensures Cocoapods compatibility

- Bumps the minor version

### ios major

```sh
[bundle exec] fastlane ios major
```

This does the following: 



- Runs the unit tests

- Ensures Cocoapods compatibility

- Bumps the major version

### ios test

```sh
[bundle exec] fastlane ios test
```



### ios submit_pod

```sh
[bundle exec] fastlane ios submit_pod
```

Push the repo to remote and submits the Pod to the given spec repository. Do this after running update to run tests, bump versions, and commit changes.

----

This README.md is auto-generated and will be re-generated every time [_fastlane_](https://fastlane.tools) is run.

More information about _fastlane_ can be found on [fastlane.tools](https://fastlane.tools).

The documentation of _fastlane_ can be found on [docs.fastlane.tools](https://docs.fastlane.tools).
