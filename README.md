## README for wordlist-medicalterms-en


###Overview

    Description:        dictionary of English medical terms
    Terms:              98119
    Author:             Glutanimate (https://github.com/Glutanimate)
    Sources:            - OpenMedSpel by e-MedTools 
                          <http://www.e-medtools.com/openmedspel.html>
                        - MTH-Med-Spel-Chek by Rajasekharan N. of MT-Herald
                          <http://mtherald.com/free-medical-spell-checker-for-microsoft-word-custom-dictionary/>
    License:            GNU GPL v3 (see LICENSE.txt for more information)


###Description

This is a simple list of English medical terms formatted as a UTF8-encoded text file. It is based on two prominent medical dictionary projects:

 - [OpenMedSpel](http://www.e-medtools.com/openmedspel.html) by e-MedTools
 - [MTH-Med-Spel-Chek by Rajasekharan N. of MT-Herald](http://mtherald.com/free-medical-spell-checker-for-microsoft-word-custom-dictionary/)
 
The two sources have been merged, deduplicated, corrected and formatted as a text file that should be compatible with Android dictionary managers, LibreOffice, and Word.


###Usage

**Android**

Copy `wordlist.txt` to the root directory of your Android phone. Then install the excellent [User Dictionary Manager](https://play.google.com/store/apps/details?id=com.usr.dict.mgr) by Adrian Vintu and use it to import the terms to your user dictionary. More information may be found [here](http://udm.adrianvintu.com/). Note: Because of the size of the wordlist importing might take a (very long) while.

**LibreOffice**

*Manual installation*

Follow the instructions provided in [this Q&A](http://ask.libreoffice.org/en/question/11170/create-basic-english-dictionary/?answer=11187#post-id-11187) to create a new custom dictionary. Make sure to name it in a recongizable fashion (e.g. medicalterms-en) and activate it in the menu. 

[Find out where your LO user profile is located](https://wiki.documentfoundation.org/UserProfile#User_profile_location). Then proceed to navigate to `<LO user profile directory>\3\user\wordbook` and find your dictionary (e.g. medicalterms-en.dic). Open it in a text editor of your choice (e.g. Gedit on Ubuntu; Notepad++ on Windows, NOT Notepad!). Copy and paste the full contents of `wordlist.txt` below the dashed line (`---`). Save the file while making sure it remains UTF-8 encoded and restart LibreOffice.

**Word**

Rename `wordlist.txt` to `medicalterms-en.dic` and follow the instructions provided [here](http://support.microsoft.com/kb/322198).


###Waranty

This software comes with no warranty of any kind. Some misspelled words might be included. Please make sure to submit a bug report if you find any mistakes.
