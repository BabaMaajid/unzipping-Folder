# unzipping-Folder
## Code for Unzipping a folder
'''python
import zipfile as zf
files = zf.ZipFile("foldername.zip", 'r')
files.extractall('Directory name where to unzip')
files.close()
'''
