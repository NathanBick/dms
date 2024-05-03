# Document Managenent System

A DMS should have the following components:

- version control for document changes
- metadata storage system

git and GitHub are the best VCS options, but require flat files. We may not want to use flat files for document editing. We can use a GitHub Action to convert Word docs to markdowns which can give us the tracking and serve as the "official" source of truth. These markdowns can then be converted to other formats for consumption. 