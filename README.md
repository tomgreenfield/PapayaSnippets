# Papaya Snippets

This is a Sublime Text package providing snippets for Papaya templates.

## Installation

Note: you must have [Package Control](https://sublime.wbond.net/installation) installed before following these steps.

1. In Sublime Text, open the Command Palette by clicking *Tools > Command Palette…* or by pressing <kbd>Ctrl</kbd>+<kbd>⇧ Shift</kbd>+<kbd>P</kbd>.
2. Type `add repo` and select *Package Control: Add Repository*.
3. Type `https://github.com/tomgreenfield/PapayaSnippets` and press <kbd>↵ Enter</kbd>.
4. Open the Command Palette again, type `install` and select *Package Control: Install Package*.
5. Select *PapayaSnippets* from the list that appears to install the package.

## Usage

The easiest way to insert snippets is by using triggers.

For example, type `hotgraphic` then press <kbd>Tab ↹</kbd> to insert a hot graphic component.

These snippets are only programmed to trigger in XML files. To see a list of all snippets and their triggers, open the Command Palette and type `snippet`.

To turn on autocomplete for snippets in XML files, add the following line to *Preferences > Settings – User*
```
"auto_complete_selector": "source - comment, meta.tag - punctuation.definition.tag.begin, text.xml"
```

This package includes snippets for

* Animation
* Carousel (five variations)
* Drag and Stack
* Drag and Stick
* Dropdown List
* Graphical MCQ
* Hot Graphic
* Hot Text
* MCQ (five variations)
* Open Input
* Photo Story
* Structure XML
* Tabbed
* Text and Graphic
* Topic Summary
* Vertical Sliding Tabs
* Video (two variations)

Audio nodes and attributes have been omitted for succinctness. Please reference Papaya’s source if these are required.