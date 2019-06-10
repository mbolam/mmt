---
title: Start
nav: true
---

# What is Metadata?

Metadata is “a set of data that describes and gives information about other data.”

Or

“Information about information”

{% include figure.html img="lapark.jpg" alt="LA Park stands on a chair in Cleveland, Ohio" caption="LA Park stands on a chair in Cleveland, Ohio" width="100%" %}

## Types of Metadata

**Descriptive metadata** describes a resource for purposes such as discovery and identification. It can include elements such as title, abstract, author, and keywords.

{% include figure.html img="Descriptive_Metadata.JPG" alt="Example of Descriptive Metadata" caption="Date, Title, and Content are all Descriptive Metadata" width="100%" %}

**Structural metadata** indicates how compound objects are put together, for example, how pages are ordered to form chapters.

{% include figure.html img="Structural_Metadata.JPG" alt="Example of Structural Metadata" caption="Structural Metadata is typically created so digital collections systems can manage and display the files properly." width="100%" %}

**Administrative metadata** is an umbrella term for the metadata that provides information to help manage a resource, such as when and how it was created, file type and other technical information, and who can access it.
 * **Technical metadata** - For decoding and rendering files
 * **Preservation metadata** - Long-term management of files
 * **Rights metadata** - Intellectual property rights attached to content

{% include figure.html img="Technical_Metadata.JPG" alt="Example of Technical Metadata" caption="Technical Metadata is for decoding and rendering files so computers know how to interact with them." width="100%" %}

# Where to start with metadata management?
{% include figure.html img="fork-in-the-road.jpg" alt="forked road" caption="Forked Path - CC0 - https://www.publicdomainpictures.net/en/view-image.php?image=210429" width="100%" %}

The first step to managing your metadata is figuring out what type of metadata you have, where it’s going, and how to get it there.

In this section, we will learn about the following topics:
* What is metadata management?
* File types
* Extracting technical metadata (using Command Line and the File Information Toolset)
* File conversion (using Excel to export XML)
* File conversion (using MarcEdit)

## What is Metadata Management?
*"Metadata management is the administration of data that describes other data." -- [Margaret Rouse](https://whatis.techtarget.com/definition/metadata-management)*

Establishing policies and processes that ensure information can be:
* integrated
* accessed
* shared
* linked
* analyzed
* maintained

Metadata Standards define elements.
Content Standards tell you what and how to record those elements.

## Where do we start?

* What kind of metadata are we dealing with?
* What file types are we working with?
* Where is it going?

## Descriptive Metadata Scenario

Your colleague used MarcEdit to modify a collection of MARC records, and now you need to import the changes back into your catalog. The file delivered is a .mrk (mnemonic MARC file), but you know your catalog is expecting a .mrc (binary MARC File).

* What kind of metadata are we dealing with?
* What file types are we working with?
* Where is it going?

## Technical Metadata Scenario 1

You have an Excel spreadsheet (.xsl) that you have downloaded from your institutional repository containing metadata for electronic theses and dissertations (ETDs). You decided you want to add file type and file size to the metadata, so that researchers accessing the ETDs have an idea what they are about to download.

* What kind of metadata are we dealing with?
* What file types are we working with?
* Where is it going?

## Technical Metadata Scenario 2

You have xml records that you have downloaded from your digital repository containing metadata for pdf files of electronic theses and dissertations (ETDs). You decided you want to see if you can add the page counts, software used to create the files, and file type for the individual pdfs.

* What kind of metadata are we dealing with?
* What file types are we working with?
* Where is it going?

## Administrative Metadata Scenario

You have received a file with image files that you are planning to accession into your digital archive (which ingests XML). Before you make the image files available to the public, you want to record technical, preservation, and rights metadata about the files. You do not feel comfortable using command line.

* What kind of metadata are we dealing with?
* What file types are we working with?
* Where is it going?

## Programs mentioned by order of appearance:
* [MarcEdit](https://marcedit.reeset.net/)
* [Git](https://git-scm.com/)
* Command Line - Built into your computer
* [Notepad++](https://notepad-plus-plus.org/download/v7.7.html)
* [Sublime Text Editor](https://www.sublimetext.com/)
* [Linux Command Line Emulator](https://www.masswerk.at/jsuix/)
* [FITS (File Information Tool Set)](https://projects.iq.harvard.edu/fits/home)
* [DataAccessioner](http://dataaccessioner.org/)
* [DataAccessioner Metadata Transformer](http://dataaccessioner.org/da-mt.htm)
* [RightsStatements.org](http://rightsstatements.org/)
