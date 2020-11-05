# Specimen Builder: Print Template
This Indesign template is a template generated as part of the [Type Specimens](https://typespecimens.xyz) project. Here is the [digital counterpart](https://github.com/markboulton/specimen-builder). 

The design of the template is based on insights from a considerable amount of user research into what is a usable and useful format. This can be summarised as:

* Print specimens are used as reference or cataloging detailed information.
* The back story or design reference for the typeface is of less importance than detail of the glyphs and language support.
* Users expect paragraphs and headings set in every weight or style at multiple sizes.
* Users also expect a complete list of all glyphs.  


## Generating the list of glyphs
To generate a list of glyphs for your font, you will need a license for [Glyphs](https://glyphsapp.com) and [this Glyphs script](https://github.com/Tosche/Glyphs-Scripts) from Tosche Omagari

### Installing the script
Put the scripts into the Scripts folder which appears when you choose `Open Scripts Folder` from the `Scripts` menu. After installation, either choose `Refresh Script Menu (Option+Shift+Command+Y)` or restart the application.

For some scripts, you will also need to install Tal Leming's Vanilla and may need to install other modules. In Glyphs 2, you can install them from `Preferences > Addons`.

### Generating the text file for importing into Indesign
To generate the list of categorised glyphs:

1. Open the font file in Glyphs.
2. From the top menu, choose `Scripts > Export Indesign tagged Text with All Glyphs`. This loads a diaglogue box with the following options:

* Choose weight or style file to export from the dropdown.
* Choose if the export file should be tab-separated, unicode characters first, or to break up the unicode characters into categories.

3. Click `Export`
4. This will generate a text file in the same folder as the font file you opened with Glyphs.

### Importing the text file into Indesign
1. The font needs to be loaded in Indesign.
2. In the specimen template, delete all content in the `Glyphset` text boxes.
3. From the main menu, go to `File > Place` and choose the exported text file.