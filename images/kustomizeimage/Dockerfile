FROM registry.access.redhat.com/ubi8/ubi-init 

RUN yum -y install tar
RUN yum -y install curl 
RUN yum -y install bash
RUN yum -y install git

WORKDIR /usr/local/bin
 
RUN curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh"  | bash

WORKDIR /tmp

CMD [ "/bin/bash" ]
