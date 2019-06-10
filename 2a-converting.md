---
title: Converting
nav: false
---

# When to Convert Files

We convert files when a use case requires the metadata to be in another form. For example, if we start out with an Excel file of Dublin Core metadata that we need to convert to MARC and upload into our ILS or LSP, there are about 4 different file format conversions we will need to undertake in order to get from start to finish.

Tools like MarcEdit, pymarc, OpenRefine, and XSLT can be used to convert metadata files.

When converting files back and forth, remember to implement smart file naming conventions:
* Be consistent
* Be descriptive
* Be distinctive

## Converting between .mrk and .mrc using MarcEdit

{% include figure.html img="marcedit_home.jpg" alt="MarcEdit home screen" caption="MarcEdit home screen" width="100%" %}

### Converting .mrk to .mrc

1. Open Marc Tools
1. Select MarcMaker
1. **Open:** Select the metadata collection to be converted (.mrk)
1. **Save as:** Provide a location and filename for the converted file (.mrc)

### Converting .mrc to .mrk
1. Open Marc Tools
1. Select MarcBreaker
1. **Open:** Select the metadata collection to be converted (.mrc)
1. **Save as:** Provide a location and filename for the converted file (.mrk)

Other file conversions in MarcEdit:
* MARCXML
* JSON
* Dublin Core
* MODS
* FGDC
