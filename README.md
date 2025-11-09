templates
=========

This repository contains some [copier](https://copier.readthedocs.io) templates I use.

Setup
-----

Clone the repository to, e.g. `~/code/templates` and create a copier settings file [in
the correct place](https://copier.readthedocs.io/en/stable/settings/):

```yml
trust:
- ~/code/templates

defaults:
  user_name: "Jochen Klar"
  user_email: mail@jochenklar.de
```

Usage
-----

In a new repo or project run:

```bash
copier copy ~/code/templates/git .
copier copy ~/code/templates/python .
```
