# template-config-templates
Configuration templates to start from when creating configuration files for official Platform.sh templates. Includes ALL top-level properties
that are possible, comments describing the property, and a link to the docs for more information on the property. 

## Description
* Top-level properties should be in the same order as [listed in the docs](https://docs.platform.sh/create-apps/app-reference.html#top-level-properties). Not all properties are needed by all templates, so only needed ones should be included, but their order in the config file should match the order as we’ve provided in the docs.   
**REMOVE PROPERTIES AND COMMENTS THAT ARE NOT USED IN THE TEMPLATE YOU ARE CREATING**
* Configuration files should maintain consistent formatting. Spaces are required. A `.editorconfig` file has been included to set the format.
*  All calls to bash scripts should not assume the script file is executable and should instead explicitly pass the file the bash binary.
*  Exceptions should be documented in the config file.
*  Samples have been encluded and can be identified by being enclosed by `<` and `>` (e.g. `<app-name>`). These **MUST** be replaced.
*  Properties that do not contain a value (e.g. `size:`) **MUST** be completed or removed.
