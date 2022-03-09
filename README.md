# Zipping your files
This repo is designed to be an example of working with potentially large folder(s) of data and preserve some precious storage on your machine. Specifically, [ZippingFiles.ipynb](/ZippingFiles.ipynb) contains code that shows how you can:

1. Compress a large folder into a ZIP file (i.e. after you download a lot of files) and delete the original, uncompressed folder
2. Use files inside the ZIP file without needing to decompress it.

This repo uses [shutil](https://docs.python.org/3/library/shutil.html) as well as [zipfile](https://docs.python.org/3/library/zipfile.html) as primary libraries to operate on files and provide tools to work with ZIP files.
