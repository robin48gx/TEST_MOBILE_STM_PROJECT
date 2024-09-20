# Making an STM32 IDE project that can be restored from git and actually compiled first GO!


Create the project but do not allow to write into its default workspace.

Create a new project in your projects directory (for me ~/projects).

Force the STM32IDE to use this directory.


Now add (git add -f)

* .cproject
* .mxproject
* .project
* .settings/language.settings.xml
* .settings/org.eclipse.core.resources.prefs
* .settings/stm32cubeide.project.prefs
* TEST_MOBILE_STM_PROJECT.ioc
* STM32F446RETX_FLASH.ld
* Core/
* Drivers/


Now with all this you should be able to git restore and compile 
without being mucked about by eclipse.





