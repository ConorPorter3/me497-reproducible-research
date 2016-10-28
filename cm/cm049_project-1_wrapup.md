
wrap-up project 1
=================

When you think you are done, there are some last minute items to check.

scripts
-------

-   The F7 function button activates a spell-check. Check every script.
-   Set the `knitr` options to include `echo = TRUE` generally for work that does not go to a client.
-   Does each working script produce an HTML output that is error-free?
-   Does the script for the client report produce a DOCX output that is error free?
-   Other than document formatting (which we haven't addressed yet) is the report client worthy?
-   Have you run the scripts using the updated data set with 6 cycles instead of 3)? Does every output document correctly update when you do?

file management
---------------

To make it easy for me to review your work, please ensure that your `.gitignore` file includes:

    # ignore DOCX files 
    *.docx
    */*.docx

    # ignore HTML files
    *.html
    */*.html

    # ignore special  R files 
    .Renviron
    .Rhistory
    .RData

    # ignore a hidden RStudio directory
    .Rproj.user/

    # ignore the RStudio project file 
    *.Rproj

Once your `.gitignore` file is up to date, you should:

-   Delete all HTML and DOCX files from your project directories.
-   Stage/Commit/Push your changes to the GitHub repo.

Great! You're done.

------------------------------------------------------------------------

[main page](../README.md)