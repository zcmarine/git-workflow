Visualize your Git!
===================

It makes pictures that look like this:

![](http://i.imgur.com/ezMmOXv.png)


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
