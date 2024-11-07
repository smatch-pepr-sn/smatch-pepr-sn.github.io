# HOW TO update stuff on our wonderful website


* Log into your github account and make sure the computer you are on has been listed through a ssh key
* Clone the repo:

`git clone git@github.com:smatch-pepr-sn/smatch.github.io.git`

If you have an authentification error,  try using the https protocol

`git clone https://github.com/smatch-pepr-sn/smatch.github.io.git`


Now the fun can start!

NB: if you want to avoid to enter your SSH passphrase upon each action, you can used `ssh-add` once and for all on your computer.


So then the process is:
- make changes to the site
- push
- take a coffee!
- look at the webpage!


To be noted:
* Index page is layed out in `about.md`
* The rest are markdown pages. See [here for a cheat sheet.](https://www.markdownguide.org/cheat-sheet/)
* Stored files are in the **files** folder
* Publications are automatically listed from the **_publications** folder via the publications.md file.


## Adding and updating members

Members are compiled automatically from the markdown files in `_peoples`.

- To add a picture, (git) add the image in `assets/img/people/` and update the
  header.
- Here's an example of template:

        ---
        title: "Boris Hejblum"
        name: "Boris Hejblum"
        collection: peoples
        permalink: /people/boris_hejblum
        image: boris.jpg
        position: "Permanent researcher"
        website: "https://borishejblum.science/"
        github: "https://github.com/borishejblum/"
        googlescholar: "https://scholar.google.com/citations?sortby=pubdate&hl=en&user=xU72YmYAAAAJ&view_op=list_works/"
        orcid: "https://orcid.org/0000-0003-0646-452X"
        ---

        **[Boris Hejblum](https://borishejblum.science/)** is a researcher in Biostatistics at [Inserm U1219 *Bordeaux Population Health*](https://www.bordeaux-population-health.center/) in the [SISTM team](https://www.bordeaux-population-health.center/the-teams/sistm/). His research focuses on the development of statistical methods for the analysis of longitudinal high-throughput biomedical data, in particular for studying gene expression in human vaccine trials.

    You can add more markdown text here.


## Adding publications

We are use HAL to deposit publications and automatically create a publication list. 
Make sure to adequatly identify the ANR funding for SMATCH (code 22-PESN-0003) in 
your publication/preprint deposit on HAL, and the reference will appear here


