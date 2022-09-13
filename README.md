Part of pset6 of MIT OCW 6.006 Fall 2011.

Determines the shortest path between two places. Uses The National Highway Planning Network database of USA's major highway system.

* dijkstra.py -  implements Dijkstra's algorithm
* nhpn.py - loader for parsing data from NHPN files
* priority_queue.py - heap-based priority queue

USAGE

dijkstra.py's behavior can be tweaked using the TRACE environment variable. If 
TRACE=kml, two kml files path_flat.kml and path_curved.kml will be created 
representing the shortest path from the source to the destination. The files can
be viewed on Google Map. If not, a text description of the path is output to the
stdout.
