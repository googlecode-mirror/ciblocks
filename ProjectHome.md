This project is a block system for CodeIgniter (php framework)

CIBlocks is very lightweight, easy to install and use.

It's used to make regions with blocks in your web application.

For example you need a region where you can place your left sidebar blocks.

You put the following code to the general view, the view that holds the main theme.

<?php echo isset($blocks['left']) ? $blocks['left'] : ""; ?>

Then the only thing you have to do is to build some blocks from the CIBlocks controller.

Simple as that.

Features:

- The block can have or not a title
- Display per role (anonymous, registered, moderators) if there are any
- Display per page, you can select in which pages the block will or will not be displayed
- Weight, you can set the order of the blocks
- Regions, you can create unlimited groups of regions
- Supports HTML and PHP by evaluating
- Easy block styling as every block and region has it's own id


Ask for MORE!


Changelog

(17/12/08):

Changed region.php view preg\_replace to preg\_match because it didn't work under php 4


(8/12/08):

Start of the project

Building the base system

Added library, module, view and controller

Changed this page