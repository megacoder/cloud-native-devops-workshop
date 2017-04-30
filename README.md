![](common/images/customer.logo.png)
---
# ORACLE Cloud-Native DevOps workshop #

## Introduction ##

Oracle Cloud is the industry’s broadest and most integrated public cloud. It offers best-in-class services across software as a service (SaaS), platform as a service (PaaS), and infrastructure as a service (IaaS), and even lets you put Oracle Cloud in your own data center. Oracle Cloud helps organizations drive innovation and business transformation by increasing business agility, lowering costs, and reducing IT complexity. The workshop content shows different aspects of Application Development in the cloud using different sets of Oracle Cloud Services.


### Prerequisites ###

The workshop is intended to work with an Oracle PaaS trial account. To get an account look into [here](common/request.for.trial.md). Get the following account details ready to complete the tutorial and replace to your values when it is required:

+ Oracle Cloud account **username** and **password**
+ Oracle Cloud **identity domain**
+ **Data center/region**

NOTE: Before you start to use your new Oracle Public Cloud services ensure the *replication policy* has been set for your account. Otherwise you can not create a storage container, which is necessary for most of the services. See [Selecting a Replication Policy for Oracle Storage Cloud Service](https://docs.oracle.com/cloud/latest/storagecs_common/CSSTO/GUID-5D53C11F-3D9E-43E4-8D1D-DDBB95DEC715.htm).

### Important ###

During the execution you will create several cloud service instances that will be publicly available on the world wide web. Even if these instances are for demo purposes keep in mind it is not a best practice to use weak or known (stored here in the tutorial) passwords.  This is  especially important in an open environment. For this reason the workshop content does not recommend any passwords; you must define those. You will be asked to provide the passwords at certain points. Please remember them  for  later usage.

The content contains several independent modules that cover different aspects of Oracle Cloud application development. These modules could be executed independently unless the Prerequisites state they are interdependent.

----

#### Container based application development lifecycle using Wercker and Container Cloud Service ####

+ [Build Spring Boot container packaged application using Wercker and deploy to Oracle Container Cloud Service](springboot-sample/create.wercker.ci.md)

#### Support SpringBoot application development lifecycle using Oracle Developer Cloud Service, Application Container Cloud Service and Oracle Enterprise Pack For Eclipse ####

+ [Create Oracle Developer Cloud Service project for SpringBoot application](springboot-sample/create.devcs.project.md)
+ [Create continuous build integration using Oracle Developer Cloud Service and Oracle Application Container Cloud Service](springboot-sample/devcs.accs.ci.md)
+ [Using Eclipse IDE (Oracle Enterprise Pack for Eclipse) with Oracle Developer Cloud Service](oepe/setup.oepe.md)

#### Bind Frontend Application running on lightweight container in Oracle Appplication Container Cloud with backend resources running on Java Cloud Service ####

+ [Implement new function (REST client) in SpringBoot sample application using Service Bindings to access Oracle Java Cloud Services](devops-bind/README.md)

#### Perform basic monitoring of application run inside Application Container Cloud thrugh diagnostic capabilities of Java Mission Control and Java Flight Recorder ####

+ [Monitor and tune SpringBoot application deployed on Oracle Application Container Cloud Service](monitor-tune/README.md)

#### Integrate telemetry into continuous delivery and monitor an application using the Oracle Management Cloud ####
+ [Deploying APM Agent on Apache Tomcat based application and setting up Application Performance Monitoring](apm/README.md)

#### Deploy complex cloud environment using Oracle Cloud Stack Manager ###
+ [Deploy complex cloud environment using Oracle Cloud Stack Manager](stack/README.md)

#### Run Lightweight Java container (Tomcat) in the  Oracle Application Container Cloud Service ####

+ [Deploy Apache Tomcat based application to Oracle Application Container Cloud](accs-tomcat/README.md)
+ [Scale up/down Application Container Service using user interface and PaaS Service Manager (PSM) Command Line Interface (CLI) tool](accs-psm/README.md)

#### Deploy Java EE application to Oracle Java Cloud Service ####

+ [Create Database Cloud Service Instance using user interface](dbcs-create/README.md)
+ [Create Java Cloud Service Instance using user interface](jcs-create/README.md)
+ [Prepare Database Cloud Service Instance to store sample application's data](dbcs-prepare/README.md)
+ [Deploy Java EE sample application to Oracle Java Cloud Service using Admin console](jcs-deploy/README.md)

#### Manage Oracle Java Cloud Service using UI and PaaS Service Manager ####

+ [Direct access and management of Oracle Java Cloud Service](jcs-direct/README.md)
+ [Scale-Out Oracle Java Cloud Service using user interface](jcs-scale-ui/README.md)
+ [Scale-In Oracle Java Cloud Service using PaaS Service Manager (PSM) Command Line Interface (CLI)](jcs-scale-psm/README.md)

#### Making Java Cloud Service elastically scalable through Policy based Auto-scaling ####

+ [Oracle Java Cloud Service Policy Based Auto Scaling](jcs-autoscale/README.md)

#### Upgrade WebLogic Server 11g (10.3.6) running on premise to 12cR2 with Multitenancy and migrate to Java Cloud Service ####

+ [Convert WebLogic 11g domain into the 12cR2 partition using DPCT (Domain to Partition Conversion Tool)](dpct/README.md)
+ [Move partition from WebLogic Server 12cR2 to Oracle Java Cloud Service](lift-and-shift/README.md)

#### Migrate WebLogic 10.3.6 (on premise) Application to Java Cloud Service with App2Cloud tool ####

+ [Migrate Weblogic 10.3.6 (on premise) Application to Java Cloud Service with App2Cloud tool](app-2-cloud/README.md)

#### Clean up the environment ####

+ [Delete Java Cloud, Database Cloud and Database Container Services using user interface](cleanup/cleanup-ui.md)
+ [Delete Application Cloud Container Service using PaaS Service Manager (PSM) Command Line Interface (CLI)](cleanup/cleanup-psm.md)

---

#### Customizing and personalizing the workshop content ####

+ [Customize and personalize the workshop materials](customize/README.md)

---

## [Contributing](CONTRIBUTING.md)
Pull Requests are currently not being accepted. See [CONTRIBUTING](CONTRIBUTING.md) for details.

## [License](LICENSE.md)
Copyright (c) 2014, 2016 Oracle and/or its affiliates
The Universal Permissive License (UPL), Version 1.0
