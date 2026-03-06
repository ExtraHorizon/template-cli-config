# Template Extra Horizon CLI configuration

This repository provides the basic configuration for your Extra Horizon cluster, including:

- Default email templates and their localizations:
  - `password_reset_mail`
  - `activate_account_mail`
  - `reactivate_account_mail`
- `service-settings.json` with your service configurations.

## Prerequisites

- Extra Horizon CLI (version >= 1.13.0) installed and configured for your target cluster.
  - [Installation guide](https://docs.extrahorizon.com/cli/readme/installation)
- Verify installation and environment:
  - Run `exh --version` to check your CLI version.
  - Run `exh whoami` to confirm your CLI is targeting the correct environment.

## Usage

- Clone this repository and navigate to its folder.
- Run `exh sync` to create/update your cluster settings.
