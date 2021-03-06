# Libraries

The following libraries are used by DNA:

- Measurements & statistics
	- AspectJ <https://eclipse.org/aspectj/>
	- *aspectjrt-1.7.4.jar*
- Datastructures
	- **Guava** <https://github.com/google/guava>
	- *guava-16.0.1.jar*
- Isomorphism check
	- **jGraphT** <http://jgrapht.org>
	- *jgrapht-core-0.9.1.jar*
- Graph visualization
	- **GraphStream** <http://graphstream-project.org>
	- *gs-core-1.3.jar, gs-ui-1.3.jar*
	- **Monte Media Library** <http://www.randelshofer.ch/monte/>
	- *monte-cc.jar*
- Result visualization
	- **jpathwatch** <https://jpathwatch.wordpress.com>
	- *jpathwatch-0-95.jar*
	- **JChart2d** <http://jchart2d.sourceforge.net>
	- *jchart2d\_modified.jar*
		- The library is a hand-modified version of the jchart2d-3.2.2.
		It changed the way NumberFormats are handled on y-axis.
		The library	was overwriting the set NumberFormat on it's own while calculating the
		used space of the y-axis labels. This has been disabled.