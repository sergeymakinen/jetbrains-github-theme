# JetBrains GitHub 3 theme

JetBrains' IDEA/PhpStorm/PyCharm/DataGrip/… theme inspired by the GitHub syntax highlighting style (version 3).

Tested with:

* Bash
* CSS
* Go
* HTML
* INI
* JavaScript
* JSON
* PHP
* Python
* XML

## How to install

> Shameless rip-off from [this document](https://intellij-support.jetbrains.com/hc/en-us/articles/206544519-Directories-used-by-the-IDE-to-store-settings-caches-plugins-and-logs).

1. Copy [GitHub 3.icls](GitHub%203.icls) to your preferences directory:

    #### Windows Vista, 7, 8, 10:
    
    ```
    <SYSTEM DRIVE>\Users\<USER ACCOUNT NAME>\.<PRODUCT><VERSION>\colors
    ```
    
    #### Windows XP:
    
    ```
    <SYSTEM DRIVE>\Documents and Settings\<USER ACCOUNT NAME>\.<PRODUCT><VERSION>\colors
    ```
    
    #### Linux and other Unix systems
    
    Product directory starting with dot can be found in your user home directory, the pattern is:
    
    ```
    ~/.<PRODUCT><VERSION>/colors
    ```
     
    #### macOS
    
    ```
    ~/Library/Preferences/<PRODUCT><VERSION>/colors
    ```
    
    #### `PRODUCT` values
    
    * `IntelliJIdea` (IntelliJ IDEA Ultimate Edition)
    * `IdeaIC` (IntelliJ IDEA Community Edition)
    * `RubyMine`
    * `WebIde` (PhpStorm versions before 2016.1 and WebStorm before 7.0 use this common directory)
    * `PhpStorm` (PhpStorm starting from 2016.1 version)
    * `WebStorm` (WebStorm starting from 7.0 version)
    * `PyCharm`
    * `AppCode`
    * `CLion`
    * `DataGrip`
    * `AndroidStudio`

2. Restart your product.

3. Go to Preferences, choose Editor > Color Scheme and select `GitHub 3`.

## Screenshots

![PHP in PhpStorm](Screenshot%20-%20PhpStorm.png)

![Python in PyCharm](Screenshot%20-%20PyCharm.png)
