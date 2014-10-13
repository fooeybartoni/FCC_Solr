FCC_Solr
========

This is a prototype repo to accomplish the following:

* Set up Solr automatically with Vagrant using Ansible
* Parse XML file into Solr for indexing
* Dependent on submodules (not formally identified in Git) to load java, tomcat6, solr, and configure tomcat and solr
  * ansible-role-java
  * ansible-role-tomcat6
  * ansible-role-solr
