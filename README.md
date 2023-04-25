# Packit configuration updates

This repo contains a Python script `packit_config_checker.py` and related migration files 
that automate obtaining, checking and updating of Packit configurations of active Packit users.

The script provides 3 commands (see particular command's `--help` for more info):

1. `download-configs` - to download the configs of the repos that used Packit Service in the past year
2. `list-affected` - to list the projects affected by particular migration
 3. `migrate` - to update the config and create PR

For more background, see 
[the research document](https://github.com/packit/research/blob/main/automatic-config-updates/README.md).