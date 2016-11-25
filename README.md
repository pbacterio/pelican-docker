Pelican docker image
====================

Example usage:
--------------

    $ sudo docker run --rm -v WEBSITE-SOURCE-DIR:/build/input:ro,Z \
      -v WEBSITE-OUTPUT-DIR:/build/output:Z  pbacterio/pelican-docker
