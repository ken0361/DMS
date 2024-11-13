# DMS
A Document Management System (DMS) developed using Tkinter, featuring capabilities for tagging, label-based search, and fuzzy search to efficiently organize and retrieve documents.

![DMS](images/DMS.png)

## Introduction

The Document Management System (DMS) provides the following features:
1. Tree structure display of folder contents
2. Tagging files with labels
3. Tag search
4. Fuzzy search

### Route

Default button - Select the default path, which will become the path used each time the DMS is opened.  
Path button - Select a path.  
Extend button - Expand the tree structure.  
Close button - Collapse the tree structure.

### Tagging

![DEMO2](images/update_tag.gif)

Right-click on a file to open the tag window, where you can choose to add or remove tags. The tree structure will automatically display the tags associated with the file.


### Tag Search & Fuzzy Search

![DEMO1](images/search_and_open.gif)

#### Tag Search

DMS will perform a tag search based on the text entered in the input field. Files that match the search will be highlighted in the tree structure.

#### Fuzzy Search

DMS also provides a fuzzy search feature, which will search the filenames and contents of all files under the path, highlighting the files that match the search criteria. The fuzzy search supports `regular expressions`.

#### Open file

Double-clicking a file with the left mouse button will open the file in the default manner.

