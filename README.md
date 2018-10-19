# Swissup scripts

### Install

Easy way to install the module downloaded from the one of our sites.

> Additionally, this script helps to migrate from old SwissUpLabs modules
> (installed in `app/code` folder) to the new format — composer-based
> installation.

 1. Get the new zip archive(s) for the module(s) you'd like to update
 2. Upload archives into the `<magento_root>/swissup` folder
 3. Run the command below from `<magento_root>` folder

    ```bash
    curl -s https://raw.githubusercontent.com/swissup/scripts/master/install | bash
    # or
    wget https://raw.githubusercontent.com/swissup/scripts/master/install -qO - | bash
    ```
