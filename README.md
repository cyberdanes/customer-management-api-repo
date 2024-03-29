# CUSTOMER MANAGEMENT API

## Overview
The Process API for managing Customer Records. Invokes the Records API for performing basic CRUD operations on the customer resource.  

## Operations Supported  
This API supports the basic CRUD operations on the resources.    

### GET:  
	This operation returns the available customer resources. There are two ways to invoke this:  
	1. Without any customer id.  
		This would return all customer records.  
	2. With customer id.  
		This invokation returns the customer object with the specified id.  
   	
### POST:   
	This operation creates a new customer resource.   

### PUT:   
	This operation updates the customer with the id given in the uri parameters.   

### DELETE:
	This is used to delete a customer obeject with the given id.   


## Authentication
	This API supports basic authentication.   

## Status Codes
	200 : OK   
	201 : Created   
	204 : Empty Response   

## Error Codes
	404 : Not found