
# Docker Installation Script for Ubuntu

This shell script automates the installation process of Docker on Ubuntu systems.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/manyal12345/docker_installation_in_ubuntu_server.git
   
2. Navigate to the directory containing the script:
   ```bash
   cd docker_installation_in_ubuntu_server
  
3. Make the script executable:
   ```bash
   chmod 777 dock_ubuntu.sh

4. Execute the script:
   ```bash
   ./dock_ubuntu.sh

Follow the on-screen instructions.

# Description
This script performs the following tasks:

- Updates the apt package index.
- Installs packages required for apt to use repositories over HTTPS.
- Adds Docker's official GPG key.
- Adds Docker repository to apt sources.
- Installs Docker Community Edition (docker-ce).

# Requirements
- Ubuntu operating system
- Internet connection
  
## License

This script is licensed under the [MIT License](LICENSE).
