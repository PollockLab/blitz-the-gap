# Website for Blitz the Gap: Challenges 🌱

[![badge](https://img.shields.io/static/v1?style=for-the-badge&label=View&message=Website&color=8abd5e)](https://pollocklab.github.io/blitz-the-gap/)

## Summary

This website presents information about Blitz the Gap, including: 

* `_quarto.yml` : Website structure and settings.
* `index` : Description of the Blitz the Gap and a listing of challenges, retrieved from the `challenges/` folder.
* `tutorial` : Example workflow to make a priority map for a challenge.
* `challenges/` : Contains docs for a list of the challenges with a description, a map, and a list of authors.

## Building the website

1. Set your working directory to the website repository folder, or open the R project.

2. To preview your changes locally, run `quarto preview` in the terminal. Always edit on the master branch.

3. To build the site locally, run `quarto render`. You must build the site before pushing any changes to this repository in order to ensure it is still buildable.

4. To deploy the website through GitHub Pages, run `quarto publish gh-pages` in the terminal. If you need to, push the automatic commit from the gh-pages (but it should do this after taking your GitHub credentials).
