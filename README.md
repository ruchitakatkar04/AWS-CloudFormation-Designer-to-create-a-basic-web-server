# AWS-CloudFormation-Designer-to-create-a-basic-web-server


**Step 1: Add and connect resources**

AWS CloudFormation Designer drag-and-drop interface is used to add an Amazon EC2 instance and network resources, such as a VPC, subnet, route table, and Internet gateway. 
After adding all the resources, connections between them are created. 

**Step 2: Add parameters, mappings, and outputs**

In this step, we'll use the AWS CloudFormation Designer integrated editor to add parameters, mappings, and outputs. 
Then, we can refer to these parameters and mappings when we specify resource properties.

_**To add parameters**_

Parameters are input values that you specify when you create a stack. They're useful for passing in values so that you don't have hard coded values in templates. 
So that we can use the same template to create multiple web servers with different instance types.

_**To add mappings**_

Mappings are a set of keys that are associated with a set of name-value pairs. They're useful for specifying values based on an input parameter value.

_**To add outputs**_

Outputs declare values that you want available to describe stacks API call or through the CloudFormation console stack Outputs tab.

**Step 3: Specify resource properties**

AWS CloudFormation Designer integrated editor is used to specify resource properties that define their configurations or settings, such as which instance type to use for the web server. 

**Step 4: Provision resources**

To create a stack, you can launch the CloudFormation Create Stack Wizard from AWS CloudFormation Designer. After CloudFormation provisions all of your resources, you'll have a basic website up and running.
