FROM registry.access.redhat.com/ubi8:latest

LABEL io.openshift.s2i.scripts-url="image:///usr/libexec/s2i"

ADD s2i /usr/libexec/s2i
USER 1001
CMD ["/usr/libexec/s2i/run"]
