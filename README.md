# Noel's grab bag of Azure CLI goodies

This repo contains things that I like or find useful, offered up with absolutely zero guarantee that it will work for anyone else

## Azure Active Directory

* `az ad sp create-for-ralph`: Create a Service Principal and store the password in Key Vault ([thread](https://twitter.com/acanthamoeba/status/988185653199360002))

## Log Analytics

* `az loganalytics workspace create`
* `az loganalytics workspace delete`
* `az loganalytics workspace show`
* `az loganalytics workspace update`
* `az loganalytics workspace keys list`

## Virtual Machines

* `az vm auto-shutdown enable`
* `az vm auto-shutdown disable`
* `az vm auto-shutdown show`

## Development

Use the `scripts/hack.sh` script

```bash
source scripts/hack.sh
```

or, do it the long way with your directories

```bash
export AZURE_EXTENSION_DIR=~/.azure/devcliextensions
pip install --upgrade --target ~/.azure/devcliextensions/noelbundick ~/code/noelbundick/azure-cli-extension-noelbundick/src/noelbundick
```