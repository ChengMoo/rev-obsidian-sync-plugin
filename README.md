# Rev Obsidian Sync Plugin

Plugin to be used alongside https://github.com/acheong08/rev-obsidian-sync/

## Installation
- `cd /path/to/vault/.obsidian`
- `mkdir -p plugins/custom-sync-plugin && cd plugins/custom-sync-plugin`
- `wget https://github.com/acheong08/rev-obsidian-sync-plugin/raw/master/main.js https://github.com/acheong08/rev-obsidian-sync-plugin/raw/master/manifest.json`

## Usage:
- Go to community plugins
- Enable the plugin
- Configure the API URL in settings after setting up your sync server
- Go to core plugins
- Enable sync
- Connect to remote vault

## FAQ
> Why is this not part of the community plugins?

A: This cuts into their profits since they charge $10/month for sync

> What platforms does this work on?

All

> I can't find the .obsidian directory

It's hidden. You can configure your file app to show hidden files or use a terminal. For IOS, you might need to plug it into a computer, go to "Documents on iPhone", then `Obsidian/<your vault name>/.obsidian`. Then follow the installation instructions.

> How to I get a remote vault onto multiple devices?

You can make multiple local vaults which sync to the same remote vault. Simply create a new vault, repeat the instructions, and connect to the same remote vault.

> Privacy?

The plugin is dead simple. No data collected. You can even run your sync server on the local network without access to the internet.

## Credits
[@tuxmachine](https://github.com/tuxmachine) for the idea 
