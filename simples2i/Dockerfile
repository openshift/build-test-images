FROM quay.io/quay/busybox:latest

LABEL io.openshift.s2i.scripts-url="image:///usr/libexec/s2i"

ADD s2i /usr/libexec/s2i
CMD ["/usr/libexec/s2i/run"]

