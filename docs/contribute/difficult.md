# For Those More Tech-Savvy

The source files for this site are stored at [Axemoor Docs on Github](https://github.com/Axemoor/axemoor-docs)

## Without Contribution Access

If you do not have repository contribution access, create a fork of the repository and clone it to your preferred environment.

You will need to have Python 3 installed, as well as Python packages `mkdocs` and `mkdocs-material`

Do:
```sh
pip install mkdocs mkdocs-material
```

Edit the files in your preferred text editor. 

You can check them by running the mkdocs development server:

from the folder where mkdocs.yml is, do:

```sh
mkdocs serve
```
The pages will now be available at the address specified by the mkdocs server. Load it in a browser.

You can leave the server running and edit in another terminal window, and when you save a file, the server will automatically reload the site for you.

When you are happy with your changes, commit them and push them back to your fork.

On Github, submit a pull request back to the main repository. Describe your changes in the PR description.

The Webminister will review your changes, check out your PR and test your changes, and seek approval at the next meeting if needed.

If your changes are accepted, the Webminister will merge the pull request into the Approved version, then generate the site files and upload them.

## With Contribution Access

The process is mostly the same, except that you can clone the main repository and push changes back.

Create a new branch for your proposed changes - don't push changes to `main`.

Commit and push as needed.

Before your last commit and push, do:

```sh
mkdocs build
```

This will generate the new static files.

Create a Pull Request when you are ready. Include a description of the changes.

Your proposed changes will still be reviewed and brought to the Populace if necessary.

If approved, the Webminister will merge the changes into the main branch and upload the new static files to the webserver.
