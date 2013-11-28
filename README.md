wiki-docs-template
==================

Standard template for a wiki to contain project documentation on GitHub.

# Set-up process

When the projects starts, the repo should be set up within GitHub.

Once created, go to the wiki tab within the repo, which is located on the right of the page. You should land on the Home page.

  If there is not a homepage visible (should say Home. Welcome to the {wiki name} wiki!), go to the Pages tab, which is located above the main page content. There should be a home page here, and if you then go Home again the content should show up.

  If for some reason there is not a Home page set up, click New Page and create a Home.md file.

Once a home page has been set up you should then get a button for Clone URL. This will give you JUST the URL for the wiki rather than the entire repo. It will look like this: https://github.com/{accountname}/{projectname}.wiki.git

Merge in the files from the standard template repo - i.e. the files in this repo's wiki.

Once you’ve added your files, push them back into your project's master wiki branch. 

# Giving the page more structure

The following files are what will allow you to have a sidebar and a footer. These are not something that you can create through the web interface. 

* _Footer.md
* _Sidebar.md

Once these are included in the project then editing your pages through the web interface will give you the option to make changes to the sidebar/footer too. Note that there is no wysiwyg editor here. If you’re not cool with markdown you can use the editor for the page content, and paste in.

Sidebars and footers can be applied globally by placing the above in the project root, or additional versions can be placed within directories to apply only to those files. Note that directories will be 'flattened' in terms of the wiki URLs and all files will appear to be on the root, but actually the directories persist. If you need to organise your files into different directories you'll have to do this locally rather than through the web interface.
