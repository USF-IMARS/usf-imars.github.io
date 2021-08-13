# USF IMaRS Website Redesign

I am porting the IMaRS website out of drupal and into jekyll.
Though I have tried porting over with automated tools with no luck,
starting from the jekyll Wall-E theme will allow me to
port things over with less effort than it will take to maintain an aging, undocumented drupal site.

--------------------------------------------------------------------

To get started working with this website, I suggest you create your user page using the guide in [/documentation/your_first_edit.md](https://github.com/USF-IMARS/usf-imars.github.io/blob/master/documentation/your_first_edit.md).
For more info, check out the other files in the [/documentation/](https://github.com/USF-IMARS/usf-imars.github.io/blob/master/documentation/) folder.

## Editing Workflow Quickstart
Too busy to read through `/documntation/`? This is a quick rundown of how to modify a page.
1. navigate to the page on github. For example: https://github.com/USF-IMARS/usf-imars.github.io/blob/master/coastal-cities-summit.md
2. click the pencil icon to edit the page
3. modify the markdown (or html)
4. use the "preview" tab to view a rendering of the html
5. describe & commit your changes using the form at the bottom
6. done! your changes will automatically be applied to the test website at https://usf-imars.github.io/

NOTE: new to markdown or want a more feature-full WYSiWYG-like editor? You can also edit these pages using https://prose.io or https://stackedit.io.

## Justification
Jekyll allows users to build pages using [markdown](https://en.wikipedia.org/wiki/Markdown), rather than using the drupal interface.

### Why is markdown better than drupal's WYSIWYG editor?
Markdown is a markup language designed to maximize human-readability and ease-of-use.
Drupal uses a "What You See Is What You Get" (WYSIWYG) html editor to produce pages.

1. Markdown syntax is intuitive and easy to learn, arguably just as fast to pick up as the drupal WYSIWYG editor.
2. Once learned, documents can be created and edited much more efficiently in markdown.
3. Learning markdown benefits students more than learning to use drupal, because they will likely encounter markdown and github again in their studies.

## Why is github+jekyll better than drupal?
1. git+github are tools that nearly all programmers will be familiar with.
2. exposure to the github workflow benefits students who may need to use github in their later work.
3. Learning to use github's website will help users connect with USF-IMaRS's other resources on github (issue trackers, project trackers, other code repositories).
4. Exposure to this website's workflow lowers the barrier of entry if users wish to set up their own blog/website using jekyll in the future.
5. Edits in github are version-controlled using git, which means that edits can always be undone, and changes can be well documented with commit messages.

--------------------------------------------------------------------

## Additional info
Additional documentation can be found in the `/documentation/` directory.
These docs include:

* documentation from the wall-e jekyll theme
* advanced editing workflow on your local machine
