
You can run these notebooks using the Jupyter notebooks installation of the Docker image provided in https://github.com/MTG/MIRCourse. Just copy this folder to the root folder of MIRCourse repository and run the Docker image.

Alternatively you can do a manual installation of the required python packages and run the notebooks without the docker image. The requirements are jupyter numpy sklearn matplotlib, which you can install by running:
pip install jupyter numpy sklearn matplotlib

Notebooks should run both in Python 2 and 3.

To visualize the "trees" in nice images (notebook B), you'll need to install Graphviz's 'dot' command line tool (https://graphviz.gitlab.io/download/). This is not included in the Docker image therefore if you want to print the trees in images you’ll have to go for the manual installation option. Alternatively trees can be print as raw text and this will work in both versions.
