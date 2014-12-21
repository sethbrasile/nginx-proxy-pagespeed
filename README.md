**note** Some of combro2k's recent changes has broken this container (for me at least) and I haven't had a chance to figure out why. If you're having problems, stop using this Dockerfile, and just pull the pre-built container from Docker Hub.

nginx-proxy-pagespeed
=====================

Based on combro2k/nginx-proxy
To enable Pagespeed module per host 
docker run .... -e PAGESPEED=1
