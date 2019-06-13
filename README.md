# cl_recipes
Cmd Line Recipes

Search and replace pattern in files :

    $ find . -type f -regex '<file_regexp>' -exec sed -i 's/foo/bar/' {} +
