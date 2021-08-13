# Your First IMaRS Website Edit : A Guide

This document will walk you through how to create and edit your user page on the IMaRS website.
The basics learned here can also be applied to editing other parts of the IMaRS website.
Some skills you will learn have general utility beyond just the IMaRS webpage, like how to edit files on github and use markdown syntax.

Steps:
1. ensure you are logged into github and you have write access to the USF-IMaRS/usf-imars.github.io repository.
2. Create your user page (skip this if your page already exists)
    1. navigate to [USF-IMARS/usf-imars.github.io/_students](https://github.com/USF-IMARS/usf-imars.github.io/tree/master/_students) (or [USF-IMARS/usf-imars.github.io/_staff](https://github.com/USF-IMARS/usf-imars.github.io/tree/master/_staff)).
    2. Click the "add file" button in top right ish.
    3. name the file something like `yourname.md`
    4. put the following at the top of your file:
      ```
      ---
      layout: page
      title: Charles ReplaceThisWithYourName Darwin
      ---
      ```
    5. add whatever content you like below that. You can use plain text, markdown syntax, or html.
    6. skip to step "4. commit your content" below
3. To edit an existing file
    1. Click the pencil icon to edit the file    
    2. modify content
4. "commit" your content    
    1. scroll down to the bottom of the edit page
    2. enter a short message describing your edit
    3. click "commit changes" button

After following these steps your changes should show up on the site after a few minutes.
Once your changes have been processed your commit will show up in the [repository's commit history](https://github.com/USF-IMARS/usf-imars.github.io/commits/master) with a green checkmark.
