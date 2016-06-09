# Greek and Latin lexica


## **Contents**  

PerseusDL/lexica hosts the source files for two specific Perseus works: 

1. [The LSJ9 Perseus edition](http://www.perseus.tufts.edu/hopper/text?doc=Perseus%3atext%3a1999.04.0057)  
Henry George Liddell. Robert Scott. *A Greek-English Lexicon*. revised and augmented throughout by. Sir Henry Stuart Jones. with the assistance of. Roderick McKenzie. Oxford. Clarendon Press. 1940.

2. [The Lewis and Short Latin Dictionary](http://www.perseus.tufts.edu/hopper/text?doc=Perseus%3atext%3a1999.04.0059)  
*A Latin Dictionary*. Founded on Andrews' edition of Freund's Latin dictionary. revised, enlarged, and in great part rewritten by. Charlton T. Lewis, Ph.D. and. Charles Short, LL.D. Oxford. Clarendon Press. 1879.

## **Status**  

These two files were not included in the [Perseus source data downloads] (http://www.perseus.tufts.edu/hopper/opensource/download) as, at the time of the open source releases, it was determined that there were markup problems with the data. 
As these files were frequently requested by researchers, app developers, and other end users, and we began the practice of distributing the files on an informal ad hoc basis.  
Once we began the from the old Perseus Java Hopper open source releases to PerseusDL on GitHub, we no longer wished to maintain this special means of distribution channel, as this led to confusion about licensing, credits, and file history.
Accordingly, the files were moved to this repo. At that time, some regularization clean up was done on citations to address one area of known issues.

## **Limitations**  

* The Greek is still in beta code, not Unicode.  
* The LSJ9 file is split because of the size of the original file, which is not ideal.  
* There are known inconsistencies with tagging and related markup, as well as silent data entry errors. 
* This is not the same data as is currently hosted on the Perseus Digital Library: there may be changes in these files that are not visible on the Perseus site.  

## **Making changes and reporting errors**  

Please note that any changes made to the data hosted on GitHub will not be visible on the Perseus Digital Library. We nonetheless want to make improvements and corrections to the files, and will be using the files in this repo as the source for future Perseus work.  

If you know of an error in the Perseus edition of the LSJ9 or the Perseus edition of the Lewis & Short, we recommend the following:  

### Using GitHub  

* [Create an issue in this repository.](https://github.com/PerseusDL/lexica/issues) Please include as much information as possible, including links to Perseus that fully describe the problem. You need not do anything further.    
* After creating the issue, you may feel free to clone this repo, create a branch that references your issue number, make any corrections, and enter a pull request. In the case of extensive edits, please inform us if you wish to receive a credit line in the file for your change.  

### Via email  

* Please email the [Perseus Webmaster](mailto:perseus_webmaster@tufts.edu) and we will create an issue on your behalf. As above, please include as much information as possible, including links to Perseus that fully describe the problem. 
* In the case of extensive edits, you may request a credit line in the file.  

## **Reuse**  

These files are made available according to the following terms. Tufts University holds the overall copyright to the Perseus Digital Library; the materials therein (including all texts, translations, images, descriptions, drawings, etc.) are provided for the personal use of students, scholars, and the public.

Materials within the Perseus DL have varying copyright status: please contact the project for more information about a specific component or object. Copyright is protected by the copyright laws of the United States and the Universal Copyright Convention.

Unless otherwise indicated, all contents of this repository are licensed under a Creative Commons Attribution-ShareAlike 3.0 United States License. You must offer Perseus any modifications you make. Perseus provides credit for all accepted changes. 

We ask in all cases that you respect the work of those who funded and curated this data and preserve the header(s) of the files. If you have questions about credits for a derivative work, please create an issue or email the [Perseus Webmaster](mailto:perseus_webmaster@tufts.edu).
