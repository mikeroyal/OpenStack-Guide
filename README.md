<h1 align="center">
 <img src="https://user-images.githubusercontent.com/45159366/113783692-f9a74480-96e8-11eb-9c2f-513c663ee1f5.png">
  <br />
 OpenStack Guide
</h1>

 #### A guide for getting started with OpenStack inlcuding the Tools and Applications that make you a better and more efficient engineer with OpenStack.
 
 **Note: You can easily convert this markdown file to a PDF in [VSCode](https://code.visualstudio.com/) using this handy extension [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf).**
 
 
# Table of Contents

1. [OpenStack Learning Resources](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#docker-learning-resources)

2. [Openstack Tools](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#docker-tools)

3. [OpenStack Devops Tools Integration](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#docker-devops-tools-integration)
 
4. [Networking](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#networking)

5. [Databases](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#databases)

6. [Telco 5G](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#telco-5g)

7. [Open Source Security](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#open-source-security)

8. [Kubernetes](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#kubernetes)

9. [Machine Learning](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#machine-learning)

10. [Python Development](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#python-development)

11. [Ruby Development](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#ruby-development)

12. [Node.js Development](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#nodejs-development)

13. [Go Development](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#go-development)

14. [Bash/PowerShell Development](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#bashpowershell-development)


 <img src="https://user-images.githubusercontent.com/45159366/113783694-fad87180-96e8-11eb-9ae5-d48ece38afe6.png">
 
**OpenStack integrated with VMware. Source: [VMware](https://blogs.vmware.com/telco/vmware-integrated-openstack-6-0-whats-new/)**

## OpenStack Learning Resources

[Open Stack](https://www.openstack.org/) is an open source cloud platform, deployed as infrastructure-as-a-service (IaaS) to orchestrate data center operations on bare metal, private cloud hardware, public cloud resources, or both (hybrid/multi-cloud architecture). OpenStack includes advance use of virtualization & SDN for network traffic optimization to handle the core cloud-computing services of compute, networking, storage, identity, and image services.

[OpenStack Wiki](https://wiki.openstack.org/)

[OpenStack Community](https://www.openstack.org/community/)

[OpenStack Marketplace](https://www.openstack.org/marketplace/)

[Use Cases for OpenStack in Production](https://www.openstack.org/use-cases/)

[OpenStack Training Program](https://www.openstack.org/marketplace/training/)

[Red Hat OpenStack training and certification](https://www.redhat.com/en/services/training/openstack)

[OpenStack, Cloud Native & MOSK Training and Certification from Mirantis](https://training.mirantis.com/)

[OpenStack Courses on Udemy](https://www.udemy.com/topic/openstack/)

[Introduction to OpenStack on edX](https://www.edx.org/course/introduction-to-openstack)

[OpenStack- Introduction to private cloud course on Coursera](https://www.coursera.org/lecture/private-cloud-ibm-power-systems/openstack-in-detail-kLMKE)

## OpenStack Tools

[Back to the Top](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#table-of-contents)

[OpenStack Deployment Tools](https://www.openstack.org/software/project-navigator/deployment-tools)

[OpenStackClient(OSC)](https://www.openstack.org/software/releases/victoria/components/openstackclient) is a command-line client for OpenStack that brings the command set for Compute, Identity, Image, Object Storage and Block Storage APIs together in a single shell with a uniform command structure.

[Airship](https://www.airshipit.org/) is a collection of open source tools for automating cloud provisioning and management. Airship provides a declarative framework for defining and managing the life cycle of open infrastructure tools and the underlying hardware. These tools include [OpenStack](https://wiki.openstack.org/wiki/Airship) for virtual machines, Kubernetes for container orchestration, and MaaS for bare metal, with planned support for OpenStack Ironic.

[NOVA](https://www.openstack.org/software/releases/victoria/components/nova) is a collection of services and associated libraries to provide massively scalable, on demand, self service access to compute resources, including bare metal, virtual machines, and containers.

[ZUN](https://www.openstack.org/software/releases/victoria/components/zun) is an OpenStack API for launching and managing containers backed by different container technologies. Different from Magnum, Zun is for users who want to treat containers as OpenStack-managed resource. Containers managed by Zun are supposed to be integrated well with other OpenStack resources, such as Neutron network and Cinder volume. Users are provided a simplified APIs to manage containers without the need to explore the complexities of different container technologies.

[SWIFT](https://www.openstack.org/software/releases/victoria/components/swift) is a highly available, distributed, eventually consistent object/blob store. Organizations can use Swift to store lots of data efficiently, safely, and cheaply. It's built for scale and optimized for durability, availability, and concurrency across the entire data set. 

[CINDER](https://www.openstack.org/software/releases/victoria/components/cinder) is a Block Storage service for OpenStack. It virtualizes the management of block storage devices and provides end users with a self service API to request and consume those resources without requiring any knowledge of where their storage is actually deployed or on what type of device.

[NEUTRON](https://www.openstack.org/software/releases/victoria/components/neutron) is an SDN networking project focused on delivering networking-as-a-service (NaaS) in virtual compute environments.

[OCTAVIA](https://www.openstack.org/software/releases/victoria/components/octavia) is an open source, operator-scale load balancing solution designed to work with OpenStack. Octavia was borne out of the Neutron LBaaS project, and starting with the Liberty release of OpenStack, Octavia has become the reference implementation for Neutron LBaaS version 2. Octavia accomplishes its delivery of load balancing services by managing a fleet of virtual machines, containers, or bare metal servers known as amphorae, which it spins up on demand.

[DESIGNATE](https://www.openstack.org/software/releases/victoria/components/designate) is a DNS-as-a-service for OpenStack.

[KEYSTONE](https://www.openstack.org/software/releases/victoria/components/keystone) is an OpenStack service that provides API client authentication, service discovery, and distributed multi-tenant authorization by implementing OpenStack’s Identity API. It supports LDAP, OAuth, OpenID Connect, SAML and SQL.

[GLANCE](https://www.openstack.org/software/releases/victoria/components/glance) is an image services include discovering, registering, and retrieving virtual machine images. Glance has a RESTful API that allows querying of VM image metadata as well as retrieval of the actual image. VM images made available through Glance can be stored in a variety of locations from simple filesystems to object-storage systems like the OpenStack Swift project.

[HEAT](https://www.openstack.org/software/releases/victoria/components/heat) is an orchestrates system that provides infrastructure resources for a cloud application based on templates in the form of text files that can be treated like code. Heat provides both an OpenStack-native ReST API and a CloudFormation-compatible Query API. Heat also provides an autoscaling service that integrates with the OpenStack Telemetry services, so you can include a scaling group as a resource in a template.

[SENLIN](https://www.openstack.org/software/releases/victoria/components/senlin) is a clustering service for OpenStack clouds. It creates and operates clusters of homogeneous objects exposed by other OpenStack services. The goal is to make orchestration of collections of similar objects easier.

[MAGNUM](https://www.openstack.org/software/releases/victoria/components/magnum) is a container orchestration engines such as Docker Swarm, Kubernetes, and Apache Mesos available as first class resources in OpenStack. Magnum uses Heat to orchestrate an OS image which contains Docker and Kubernetes and runs that image in either virtual machines or bare metal in a cluster configuration.

[FREEZER](https://www.openstack.org/software/releases/victoria/components/freezer) is a distributed backup, restore and disaster recovery as a service platform. It is designed to be multi OS (Linux, Windows, macOS), focused on providing efficiency and flexibility for block based backups, file based incremental backups, point-in-time actions, jobs synchronization (backup synchronization over multiple nodes) and many other features. It is aimed at being useful for all environments, including large ephemeral Clouds.

[EC2API](https://www.openstack.org/software/releases/victoria/components/ec2api) is an EC2-compatible API to OpenStack Nova.

[HORIZON](https://www.openstack.org/software/releases/victoria/components/horizon) is a canonical implementation of OpenStack's dashboard, which is extensible and provides a web based user interface to OpenStack services.

[Other OpenStack Components](https://www.openstack.org/software/project-navigator/openstack-components#openstack-services)

# OpenStack DevOps Tools Integration

[Back to the Top](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#table-of-contents)


[Ansible](https://www.ansible.com/) is a simple IT automation engine that automates cloud provisioning, configuration management, application deployment, intra-service orchestration, and many other IT needs. It uses a very simple language (YAML, in the form of Ansible Playbooks) that allows you to describe your automation jobs in a way that approaches plain English. Anisble works on Linux (Red Hat EnterPrise Linux(RHEL) and Ubuntu) and Microsoft Windows.

[Ansible cmdb](https://github.com/fboender/ansible-cmdb) is a tool that takes the output of Ansible’s fact gathering and converts it into a static HTML overview page containing system configuration information.

[Ansible Inventory Grapher](https://github.com/willthames/ansible-inventory-grapher) visually displays inventory inheritance hierarchies and at what level a variable is defined in inventory.

[Ansible Playbook Grapher](https://github.com/haidaraM/ansible-playbook-grapher) is a  command line tool to create a graph representing your Ansible playbook tasks and roles.

[Ansible Shell](https://github.com/dominis/ansible-shell) is an interactive shell for Ansible with built-in tab completion for all the modules.

[Ansible Silo](https://github.com/groupon/ansible-silo) is a self-contained Ansible environment by [Docker](https://www.docker.com/).

[Ansigenome](https://github.com/nickjj/ansigenome) is a command line tool designed to help you manage your Ansible roles.

[ARA](https://github.com/openstack/ara) is a records Ansible playbook runs and makes the recorded data available and intuitive for users and systems by integrating with Ansible as a callback plugin.

[Red Hat OpenShift](https://www.openshift.com/) is focused on security at every level of the container stack and throughout the application lifecycle. It includes long-term, enterprise support from one of the leading Kubernetes contributors and open source software companies.

[OpenShift Hive](https://github.com/openshift/hive) is an operator which runs as a service on top of Kubernetes/OpenShift. The Hive service can be used to provision and perform initial configuration of OpenShift 4 clusters.

[GitHub](https://github.com/) provides hosting for software development version control using Git. It offers all of the distributed version control and source code management functionality of Git as well as adding its own features. It provides access control and several collaboration features such as bug tracking, feature requests, task management, and wikis for every project.

[GitHub Codespaces](https://docs.github.com/en/free-pro-team@latest/github/developing-online-with-codespaces) is an integrated development environment(IDE) on GitHub. That allows developers to develop entirely in the cloud using Visual Studio and Visual Studio Code.
  
[GitHub Actions](https://docs.github.com/en/actions) will automate, customize, and execute your software development workflows right in your repository with GitHub Actions. You can discover, create, and share actions to perform any job you'd like, including CI/CD, and combine actions in a completely customized workflow.[GitHub Actions for Azure](https://docs.microsoft.com/en-us/azure/developer/github/github-actions) you can create workflows that you can set up in your repository to build, test, package, release and deploy to Azure.Learn more about all other integrations with Azure.

[GitLab](https://about.gitlab.com/) is a web-based DevOps lifecycle tool that provides a Git-repository manager providing wiki, issue-tracking and CI/CD pipeline features, using an open-source license, developed by GitLab Inc.

[Jenkins](https://jenkins.io/) is a free and open source automation server. Jenkins helps to automate the non-human part of the software development process, with continuous integration and facilitating technical aspects of continuous delivery.

[Bitbucket](https://bitbucket.org/) is a web-based version control repository hosting service owned by Atlassian, for source code and development projects that use either Mercurial or Git revision control systems. Bitbucket offers both commercial plans and free accounts. It offers free accounts with an unlimited number of private repositories. Bitbucket integrates with other Atlassian software like Jira, HipChat, Confluence and Bamboo.

[Bamboo](https://www.atlassian.com/software/bamboo) is a continuous integration (CI) server that can be used to automate the release management for a software application, creating a continuous delivery pipeline.

[Codecov](https://codecov.io/) is the leading, dedicated code coverage solution. It provides highly integrated tools to group, merge, archive and compare coverage reports. Whether your team is comparing changes in a pull request or reviewing a single commit, Codecov will improve the code review workflow and quality.

[Drone](https://drone.io/) is a Continuous Delivery system built on container technology. Drone uses a simple YAML configuration file, a superset of docker-compose, to define and execute Pipelines inside Docker containers.

[Travis CI](https://travis-ci.org/) is a hosted continuous integration service used to build and test software projects hosted at GitHub.

[Circle CI](https://circleci.com/) is a continuous integration and continuous delivery platform that helps software teams work smarter, faster.

[Zuul-CI](https://zuul-ci.org/index.html) is a program that drives continuous integration, delivery, and deployment systems with a focus on project gating and interrelated projects. Using the same [Ansible playbooks](https://docs.ansible.com/ansible/latest/user_guide/playbooks.html) to deploy your system and run your tests.

[Artifactory](https://jfrog.com/artifactory/) is a Universal Artifact Repository Manager developed by JFrog. It supports all major packages, enterprise ready security, clustered, HA, Docker registry, multi-site replication and scalable.

[Azure DevOps](https://azure.microsoft.com/en-us/services/devops/?nav=min) is a set of services for teams to share code, track work, and ship software; CLIs Build, deploy, diagnose, and manage multi-platform, scalable apps and services; Azure Pipelines Continuously build, test, and deploy to any platform and cloud; Azure Lab Services Set up labs for classrooms, trials, development and testing, and other scenarios.

[Team City](https://www.jetbrains.com/teamcity/) is a build management and continuous integration server from JetBrains.

[Shippable](https://www.shippable.com/) simplifies DevOps and makes it systematic with an Assembly Line platform that is heterogeneous, flexible, and provides complete visibility across your DevOps workflows. 

[Spinnaker](https://www.spinnaker.io/) is an open source, multi-cloud continuous delivery platform for releasing software changes with high velocity and confidence.

[AWS CodeBuild](https://aws.amazon.com/codebuild/) is a fully managed continuous integration service that compiles source code, runs tests, and produces software packages that are ready to deploy. With CodeBuild, you don't need to provision, manage, and scale your own build servers.

[Selenium](https://www.seleniumhq.org/) is a free (open source) automated testing suite for web applications across different browsers and platforms. 

[Cucumber](https://cucumber.io/) is a tool based on Behavior Driven Development (BDD) framework which is used to write acceptance tests for the web application. It allows automation of functional validation in easily readable and understandable format (like plain English) to Business Analysts, Developers, and Testers.

[JUnit](https://junit.org/junit5/) is a unit testing framework for the Java programming language.

[Mocha](https://mochajs.org/) is a JavaScript test framework for Node.js programs, featuring browser support, asynchronous testing, test coverage reports, and use of any assertion library.

[Karma](https://karma-runner.github.io/latest/index.html) is a simple tool that allows you to execute JavaScript code in multiple real browsers.

[Jasmine](https://jasmine.github.io/) is an open source testing framework for JavaScript. It aims to run on any JavaScript-enabled platform, to not intrude on the application nor the IDE, and to have easy-to-read syntax.

[Maven](https://maven.apache.org/) is a build automation tool used primarily for Java projects. Maven can also be used to build and manage projects written in C#, Ruby, Scala, and other languages. The Maven project is hosted by the Apache Software Foundation.

[Gradle](https://gradle.org/) is an open-source build-automation system that builds upon the concepts of Apache Ant and Apache Maven and introduces a Groovy-based domain-specific language instead of the XML form used by Apache Maven for declaring the project configuration.

[Chef](https://www.chef.io/) is an effortless Infrastructure Suite offers visibility into security and compliance status across all infrastructure and makes it easy to detect and correct issues long before they reach production.

[Puppet](https://puppet.com/) is an open source tool that makes continuous integration and delivery of your software on traditional or containerized infrastructure easy by pulling together all your existing tools and giving you flexibility to deploy your way. 

[KubeInit](https://github.com/kubeinit/kubeinit) provides Ansible playbooks and roles for the deployment and configuration of multiple Kubernetes distributions.

[Salt](https://www.saltstack.com/) is Python-based, open-source software for event-driven IT automation, remote task execution, and configuration management. Supporting the "Infrastructure as Code" approach to data center system and network deployment and management, configuration automation, SecOps orchestration, vulnerability remediation, and hybrid cloud control. 

[Terraform](https://www.terraform.io/) is an open-source infrastructure as code software tool created by HashiCorp.It enables users to define and provision a datacenter infrastructure using a high-level configuration language known as Hashicorp Configuration Language (HCL), or optionally JSON.

[Consul](https://www.consul.io) is a service networking solution to connect and secure services across any runtime platform and public or private cloud.

[Packer](https://www.packer.io/) is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

[Nomad](https://www.nomadproject.io/) is a highly available, distributed, data-center aware cluster and application scheduler designed to support the modern datacenter with support for long-running services, batch jobs, and much more.

[Vagrant](https://www.vagrantup.com/) is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time and increases production parity.

[Vault](https://www.hashicorp.com/products/vault/) is a tool for securely accessing secrets. A secret is anything that you want to tightly control access to, such as API keys, passwords, certificates, and more. Vault provides a unified interface to any secret, while providing tight access control and recording a detailed audit log.

[CFEngine](https://cfengine.com/) is an open-source configuration management system, written by Mark Burgess.Its primary function is to provide automated configuration and maintenance of large-scale computer systems, including the unified management of servers, desktops, consumer and industrial devices, embedded networked devices, mobile smartphones, and tablet computers.

[Octpus Deploy](https://octopus.com/) is the deployment automation server for your entire team, designed to make it easy to orchestrate releases and deploy applications, whether on-premises or in the cloud.

[AWS CodeDeploy](https://aws.amazon.com/codedeploy/) is a fully managed deployment service that automates software deployments to a variety of compute services such as Amazon EC2, AWS Fargate, AWS Lambda, and your on-premises servers. AWS CodeDeploy makes it easier for you to rapidly release new features, helps you avoid downtime during application deployment, and handles the complexity of updating your applications.

[Kubernetes](https://kubernetes.io/) is an open-source container-orchestration system for automating application deployment, scaling, and management. It was originally designed by Google, and is now maintained by the Cloud Native Computing Foundation.

[Docker](https://www.docker.com/) is a set of platform as a service products that use OS-level virtualization to deliver software in packages called containers. Containers are isolated from one another and bundle their own software, libraries and configuration files; they can communicate with each other through well-defined channels. All containers are run by a single operating-system kernel and are thus more lightweight than virtual machines.

[PowerShell/PowerShell Core](https://docs.microsoft.com/en-us/powershell/) is a cross-platform (Windows, Linux, and macOS) automation and configuration tool/framework that works well with your existing tools and is optimized for dealing with structured data (e.g. JSON, CSV, XML, etc.), REST APIs, and object models. It includes a command-line shell, an associated scripting language and a framework for processing cmdlets.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) creates virtual machines on Windows 10. Hyper-V can be enabled in many ways including using the Windows 10 control panel, PowerShell or using the Deployment Imaging Servicing and Management tool (DISM).

[Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor) is an open source Virtual Machine Monitor (VMM) that runs on top of [KVM](https://www.kernel.org/doc/Documentation/virtual/kvm/api.txt). The project focuses on exclusively running modern, cloud workloads, on top of a limited set of hardware architectures and platforms. Cloud workloads refers to those that are usually run by customers inside a cloud provider. Cloud Hypervisor is implemented in [Rust](https://www.rust-lang.org/) and is based on the [rust-vmm](https://github.com/rust-vmm) crates.

[VMware vSphere Hypervisor](https://www.vmware.com/products/vsphere-hypervisor.html) is a bare-metal hypervisor that virtualizes servers; allowing you to consolidate your applications while saving time and money managing your IT infrastructure.

[VMware vSphere](https://www.vmware.com/products/vsphere.html) is the industry-leading compute virtualization platform, and your first step to application modernization. It has been rearchitected with native Kubernetes to allow customers to modernize the 70 million+ workloads now running on vSphere.

[VMware Tanzu](https://tanzu.vmware.com/tanzu) is a centralized management platform for consistently operating and securing your Kubernetes infrastructure and modern applications across multiple teams and private/public clouds.

[Rancher](https://rancher.com/) is a complete software stack for teams adopting containers. It addresses the operational and security challenges of managing multiple Kubernetes clusters, while providing DevOps teams with integrated tools for running containerized workloads.

[K3s](https://github.com/rancher/k3s) is a highly available, certified Kubernetes distribution designed for production workloads in unattended, resource-constrained, remote locations or inside IoT appliances. 

[Rook](https://rook.io/) is an open source cloud-native storage orchestrator for Kubernetes that turns distributed storage systems into self-managing, self-scaling, self-healing storage services. It automates the tasks of a storage administrator: deployment, bootstrapping, configuration, provisioning, scaling, upgrading, migration, disaster recovery, monitoring, and resource management.

[Google Kubernetes Engine (GKE)](https://cloud.google.com/kubernetes-engine/) is a managed, production-ready environment for deploying containerized applications.

[Anthos](https://cloud.google.com/anthos/docs/concepts/overview) is a modern application management platform that provides a consistent development and operations experience for cloud and on-premises environments.

[AWS ECS](https://aws.amazon.com/ecs/) is a highly scalable, high-performance container orchestration service that supports Docker containers and allows you to easily run and scale containerized applications on AWS. Amazon ECS eliminates the need for you to install and operate your own container orchestration software, manage and scale a cluster of virtual machines, or schedule containers on those virtual machines.

[Apache Mesos](http://mesos.apache.org/) is a cluster manager that provides efficient resource isolation and sharing across distributed applications, or frameworks. It can run Hadoop, Jenkins, Spark, Aurora, and other frameworks on a dynamically shared pool of nodes.

[Apache Spark](https://spark.apache.org/) is a unified analytics engine for big data processing, with built-in modules for streaming, SQL, machine learning and graph processing.

[Apache Hadoop](http://hadoop.apache.org/) is a framework that allows for the distributed processing of large data sets across clusters of computers using simple programming models. It is designed to scale up from single servers to thousands of machines, each offering local computation and storage. Rather than rely on hardware to deliver high-availability, the library itself is designed to detect and handle failures at the application layer, so delivering a highly-available service on top of a cluster of computers, each of which may be prone to failures.

[Microsoft Azure](https://azure.microsoft.com/en-us/) is a cloud computing service created by Microsoft for building, testing, deploying, and managing applications and services through Microsoft-managed data centers.

[Azure Functions](https://azure.microsoft.com/en-us/services/functions/) is a solution for easily running small pieces of code, or "functions," in the cloud. You can write just the code you need for the problem at hand, without worrying about a whole application or the infrastructure to run it. 

[Rkt](https://coreos.com/rkt/) is a pod-native container engine for Linux. It is composable, secure, and built on standards. 

[AWS Lambda](https://aws.amazon.com/lambda/) is an event-driven, serverless computing platform provided by Amazon as a part of the Amazon Web Services. It is a computing service that runs code in response to events and automatically manages the computing resources required by that code.

[Helm](https://helm.sh/) is the Kubernetes Package Manager.

[Kubespray](https://kubespray.io/) is a tool that combines Kubernetes and Ansible to easily install Kubernetes clusters that can be deployed on [AWS](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/aws.md), GCE, [Azure](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/azure.md), [OpenStack](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/openstack.md), [vSphere](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/vsphere.md), [Packet](https://github.com/kubernetes-sigs/kubespray/blob/master/docs/packet.md) (bare metal), Oracle Cloud Infrastructure (Experimental), or Baremetal

[OKD](https://okd.io/) is a community distribution of Kubernetes optimized for continuous application development and multi-tenant deployment. OKD adds developer and operations-centric tools on top of Kubernetes to enable rapid application development, easy deployment and scaling, and long-term lifecycle maintenance for small and large teams.

[Odo](https://odo.dev/) is a fast, iterative, and straightforward CLI tool for developers who write, build, and deploy applications on Kubernetes and OpenShift.

[Kata Operator](https://github.com/openshift/kata-operator) is an operator to perform lifecycle management (install/upgrade/uninstall) of [Kata Runtime](https://katacontainers.io/) on Openshift as well as Kubernetes cluster.

[Knative](https://knative.dev/) is a Kubernetes-based platform to build, deploy, and manage modern serverless workloads. Knative takes care of the operational overhead details of networking, autoscaling (even to zero), and revision tracking. 

[Etcd](https://etcd.io/) is a distributed key-value store that provides a reliable way to store data that needs to be accessed by a distributed system or cluster of machines. Etcd is used as the backend for service discovery and stores cluster state and configuration for Kubernetes.

[OpenStack](https://www.openstack.org/) is a free and open-source software platform for cloud computing, mostly deployed as infrastructure-as-a-service that controls large pools of compute, storage, and networking resources throughout a datacenter, managed through a dashboard or via the OpenStack API. OpenStack works with popular enterprise and open source technologies making it ideal for heterogeneous infrastructure.

[Cloud Foundry](https://www.cloudfoundry.org/) is an open source, multi cloud application platform as a service that makes it faster and easier to build, test, deploy and scale applications, providing a choice of clouds, developer frameworks, and application services. It is an open source project and is available through a variety of private cloud distributions and public cloud instances. 

[Splunk](https://www.splunk.com/) software is used for searching, monitoring, and analyzing machine-generated big data, via a Web-style interface.

[Prometheus](https://prometheus.io/) is a free software application used for event monitoring and alerting. It records real-time metrics in a time series database (allowing for high dimensionality) built using a HTTP pull model, with flexible queries and real-time alerting.

[Loki](https://grafana.com/oss/loki/) is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. It is designed to be very cost effective and easy to operate. It does not index the contents of the logs, but rather a set of labels for each log stream.

[Thanos](https://thanos.io/) is a set of components that can be composed into a highly available metric system with unlimited storage capacity, which can be added seamlessly on top of existing Prometheus deployments.

[Container Storage Interface (CSI)](https://www.architecting.it/blog/container-storage-interface/) is an API that lets container orchestration platforms like Kubernetes seamlessly communicate with stored data via a plug-in.

[OpenEBS](https://openebs.io/) is a Kubernetes-based tool to create stateful applications using Container Attached Storage.

[ElasticSearch](https://www.elastic.co/) is a search engine based on the Lucene library. It provides a distributed, multitenant-capable full-text search engine with an HTTP web interface and schema-free JSON documents. Elasticsearch is developed in Java.

[Logstash](https://www.elastic.co/products/logstash) is a tool for managing events and logs. When used generically, the term encompasses a larger system of log collection, processing, storage and searching activities.

[Kibana](https://www.elastic.co/products/kibana) is an open source data visualization plugin for Elasticsearch. It provides visualization capabilities on top of the content indexed on an Elasticsearch cluster. Users can create bar, line and scatter plots, or pie charts and maps on top of large volumes of data.

[New Relic](https://newrelic.com/) is a SaaS-based monitoring tool that fully supports the way DevOps teams work in the modern enterprise by streamlining your workflows with today's collaboration software and orchestration tools like Puppet, Chef, and Ansible.

[Nagios](https://www.nagios.org/) is a free and open source computer-software application that monitors systems, networks and infrastructure. Nagios offers monitoring and alerting services for servers, switches, applications and services. It alerts users when things go wrong and alerts them a second time when the problem has been resolved.

[SonarQube](https://www.sonarqube.org/) is an open-source platform developed by SonarSource for continuous inspection of code quality to perform automatic reviews with static analysis of code to detect bugs, code smells, and security vulnerabilities on 20+ programming languages.

[Genie](https://netflix.github.io/genie) is a federated job orchestration engine developed by Netflix. Genie provides REST APIs to run a variety of big data jobs like Hadoop, Pig, Hive, Spark, Presto, Sqoop and more. It also provides APIs for managing the metadata of many distributed processing clusters and the commands and applications which run on them.

[Inviso](https://github.com/Netflix/inviso) is a lightweight tool that provides the ability to search for Hadoop jobs, visualize the performance, and view cluster utilization.

[Fenzo](https://github.com/Netflix/Fenzo) is a scheduler Java library for Apache Mesos frameworks that supports plugins for scheduling optimizations and facilitates cluster autoscaling.

[Dynomite](https://github.com/Netflix/dynomite) is a thin, distributed dynamo layer for different storage engines and protocols, which includes [Redis](http://redis.io/) and [Memcached](http://www.memcached.org/). Dynomite supports multi-datacenter replication and is designed for High Availability(HA).

[Dyno](https://github.com/Netflix/dynomite) is a tool that is used to scale a Java client application utilizing [Dynomite](https://github.com/Netflix/dynomite).

[Raigad](https://github.com/Netflix/Raigad) is a process/tool that runs alongside Elasticsearch to automate backup/recovery, Deployments and Centralized Configuration management.

[Priam](https://github.com/Netflix/Priam) is a process/tool that runs alongside Apache Cassandra to automate backup/recovery, Deployments and Centralized Configuration management.

[Chaos Monkey](https://github.com/Netflix/chaosmonkey) is a resiliency tool  used to randomly terminates virtual machine instances and containers that run inside of your production environment. Chaos Monkey should work with any backend that [Spinnaker](http://www.spinnaker.io/) supports (AWS, Google Compute Engine, Microsoft Azure, Kubernetes, and Cloud Foundry).

[Falcor](https://netflix.github.io/falcor/) is a JavaScript library for efficient data fetching. Falcor lets you represent all your remote data sources as a single domain model via a virtual JSON graph, whether in memory on the client or over the network on the server.

[Restify](https://github.com/restify/node-restify) is a framework, utilizing [connect](https://github.com/senchalabs/connect) style middleware for building REST APIs. 

[Traefik](https://traefik.io/traefik/) is an open source Edge Router that makes publishing your services a fun and easy experience. It receives requests on behalf of your system and finds out which components are responsible for handling them. What sets Traefik apart, besides its many features, is that it automatically discovers the right configuration for your services.

[Jira](https://www.atlassian.com/software/jira) is a proprietary issue tracking product developed by Atlassian that allows bug tracking and agile project management.

[Pivotal Tracker](https://www.pivotaltracker.com/) is the agile project management tool of choice for developers around the world for real-time collaboration around a shared, prioritized backlog.

# Networking

[Back to the Top](https://github.com/mikeroyal/OpenStack-Guide/blob/main/README.md#table-of-contents)

## Networking Learning Resources
  
[AWS Certified Security - Specialty Certification](https://aws.amazon.com/certification/certified-security-specialty/)

[Microsoft Certified: Azure Security Engineer Associate](https://docs.microsoft.com/en-us/learn/certifications/azure-security-engineer)

[Google Cloud Certified Professional Cloud Security Engineer](https://cloud.google.com/certification/cloud-security-engineer)

[Cisco Security Certifications](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications/security.html)

[The Red Hat Certified Specialist in Security: Linux](https://www.redhat.com/en/services/training/ex415-red-hat-certified-specialist-security-linux-exam)

[Linux Professional Institute LPIC-3 Enterprise Security Certification](https://www.lpi.org/our-certifications/lpic-3-303-overview)

[Cybersecurity Training and Courses from IBM Skills](https://www.ibm.com/skills/topics/cybersecurity/)

[Cybersecurity Courses and Certifications by Offensive Security](https://www.offensive-security.com/courses-and-certifications/)  
  
[Citrix Certified Associate – Networking(CCA-N)](http://training.citrix.com/cms/index.php/certification/networking/)

[Citrix Certified Professional – Virtualization(CCP-V)](https://www.globalknowledge.com/us-en/training/certification-prep/brands/citrix/section/virtualization/citrix-certified-professional-virtualization-ccp-v/)

[CCNP Routing and Switching](https://learningnetwork.cisco.com/s/ccnp-enterprise)

[Certified Information Security Manager(CISM)](https://www.isaca.org/credentialing/cism)

[Wireshark Certified Network Analyst (WCNA)](https://www.wiresharktraining.com/certification.html)

[Juniper Networks Certification Program Enterprise (JNCP)](https://www.juniper.net/us/en/training/certification/)

[Networking courses and specializations from Coursera](https://www.coursera.org/browse/information-technology/networking)

[Network & Security Courses from Udemy](https://www.udemy.com/courses/it-and-software/network-and-security/)

[Network & Security Courses from edX](https://www.edx.org/learn/cybersecurity)
  
## Tools & Networking Concepts
  
    • Connection: In networking, a connection refers to pieces of related information that are transferred through a network. This generally infers that a connection is built before the data transfer (by following the procedures laid out in a protocol) and then is deconstructed at the at the end of the data transfer.
    
    • Packet: A packet is, generally speaking, the most basic unit that is transferred over a network. When communicating over a network, packets are the envelopes that carry your data (in pieces) from one end point to the other.
    
Packets have a header portion that contains information about the packet including the source and destination, timestamps, network hops. The main portion of a packet contains the actual data being transferred. It is sometimes called the body or the payload.

    • Network Interface: A network interface can refer to any kind of software interface to networking hardware. For instance, if you have two network cards in your computer, you can control and configure each network interface associated with them individually.
    
A network interface may be associated with a physical device, or it may be a representation of a virtual interface. The "loop-back" device, which is a virtual interface to the local machine, is an example of this.

    • LAN: LAN stands for "local area network". It refers to a network or a portion of a network that is not publicly accessible to the greater internet. A home or office network is an example of a LAN.
    
    • WAN: WAN stands for "wide area network". It means a network that is much more extensive than a LAN. While WAN is the relevant term to use to describe large, dispersed networks in general, it is usually meant to mean the internet, as a whole.
If an interface is connected to the WAN, it is generally assumed that it is reachable through the internet.

    • Protocol: A protocol is a set of rules and standards that basically define a language that devices can use to communicate. There are a great number of protocols in use extensively in networking, and they are often implemented in different layers. 
    
Some low level protocols are TCP, UDP, IP, and ICMP. Some familiar examples of application layer protocols, built on these lower protocols, are HTTP (for accessing web content), SSH, TLS/SSL, and FTP.

    • Port: A port is an address on a single machine that can be tied to a specific piece of software. It is not a physical interface or location, but it allows your server to be able to communicate using more than one application.
    
    • Firewall: A firewall is a program that decides whether traffic coming into a server or going out should be allowed. A firewall usually works by creating rules for which type of traffic is acceptable on which ports. Generally, firewalls block ports that are not used by a specific application on a server.
    
    • NAT: Network address translation is a way to translate requests that are incoming into a routing server to the relevant devices or servers that it knows about in the LAN. This is usually implemented in physical LANs as a way to route requests through one IP address to the necessary backend servers.
    
    • VPN: Virtual private network is a means of connecting separate LANs through the internet, while maintaining privacy. This is used as a means of connecting remote systems as if they were on a local network, often for security reasons.
    
## Network Layers

	While networking is often discussed in terms of topology in a horizontal way, between hosts, its implementation is layered in a vertical fashion throughout a computer or network. This means is that there are multiple technologies and protocols that are built on top of each other in order for communication to function more easily. Each successive, higher layer abstracts the raw data a little bit more, and makes it simpler to use for applications and users. It also allows you to leverage lower layers in new ways without having to invest the time and energy to develop the protocols and applications that handle those types of traffic.
 
	As data is sent out of one machine, it begins at the top of the stack and filters downwards. At the lowest level, actual transmission to another machine takes place. At this point, the data travels back up through the layers of the other computer. Each layer has the ability to add its own "wrapper" around the data that it receives from the adjacent layer, which will help the layers that come after decide what to do with the data when it is passed off.
 
	One method of talking about the different layers of network communication is the OSI model. OSI stands for Open Systems Interconnect.This model defines seven separate layers. The layers in this model are:

    • Application: The application layer is the layer that the users and user-applications most often interact with. Network communication is discussed in terms of availability of resources, partners to communicate with, and data synchronization.
    
    • Presentation: The presentation layer is responsible for mapping resources and creating context. It is used to translate lower level networking data into data that applications expect to see.
    
    • Session: The session layer is a connection handler. It creates, maintains, and destroys connections between nodes in a persistent way.
    
    • Transport: The transport layer is responsible for handing the layers above it a reliable connection. In this context, reliable refers to the ability to verify that a piece of data was received intact at the other end of the connection. This layer can resend information that has been dropped or corrupted and can acknowledge the receipt of data to remote computers.

    • Network: The network layer is used to route data between different nodes on the network. It uses addresses to be able to tell which computer to send information to. This layer can also break apart larger messages into smaller chunks to be reassembled on the opposite end.
    
    • Data Link: This layer is implemented as a method of establishing and maintaining reliable links between different nodes or devices on a network using existing physical connections.
    
    • Physical: The physical layer is responsible for handling the actual physical devices that are used to make a connection. This layer involves the bare software that manages physical connections as well as the hardware itself (like Ethernet).
    
The TCP/IP model, more commonly known as the Internet protocol suite, is another layering model that is simpler and has been widely adopted.It defines the four separate layers, some of which overlap with the OSI model:

    • Application: In this model, the application layer is responsible for creating and transmitting user data between applications. The applications can be on remote systems, and should appear to operate as if locally to the end user. 
The communication takes place between peers network.

    • Transport: The transport layer is responsible for communication between processes. This level of networking utilizes ports to address different services. It can build up unreliable or reliable connections depending on the type of protocol used.
    
    • Internet: The internet layer is used to transport data from node to node in a network. This layer is aware of the endpoints of the connections, but does not worry about the actual connection needed to get from one place to another. IP addresses are defined in this layer as a way of reaching remote systems in an addressable manner.
    
    • Link: The link layer implements the actual topology of the local network that allows the internet layer to present an addressable interface. It establishes connections between neighboring nodes to send data.
    
## Interfaces
Interfaces are networking communication points for your computer. Each interface is associated with a physical or virtual networking device. Typically, your server will have one configurable network interface for each Ethernet or wireless internet card you have. In addition, it will define a virtual network interface called the "loopback" or localhost interface. This is used as an interface to connect applications and processes on a single computer to other applications and processes. You can see this referenced as the "lo" interface in many tools.

## Protocols
Networking works by piggybacks on a number of different protocols on top of each other. In this way, one piece of data can be transmitted using multiple protocols encapsulated within one another.

Media access control is a communications protocol that is used to distinguish specific devices. Each device is supposed to get a unique MAC address during the manufacturing process that differentiates it from every other device on the internet. Addressing hardware by the MAC address allows you to reference a device by a unique value even when the software on top may change the name for that specific device during operation. Media access control is one of the only protocols from the link layer that you are likely to interact with on a regular basis.

The IP protocol is one of the fundamental protocols that allow the internet to work. IP addresses are unique on each network and they allow machines to address each other across a network. It is implemented on the internet layer in the IP/TCP model. Networks can be linked together, but traffic must be routed when crossing network boundaries. This protocol assumes an unreliable network and multiple paths to the same destination that it can dynamically change between. There are a number of different implementations of the protocol. The most common implementation today is IPv4, although IPv6 is growing in popularity as an alternative due to the scarcity of IPv4 addresses available and improvements in the protocols capabilities.

ICMP: internet control message protocol is used to send messages between devices to indicate the availability or error conditions. These packets are used in a variety of network diagnostic tools, such as ping and traceroute. Usually ICMP packets are transmitted when a packet of a different kind meets some kind of a problem. Basically, they are used as a feedback mechanism for network communications.

TCP: Transmission control protocol is implemented in the transport layer of the IP/TCP model and is used to establish reliable connections. TCP is one of the protocols that encapsulates data into packets. It then transfers these to the remote end of the connection using the methods available on the lower layers. On the other end, it can check for errors, request certain pieces to be resent, and reassemble the information into one logical piece to send to the application layer. The protocol builds up a connection prior to data transfer using a system called a three-way handshake. This is a way for the two ends of the communication to acknowledge the request and agree upon a method of ensuring data reliability. After the data has been sent, the connection is torn down using a similar four-way handshake. TCP is the protocol of choice for many of the most popular uses for the internet, including WWW, FTP, SSH, and email. It is safe to say that the internet we know today would not be here without TCP.

UDP: User datagram protocol is a popular companion protocol to TCP and is also implemented in the transport layer. The fundamental difference between UDP and TCP is that UDP offers unreliable data transfer. It does not verify that data has been received on the other end of the connection. This might sound like a bad thing, and for many purposes, it is. However, it is also extremely important for some functions. It’s not required to wait for confirmation that the data was received and forced to resend data, UDP is much faster than TCP. It does not establish a connection with the remote host, it simply fires off the data to that host and doesn't care if it is accepted or not. Since UDP is a simple transaction, it is useful for simple communications like querying for network resources. It also doesn't maintain a state, which makes it great for transmitting data from one machine to many real-time clients. This makes it ideal for VOIP, games, and other applications that cannot afford delays.

HTTP: Hypertext transfer protocol is a protocol defined in the application layer that forms the basis for communication on the web. HTTP defines a number of functions that tell the remote system what you are requesting. For instance, GET, POST, and DELETE all interact with the requested data in a different way.

[JSON Web Token (JWT)](https://jwt.io) is a compact URL-safe means of representing claims to be transferred between two parties. The claims in a JWT are encoded as a JSON object that is digitally signed using JSON Web Signature (JWS).

[OAuth 2.0](https://oauth.net/2/) is an open source authorization framework that enables applications to obtain limited access to user accounts on an HTTP service, such as Amazon, Google, Facebook, Microsoft, Twitter GitHub, and DigitalOcean. It works by delegating user authentication to the service that hosts the user account, and authorizing third-party applications to access the user account.

FTP: File transfer protocol is in the application layer and provides a way of transferring complete files from one host to another. It is inherently insecure, so it is not recommended for any externally facing network unless it is implemented as a public, download-only resource.

DNS: Domain name system is an application layer protocol used to provide a human-friendly naming mechanism for internet resources. It is what ties a domain name to an IP address and allows you to access sites by name in your browser.

SSH: Secure shell is an encrypted protocol implemented in the application layer that can be used to communicate with a remote server in a secure way. Many additional technologies are built around this protocol because of its end-to-end encryption and ubiquity. There are many other protocols that we haven't covered that are equally important. However, this should give you a good overview of some of the fundamental technologies that make the internet and networking possible.

## Virtualization

[KVM (for Kernel-based Virtual Machine)](https://www.linux-kvm.org/page/Main_Page) is a full virtualization solution for Linux on x86 hardware containing virtualization extensions (Intel VT or AMD-V). It consists of a loadable kernel module, kvm.ko, that provides the core virtualization infrastructure and a processor specific module, kvm-intel.ko or kvm-amd.ko.

[QEMU](https://www.qemu.org) is a fast processor emulator using a portable dynamic translator. QEMU emulates a full system, including a processor and various peripherals. It can be used to launch a different Operating System without rebooting the PC or to debug system code.

[Hyper-V](https://docs.microsoft.com/en-us/virtualization/hyper-v-on-windows/) enables running virtualized computer systems on top of a physical host. These virtualized systems can be used and managed just as if they were physical computer systems, however they exist in virtualized and isolated environment. Special software called a hypervisor manages access between the virtual systems and the physical hardware resources. Virtualization enables quick deployment of computer systems, a way to quickly restore systems to a previously known good state, and the ability to migrate systems between physical hosts.

[VirtManager](https://github.com/virt-manager/virt-manager) is a graphical tool for managing virtual machines via libvirt. Most usage is with QEMU/KVM virtual machines, but Xen and libvirt LXC containers are well supported. Common operations for any libvirt driver should work.

[oVirt](https://www.ovirt.org) is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible.Founded by Red Hat as a community project on which Red Hat Enterprise Virtualization is based allowing for centralized management of virtual machines, compute, storage and networking resources, from an easy-to-use web-based front-end with platform independent access.

[Xen](https://github.com/xen-project/xen) is focused on advancing virtualization in a number of different commercial and open source applications, including server virtualization, Infrastructure as a Services (IaaS), desktop virtualization, security applications, embedded and hardware appliances, and automotive/aviation.

[Ganeti](https://github.com/ganeti/ganeti) is a virtual machine cluster management tool built on top of existing virtualization technologies such as Xen or KVM and other open source software. Once installed, the tool assumes management of the virtual instances (Xen DomU).

[Packer](https://www.packer.io/) is an open source tool for creating identical machine images for multiple platforms from a single source configuration. Packer is lightweight, runs on every major operating system, and is highly performant, creating machine images for multiple platforms in parallel. Packer does not replace configuration management like Chef or Puppet. In fact, when building images, Packer is able to use tools like Chef or Puppet to install software onto the image.

[Vagrant](https://www.vagrantup.com/) is a tool for building and managing virtual machine environments in a single workflow. With an easy-to-use workflow and focus on automation, Vagrant lowers development environment setup time, increases production parity, and makes the "works on my machine" excuse a relic of the past. It provides easy to configure, reproducible, and portable work environments built on top of industry-standard technology and controlled by a single consistent workflow to help maximize the productivity and flexibility of you and your team.

[VMware Workstation](https://www.vmware.com/products/workstation-pro.html) is a hosted hypervisor that runs on x64 versions of Windows and Linux operating systems; it enables users to set up virtual machines on a single physical machine, and use them simultaneously along with the actual machine.

[VirtualBox](https://www.virtualbox.org) is a powerful x86 and AMD64/Intel64 virtualization product for enterprise as well as home use. Not only is VirtualBox an extremely feature rich, high performance product for enterprise customers.
