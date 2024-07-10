## [Commit Message Format](https://github.com/angular/angular/blob/main/CONTRIBUTING.md#-commit-message-format)

```
<type>(<scope>): <short summary>
  │       │             │
  │       │             └─⫸ Summary in present tense. Not capitalized. No period at the end.
  │       │
  │       └─⫸ Commit Scope: animations|bazel|benchpress|common|compiler|compiler-cli|core|
  │                          elements|forms|http|language-service|localize|platform-browser|
  │                          platform-browser-dynamic|platform-server|router|service-worker|
  │                          upgrade|zone.js|packaging|changelog|docs-infra|migrations|
  │                          devtools
  │
  └─⫸ Commit Type: build|ci|docs|feat|fix|perf|refactor|test
```

### generate a patch
`git commit -m "ci(core): test a new"`

### generate a minor
`git commit -m "feat(changelog): test a new"`

### generate a major
`git commit -m "refactor(common): test a new"`


