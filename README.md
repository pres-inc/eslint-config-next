# eslint-config-next

## Installation

1. Run the install command
   ```bash
   $ npm install -D @pres-inc/eslint-config-next
   ```
2. You also need to install peer dependencies
   ```bash
   $ npm install -D @pres-inc/eslint-config-js @pres-inc/eslint-config-react @pres-inc/eslint-config-typescript eslint eslint-config-next
   ```

## Usage

`.eslintrc.yaml`

```yaml
extends:
  - "@pres-inc/eslint-config-next"
```

You may need to use `--resolve-plugins-relative-to` option:

```bash
$ yarn eslint --resolve-plugins-relative-to .
```
