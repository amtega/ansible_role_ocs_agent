# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.5.1] - 2022-04-22
### Added
- Manage ipmitool dependency. Uninstall by default. Related to ansible/playbooks/linux#85

### Fixed
- Fixed config dir and birary routes. Related to ansible/roles/amtega.vmware_provisioner#53

## [1.5.0] - 2022-04-04
- Refactored to install from epel repository. Related to ansible/playbooks/linux#78

## [1.4.0] - 2022-02-22
### Changed
- Refactored powertools stuff.

### Fixed
- Adapted for CentOS derived distros. Related to ansible/main#263

## [1.3.1] - 2022-02-15
### Fixed
- Fixed missing variable.

## [1.3.0] - 2022-02-03
### Changed
- Supported distros. Related to ansible/main#178
