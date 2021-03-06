Koolkalang Fork 
---------------
This fork is just meant to see if I can configure the DPA Pipeline to work on my system. 
So far I've gotten it to work within a Xubuntu VM, but am aiming to make it work with Bash on Windows 
(fingers crossed)!


DPA Pipeline Framework (backend)
----------------------------------

This repository represents a backend implementation of a production pipeline framework described in a talk at SIGGRAPH 2014 titled `A Framework for Global Visual Effects Production Pipelines <https://vimeo.com/116364653>`_. The code was developed for, and is used by, the `Digital Production Arts program at Clemson University <http://clemson.edu/dpa>`_. 

This implementation is by no means complete, and the code should be considered a work-in-progress. There are quite a few moving parts and admittedly a ton of room for improvement when it comes to security and authentication, data caching, testing, etc. That said, the core pieces described in the SIGGRAPH talk have been implemented and are in use by DPA students. A few students have also contributed to this codebase and even more are extending it on production - building tools and workflows for themselves and their classmates.

If you are interested in contributing or have questions about the project, please contact `josh-t <https://github.com/josh-t>`_ or `Clemson-DPA <https://github.com/Clemson-DPA>`_.

The front end of this framework can be found here: https://github.com/Clemson-DPA/dpa-pipe
