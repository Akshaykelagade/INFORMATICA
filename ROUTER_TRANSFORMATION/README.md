## ROUTER TRANSFORMATION
The Router transformation is an active transformation that you can use to apply a condition to incoming data. In a Router transformation, Data Integration. uses a filter condition to evaluate each row of incoming data. It tests the conditions of each user-defined group before processing the default group.

## Steps to create router transformation
* Bring EMP table from database to soure analyser.
* Drag the EMP source table 4 times to target designer and rename each tables.
* Rename first table as emp_salesman,second table as emp_clerk,third table as emp_manager and fourth table as emp_others.Here third and fourth table we take as flat files.
* Go to target----> click on generate and execute sql
* Create mapping in that drag source table and 4 target tables.Create Router Transformer ,map source qualifier output to Router of input.Double click on Router go to group and add 3 groups and 1 default.
* Group names and their conditions are shown in the condtions image below.
* After adding conditions to Router map the Router output to Target of input.
* Save the mapping and Go to workflow designer in that create session and workflow.After that start the work flow and see the output which is shown in session output below.
## Mapping
![router](https://user-images.githubusercontent.com/98802184/236833014-6ac0cd07-6b3f-420c-8893-7700f1eca7ef.PNG)

## Conditions
![router_condition](https://user-images.githubusercontent.com/98802184/236833193-44e34717-17c7-4130-989c-c890be604552.PNG)

## Session Output
![router_session](https://user-images.githubusercontent.com/98802184/236833284-b2b2630c-2a42-47f7-8308-4a931cddc454.PNG)

## ORACLE Outputs
### Salesman
![router_sales](https://user-images.githubusercontent.com/98802184/236833410-14446e31-01ba-47a6-9ad0-85df7db92806.PNG)

### CLERK
![router_clerk](https://user-images.githubusercontent.com/98802184/236833590-ffbac437-6307-46ce-8368-efa65620d3a6.PNG)


### MANAGER
![router_manger](https://user-images.githubusercontent.com/98802184/236833679-7b6c9e99-ac03-4a5e-afa8-3502466a20b2.PNG)

### OTHERS
![router_others](https://user-images.githubusercontent.com/98802184/236833755-e67f81b7-d5b3-4b2b-bac2-f1f8403e8f8a.PNG)


