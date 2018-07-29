# teracy-dev-essential

This is an extension to set up a good enough basic essential dev workstation


## How to use

Configure `workspace/teracy-dev-entry/config_default.yaml` with the following sample content:

```yaml
teracy-dev:
  extensions:
    - _id: "entry-0"
      path: workspace/teracy-dev-essential/
      require_version: ">= 0.1.0-SNAPSHOT"
      enabled: true
```