FROM registry.access.redhat.com/ubi8/ubi-init 

RUN yum -y install tar, curl, git, bash; yum clean all

RUN curl -s "https://raw.githubusercontent.com/kubernetes-sigs/kustomize/master/hack/install_kustomize.sh"  | bash

CMD [ "/bin/bash" ]
