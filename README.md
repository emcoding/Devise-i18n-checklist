 # The Ultimate Checklist to Properly Internationalise Devise, including a Dutch treat 🇳🇱
 Blogpost: appsignal blog <add link>

## In this repo:

* devise.nl.yml  
with new, streamlined Dutch translation (In the Checklist: step 3)🇳
This translation uses a user centered, informal tone of voice, in a consistent style for all the i18n-ed **user interface strings** provided by the Devise gem. 

* active_record.nl.yml  
the keys for the **User attributes** (In the Checklist: steps 5 and 7)
Optimized for using in both the Devise forms and the Rails error messages.

* rails_error_messages  
The Rails keys, with a translation that is in sync with the new translations in devise.nl.yml


## Bonus files

* views.nl.yml  
my personal bootstrap file for translating the **Active Record attributes added by the Devise Modules**.
The translations follow the same principles as in the main file (devise.nl.yml).
This is still a work in progress, so proceed with care.
To use this file the keys need to be referenced from the Devise-views. In the zipfile in this repo there's my own version. Again: still a work in progress; not all the strings are translated yet. 

* devise_views  
A few examples (the shared views, the log in template) that use with the new views.nl.yml
