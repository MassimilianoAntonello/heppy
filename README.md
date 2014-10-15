Heppy : a python framework for high-energy physics data analysis
================================================================

Prerequisites
-------------

**python 2.x, x>5**

**ROOT 5, with pyroot support**

Note that you need to ensure that ROOT was compiled with the same version of python as the one in your PATH.

Environment
-----------

From this directory, run the initialization script:

	source init.sh


Examples
--------

Several examples are provided in the test/ directory:

	cd test/

Read a root file and print each event:

	multiloop.py  Trash   print_events_cfg.py

Read a root file and create a simple tree:

	multiloop.py  Trash2  simple_tree_cfg.py

