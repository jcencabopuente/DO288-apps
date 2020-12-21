# Use the httpd-parent image as base
FROM quay.io/redhattraining/httpd-parent

EXPOSE 8080

RUN rm -rf /run/httpd && mkdir /run/httpd && \
    chgrp -R 0 /run/httpd && \
    chmod -R g=u /run/httpd

USER 1001


