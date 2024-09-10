# Mathematical Tools for Chemical Problems  

This repository contains the materials for the Fall 2024 3PC3 class. You can access the website [here](https://chemai-lab.com/Teaching.html), where you will find all the information about the course, as well as notes for both classes and tutorials.

If you want to [clone](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository) this repository and work on your local computer you will need to first install [Jupyter Book](https://jupyterbook.org/en/stable/intro.html) and then build the book.   

# Install jupyter book 

You can install Jupyter Book via: 
```
pip install -U jupyter-book
```


# Build the book 

We have a collection of notebook/Markdown files inside the `website/` folder, a `_toc.yml` that defines the structure of the book and a `_config.yml` file for any configuration we’d like. To build our book, we run the following command: 
``` 
jb build website/ 
```

This will generate a fully-functioning HTML site using a static site generator. The site will be placed in the `_build/html` folder, something like this: 
``` 
website
 └──_build
    └── html
       ├── _images
       ├── _static
       ├── index.html
       ├── intro.html
       ...
```

You can preview the content of the `html` file by passing directly on the navigation bar of your browser `file://Users/my_path_to_book/_build/index.html`. 

Whenever you make changes to the files inside the `website/` folder, delete the `build/` folder, run the `build` command again, and then push the changes to the repository. 

# Notes 

You can also access the class notes [here](https://github.com/ChemAI-Lab/Math4Chem/tree/main/website/Lecture_Notes) and the tutorial notes [here](https://github.com/ChemAI-Lab/Math4Chem/tree/main/website/Tutorial_Presentation).  
