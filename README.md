# Azure-MLOps
Azure Progress and MLOps work.

### Core principles of DevOps:
- Continuous Integration and Continuous Delivery (Ci/CD)
- Real-Time monitoring
-Incident Response system
- Collaboration platforms

### Benefits of DevOps
- Accelerating time to market
- Adapting to market and competition 
- Maintaining system stability and reliability
- Improving mean time to recovery


### DevOps and the Application Life-Cycle

- Plan
- Devlop
- Deliver
- Operate

### Azure DevOps

- Plan 
- Collaborate
- Build
- Deploy

### Azure DeOps service

- Quick set-up
- Maintenance-free operations
- Easy collaboration across domains
- Elastic scale
- Rock-solid security


### DevOps and the Cloud

- Cloud Agility
- Orchestration
- Serverless Computing

### Features of Azure DevOps

- Flexible
- Platform agnostic
- Cloud agnostic

### Azure DevOps Services

- Azure repos 
- Azure pipelines
- Azure Boards
- Azure Test plans 
- Azure Artifacts

Also
- Collaboration Tools
- Wikis
- Notification Tools
- Extension Support
---------------------------------------------------

# FastAPI

- Modern, fast, high-performance web framework for building APIs with Python
- Uses a web server called ASGI or Asynchronous Server Gateway Interface
- Starlette for the web parts
- Pydntic for the data parts

## Features of FastAPI


- Fast
- Fast to code
- Fewer bugs 
- Intuitive
- Easy 
- Short
- Robust
- Standards-based

## Routing  Methods
* Routing refers to how an apllication's endpoints (URLs) respond to client requests.
- GET() Method
- Post() Method

----------------------------------------------------------------

# Docker

- Docker is an open platform for developing, shipping, and running applicaitons
- Manage infrastructures and applications
- Ability to package and run an application in a loosely isolated environment called a container
- Containers are lightweight and contain everything needed to tun the application

----------------------------------------------------------------

## Uses of Docker

- Docker streamlines the development lifecycle by allowing developers to work in standardized environments
- Containers are great for (CI/CD) workflows
- Responsive deployment and scaling 
- Running more workloads on the same hardware

----------------------------------------------------------------

## Docker Images and Containers

    - An images is a read-only template with infrastructure for creating a Docker container.
    - We create a Dockerfile with a simple syntax for defining the steps needed to create the image and run it.
    - A container is a runnable instance of an image. You can create, start, sotp, move, or delete a container using the Docker API or CLI.
    - A container is defined by its images as well as any configuration options you provide to it when you create a start it.

------------------------------------------------------------------

 # Azure Resource Group:

    - Container that holds related resources for an Azure solution
    - Allocate resources to resource groups 
    - Stores metadata about the resources

----------------------------------------------------------------

## Create Azure Resource Groups

    - The Azure Portal
    - Azure PowerShel scripts
    - The Azure CLI
    - The ARM template

----------------------------------------------------------------

## Azure Container Registry

- The Azure container registry is a hosting platform for Docker images.
- Private registry to store and manage private docker container images and other related artifacts
- Fast, scalable retreval of container workloads
- Handles private Docker container images as well as related content formats
- Automate container building and patching

----------------------------------------------------------------

## Benefits of Azure Container Registry

    - Store and manage images for all types of container deployments
    - Automated container builds, testing and security scanning
    - Store common Command line interface (CLI) to interact with the registry
    - Manage windows and Linux container images in a single registry

-----------------------------------------------------------------

## Advantages of Azure Resource Groups

    - Straightforward way to create and manage resources
    - Provides a flecible, customizable, high-level view of available resource
    - Collects metadata from each individual resource to facilitate more granular management than at the subsciption level
    - Effective administration, cost management and role-base access controls.

----------------------------------------------------------------

# Introduction Pipelines

    - Automatically builds and tests code projects
    - Continuos integration + Continuous Delivery
    - Continuous Testing

-----------------------------------------------------------------

# CI/CD/CT:

- Continuous AIntegration (CI) is the practice used by development teams of automating merging and testing code.
- Continuous Delivery (CD) is a process by which code is built, tested and deployed to tone or more test production enviroinment
- Continuous Testing (CT) is the use of automated build-deploy-test workflows that test your changes continuously

----------------------------------------------------------------

## Features of Azure Pipeline:

    - Version control systems
    - Languages
    - Apllication types
    - Deployment targets
    - Continuous testing 
    - Package formats

----------------------------------------------------------------

## Perqusites

    - Azure DevOps account
    - Source code in Version Control System

----------------------------------------------------------------

## Benefits of  Azure Pipelines

    - Works with any lanuauage or platform
    - Deployes to different types of targets at the same time
    - Integrates with Azure deployments
    - Builds on Windows, Linux, or Mac machines
    - Integrates with GitHub
    - Works with open-source projects

----------------------------------------------------------------

## Building Azure Pipelines

    * Continuous Integration | * Continuous Delivery

### Defining Pipelines: 
    - YAML Syntax
    - Classic interface
    - Define pipeline in a YAML file called azure-pipelines.yml
    - Create and configure pipelines in the Azure DevOps web portal with the classic user interface editor.

----------------------------------------------------------------

# YAML

    - Data serialization language that is used for writing configuration file
    - YAML is for data, not documents
    - Human-readable and easy to understand
    - YAML has features that come from other programming languages
    - The structure of a YAML file is a map or a list
     
----------------------------------------------------------------

# Customize YAML Pipeline

    - Change the platform for build
    - Add steps
    - Build across multiple platforms
    - Bild using multiple versions
    - Customize CI triggers

----------------------------------------------------------------

# Azure Web App

    - Create and deploy scalable web applications
    - End point for deployment
