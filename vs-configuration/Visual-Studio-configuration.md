# Visual Studio configuration

The **vs-configuration** folder contains the exported settings from Visual Studio.

This page describes how to export or import settings.

## Table of contents

- [Exporting Visual Studio settings](#Exporting-Visual-Studio-settings)
- [Importing Visual Studio settings](#Importing-Visual-Studio-settings)

- - -

## Exporting Visual Studio settings

Click `Tools` -> `Import and Export Settings...`

![import-export-settings-menu](images/import-export-settings-menu.png)

In the `Import and Export Setting Wizard`, select `Export selected environment settings`, and then click `Next`.

![export-settings-wizard](images/export-settings-wizard.png)

Select `All Settings`, and click `Next`.

![export-settings-wizard-select-all](images/export-settings-wizard-select-all.png)

Set the file name and the directory to store the settings in this git repository, and click `Finish`.

![export-settings-wizard-finish](images/export-settings-wizard-finish.png)

## Importing Visual Studio settings

Click `Tools` -> `Import and Export Settings...`

![import-export-settings-menu](images/import-export-settings-menu.png)

In the `Import and Export Setting Wizard`, select `Import selected environment settings`, and then click `Next`.

![import-settings-wizard](images/import-settings-wizard.png)

Select `No, just import new settings, overwritting my current settings`, and clieck `Next`

![import-settings-wizard-just-import](images/import-settings-wizard-just-import.png)

Click `Browse...`, select the saved __`.vssettings`__ file and then click `Next`.

![import-settings-wizard-choose-collection](images/import-settings-wizard-choose-collection.png)

Select `All Settings`, and click `Finish`.

![import-settings-wizard-finish](images/import-settings-wizard-finish.png)
