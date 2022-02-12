# Elastic and kibana's ansible playbook
This playbook will install elasticsearch and kibana

A few of the things these playbooks accomplish:
- Install java
  - Set facts
  - Upload from local storage
  - Extract
- Install Elasticsearch
  - Upload from remote URL
  - Extract
- Install Kibana
  - Upload from remote URL
  - Extract

Playbook has some parameters:
- all
  - java_jdk_version
  - java_oracle_jdk_package
- elasticsearch
  - elastic_version
  - elastic_home
- kibana
  - kibana_version
  - kibana_home

Tags in playbook:
- java
- elastic
- kibana