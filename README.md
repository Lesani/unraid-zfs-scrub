# Unraid ZFS Scrub Script

This script automates the process of performing scrubs on ZFS pools on Unraid servers. It includes functionality to exclude specific pools and integrates with Unraid's notification system to inform users about the status and outcome of the scrubs.

## Features

- **Automatic Scrubbing:** Automatically initiates scrubs on all ZFS pools.
- **Exclusion List:** Allows specifying which pools to exclude from scrubbing.
- **Notifications:** Utilizes Unraid's notification system to send alerts about scrub operations. Notifications can be customized by severity level.

## Prerequisites

- An Unraid server with ZFS support installed and configured.
- [User Scripts plugin](https://forums.unraid.net/topic/48286-plugin-ca-user-scripts/) must be installed on your Unraid server to run this script as part of scheduled tasks or on demand.

## License

This script is provided under the GNU General Public License v3.0. See the `LICENSE` file in the repository for the full license text.
