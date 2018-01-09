

## Installation of wordcloud on Windows

Follow the steps:
- Download the .whl file compatible with your Python version and your windows distribution (32bit or 64bit) from [here](https://www.lfd.uci.edu/~gohlke/pythonlibs/#wordcloud).
- `cd` to the file path (using [the command prompt](https://www.wikihow.com/Navigate-the-Windows-Directory)).
- Run this command: `python -m pip install <filename>`.

Some possible problems might happened:
- **python not recognised as a command** -- You need to add the python executable path to your Window's PATH variable.
1. From the desktop, right-click My Computer and click Properties.
2. In the System Properties window, click on the Advanced tab.
3. In the Advanced section, click the Environment Variables button.
4. Highlight the Path variable in the Systems Variable section and click the Edit button.
5. Add [the path of your python executable](https://stackoverflow.com/questions/647515/how-can-i-get-python-path-under-windows). Each different directory is separated with a semicolon. (Note: do not put spaces between elements in the PATH. Your addition to the PATH should read ;c:\Python27 NOT ; C\Python27)
6. Apply the changes. You might need to restart your system, though simply restarting cmd.exe should be sufficient.
7. Launch cmd and try again. It should work.
