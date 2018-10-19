# Swissup scripts

### Code2Vendor

This script helps migrate from old SwissUpLabs modules (installed
in `app/code` folder) to the new format — composer-based installation.

 1. Get the new zip archive(s) for the module(s) you'd like to update
 2. Upload archives into the `<magento_root>/swissup` folder
 3. Run the command below from `<magento_root>` folder

    ```bash
    curl -s https://raw.githubusercontent.com/swissup/scripts/master/code2vendor | bash
    # or
    wget https://raw.githubusercontent.com/swissup/scripts/master/code2vendor -qO - | bash
    ```
