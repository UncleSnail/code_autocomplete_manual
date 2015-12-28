*****************
Addon Development
*****************

Code Autocomplete comes with several tools which simplify addon development
inside of Blender a lot. Blender itself is not good for it, because it is hard to
manage multiple files and to register everything correctly. This addon tries to
overcome these difficulties by providing templates and operators to quickly create,
extend and export code.

The Addon Development tools only work with addons which have their own folders
(not single-file addons, these can be created without Code Autocomplete).

Before you can start coding you have to choose which addon you want to work on.
You can either work on an existing one or create a completely new one.
To select one that already exist you can write its name in the corresponding field
or click on the eyedropper next to it to get a list of all installed multi-file addons.

.. image:: images/addon_development/panel_empty.png

.. image:: images/addon_development/list_of_installed_addons.png


Creating a new Addon
====================

To start a new addon you have to write the name it should have in the text box.
Code Autocomplete will check automatically if the addon already exists and decides
wether it should give you the options to create a new one or not. It will also
not allow you to use addon names that may become problematic later.

If you inserted a 'incorrect' addon name, a button to correct this name appears.
Basically this operator replaces spaces with underscores and makes everything
lower case (this is not the name the end user will see, and changing it later is easy).

.. image:: images/addon_development/incorrect_addon_name.png

.. image:: images/addon_development/corrected_addon_name.png