- Creates the following:
	- 6 Subnets (2 Private, 2 DB and 2 Public) by using the custom VPCInfo Resource type which invokes the lamda function to get the VpcID
	
Note: need to update subnets-parameter.json with Lambda ARN of the 'vpc' stack before attempting to create this stack.
	stack-outputs vpc | grep -i lambda
