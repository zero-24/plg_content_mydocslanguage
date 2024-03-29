# MyDocsLanguage Plugin

This Joomla plugin automatically adds the Special:MyLanguage tag for docs.joomla.org links if needed

## Feature

This plugin runs onContentBeforeSave and makes sure that all links to docs.joomla.org contain the Special:MyLanguage tag for translation.

## Configuration

### Initial setup the plugin

- [Download the latest version of the plugin](https://github.com/zero-24/plg_content_mydocslanguage/releases/latest)
- Install the plugin using `Upload & Install`
- Enable the plugin `Content - MyDocsLanguage` from the plugin manager

Now the inital setup is completed.

### Update Server

Please note that my update server only supports the latest version running the latest version of Joomla and atleast PHP 7.0.
Any other plugin version I may have added to the download section don't get updates using the update server.

## Issues / Pull Requests

You have found an Issue, have a question or you would like to suggest changes regarding this extension?
[Open an issue in this repo](https://github.com/zero-24/plg_content_mydocslanguage/issues/new) or submit a pull request with the proposed changes.

## Translations

You want to translate this extension to your own language? Check out the [Crowdin Page for my Extensions](https://joomla.crowdin.com/zero-24) for more details. Feel free to [open an issue here](https://github.com/zero-24/plg_content_mydocslanguage/issues/new) on any question that comes up.

## Joomla! Extensions Directory (JED)

This plugin can also been found in the Joomla! Extensions Directory: [MyDocsLanguage by zero24](https://extensions.joomla.org/extension/mydocslanguage/)

## Release steps

- `build/build.sh`
- `git commit -am 'prepare release MyDocsLanguage 1.0.x'`
- `git tag -s '1.0.x' -m 'MyDocsLanguage 1.0.x'`
- `git push origin --tags`
- create the release on GitHub
- `git push origin master`

## Crowdin

### Upload new strings

`crowdin upload sources`

### Download translations

`crowdin download --skip-untranslated-files --ignore-match`
