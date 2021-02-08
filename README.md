# dependency-validation-pre-commit

# Flutter Dependency Validation `pre-commit` hook

[`pre-commit`](https://pre-commit.com) hook for running Flutter Dependency Validation Hook

Add the following in your `.pre-commit-config.yaml`:
```yaml
- repo: https://github.com/guid-empty/flutter-dependency-validation-pre-commit
  rev: "master"
  hooks:
    - id: flutter-dependency-validation
```

## How to configure your Flutter project

* open pubspec.yaml file
* find dev_dependency section
* add dependency_validator package dependency as it's shown on https://pub.dev/packages/dependency_validator

```
dev_dependencies:
  dependency_validator: ^semver from pub.dev
```


## Acknowledgements and other hooks useful to be used in your Flutter projects

[Workiva] (https://github.com/Workiva) for creating the dependency_validator package, see more details here:

https://github.com/Workiva/dependency_validator

https://pub.dev/packages/dependency_validator

[Charles Crete](https://github.com/Cretezy/) for creating `flutter-format-pre-commit`

[Dariusz Łuksza](https://github.com/dluksza) for creating `flutter-analyze-pre-commit` 
https://github.com/dluksza/flutter-analyze-pre-commit/
