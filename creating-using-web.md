---
layout: episode
title: Creating repositories using the web interface
teaching: 15
exercises: 15
questions:
  - Creating repositories on GitHub
  - How to record (commit) changes
  - Browsing changes
  - Repository insights and settings
---

# Creating repositories using the web interface

We will practice creating a new repository using the web interface, committing
changes to it, browsing the changes, creating branches, and more.
This is everything you need to do basic file management, though you'll
probably want something faster to use.  Still, it can be good for
quick edits and contributions.

---

## Step 1: Create a repository with a README and a license

You start off by creating a repository from the web.  In fact, we
usually end up doing this from the web, no matter how you do your daily
work.  The important questions are who is the *owner* and what is the
*name* of the repository.

Make sure that you are **logged into GitHub**.

To create a repository we either click the green button "New" (top left corner):

```{image} /img/creating-using-web/new-top-left.png
:width: 400px
:class: border
```

---

Or if you see your profile page, there is a "+" menu (top right corner):

```{image} /img/creating-using-web/new-top-right.png
:width: 400px
:class: border
```

---

We then land at the following form.  Please fill it out and set **Initialize
this repository with a README**. Leave "Choose a License" as "None". We will address this in the next section on [choosing a license](choosing_a_license.md).

```{image} /img/creating-using-web/form.png
:width: 600px
:class: border
```

---

And now we have a repository with a README and LICENSE and one commit:

```{image} /img/creating-using-web/created.png
:width: 600px
:class: border
```

---

## Step 2: Create a new file

We can easily add new files from the web interface.

Create a file, e.g. `guacamole.md` (the "md" ending signals that this is in Markdown format):

```{image} /img/creating-using-web/new-file-buttons.png
:width: 600px
:class: border
```

In the new file you can share your favorite cooking recipe (or something else).
You can also copy-paste this as a starting point:
```
Ingredients:
- 2 avocados
- 1 lime
- 2 tsp salt

Instructions:
- cut and mash avocados
- chop onion
- squeeze lime
- add salt
- and mix well
```

```{image} /img/creating-using-web/new-file-editor.png
:width: 400px
:class: border
```

Then add a commit message and commit (save):

```{image} /img/creating-using-web/new-file-commit.png
:width: 600px
:class: border
```

```{admonition} Discussion: Good commit messages
- What has changed is more useful than which file has changed
- Sometimes we forget to document *why* something was changed
- Many projects start out as projects "just for me" and end up to be successful projects
  that are developed by 50 people over decades.
- Write commit messages in English that will be understood
  15 years from now by someone else than you.
- ["My favourite Git commit"](https://fatbusinessman.com/2019/my-favourite-git-commit)
- ["On commit messages"](https://who-t.blogspot.com/2009/12/on-commit-messages.html)
- ["How to Write a Git Commit Message"](https://chris.beams.io/posts/git-commit/)
```

---

## Step 3: Modify a file

We can also easily modify files from the web.

Now improve the recipe by adding an ingredient or an instruction step:
- Click on the file.
- Click the "pen" icon on top right ("edit this file").

Make an improvement, write a commit message, commit:

```{image} /img/creating-using-web/edit-file-preview.png
:width: 400px
:class: border
```

Once you have done that, browse your commits:

```{image} /img/creating-using-web/commits-browse.png
:width: 400px
:class: border
```

In my example I got:

```{image} /img/creating-using-web/commits-example.png
:width: 800px
:class: border
```

---

```{admonition} Summary
In this episode, we saw how we could do basic file management from the
web.  It's not the best for making lots of new content, but it's
pretty convenient for quick edits.  We will now see more advanced ways
to do the same things - you can always check back on the web to see
the effect.
```

## MarkDown

Markdown is a lightweight markup language for creating formatted text using a plain-text editor. John Gruber and Aaron Swartz created Markdown in 2004. (Wikipedia: https://en.wikipedia.org/wiki/Markdown)

To practice using Markdown, and seeing how it is formatted, open up a [new CodiMD document](https://codimd.carpentries.org/new) in your browser.

By default, the document will open in rendered view, but click on the middle split pane icon in the top left to show the Markdown and rendered views side-by-side.

```{image} /img/creating-using-web/codimd_edit.png
:width: 800px
:class: border
```

Now using the CodiMD interface, we will learn the following Markdown equivalents:

Markdown uses keyboard characters to change formatting

\\backslashes keep the special character visible

Use double line returns (i.e. blank spaces between lines) to allow for proper spacing.  

one
return
at
end
of
each
word

two

returns

at 

end

of

each

word


# heading is made using \#
\# Big Heading
## smaller heading is made using multiple \#
\## smaller heading
- bullet points can be made with \- or \*

\- bullet style one

\* bullet style two

**bold uses double \*\* around your phrase**

\*\*bold\*\*

_italic uses \_ underscores_

\_italic\_

1. number in list
2. automatically populates once you type '1.'

let's try a [link](http://www.github.com)
you must include the 'http://' for the link to work correctly

\\-backslashes keep the special character visible



`````{admonition} Exercise
:class: tip
Use as many of the Markdown skills you just learned to edit either the README.md or guacamole.md files.
`````
