# Sequential Transformation
In Sequential transformation the data's are arranged in sequential manner. It is passive and connected transformation. 

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

# Mapping
![WhatsApp Image 2023-05-24 at 10 05 26 PM](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/10c472fc-7f52-4dd0-8c76-5bcc0fd12fcd)

# Conditions
![WhatsApp Image 2023-05-24 at 10 10 27 PM](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/ca595ba1-d1ca-49ca-b03d-8d10d739cc4c)


# Session Output
![WhatsApp Image 2023-05-24 at 10 10 29 PM](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/e79e701e-3049-46f6-a553-66c3373e3e7c)

# Oracle Output
![WhatsApp Image 2023-05-24 at 10 10 30 PM](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/1c6295df-479b-4228-8b2a-f0292fed1630)




