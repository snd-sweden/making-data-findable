# Making data findable: Recommendations for making published research data findable

This website resource is being developed as a part of a flagship project by members
of the SND consortium.

Contributors:
* Chalmers University of Technology
* KTH Royal Institute of Technology
* SND Office
* University of Gothenburg

## Instructions for building the static site locally

If you want to build the web resource locally you may do so by installing a MkDocs environment:

1. Install a basic Python 3 environment on your operating system of choice. Install the *virtualenv* package if not already available.
2. Using the shell, make a virtual environment for MkDocs in a folder of your choice (you may of course pick something other than
*making-data-findable*):

`python3 -m venv making-data-findable`

3. Activate the virtual environment in your shell (OS/shell dependent):

Unix-compatible:

`source making-data-findable/bin/activate`

Windows:

`.\making-data-findable\Scripts\activate`

4. Install the requirements using pip (make sure the venv is activated first):

`pip3 install mkdocs pypandoc_binary mkdocs-bibtex mkdocs-material`

5. Navigate to the folder where the repository has been cloned or pulled.

To update HTML files with the latest changes:
`mkdocs build`

To host a local web server with the latest changes:
`mkdocs serve`
The address to the local web site should appear in the shell window i.e. `Serving on http://127.0.0.1:8000/`

If you are using `mkdocs serve` local changes should be updated automatically when refreshing the browser.
