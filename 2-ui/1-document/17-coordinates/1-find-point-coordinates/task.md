importance: 5

---

# Find the coordinates in the document

In the iframe below you can see a document with the green "field".

Use JavaScript to find window coordinates of corners pointed by with arrows.

There's a small feature implemented in the document for convenience. A click at any place shows coordinates there.

[iframe border=1 height=360 src="source" link edit]

Your code should use DOM to get window coordinates of:

1. Left-upper outer corner (that's simple).
2. Right-bottom outer corner (simple too).
3. Left-upper inner corner (a bit harder).
4. Right-bottom inner corner (there are several ways, choose one).

The coordinates that you calculate should be the same as those returned by the mouse click.

P.S. The code should also work if the element has another size or no border.