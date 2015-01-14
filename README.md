SystemOne-Next
==============

The next version of the registration system of the University of the Philippines Los Baños, SystemOne, whose goal is to be a more efficient version than the previous one in terms of performance.

Software and Programming Language
=================================

The current choices are either [Node.JS](http://nodejs.org/) or [Apache/Lighttpd/Nginx+PHP](https://wiki.archlinux.org/index.php/LAMP).
Programming in an object-oriented manner is much easier in PHP as compared to Node.JS. It would be preferable to program this way when working with several people.

However, Node.JS offers a very huge increase in speed compared to PHP according to [benchmarks](http://zgadzaj.com/benchmarking-nodejs-basic-performance-tests-against-apache-php) found on the web. Since the primary goal of this project is to create a much faster replacement for SystemOne v3, Node.JS might be a more viable choice.

We might have to do a benchmark on these two first though. From what I remember, Node.JS is [single-threaded](http://stackoverflow.com/questions/5200821/grasping-the-node-js-alternative-to-multithreading#5203780). I'm not really sure if this is still the case today. 
