# Manifest for Privileges

This is an external app manifest file commonly used in Jamf for configuring the [Privileges app from SAP](https://github.com/SAP/macOS-enterprise-privileges).

The project contains two different manifests. One works, and one does not.

`corp.privileges.json` located in the root of this repository is the current working version. It does not support configuring Privileges for central logging due to Jamf not supporting recursive configurables.

`unsupported/corp.privileges.json` is a version designed for a future where Jamf supports nested configurables. Do not use this, it will not work as of July 2023.

If you have any improvements, you are more than welcome to put in a PR once they are working. Currently I am not able to test functionality as I no longer have access to a Jamf Pro tenant.