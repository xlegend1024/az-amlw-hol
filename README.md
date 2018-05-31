# Azure Machine Learning Workbench Hands on Lab

## Prerequisites

If you don't have an Azure subscription, create a [free account](https://azure.microsoft.com/free/?WT.mc_id=A261C142F) before you begin.

To complete this tutorial, you must have:
- Azure subscription with owner/contributor role of a subscription or owner role of a resource group
- Data Science Virtual Machine with D4s v3 size or higher 
    - Install docker on the DSVM
    - Install Azure Machine Learning Workbench 
- An Azure Machine Learning Experimentation account

If you don't have these prerequisites already, follow the steps:

1. [Create DSVM for Windows Server](https://docs.microsoft.com/en-us/azure/machine-learning/data-science-virtual-machine/provision-vm#create-your-microsoft-data-science-virtual-machine)
2. [Create Azure Machine Learning services accounts](https://docs.microsoft.com/en-us/azure/machine-learning/service/quickstart-installation#create-azure-machine-learning-services-accounts)
3. [Create a project in Workbench](https://docs.microsoft.com/en-us/azure/machine-learning/service/quickstart-installation#create-azure-machine-learning-services-accounts)
4. [Install Machine Learning Worksbench](https://docs.microsoft.com/en-us/azure/machine-learning/service/quickstart-installation#install-and-log-in-to-workbench)

## Check list

- Azure Subscription
- Role 
    - Subscription Owner, Subscription Contributor or Resource Group Owner
- ML service account
- DSVM 
    - Size: D4sV3 or higher
    - Docker installed
    - ML Workbench installed
- Client
    - Windows 10 with build 18xx or higher


## Hand on lab agenda

1. [Create New Project](./01.CreateNewProject.md)

    Create a Azure Machine Learning Experiment and Model from a portal. And create new machine leanring project.

1. [Model Selection](./02.ModelSelection.md)

    Conduct experiment and find model for your business.

1. [Deploy Model](./03.DeployModel.md)

    Have a model and schema and containerize them. Push container image to ACR and provision the container image to operationalize score model.

1. [Exercise](./04.Exercise.md)

    Start a new project with pySpark.

## Original documents are here:

1. https://docs.microsoft.com/en-us/azure/machine-learning/desktop-workbench/tutorial-classifying-iris-part-1
2. https://docs.microsoft.com/en-us/azure/machine-learning/desktop-workbench/tutorial-classifying-iris-part-2
3. https://docs.microsoft.com/en-us/azure/machine-learning/desktop-workbench/tutorial-classifying-iris-part-3 
