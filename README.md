# Adding and updating members

Members are compiled automatically from the markdown files in [`_peoples`](https://github.com/smatch-pepr-sn/smatch-pepr-sn.github.io/tree/gh-pages/_peoples).

 - To add a new member, [create a new file in the `_peoples` folder](https://github.com/smatch-pepr-sn/smatch-pepr-sn.github.io/new/gh-pages/_peoples) and copy-paste the header below, before updating it accordingly:
   
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

- To add a picture, [add an image in `assets/img/people/`](https://github.com/smatch-pepr-sn/smatch-pepr-sn.github.io/upload/gh-pages/assets/img/people), and update the
  header above with its name

# Adding publications

We are use HAL to deposit publications and automatically create a publication list. 
Make sure to adequatly identify the ANR funding for SMATCH (code **ANR-22-PESN-0003**) in 
your publication/preprint deposit **metadata on *HAL***, and the reference will appear on the 
website ~~magically~~ automatically.


# Adding events

Add a specific line describing the event in the markdown file in [`events.md`](https://github.com/smatch-pepr-sn/smatch-pepr-sn.github.io/edit/gh-pages/events.md).


# Adding softwares

Add a specific line describing the software in the markdown file in [`softwares.md`](https://github.com/smatch-pepr-sn/smatch-pepr-sn.github.io/edit/gh-pages/softwares.md).



## HOW TO update other stuff on our wonderful website

To be noted:
* Home index page is layed out in `about.md`
* The rest are markdown pages. See [here for a cheat sheet.](https://www.markdownguide.org/cheat-sheet/)
* Stored files are in the `files` folder




## HOW TO locally edit the content (advanced users)

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
