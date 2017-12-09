Visualize your Git!
===================

It makes pictures that look like this:

![](http://i.imgur.com/ezMmOXv.png)

Note: the original implementation doesn't really support any aliases or functions that you may have
for git functionality, which means it's probably not very helpful in its current state.

How To Use
-------------------

```
mktmpenv -n
pip install -r requirements.local.txt
history | python git-workflow.py > graph.svg
deactivate

# Open the SVG file in a web browser with `open .` and then
# right-clicking the file and choosing Open With > Google Chrome
```
