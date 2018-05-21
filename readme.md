# Bags of Colors

This is a personal, unofficial implementation of bags of colors for image descriptors. It is based on the following paper:

> Christian Wenger, Matthijs Douze, Hervé Jégou, \"Bag-of-colors for improved image search\". Online: <https://dl.acm.org/citation.cfm?id=2072298.2072034>

### Using

Serve the notebook file with [Jupyter](http://jupyter.org). Image data sets need to be obtained and prepared separately, and some constants may have to be updated accordingly.

In order to prepare the data sets, create two directories, `training_data` and `testing_data`, each containing nothing but standard image files (e.g. PNG). A substantial amount of images is recommended (>10k).

### Requirements

Python 3 is required. Aside from the given Python dependencies in [requirements.txt](requirements.txt), the Python bindings for [Faiss](https://github.com/facebookresearch/faiss) must also be installed in the system. Please follow the [instructions](https://github.com/facebookresearch/faiss/blob/master/INSTALL.md#step-2-compiling-the-python-interface) in the official repository on building Faiss for Python. GPU support is recommended, but the code can be easily adjusted to function without it.

### License

MIT
