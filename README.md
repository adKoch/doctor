# Project DOCtor

## Introduction

This project is mainly a learning opportunity to learn indexed documents technologies - Apache lucene/Elasticsearch.

Main focus in this project is to store documentation written in markdown format with indexing of phrases/terms inside.

## Functionality

### Documentation Storage System

Account/group based documentation storage system. The whole documentation should be downloadable as a zip file as basic .md files.

Whole documentation on-site should be generatable from markdown files in a proper directory file hierarchy format.

Software should generate everything from downloaded files.

### Extended Markdown format

All documents should be written with .md extension that can be extended with indexing and maybe additional functionalities that are visible through web app viewer/editor.

### Phrase/Document indexing

The whole purpose of indexing and addition of new functions based on making connection between documents should serve to make browsing through large documentation easy.

All connections should be made on premise of existing base definitions. System should index phrases based on file names. These phrases should show up in other documents as underlines with additional indications (probably based on color).

## Technologies

* Microservices written in java/kotlin
* Elasticsearch

## Repository format

### Branches

* master - branch dedicated to deployment of incremental versions (if there will be any)
* develop - branch with the most recent changes

### Directories

* run - all files associated to running application
* src - source code fo the application
