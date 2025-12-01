# hibernate-ide-codestyles

This repository contains the IDE settings for Eclipse and Intellij IDEA.

> [!WARNING]
> This repository only contains the historical code styles.
> Most of the Hibernate projects evolved to leverage automatic code formatting
> and checks.
> 
> Please refer to the specific project repository and its contributing guide
> for up-to-date information:
> * https://github.com/hibernate/hibernate-orm
> * https://github.com/hibernate/hibernate-validator
> * https://github.com/hibernate/hibernate-search
> * https://github.com/hibernate/hibernate-reactive
> * https://github.com/hibernate/hibernate-tools

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

Importing code styles can also be done through the UI.

To do so:

 * go to `IntelliJ IDEA` -> `Preferences` on a Mac or `File` -> `Settings` on Windows
 * then to `Editor` -> `Code Style` -> `Java` and click `Manage`
 * in the `Code Style Schemas` dialog, press `Import` and add the provided XML file
 * after that, select the imported schema from the `Schema` dropdown

## Importing in Eclipse

In Eclipse, you import the three provided files from within the UI.
Open menu `Window` -> `Preferences`; then open section `Java` -> `Code Style`.
You'll see three sub sections:
 - Clean Up
 - Code Templates
 - Formatter

Each of these has a separate `Import` button; import the provided xml files
and then mark them as active in the current profile.
