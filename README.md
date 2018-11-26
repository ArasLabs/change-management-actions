# Change Management Actions

This package contains convenience actions for PRs and ECRs. It provides menu choices to quickly convert a PR to an ECR or NCR and an ECR to an ECN. It also provides menu choices on Parts and Documents to add them to a new PR or ECR.

## History

This project and the following release notes have been migrated from the old Aras Projects page. 

Release | Notes
--------|--------
[v4](https://github.com/ArasLabs/change-management-actions/releases/tag/v4) | Tested on 11.0 SP15. Addition of PR to NCR action.
[v3](https://github.com/ArasLabs/change-management-actions/releases/tag/v3) | Release for Aras Innovator 11.0 SP10. Actions are included for PRs and ECRs, but other actions were removed as they are now part of standard product.
[v2](https://github.com/ArasLabs/change-management-actions/releases/tag/v2) | Release for Aras Innovator 9.1 Actions are included for PRs, ECR, ECNs, ECOs and MCOs. The administrator should hide those that won't be used.
[v1.2](https://github.com/ArasLabs/change-management-actions/releases/tag/v1.2) | Fix naming conflict with the Multi-Level BOM Tools package
[v1.1](https://github.com/ArasLabs/change-management-actions/releases/tag/v1.1) | Fix for import errors
[v1](https://github.com/ArasLabs/change-management-actions/releases/tag/v1) | Initial Release

#### Supported Aras Versions

Project | Aras
--------|------
[v4](https://github.com/ArasLabs/change-management-actions/releases/tag/v4) | 11.0 SP 11-15 
[v3](https://github.com/ArasLabs/change-management-actions/releases/tag/v3) | 11.0 SP0-SP10
[v2](https://github.com/ArasLabs/change-management-actions/releases/tag/v2) | 9.1
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
4. QMS application must be installed for PR to NCR functionality

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
