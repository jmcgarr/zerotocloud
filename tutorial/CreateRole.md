# Step 5 - Create Role

A role is a set of permission that can be granted to an instance, allowing API calls on an instance to inherit those permissions with the explicit need for credentials in hand.
In this tutorial, we're creating a single broad role for convenience. Each @netflixoss project that can leverage a role will specify it's own minimum policy.  

1. View <a href="https://console.aws.amazon.com/iam/home?region=us-west-2#roles" target="_blank">Roles</a> page. Which can also be accessed from the _Services | IAM | Roles_. ![](images/create-new-role.png)
2. Click "Create New Role", name it “jumphost”, click “Continue”. ![](images/create-role-jumphost.png)
3. Click "Select" next to the “Amazon EC2” service role type. ![](images/select-amazon-ec2.png)
4. Click "Select" next to the “Administrator Access”  policy template. ![](images/select-administrator-access.png)
5. Click "Next Step". ![](images/create-role-policy-doc.png)
6. Click "Create Role". ![](images/create-role-final-screen-2.png)
