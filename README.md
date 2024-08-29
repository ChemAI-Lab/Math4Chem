# Install jupyter book 

You can install Jupyter Book via: 
```python 
pip install -U jupyter-book


# Build the book 

We have a collection of notebook/Markdown files inside the `website/` folder, a `_toc.yml` that defines the structure of the book and a `_config.yml` file for any configuration we’d like. To build our book, we run the following command: 
```python 
jb build website/ 


This will generate a fully-functioning HTML site using a static site generator. The site will be placed in the `_build/html` folder, something like this: 
```python 
website
 └──_build
    └── html
       ├── _images
       ├── _static
       ├── index.html
       ├── intro.html
       ...


You can preview the content of the `html` file by passing directly on the navigation bar of your browser `file://Users/my_path_to_book/_build/index.html`. 

Whenever I make changes to the files inside the `website/` folder, I delete the `build/` folder, run the `build` command again, and then push the changes to the repository. 
