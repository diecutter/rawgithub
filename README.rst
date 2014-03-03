RawGithub
=========

rawgithub is a simple wsgi server that allows you to serve a file from Github even if you need to provide an access_token.

Just do:

    GET /:owner/:repo/:file?[access_token=<your_token>]&[ref=master]

And that's all.

Run the service
+++++++++++++++

    pserve rawgithub.ini
