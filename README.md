Navigate to [Microsoft HLS Home repo](https://github.com/microsoft/hls-home)

## Contents

Outline the file contents of the repository. It helps users navigate the codebase, build configuration and any related assets.

| File/folder       | Description                                |
|-------------------|--------------------------------------------|
| `src`             | Sample source code.                        |
| `.gitignore`      | Define what to ignore at commit time.      |
| `CHANGELOG.md`    | List of changes to the sample.             |
| `CONTRIBUTING.md` | Guidelines for contributing to the sample. |
| `README.md`       | This README file.                          |
| `LICENSE`         | The license for the sample.                |

## Starter Kit Challenge

This "starter kit" is intended to provide monitoring of the CDC guidance page. Created for the COVID crisis, this could be adapted to monitor other parts of the CDC website.
- CDC URL here: https://www.cdc.gov/coronavirus/2019-ncov/communication/guidance-list.html?Sort=Date%3A%3Adesc

1. Healthcare organization wants to be notified of changes to CDC guidance.
2. Healthcare organization wants to establish filters to include or exclude certain guidance changes.

## Expected Skills & Technologies

- HTML screen-scraping?
- Web API - build a service that crawls CDC site 
- database - probably prefer "no-SQL" type of data store, but up to the team to store and/or cache data points and/or metadata
- Web Hook - means of subscribing to and consuming changes detected by Web API
- hosting & deployment - provide easy means of deploying to Azure
- writing - documentation on how to provision, configure, and consume

## Contributing

This project welcomes contributions and suggestions.  Most contributions require you to agree to a
Contributor License Agreement (CLA) declaring that you have the right to, and actually do, grant us
the rights to use your contribution. For details, visit https://cla.opensource.microsoft.com.

When you submit a pull request, a CLA bot will automatically determine whether you need to provide
a CLA and decorate the PR appropriately (e.g., status check, comment). Simply follow the instructions
provided by the bot. You will only need to do this once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or
contact [opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.
