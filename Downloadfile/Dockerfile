FROM ubuntu:14.04
MAINTAINER gem <likeyou20@qq.com>

RUN cat https://rawgit.com/kubernetes/dashboard/master/src/deploy/kubernetes-dashboard.yaml > /my-kubernetes-dashboard.yaml
RUN -o /o-kubernetes-dashboard.yaml https://rawgit.com/kubernetes/dashboard/master/src/deploy/kubernetes-dashboard.yaml
RUN -O https://rawgit.com/kubernetes/dashboard/master/src/deploy/kubernetes-dashboard.yaml > kubernetes-dashboard.yaml
