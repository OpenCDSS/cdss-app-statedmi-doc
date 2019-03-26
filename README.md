# cdss-app-statedmi-doc #

This repository contains the legacy Word/PDF StateDMI software documentation,
including user manual, training materials, and a variety of developer resources.

**This documentation is being phased out in favor of new Markdown/MkDocs documentation.
In general, do not edit this documentation and only use as a reference when migrating into the newer format.**
See the
[StateDMI Developer Documentation](https://github.com/OpenCDSS/cdss-app-statedmi-doc-dev) and
[StateDMI User Documentation](https://github.com/OpenCDSS/cdss-app-statedmi-doc-user) repositories.

See the following online resources:

* [Colorado's Decision Support Systems (CDSS)](http://cdss.state.co.us)
* [OpenCDSS](http://learn.openwaterfoundation.org/cdss-website-opencdss/) - currently
hosted on Open Water Foundation website while OpenCDSS server is configured
* [StateDMI Developer Documentation](http://learn.openwaterfoundation.org/cdss-app-statedmi-doc-dev/) - currently
hosted on Open Water Foundation website while OpenCDSS server is configured
* [StateDMI User Documentation](http://learn.openwaterfoundation.org/cdss-app-statedmi-doc-user/) - currently
hosted on Open Water Foundation website while OpenCDSS server is configured

See the following sections in this page:

* [Repository Folder Structure](#repository-folder-structure)
* [Repository Dependencies](#repository-dependencies)
* [Development Environment Folder Structure](#development-environment-folder-structure)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)

-----

## Repository Folder Structure ##

The following are the main folders and files in this repository, listed alphabetically.
See also the [Development Environment Folder Structure](#development-environment-folder-structure)
for overall folder structure recommendations.

```
cdss-app-statedmi-doc/        StateDMI Word/PDF documentation files.
  .git/                       Git repository folder (DO NOT MODIFY THIS except with Git tools).
  .gitattributes              Git configuration file for repository.
  .gitignore                  Git configuration file for repository.
  doc/                        Documentation files.
    CDSSOverview/             CDSS overview.
    DeveloperManual/          Developer resources.
    Training/                 Training lessons.
    UserManual/               User manual files.
  LICENSE.txt                 StateDMI documentation license file.
  README.md                   This file.
```

## Repository Dependencies ##

Repository dependencies fall into two categories as indicated below.

### StateDMI Documentation Repository Dependencies ###

None, although more information may be added here later about PDF merge utilities.
Such utilities are no longer needed given that this documentation is being migrated to online format.

### Repositories that Depend on This Repository ###

|**Repository**|**Description**|
|-------------------------------------------------------------------------------------|----------------------------------------|
|[`cdss-app-statedmi-main`](https://github.com/OpenCDSS/cdss-app-statedmi-main)|Main StateDMI software repository/project.|

## Development Environment Folder Structure ##

See the [StateDMI main software repository](https://github.com/OpenCDSS/cdss-app-statedmi-main)
for information about the StateDMI development environment folder structure.

## Contributing ##

Contributions to this project can be submitted using the following options:

1. StateDMI software developers with commit privileges can write to this repository
as per normal OpenCDSS development protocols.
2. Post an issue on GitHub with suggested change.  Provide information using the issue template.
3. Fork the repository, make changes, and do a pull request.

See also the [OpenCDSS / StateDMI protocols](http://learn.openwaterfoundation.org/cdss-website-opencdss/statedmi/statedmi/).

## License ##

This documentation is released under the Creative Commons Attribution 4.0 International License (CC BY 4.0).  See the [LICENSE.md](LICENSE.md) file.

The StateDMI software is released under the GPL v3 license.
This legacy documentation has not been updated to reflect this,
given that a new version of the documentation is available.

## Contact ##

See the [OpenCDSS StateDMI information for product contacts](http://learn.openwaterfoundation.org/cdss-website-opencdss/statedmi/statedmi/#product-leadership).
