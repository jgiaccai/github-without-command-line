---
layout: episode
title: Creating a repository with GitHub Desktop
teaching: 10
exercises: 20
questions:
  - 
---

# Creating a respository with GitHub Desktop

**Scenario**: You've been given a Zip file from a colleague (who does not know how to use GitHub) that contains a full analysis of avocado prices. You would like to share this analysis with other colleagues, and make improvements.

## Step 1: Make your initial commit

First download the Zip file from [https://github.com/MikeTrizna/github-without-command-line/raw/master/data/avocado_analysis.zip](https://github.com/MikeTrizna/github-without-command-line/raw/master/data/avocado_analysis.zip), and unzip it to somewhere on your computer.

In GitHub Desktop, go to File > Add Local Repository, and select the unzipped folder.

You should get a warning like this one that says "This directory does not appear to be a Git repository". That's ok. Click the "create a repository" link.

```{image} /img/gh-desktop-create/add_local_warning.jpg
:width: 800px
:class: border
```

On the Create a new repository window, fill out the options as below:

```{image} /img/gh-desktop-create/create_new_repo.jpg
:width: 800px
:class: border
```

Click on the History tab to show that an initial commit was already created.

Now the button in the top right of the GitHub Desktop should read "Publish repository". Click that button to upload it to GitHub.

You will see a Publish repository window pop up. Make sure to uncheck "Keep this code private" (nothing secret here!), and then click "Publish repository".

```{image} /img/gh-desktop-create/publish_repo.jpg
:width: 800px
:class: border
```

Now, navigate back to your new repository on GitHub. Check out how the `avocado_analysis.ipynb` Jupyter Notebook is nicely rendered. Same with the CSV file in the `cleaned_data` folder. But uh oh, look at the CSV file in `raw_data`.