# ErbB4's Blog


## Instructions

1. `_config.yml`, line 38, change `bio: "Neuroscience"` to whatever you like. It will show up in the first page of the website as a brief introduction.
2. Photo gallery:
   a. All photos are stored in folder `_photos/photos/`. You can create folders.
   b. Photo titles and descriptions are set in `_data/galleries/`. You can create files with extension `.yml`. Each `.yml` file will be displayed as a gallery.
   c. In this example, I created a file named `life.yml`.
   d. In `life.yml` I set the name of the gallery, which will be displayed as title of gallery.
   e. `path_prefix` is the folder name of your photos in `_photos/photos/` folder. In this example, my photos are stored in `_photos/photos/life/` so I set it to `path_prefix: "/life"`.
   f. In `life.yml`, you can set photo path, title, and description. `path` is the name of the image file, with extension. `title` and `description` will be displayed in the gallery. It can be empty.
3. If you want to create new galleries, simply create a new `.yml` file in `_data/galleries/` folder. Remember to put your photos in `_photos/photos/` folder.


## For development

Just a heads up:

When I apply bundle install to this repo, an error about json 1.8.3 occurs. Simply remove Gemfile.lock fixes the problem.
