# github-wiki-autosidebar

## What is this?

Github wiki's support a sidebar, that's helpful for navigation, but don't include any tools for this sidebar to be updated automatically (although a list of all available files will always be present)

This is a simple script to automatically create a structured github wiki sidebar, based on the folder structure.

The attached wiki here gives an example of what this looks like.

## How do I use it?

Either just clone and run the autosidebar.py script, or (potentially easier) it can be pip installed with:

```
pip install github-wiki-autosidebar
```

After which the script can be ran from the command line by calling in the base level of your wiki directory:
```
github-wiki-autosidebar
```

## Hidden Files?

Only markdown files will get added into the sidebar, and anything else will be hidden.

The script will also respect hidden files or folders starting with '.' or '_' by not including them in the sidebar directory.
