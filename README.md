# Repository for SynclerScrapers providers

These providers are combined into one, easy to use repository and are for use within Syncler.

## FAQ

> #### How do I install the provider(s)?

Method 1: set-repository-url [_**Recommended**_]
1. Go to https://beta.syncler.net/provision
2. Copy and paste this provision script: `set-provider-repository-url https://raw.githubusercontent.com/SynclerScrapers/repository.synclerscrapers/main/repo.json`
3. Click "Generate the provisioned installer" and download and install it.
4. Open Syncler Installer, switch to BETA branch and wait for download and auto-install to complete
5. Success! Provisioning is indicated with a toast message (popup notification)
6. Open Syncler > Settings > Provider packages and browse the "My repository" section

_Note: If provisioning did not happen automatically, go back to Syncler Installer and press the "Provision" button._

Method 2: Entering package URL
1. Choose "Install Express source provider packages".
2. Enter the code on the website given to you in the popup.
3. Copy and paste the package URL `https://raw.githubusercontent.com/SynclerScrapers/repository.synclerscrapers/main/express/openscraper.json` when asked.
4. Press next on the website
5. Success! Press Done in the app and you are done.

> #### How do I manage my provider(s)?

In Syncler's settings, you will find the provider packages menu. Within this category you can install/uninstall packages, enable/disable automatic provider updates and manually check for provider updates.

With added repositories from Method 1, you can one-click install any package within them. **Beware of installing too many packages, Syncler may not work properly.**

## Documentation

> Further documentation on provision scripts: https://support.syncler.net/en/develop/provision-script

## License

Licensed under The GPL License.
