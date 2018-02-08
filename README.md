# hoverfly-openshift
SpectoLabs Hoverfly to include in Openshift

To include hoverfly in Openshift is necessary to create two applications: 

  1.- hoverfly-proxy
  2.- hoverfly-webserver

When hoverfly is stopped to mode change, Openshift restarts the application again in the same mode.

This repository includes Dockerfiles and Templates to create both applications in Openshift Catalog 
