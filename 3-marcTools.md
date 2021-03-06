---
title: MARC Tools
nav: true
---

# Metadata Management Tools for MARC

## MARC Cleanup and Batch Editing Scenario

You have a multiple batches of MARC records (in binary format) extracted from your ILS. It represents a collection of children's board books. There are a number of updates and changes needed to improve the records before they are added back into the catalog.

* What kind of metadata are we dealing with?
* What file types are we working with?
* Where is it going?

## MarcEdit - What is it?

{% include figure.html img="marcedit_home.jpg" alt="MarcEdit Home Screen" caption="MarcEdit -- Your Complete Free MARC Editing Utility" width="100%" %}

Terry Reese created MarcEdit in 1999 while at Oregon State University. Terry is now the Head of Digital Initiatives at Ohio State University.

MarcEdit operates on Windows, Linux, and MacOS.

## Using MarcEdit Tools

### Batch Process MARC Records

* **Batch Process MARC Records** allows you to run one of the MARC Tools (for file conversion) on multiple files at a time.

{% include figure.html img="marcedit_batch.jpg" alt="MarcEdit Batch Process Screen" caption="MarcEdit Batch Process Screen" width="70%" %}

### MARC Join

* **MARC Join** is one of many MARC Processing Tools in MarcEdit. It allows users to join a set of files into a single file.

{% include figure.html img="marcedit_join.jpg" alt="MarcEdit Join Screen" caption="MarcEdit Join Screen" width="70%" %}

### Record Depulication

* **Record Deduplication** can find duplicate records across multiple files or within a single file.

{% include figure.html img="marcedit_dedup.JPG" alt="MarcEdit Deduplication Screen" caption="MarcEdit Deduplication Screen" width="70%" %}

### Add/Delete Field

* **Add/Delete Field** allows you to add or delete an entire field across all records in the MarcEdit Mnemonic file (.mrk).

{% include figure.html img="marcedit_add_delete.jpg" alt="MarcEdit Add/Delete Screen" caption="MarcEdit Add/Delete Screen" width="70%" %}

### Special Undo

* **Special Undo** allows you to undo ONE and ONLY ONE bulk action. The standard undo does not allow you to interact with batch actions.

### MARCValidator

* In OCLC Connexion, you are able to validate MARC records against MARC21 Bibliographic Rules – you can also do this in MarcEdit using **MARCValidator**.

{% include figure.html img="marcedit_validator.jpg" alt="MarcEdit Validator Screen" caption="MarcEdit Validator Screen" width="70%" %}

### Generate Call Numbers

* **Generate Call Numbers** utilizes OCLC’s Classification web service to generate either Dewey Decimal or Library of Congress Headings.

{% include figure.html img="marcedit_callnumber.jpg" alt="MarcEdit Call Number Screen" caption="MarcEdit Call Number Screen" width="70%" %}

### Generate Cutter Numbers

* **Generate Cutters** uses order of preference to generate Cutters automatically.

{% include figure.html img="marcedit_cutter.jpg" alt="MarcEdit Generate Cutter Numbers Screen" caption="MarcEdit Generate Cutter Numbers Screen" width="70%" %}

## Regular Expressions in MarcEdit

### The power of Find & Replace

If there isn’t a feature to do exactly what you are trying to do, you may be able to use Find & Replace to get the job done. This can be very powerful when used with Regular Expressions.

**Warnings:**
* **Less is More** - Make sure you are **isolating** the elements you want to change.
* **Work from Complicated to Simple** - Always replace the longest, most detailed string **FIRST**, then work backwards.

{% include figure.html img="3010_original.png" alt="Example of bad find and replace from the Dungeons & Dragons book Encyclopedia Magica, Volume 1." caption="Example of Bad Find and Replace: Entry for the Cube of Frost Resistance. Dungeons & Dragons  Encyclopedia Magica, Volume 1. 1994." width="70%" %}

[Sample MARC ETD Data](/data/marctools/ETD_Metadata.mrk)

### Regular Expressions

A **Regular Expression** or **regex** is a text string that describes a pattern that a regex engine uses in order to find text (or positions) in a body of text, typically for the purposes of validating, finding, replacing or splitting.

{% include figure.html img="marcedit_buildnew.jpg" alt="MarcEdit Build New Fields Screen" caption="MarcEdit Build New Fields Screen Showing Example Regex" width="70%" %}

## Exporting and Importing Tab Delimited Text

The **Delimited Text Translator** maps fields in a delimited text file into a MARCXML or MARC file.

**Export Tab Delimited Records** maps fields in a .mrc or .mrk file, and exports into a .txt (Tab Delimited) file.

## pymarc - What is it?

```
_|_|_|    _|    _|  _|_|_|  _|_|      _|_|_|  _|  _|_|    _|_|_|
_|    _|  _|    _|  _|    _|    _|  _|    _|  _|_|      _|
_|    _|  _|    _|  _|    _|    _|  _|    _|  _|        _|
_|_|_|      _|_|_|  _|    _|    _|    _|_|_|  _|          _|_|_|
_|              _|
_|          _|_|
```

### Python + MARC = PyMARC/pymarc

[PyMARC or pymarc](https://pypi.org/project/pymarc/) is a Python library developed in 2005 by Gabriel Farrell, Mark Matienzo, and Ed Summers.

“It was mostly designed to be an emergency eject seat, for getting your data assets out of MARC and into some kind of saner representation. However over the years it has been used to create and modify MARC records, since despite repeated calls for it to die as a format, MARC seems to be living quite happily as a zombie.”

### When to use pymarc

* You are frequently converting MARC files to Tab Delimited Files.
* You need to parse MARC elements out and add data or pull apart MARC elements beyond fields/subfields.
* You want to customize a template for tab delimited exports with specific delimited file requirements.

### pymarc Tutorials

Two-part (free) webinar series “Introduction to Python and PyMARC” - [Part 1](http://www.ala.org/alcts/confevents/upcoming/webinar/101817); [Part 2](http://www.ala.org/alcts/confevents/upcoming/webinar/102517) - with activities by Lauren Magnuson, Head of Collection Management and Technical Services at California State University San Marcos and Development Coordinator for the PALNI Library consortium.
