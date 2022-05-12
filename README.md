This is my personal website!

I've integrated django_extensions and the Werkzeug server to support local https.
This also required some shenanigans with mkcert. To test local https on other machines,
you'll need to set up your own locally-signed cert and also deal with a bug caused
by a deprecated Werkzeug command used in django_extensions.