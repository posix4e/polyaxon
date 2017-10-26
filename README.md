# polyaxon-docs

[Documentation](http://polyaxon.com/docs/) for polyaxon

## Building the documentation

- install MkDocs: `pip install -r requirements.txt` 
- `cd` to the `docs/` folder and run:
    - `python generate_doc.py`
    - `mkdocs build`    # Builds a static site in "site" directory
    - `mkdocs serve`    # Starts a local webserver:  [localhost:8000](localhost:8000)
- deploy: `mkdocs gh-deploy -b master`
