# httpbin

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] httpbin`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree httpbin`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init httpbin
kpt live apply httpbin --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
