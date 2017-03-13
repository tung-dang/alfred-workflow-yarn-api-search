## Features

Search Yarn API in [https://github.com/yarnpkg/website/contents/lang/en/docs/cli](https://github.com/yarnpkg/website/contents/lang/en/docs/cli). 

## Installation

Open terminal at source code workflow

1. Install `nvm` - node version manager in (https://github.com/creationix/nvm)
2. Enter `nvm install` to download node version which is defined in `.nvmrc` (current version is 7.2)
3. Enter `yarn install` to download node packages dependencies
4. Import workflow into Alfred tool by one of following ways: 
    1. Double-click on exported file in `exported-worfllow-file/YarnApiSearch.alfredworkflow`
    2. Copy this repository folder into Alfred custom workflow store folder, ex: `/Users/<your-user-name>/Dropbox/app_backup/Alfred.alfredpreferences/workflows`

## Usage in Alfred workflow

### Commands
- `yarn`: Search Yarn API from [https://github.com/yarnpkg/website/contents/lang/en/docs/cli](https://github.com/yarnpkg/website/contents/lang/en/docs/cli).
    + Enter to open a selected API in `https://yarnpkg.com/en/docs/cli/` website
    + CMD + Enter to open an selected API in GitHub page `https://github.com/yarnpkg/website/contents/lang/en/docs/cli`
- `yarn_clear_cache`: clear all local cache. 

## Development

- `yarn run export-wf`: zip entire project and export to `exported-workflow-file/YarnApiSearch.alfredworklow` file 