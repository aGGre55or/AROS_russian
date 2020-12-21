# AROS [Russian]

## What's here?

Here are the files for supporting the Russian language in the AROS. The main objective of this project is to updating language files in already installed AROS.

## Well-known problems

### Libs/muimaster.catalog

muimaster.library has been localized only in January 2020, so you will have to wait until it appears in distros to that point to have the muimaster.catalog working.

### System/installaros.catalog

Similarly to muimaster.catalog

### System/sysmon.catalog

This utility has changed so many times (concerned with SMP support) that catalog descriptor was messed up. In fact, no catalog for this application can work the same across all distros: translated messages will go to unrelated elements of the window. So I made the decisions to remove sysmon.catalog until the application stabilizes.

## Also, look at here

* https://aros.sourceforge.io
* https://github.com/aros-development-team/AROS
* https://github.com/aros-translation-team/translations
<!-- language: lang-none -->
            ______ ______              ______ ______ 
     ______|:: .__|:: .__|_____ ______|:: ___|:: ___|______ _____ 
    |: ,   |:  |  |:  |  |:  ,_|:  ,__|:___  |:___  |:  -  |:  ,_|
    |__|___|______|______|___|   _____|______|______|______|___|
