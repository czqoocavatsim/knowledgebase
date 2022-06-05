## Gander Oceanic Knowledge Base

Powered by mkdocs.

### To Contribute

#### Setup

1. Download the latest Python 3 version (https://www.python.org/downloads/)
2. Clone this repository.
3. Install the requirements using the command `pip install -r requirements.txt` in the repository.


#### Editing

In the `docs` folder, you can make and edit pages. 

- `atc` is the Talking to ATC section.
- `basics` is the Basics section.
- `nattrak` is the natTrak section.
- `website` is the website help section.
- `diagrams`, `assets`, `img` folders store images.

In each directory there is a `.pages` YAML file. Use this to define how the page titles and order are displayed to the user.

#### Previewing your edits

Run the command `mkdocs serve` in your terminal within the respository. This will allow you to preview your changes.

#### Deploying changes

1. **DO NOT COMMIT ANYTHING IN THE /SITES FOLDER TO MAIN.** ONLY /DOCS.
2. Commit your changes in /docs to the main branch and push/submit PR.
3. If you have direct edit access (e.g. you're a staff member), run the command `mkdocs gh-deploy`. If all is successful check back on the live version in a few minutes and all should be changed.