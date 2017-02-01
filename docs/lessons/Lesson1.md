# Lesson 1 - Introduction to GitHub


## GitHub Overview

GitHub is a collaboration system designed to support the sharing and controlled evolution of intellectual artifacts, including source code, media, and data files. GitHub provides many services that can be used together or in isolation. We will be considering a subset of these services for this course:

- Storing and sharing versioned files of various types, typically text (basic Git version control). These files are organized into repositories.
- Enabling these files to be viewed via the web within GitHub or rendered as an external website (GitHub Pages)
- Enabling social and team review and commentary on these files and projects, via a Wiki and an Issue Tracker.


### GitHub is not just Git

 At its core, GitHub uses [Git](https://en.wikipedia.org/wiki/Git), an efficient and reliable *Version Control System*, to ensure that even if many people are changing a common set of files, these changed can be recorded in a sensible manner, with clear provenance and undoability. Version Control is a key aspect of collaborative creation, providing a *safety net* and a way to review and revert changes.

### GitHub is More

GitHub has additional features beyond Git that resemble social networks like LinkedIn, Facebook, or Twitter. For example, you can build a user profile, create new projects, and comment on other user's projects via GitHub Issues. Traditionally, Git and GitHub have been used for source code and software development. However, the GitHub platform can support many types of projects, including book authoring, thesis authoring, educational website development, and data management.

The real power of GitHub, however, is less about individuals publishing content (many places can do that, including google docs etc). It is more about that content being easily shared, built upon, and reviewed in a way that is robust to the realities of distributed collaboration. Much of GitHub's functionality is available via a web browser; although power-users will still prefer to use a desktop computer and the GitHub command-line tools.


## A Quick Tour

We'd like to show some of the features that might be useful to non-coding creatives such as authors, data librarians, and educators.

### In-browser viewing of structured content and data

One of the best features of GitHub is that not only can it store versioned content in the same way that Git can, but that it makes this content visible, and sometimes editable, via the GitHub web interface. The following links to various files within GitHub demonstrate this potential.

#### GeoJSON data

- [Oregon Cities GeoJSON](data/OregonCities.geojson)


#### CSV and TSV data

- [Near Earth Comets CSV](data/NearEarthComets.csv)


GitHub can store any kind of content, provided it isn't too big. (And now [even this is possible](https://git-lfs.github.com/)).
However, it is more capable for some filetypes than it is for others. Certain filetypes can be viewed 'natively' within the GitHub interface. These are:

- Images: png, jpg, svg
- GEOJSON
- CSV, TSV (note that files named type '.tab' will not render properly in the UI.
- Markdown
- Software code (eg. including json, HTML, xml etc)
- Any of these can also be set up outside of a repository but within your use


## GitHub Structure

GitHub supports the following types of primary entities:

- **Person:** A person who contributes to GitHub
- **Repository:** A collection of versioned files and associated Issues, Wiki, and Collaborators
- **Organization:** An entity that may correspond to an actual organization (such as a university) or to a meaningful grouping of repositories. Organizations are like Persons except that they can establish Teams.
- **Teams**: A group of Persons assembled by the administrators of an organization. A Person may participate in many Teams and Organizations, however a Team is always bound to a single Organization.

- Repositories

The relationships between any combination of these entities is many-to-many, with the nuanced exception of repositories. Repositories belong *either* to a single organization or to a single *individual*; "forks" of a repository may be set up in other organizations or in other individuals.

![](../howto/images/github-organizations-teams-repos.png)

### Markdown

```no-highlight
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~


### Issues

The GitHub issue tracker is easy to use, fairly lightweight and capable for a lot of the basic project management one would want to do.
This guide is a nice overview: https://guides.github.com/features/issues/


### [Back to Home](../index)
