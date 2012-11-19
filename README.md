podcasts
========

Simple WSGI application that generates RSS listing all of the video files in a
given directory.  Can be used to feed transcoded videos into iTunes for syncing
to an iPhone/iPad.

Usage
-----

Update the bits of the top of the script that need updating (likely VIDEO_DIR,
VIDEO_WEB_PATH and URL).  Install werkzeug (e.g. pip install werkzeug).

You can then run either run the script on its own (i.e. python podcasts.py), or
server it from apache, gunicorn, etc.. (see http://werkzeug.pocoo.org/docs/deployment/)

Then, add the appropriate URL as a podcast in iTunes.