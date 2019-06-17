---
title: OpenRefine
nav: true
---

# OpenRefine

{% include figure.html img="logo-openrefine-550.png" alt="OpenRefine Logo" caption="OpenRefine - A free, open source, powerful tool for working with messy data" width="100%" %}

## OpenRefine - What is it?

* Formally Google Refine
* It is an AMAZING cleaning tool!
* Similar to spreadsheet applications, like Microsoft Excel, but behaves more like a database!
* Available in 14 languages!

## Using OpenRefine

### Creating a New Project

You can create a new project with data from:
* Your computer
* A Web Address (URLs)
* Your clipboard
* Google Data

### Inside OpenRefine

#### Text vs. Numbers

Similar to how Excel allows you to choose the format of the data inside a cell and defaults to “General”, OpenRefine lets you choose the format of the data as well but defaults to “Text.”

This can mess up your metadata clean up. So it’s important to make sure that the format the program is using to read your data actually matches your data type.

#### Split Columns

If data in a column needs to be split into multiple columns, and the parts are separated by a common separator (say a comma, or a space), you can use that separator to divide up the pieces into their own columns.

#### Undo/Redo

OpenRefine tracks all of the changes you make in your project, so it is easy to navigate back to where you want to fix your mistake and go from there.

WARNING: Once you go back and make another change from that point, you will lose everything you did after that point originally.

#### Trim Whitespace

What is whitespace?
* Blank spaces before (leading) or after (trailing) a string of text.

Whitespace is very difficult to catch with the naked eye, especially in large datasets, but can impact how your system reads data.

#### Edit cells

There are many ways other than just trimming leading/trailing whitespace to edit cell values in OpenRefine.

#### Add Column Based on This Column

If you want to create a new column, drawing from data in another column use this feature.

You can use simple or complex language to create a new column.
(Read: You can use GREL or Python script here!)

#### Faceting

Faceting groups together every identical instance of cell values in a column.

#### Clustering

Clustering uses natural language processing to group like terms together for you to edit.

It will help you catch mistakes like “nevada” vs. “Nevada” while also letting you decide preferred forms of terms (maybe you want to prefer the plural for subjects i.e. “teachers” over “teacher”).

#### Filtering

Allows you to filter rows or records by keyword searching a column.

### Generating Scripts from OpenRefine

Let’s say you know you have to do the same changes on multiple projects over and over again.

OpenRefine allows you to extract a script of all of the changes you have made to the project.

When you create a new project, you can then apply that script and it will automatically run all of the changes on the new project.

### Saving and Exporting

#### Exporting Data

When you are done with your project, and you have decided that you only need to extract the results of your cleanup project, you will export your data.

#### Importing and Exporting Projects

When would you export a project?
* You would like to save and send the project to a collaborator
* You want to save all of your work for the sake of documentation
Exporting a project will save the data and all of the tasks you have performed on the data in one file (.tar or .tar.gz file)

You can import .tar or .tar.gz project files at the home screen, where you created a new project.
