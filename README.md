Silly push over demo
====================

This is a demo to test self-hosted commit pushes to a git tree.
To append just run:

NUM=$(tail -1 README.md)
let NUM=$NUM+1
echo $NUM >> README.md 

1
2
