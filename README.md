# Synapse Insights  

This repository hosts the files for [synapseinsights.com](http://www.synapseinsights.com/).

## How to edit

### Adding new components  

Most of the specific components that appear on different pages are controlled via files within the `/content/home` folder. For example to include a publications section simply turn on that compoonent in the `/content/home/publications.md` file by setting `active=true` at the top of the file. To edit the content that appears _within_ that component, simply edit the markdown/html at the very end of that file (anything below the `+++`).

### Adding new projects  

TO add a new project, simply create a new subfolder within the `/content/project` directory modeled after existing directories in that folder. Creating a `featured.png` file in that new sub-directory can be used to add a cover/gallery photo for the project. Editing the `index.md` in that new-subdirectory will edit the contents of that project preview/page. 

### Editing bios  

To edit bios edit the `_index.md` file within the relevant person's sub-directory in `/content/author`. For example to update Eshin, edit `/content/author/eeshin/_index.md`. 
