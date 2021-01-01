# AROS [Russian]

## Objectives / Цели

The main objective of this project is to development of support for the russian language on Amiga and updating language files in already installed AROS. Here are the files for supporting the russian language in the AROS.

Основная цель этого проекта - развитие поддержки русского языка на Amiga и обновление языковых файлов в уже установленных AROS. Репозиторий содержит файлы для поддержки русского языка в AROS.

## Well-known problems / Хорошо известные проблемы

### Libs/muimaster.catalog

muimaster.library has been localized only in January 2020, so you will have to wait until it appears in distros to that point to have the muimaster.catalog working.

Библиотека muimaster.library была локализована только в январе 2020 года, поэтому вам придется подождать, пока она обновится в дистрибутивах для того, чтобы muimaster.catalog заработал.

### Prefs/Appearance.catalog
### System/installaros.catalog

Similarly to muimaster.catalog

Аналогично muimaster.catalog

### System/sysmon.catalog

This utility has changed so many times (concerned with SMP support) that catalog descriptor was messed up. In fact, no catalog for this application can work the same across all distros: translated messages will go to unrelated elements of the window. So I made the decisions to remove sysmon.catalog until the application stabilizes.

Эта утилита менялась так много раз (в связи с поддержкой SMP), что дескриптор каталога был испорчен. Фактически, ни один локализационный каталог для этого приложения не может работать одинаково во всех дистрибутивах: переведённые сообщения попадут в не имеющие к ним отношения элементы окна. Поэтому я принял решение удалить sysmon.catalog, до тех пор пока приложение не стабилизируется.

## Also, look at here / См. также

* https://aros.sourceforge.io
* https://github.com/aros-development-team/AROS
* https://github.com/aros-translation-team/translations
<!-- language: lang-none -->
            ______ ______              ______ ______ 
     ______|:: .__|:: .__|_____ ______|:: ___|:: ___|______ _____ 
    |: ,   |:  |  |:  |  |:  ,_|:  ,__|:___  |:___  |:  -  |:  ,_|
    |__|___|______|______|___|   _____|______|______|______|___|
