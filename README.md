## Welcome to iDAAS-Connect

iDAAS Connectors for Inbound Data Processing

Powered by [Apache Camel](https://camel.apache.org/)

### Build

1. To build the idaas-connect.github.io site, first install `sphninx` and the `sphinx_rtd_theme` theme.
```
pip install sphinx sphinx_rtd_theme
```
Note: Tested with Python 3.7.7 and `pyenv global 3.7.7`.

2. Ensure that this line in conf.py is where `sphinx_rtd_theme` is stored in your environment.
```
sys.path.insert(0, os.path.abspath('/usr/local/lib/python3.7/site-packages'))
```

3. Build the site
```
sphinx-build -b html source docs
```
This builds the site from the files in the 'source' directory and places the built site in a 'docs' subdirectory of the idaas-connect/docs repo, which the repo is configured to use as the site folder.

4. Checkout a branch, push the new site to the idaas-connect/docs repo & merge the changes to master.

5. View the site at `https://idaas-connect.github.io/docs`.

### Connect

Check out the iDAAS-Connect repo on [Github](https://github.com/RedHat-Healthcare/iDAAS-Connect).
