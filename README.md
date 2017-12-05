# USF IMaRS Website Redesign

I am toying with the idea of porting our website out of drupal and into jekyll.
Though I have tried porting over with automated tools with no luck,
I think that the Wall-E theme is a good starting point that might allow me to
port things over with less effort than it will take to maintain an aging, undocumented drupal site.

--------------------------------------------------------------------

## Editing Workflow
This is a quick rundown of how to modify a page.
1. navigate to the page on github. For example: https://github.com/USF-IMARS/usf-imars.github.io/blob/master/coastal-cities-summit.md 
2. click the pencil icon to edit the page
3. modify the markdown (or html)
4. use the "preview" tab to view a rendering of the html
5. describe & commit your changes using the form at the bottom
6. done! your changes will automatically be applied to the test website at https://usf-imars.github.io/ 

NOTE: new to markdown or want a more feature-full editor? You can also edit these pages using https://prose.io or https://stackedit.io

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


# old docs retained from template we forked from

Wall-E is a modern Jekyll template with a magazine-like grid layout on the frontpage, beautiful typography and uncomplicated content.

## Features

- Mobile responsive, built with Semantic UI, customization is easy
- Disqus is integrated by default
- One column layout suitable for personal blogs with focus on content
- Beautiful typography (uses League Gothic and Open Sans)
- Feature image can be added to homescreen post cards
- Search box links to Google search by default

## Usage
Wall-E is fully furnished right out of the box. To use this template on your blog
- If this is your first Jekyll blog, follow this <a href="https://jekyllrb.com/docs/installation/">helpful guide</a> to set up Jekyll.
- Run `jekyll serve` and your blog should be live on `http://localhost:4000`. Make changes, test them locally, commit your changes and push to your fork. Your changes should be live in a couple of seconds

## Customization
- `_includes/author.html`: Add your name, link to a profile picture and a short author description that appears on the bottom of each post. See <a href="https://semantic-ui.com/views/item.html">Semantic Link</a> docs.
- `_includes/card.html`: Cards can be customized to show the essential info about a post (feature image, catagory, tags, comment count etc). See <a href="https://semantic-ui.com/views/card.html">Semantic Card</a> docs.
- `assets/css/main.css` and `assets/css/mobile.css`: Global and mobile specific CSS files respectively
- `assets/js/main.js`: Any common javascript goes here. If you wish to customize the search behaviour (for example, use a different search engine), that can be done here.

## Credits
* Based on [Wall-E Jekyll Template](https://github.com/abhn/Wall-E) - [MIT license](LICENSE.md)
    - <a href="https://demo.ghost.io">Ghost</a> blogging platform's demo page for inspiration (and the header background image).
    - <a href="http://www.jeanchristophebonis.com/">For the Wall-E image used everywhere</a>
    - <a href="https://semantic-ui.com">Semantic UI</a>
