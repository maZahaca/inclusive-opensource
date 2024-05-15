# inclusive-opensource
This is a template repo to initiate a new GitHub repository with the most popular features for better collaboration.

First of all, I'm so sorry that [template variables feature](https://github.com/orgs/community/discussions/5336) is not implemented on GitHub yet. Second, let's do it!

## Features
- Issue template forms
- Labelling project issues based on contributed directories
- Changelog pipeline
- [suggest more](https://github.com/maZahaca/inclusive-opensource/discussions/1)

## Implementation
1. We set all configuration files via `.inclusiveopensource/` folder.
2. Define 1 pipeline, which will be run when the folder has any changes
   1. This pipeline generates new workflow/issue template files based on the values defined in the configuration folder
   2. All changes are raised as a pull request in the repository and can be manually adjusted before merge

## Resources
- https://opensource.guide/
- https://github.blog/2023-11-08-the-state-of-open-source-and-ai/
- https://octoverse.github.com/2022/state-of-open-source
