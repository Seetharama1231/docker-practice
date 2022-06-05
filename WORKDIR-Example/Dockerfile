FROM busybox
RUN mkdir -p /root/demo/context1/context2
WORKDIR /root/demo
RUN touch demo.txt
WORKDIR context1
RUN touch context1.txt
WORKDIR context2
RUN touch context2.txt
CMD ["/bin/sh"]

