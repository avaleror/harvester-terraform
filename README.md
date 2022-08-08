# Testing terraform provider for Harvester

## First create the proper structure

![Alt text](https://github.com/avaleror/harvester-terraform/blob/master/pictures/repo-tree.png "Terraform repo structure")

In main.tf we will define .....
In versions.tf we will define which providers are we using and which versions


- In main.tf there will be all the resources thet need to be present, do not forget that we are talking about a "declarative approach" so we define the desired state and terraform will make sure that the desired state is achieved.

- In variables.tf we define all the vars needed in main.tf.

- In versions.tf we define which terraform modules are needed to complete the tasks and the concrete versions.
