# LICENSE UPL 1.0
#
# Copyright (c) 2015 Oracle and/or its affiliates. All rights reserved.
#
FROM ubuntu:16.04

MAINTAINER Cristian Suarez <cristian.suarez@clarochile.cl>

RUN apt-get update
RUN apt-get install python-neutronclient python-novaclient python-keystoneclient python-netaddr unzip wget python-pip python-dev python-yaml vim python-cinderclient -y
RUN pip install prometheus_client 

RUN wget https://github.com/CanonicalLtd/prometheus-openstack-exporter/archive/master.zip
RUN unzip master.zip
EXPOSE 9183



