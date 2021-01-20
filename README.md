# bluej-themes

To install a dark theme, you'll need a little bit of terminal.

As a very basic tutorial, your files are stored in a tree of folders, or directories. Using terminal and commands, you can navigate through these directories.



On Mac, press cmd+space, type "terminal", then press enter.

In terminal, type

```bash
cd ~/Library/Preferences/org.bluej
```

and press enter. cd stands for "change directory"; we are just going to a certain folder so we can edit some bluej files.

Now, type

```bash
touch java-colors.css
open java-colors.css
```

(press enter after the first line). This creates and opens a file called `java-colors.css`, which bluej reads off of.

Now, go ahead and open the `java-colors-dark+.css` in this Github repository and copy and paste the contents of the file in `java-colors.css`. Press cmd+s to save.

Your editor should now have dark theme! :)
