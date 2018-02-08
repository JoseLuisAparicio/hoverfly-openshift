# hoverfly-openshift
SpectoLabs Hoverfly to include in Openshift
To include hoverfly in Openshift is necessary create two applications: hoverfly-proxy andd hoverfly-webserver, because when hoverfly is stopped, Openshift restart the aplication again in same mode. We need two applications: one with hoverfly as proxy and other hoverfly as webserver.
This repository included Dockerfiles and Templates to create both applications 
