FROM golang:1.8
MAINTAINER luyunhua@lancai.cn
RUN go get github.com/Masterminds/glide \
    && cd $GOPATH/src/github.com/Masterminds/glide \
    && make install \
    && rm -rf $GOPATH/src/github.com/ \
    && rm -rf $GOPATH/pkg \
    && rm -f $GOPATH/bin/glide


CMD ["bash"]
