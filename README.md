# Change Management Actions

This package contains convenience actions for PRs and ECRs. It provides menu choices to quickly convert a PR to an ECR or an ECR to an ECN. It also provides menu choices on Parts and Documents to add them to a new PR or ECR.

## History

This project and the following release notes have been migrated from the old Aras Projects page. Unlike community projects that have been migrated and archived, this project will be updated for compatibility with the latest release of Aras Innovator.

Release | Notes
--------|--------
[v1.2](https://github.com/ArasLabs/change-management-actions/releases/tag/v1.2) | Fix naming conflict with the Multi-Level BOM Tools package
[v1.1](https://github.com/ArasLabs/change-management-actions/releases/tag/v1.1) | Fix for import errors
[v1](https://github.com/ArasLabs/change-management-actions/releases/tag/v1) | Initial Release

#### Supported Aras Versions

Project | Aras
--------|------
[v1.2](https://github.com/ArasLabs/change-management-actions/releases/tag/v1.2) | 9.0.1
[v1.1](https://github.com/ArasLabs/change-management-actions/releases/tag/v1.1) | 9.0.1
[v1](https://github.com/ArasLabs/change-management-actions/releases/tag/v1) | 9.0.1

## Installation

#### Important!
**Always back up your code tree and database before applying an import package or code tree patch!**

### Pre-requisites

1. Aras Innovator installed
2. Aras Package Import tool
3. **change-management-actions** import packages

### Install Steps

1. Backup your database and store the BAK file in a safe place.
2. Open up the Aras Package Import tool.
3. Enter your login credentials and click **Login**
  * _Note: You must login as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
  * Optional: Enter a description in the Description field.
5. Enter the path to your local `..\change-management-actions\Import\imports.mf` file in the Manifest File field.
6. Select all packages in the Available for Import field.
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import tool.

## Usage

![Screenshot of change management actions](./Screenshots/CM%20Actions.jpg)

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

For more information on contributing to this project, another Aras Labs project, or any Aras Community project, shoot us an email at araslabs@aras.com.

## Credits

Created by Rob McAveney, Aras Corporation.

## License

Aras Labs projects are published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
