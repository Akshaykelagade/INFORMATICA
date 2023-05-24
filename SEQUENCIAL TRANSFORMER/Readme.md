# Sequential Transformation
Sequential transformation here data's are arranged in sequential manner it is passive and connected transformation. 

# Steps to execute sequential transformation
* Bring source table to source analyazer from database. 
* Drag source table to Target and Rename the table according to STM doc. 
* Add column in Target > as SL NO > apply > ok. Then go for generate and exhicute sql. 
* In mapping > create mapping > drag source and target,map source qualifier output to target and leave SLNO port as it is. 
* Take sequencial Transformation > map > next value to sl no of target. 
* Properties > current value = 1, increment =1,end value =should be greater than current value> ok > save
* Go to workflow and create task and workflow and run the workflow. 
* If we run the workflow once again then it will append from next slno below the previous results. 
* Truncate the table and execute now it will start from slno. 
* If we want to set new current value then we have to disconnect and connect the mapping once again. 




