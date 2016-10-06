# hibernate-ide-codestyles

This repository contains the IDE settings for Eclipse and Intellij IDEA.

Import these in your IDE if you plan to make changes to the Hibernate source code,
so that you can follow consistent formatting and style conventions with every
other contributor.

## Importing in IDEA

Copy the `hibernate_orm.xml` style file in your IDEA configuration.

The path on OSX is:
 - ~/Library/Preferences/IdeaIC14/codestyles/

On Linux it is:
 - ~/.IntelliJIdea14/config/codestyles

On Windows:
 - <User home>\.IntelliJIdea14\config\codestyles

Also importing of profile can be done through the UI as well. To do it go to
 `IntelliJ IDEA` -> `Preferences` on a Mac or `File` -> `Settings` on Windows,
 then to `Editor` -> `Code Style` -> `Java` and click `Manage`.
 In `Code Style Schemas` dialog press import and add the provided xml.
 After that select imported schema from `Schema` dropdown.

## Importing in Eclipse

In Eclipse, you import the three provided files from within the UI.
Open menu `Window` -> `Preferences`; then open section `Java` -> `Code Style`.
You'll see three sub sections:
 - Clean Up
 - Code Templates
 - Formatter

Each of these has a separate `Import` button; import the provided xml files
and then mark them as active in the current profile.
