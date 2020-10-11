# Strapi application for Grow With Facebook DevC

## For Backend Developers (Enviroment Setup)

## Technologies

You need to know or research these to work on this app:

- Nodejs
- MongoDb
- Mongoose (Object Relational Mapper for Mongodb)

1. Install the latest LTS of Nodejs at [Node](https://nodejs.org/en/) for Mac or windows.
2. This project is depending on Mongodb as the main database of the content of the platform.
   For local development, install Mongodb Community Server from [Mongodb](https://www.mongodb.com/try/download/community) available for mac and windows.
3. Basic knowledge of Headless CMS is a prerequisite. This project is depending on Strapi, a nodejs headless content management system. to get upto speed with it you can refer to the documentation at [Strapi](https://strapi.io/documentation/v3.x/getting-started/quick-start.html)

## Documentation

We use [mkdocs](https://www.mkdocs.org/) for our documentation.

- ✔ It requires very little configuration
- ✔ Markdown is quick to write

### Requirements

In order to edit the documentation you will need:

- Python 3.5+
- Python Pip

Installation instructions for `mkdocs` are here: <https://www.mkdocs.org/#installation>

To install on debian run the following:

```bash
apt-get -y install --no-install-recommends gcc libpq-dev python3-dev python3-venv python3-wheel python3 python3-pip python3-setuptools
pip3 install wheels
pip3 install mkdocs mkdocs-material
```

To install on macos run the following:

```bash
brew install python
pip3 install mkdocs mkdocs-material
```

### Previewing

During development you can preview your changes to the documentation by running the `mkdocs` development server

```bash
mkdocs serve
```

Browse to <https://localhost:8000> to view the documentation while you are editing.

### Editing

- Documentation is in the form of markdown files, located in the `/docs` folder.
- The first page users view is `index.md`, all other pages are linked from there.
- New pages should be added directly to `/docs` as markdown files.
- Images should be added to the `img/` directory, and should have short, descriptive names. (e.g. `login_empty.png`).

Before you can build you **MUST**:

```bash
git clone ...
```

and

```bash
cd online-platform-devc
```
