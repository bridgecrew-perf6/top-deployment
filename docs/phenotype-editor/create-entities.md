---
layout: default
title: Create Entities
parent: Phenotype Editor
nav_order: 1
---

# Create Entities
In order to create new entities (phenotypes or categories) you have to navigate to a repository, where new entities shall be stored in.

On the left side of the screen you will see the tree view where all available entities of the repository are listed. If the repository is empty, the list is blank.

You can create new entities by right clicking anywhere in the tree. If you clicked on an empty space the new entity will be placed on root level. And if you clicked on a node, the new entity will be placed below this node.

A right click will always open a context menu with one ore more options, depending in the item you clicked on. In the example below a right click was performed on the category "Anthropometrics", thus displayed options to create abstract phenotypes, as well as to delete the category it selfe.

![Creating an entity](/assets/images/phenotype-editor-create.png)

After selecting on of the proposed options, a new tab will open on the right side of the editor. Fill out the fields and provide describing metadata where applicable. When you are satisfied, click on the "Save" button to persist the entered data.

# Modify Entities
To modify existing entities, just left click on the desired entity in the tree on the left side. A tab with the selected entity will be displayed on the right side. You can now midify the field values and click on "Save" to finish the modification.

# Versioning
Whenever you are creating or changing an entity, a new version is created. You can see the current version of an entity on the top of the entities tab (see screenshot below).

![Version of an entity](/assets/images/phenotype-editor-version.png)

By clicking on the clock on the top right side, all versions of the entity are displayed. You can jump to previous versions by left clicking on one of them.

![Entity history](/assets/images/phenotype-editor-history.png)

You will enter a read-only mode of the selected version. In this mode you can examine the metadata of that version and restore it by clicking on "Restore".