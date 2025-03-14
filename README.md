# Translate Groups.io

Help translate Groups.io into your language.

## Request a language

If the language you want to translate doesn't exist as a PO file yet, submit an issue so that we can create a template for you to get started.

## Staying up-to-date

Merge conflicts are nasty. They happen when you're translating an outdated version of the template, part of which might have been translated by someone else. To prevent this, try to fork our repository right before you translate.

If you want to do multiple translation pull requests, before doing work each time, use the "Compare" UI on your own fork to pull in all the newest changes from `groupsio:main` first by creating a pull request on your own repository and merge it in yourself, so that your own copy is up-to-update.

## Submit changes

To translate, [fork this repo](https://guides.github.com/activities/forking/) and edit the PO file of your language. After that, [submit a pull request](https://guides.github.com/activities/forking/).

Note that you don't have to clone your fork to make the edits; you can do everything on GitHub's web UI. Simply open a file in your own forked repo and click on the pencil icon to start editing.

## Translating

The translations use the Gettext PO file format. The original template, containing the English version of the site, is `en.pot`.

When you fix a translation, remove the `#, fuzzy` line above it. This signals that the translation has been fixed.

A good translation editor to use is [POEdit](https://poedit.net/).

## Existing languages

Here is a table of language code to language name, in alphabetical order, along with their status.

| Language code | Language name | Native name | Status |
| --- | --- | --- | :---: |
| `ar` | Arabic | العربية | 🚧 |
| `de` | German | Deutsch | 🚧 |
| `en` (default) | English | English | ✅ |
| `es` | Spanish | Español | 🚧 |
| `fr` | French | Français | 🚧 |
| `it` | Italian | Italiano | 🚧 |
| `nl` | Dutch | Nederlands | 🚧 |
| `pt-BR` | Brazilian Portuguese | Português do Brasil | 🚧 |
| `pt-PT` | European Portuguese | Português | 🚧 |
| `uk` | Ukrainian | Українська | 🚧 |
| `zh-CN` | Simplified Chinese | 简体中文 | 🚧 |