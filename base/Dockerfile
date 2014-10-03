FROM busybox:latest
RUN date > 00base.step
CMD for f in *.step; do echo $f; cat $f; done

