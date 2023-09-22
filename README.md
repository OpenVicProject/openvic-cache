## Workflow Configuration

### Action Inputs

| Input Name        | Description                       | Type      | Default                                   | Required |
|-------------------|-----------------------------------|-----------|-------------------------------------------|----------|
| `cache-name`      | The base name of the cache.       | `string`  | `${{github.job}}`                         | No       |
| `base-branch`     | The base branch for the cache.    | `string`  | `master`                                  | No       |
| `scons-cache`     | The path of the scons cache.      | `string`  | `${{github.workspace}}/.scons-cache/`     | No       |
