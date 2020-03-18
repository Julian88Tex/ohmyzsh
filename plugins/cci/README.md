# cci plugin

The plugin adds several aliases for common [cci](https://https://cumulusci.readthedocs.io/) commands.

To use it, add `cci` to the plugins array of your zshrc file:
```
plugins=(... cci)
```

## Aliases

| Alias | Command                          | Description   |
|-------|----------------------------------|---------------|
| ccfi  | `cci flow info`                  |
| ccfl  | `cci flow list`                  |
| ccfr  | `cci flow run`                   |
| ccob  | `cci org browser`                |
| ccoc  | `cci org connect`                |
| ccod  | `cci org default`                |
| ccoi  | `cci org info`                   |
| ccol  | `cci org list`                   |
| ccor  | `cci org remove`                 |
| ccos  | `cci org scratch`                |
| ccsd  | `cci org scratch_delete`         |
| ccrm  | `cci org scratch_delete`         |
| ccpc  | `cci project cd`                 |
| ccpd  | `cci project dependencies`       |
| ccpi  | `cci project info`               |
| ccpl  | `cci project list`               |
| ccsc  | `cci service connect`            |
| ccsl  | `cci service list`               |
| ccss  | `cci service show`               |
| cctd  | `cci task doc`                   |
| ccti  | `cci task info`                  |
| cctl  | `cci task list`                  |
| cctr  | `cci task run`                   |
| ccupg | `pip install --upgrade cumulusci`|
| cccd  | `pyenv activate cci-dev`         |
| pycd  | `pyenv activate cci-dev`         |