# FMDataMigration
This application automates the FM Data Migration Tool for a repository devops process.

# Getting Started
This application uses AppleScript and is only compatable with FileMaker Pro for the Mac.

![image](/docs/resources/Interface.png)

# Installation
1. Download the [Installer](/Install.zip).
2. Add /Migrate to the FileMaker AddOn folder: /Library/Application Support/FileMaker/Extensions/AddonModules

# Demo
1. Download the [Demo](/test/Demo.zip).
2. Open Test Data -DEV.
3. Click on the iCore Migrate button.
4. Select "Test Data -SOURCE.fmp12" as the source file.
5. Select "Test Data -DEV Clone.fmp12" as the clone file.
6. Select a destination folder for the migrated file.
7. Select "Install Migration Tool" and select the FM Data Migration Tool. The data migration tool is available through the Claris FileMaker Developer Subscription (FDS).
8. Select "Migrate Data". A new file will be created with the models, views, and controls from the Development Clone and the data from the Source file.
