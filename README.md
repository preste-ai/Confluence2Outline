# What is in this repo ?

This repo contains a Jupyter notebook that can be used to adapt and prepare Markdown files from Confluence to Outline.

Notebook : <a href="https://colab.research.google.com/github/preste-ai/Confluence2Outline/blob/main/Confluence2Outline_pub.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" height=22.5></a>

# How-to
## Prequesite

In order to use this notebook, you'll need to do the following :

1. Export your Confluence markdown pages : this is a paid functionality for Confluence, but it's reasonably cheap and can be activated separately (as of today, at least).
2. Have an Outline web server ready, and an API key with writing access for attachments

## How does the notebook works

The notebook deals with the pain points of markdown manual export/ import from Confluence to Outline, mainly :
1. Dealing with attachments : urls in Confluence mk docs won't be usable in Outline
2. Dealing with a few differences in mk language between the two platforms : 
    - Info, Warning & Notes are handled with different markdown elements
    - Google Drive links (Slides, Videos, Docs, Sheets, etc) can't be inserted in lines in Outline as they are in Confluence. 
Outline offers nice previews out-of-the-box for these, but it will delete the rest of the content if it's not isolated in a separate line.


