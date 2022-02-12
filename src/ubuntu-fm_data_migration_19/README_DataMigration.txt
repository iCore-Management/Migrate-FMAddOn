A. Contents of the download file

   * README_DataMigration.txt
   Description: Installation instructions of the Claris FileMaker data migration tool. (This file)

   * FMDataMigration
   Description: Binary executable of the FileMaker data migration tool. Use this program if the target system has FileMaker Server installed.

   * filemaker-data-migration_VN.BN_amd64.deb
   Description: Installation package of the FileMaker data migration tool, where VN and BN denote the release version and build numbers.

B. Run the following commands to install the FileMaker data migration tool if FileMaker Server is not installed on the target system, where $PACKAGE_PATH denotes the path of the installation package.

   $ sudo apt update
   $ sudo apt install $PACKAGE_PATH/filemaker-data-migration_VN.BN_amd64.deb

NOTE: Due to restrictions of the system package manager, permissible combinations of FileMaker Server and FileMaker data migration tool installation include:
   1. A full installation of FileMaker Server with the stand-alone FMDataMigration executable, which can be put anywhere in the system.
   2. A full installation of FileMaker data migration tool on a stand-alone machine WITHOUT FileMaker Server installed, where the executable is installed in /opt/FileMaker/bin/FMDataMigration and a symbolic link is added to /usr/bin/FMDataMigration.
