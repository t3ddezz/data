# data
run commands

docker run --rm -it nanozoo/guppy_gpu:4.4.1-1--a3fcea3

guppy_basecaller --print_workflows|cut -f 1 -d " " | grep "FLO" | sort | uniq  

-->flowcells

copy & paste  in an empty .txt file and upload here https://github.com/t3ddezz/data/blob/main/flowcell_data.txt


guppy_basecaller --print_workflows|cut -f 2 -d " " | grep "[V,S][Q,S]K" | sort | uniq  

-->sequencing kits

copy & paste each in an empty .txt file and upload here https://github.com/t3ddezz/data/blob/main/sequencing_data.txt


gitignore

# some data aspects
*fai  # fasta indices

# don't commit unfinished work
wip/

# large file extensions
*.pdf

# Mac OS specific
# https://github.com/github/gitignore/blob/master/Global/macOS.gitignore

*.DS_Store
.AppleDouble
.LSOverride

# Icon must end with two \r
Icon


# Thumbnails
._*

# Files that might appear in the root of a volume
.DocumentRevisions-V100
.fseventsd
.Spotlight-V100
.TemporaryItems
.Trashes
.VolumeIcon.icns
.com.apple.timemachine.donotpresent

# Directories potentially created on remote AFP share
.AppleDB
.AppleDesktop
Network Trash Folder
Temporary Items
.apdisk

# Python specific
# https://github.com/github/gitignore/blob/master/Python.gitignore

# Byte-compiled / optimized / DLL files
__pycache__/
*.py[cod]
*$py.class

# C extensions
*.so

# Distribution / packaging
.Python
env/
build/
develop-eggs/
dist/
downloads/
eggs/
.eggs/
lib/
lib64/
parts/
sdist/
var/
*.egg-info/
.installed.cfg
*.egg

# PyInstaller
#  Usually these files are written by a python script from a template
#  before PyInstaller builds the exe, so as to inject date/other infos into it.
*.manifest
*.spec

# Installer logs
pip-log.txt
pip-delete-this-directory.txt

# Unit test / coverage reports
htmlcov/
.tox/
.coverage
.coverage.*
.cache
nosetests.xml
coverage.xml
*,cover
.hypothesis/

# Translations
*.mo
*.pot

# Django stuff:
*.log
local_settings.py

# Flask stuff:
instance/
.webassets-cache

# Scrapy stuff:
.scrapy

# Sphinx documentation
docs/_build/

# PyBuilder
target/

# IPython Notebook
.ipynb_checkpoints

# pyenv
.python-version

# celery beat schedule file
celerybeat-schedule

# dotenv
.env

# virtualenv
venv/
ENV/

# Spyder project settings
.spyderproject

# Rope project settings
.ropeproject
