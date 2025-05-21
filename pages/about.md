---
title: About
layout: about
permalink: /about.html
# include CollectionBuilder info at bottom
credits: true
# Edit the markdown on in this file to describe your collection
# Look in _includes/feature for options to easily add features to the page
---

{% include feature/jumbotron.html objectid="/assets/img/jj-ying-WmnsGyaFnCQ-unsplash_opt.jpg" %}

{% include feature/nav-menu.html sections="Icebreaker;First Demo Collection;Second Demo Collection" %}

## DS Camp 2025 Outline

## Icebreaker

- CollectionBuilder-Sheets collaborative collection
- [ds_camp_demo Sheet](https://docs.google.com/spreadsheets/d/1zaMXOFtCO5boHdN7UP8QNfjndoEaTzsG6RmoZNVoJGQ/edit?gid=0#gid=0)
- See also:
    - [Digital Exhibit Lab](https://github.com/learn-static/digital-exhibit-lab)
    - [LIS Best Meal](https://collectionbuilder-lis.github.io/best-meal/)
    - [Digital Dramaturgy](https://github.com/digitaldramaturgy/digitaldramaturgy.github.io)

## First Demo Collection

### On GitHub

- GitHub orientation
- [CB-Docs](https://collectionbuilder.github.io/cb-docs/)
- [CollectionBuilder-CSV](https://github.com/CollectionBuilder/collectionbuilder-csv)
- [Generate from template](https://collectionbuilder.github.io/cb-docs/docs/repository/)
- Look around repository
- Edit "README.md" (Markdown)
- Edit "_config.yml"
    - url
    - baseurl
- [Activate GitHub Pages with Action](https://collectionbuilder.github.io/cb-docs/docs/deploy/actions/)
- View your demo site!

### On local

Get set up:

- [Git clone](https://collectionbuilder.github.io/cb-docs/docs/repository/clone/) (GitHub Desktop or VS Code)
- Open with VS Code
- Open Terminal in VS Code
- `bundle install`
- `bundle exec jekyll s`
- Ctrl + C

Orientation to development environment:

- Git
- GitHub Desktop
- VS Code
- Ruby
- Jekyll
- CollectionBuilder

## Second Demo Collection

### On local

Add new data and explore:

- Download demo data: 
    - [psychiana_cbdemo_csv.csv]({{ '/objects/psychiana_cbdemo_csv.csv' | relative_url }})
    - [sbw.csv]({{ '/objects/sbw.csv' | relative_url }})
    - [postcards.csv]({{ '/objects/postcards.csv' | relative_url }})
- Add file to repository "_data"
- Edit "_config.yml"
    - metadata
    - noindex
    - title, etc
- `bundle exec jekyll s`
- Configure stuff! Mess around!

Version control:

- Commit.
- Push.

## Writing in markdown

Introduction to narrative writing using markdown and includes in demo collection.

- writing on the web concepts (headings, shorter, links, media)
- markdown concepts
- markdown details
- using includes

## Computation concepts with Liquid

Introduction to fundamentals of computation as represented in Liquid to create basic features in CB (create and display a list of filtered items). 

- Liquid intro
- Liquid variables
- Liquid for loop
- Liquid conditionals

## Working with Spreadsheets

Introduction to CSVs, Sheets, and the data used in CB.

## Working with Files

- extensions
- filenaming
- formats
- sizes, preservation
