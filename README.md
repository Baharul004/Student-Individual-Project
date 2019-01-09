# Student(Individual)Project

My student project topic was "Evaluation of Juju as a Virtualized network function manager (VNFM) for container virtualization"

The main purpose of this student project, Juju will take part with LXD. Combination of Juju and LXD is an efficient way to deploy a software. Juju is working as a service modeling system, which also making relationship between different services and scale between them. Services are deploying in Juju model, which is focusing on machines for configuration management system. Controller will manage all the model associated with its node.
Charms are providing the services for application. To deploy and configure an application juju charm contains the all necessary instructions. Packages are included as operational code in charms which is implemented with installation process. 

In this project, a charm will be written for Kamailio server which will be developed in bash script. All packages for Kamailio should be implemented through this charm, such as installing Kamailio, changing Kamailio config file, creating Kamailio database and so on. Everything will be configured automatically when Kamailio will be deployed from charm in an application container.

In this work, a developed MySQL charm also will be deployed from charm store in an application container. A relation will be established between Kamailio application container and MySQL application container to fulfill the requirements for Kamailio server. At the end, communication will be built up between Kamailio subscribers. Last but not least, how Juju is fulfilling the functionality of VNFM will be described with the practical work.


The names of the main chapters of this student project documentation are in the below:

1.	Introduction
2.	Theoretical Background
3.	Requirements Analysis
4.	Realisation
5.	Demonstration
6.  Evaluation of Juju as VNFM
7.	Summary and Future Perspectives
8.	Abbreviations
9.	References

