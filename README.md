Block content machine name
--------

Block content machine name adds machine_name field for block_content block
content type. Which is used to define the specific block template and class name
for that specific block.

Block content machine name module requires [![machine_name_widget](https://www.drupal.org/project/machine_name_widget)]
module.

After successfully configured the module you'll have additional template suggestions
for FE.
- block--block_content--[MACHINE_NAME].html.twig

i.e.
IF you have block_content created for copyright block and you have created
machine_name for that block as copyright. then you will have template suggestion
- block--block_content--copyright.html.twig

The block will also have two additional unique classes:
- block-content--MACHINE_NAME
- block-type-block-content

Setup
--------

Enable the module and you will have the machine name field. you have to update
the machine name manually (for now) for all the block_content if you are using
the module in existing site.

Author/Maintainer
-----------------

- [Mitesh Patel](https://www.drupal.org/u/miteshmap)