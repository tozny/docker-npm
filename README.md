docker-npm
=============

Stable Docker container for Node, NPM, and Make built on top of Alpine Linux.


Usage
-----

Run the image manually using:

    docker run -it --rm -v $(pwd):/src tozny/npm [command] [parameters]