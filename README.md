# demo
How it works
1
Enter your repository information
Provide in the above form a URL or a GitHub repository that contains Jupyter notebooks, as well as a branch, tag, or commit hash. Launch will build your Binder repository. If you specify a path to a notebook file, the notebook will be opened in your browser after building.
2
We build a Docker image of your repository
Binder will search for a dependency file, such as requirements.txt or environment.yml, in the repository's root directory (more details on more complex dependencies in documentation). The dependency files will be used to build a Docker image. If an image has already been built for the given repository, it will not be rebuilt. If a new commit has been made, the image will automatically be rebuilt.
3
Interact with your notebooks in a live environment!
A JupyterHub server will host your repository's contents. We offer you a reusable link and badge to your live repository that you can easily share with others.
