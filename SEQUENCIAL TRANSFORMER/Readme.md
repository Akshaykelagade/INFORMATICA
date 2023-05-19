# Sequential Transformation
Sequential transformation here data's are arranged in sequential manner it is passive and connected transformation 

#Steps to execute sequential transformation
• Bring source table to source analyazer from database
• Drag source table to Target and Rename the table according to STM doc and go for generate and exhicute sql
• Add column in Target > as SL NO > apply > ok
• In mapping > create mapping > drag source and target map source to target leave SLNO port it is
• Take sequencial Transformation > map > next value to sl no
• Properties > current value > 1, increment by > end value > don't touch > ok > save
• Go to workflow and create task and workflow and run 
• It we run once again then it will append from next slno 
• Truncate the table and execute now it will start from slno 
• It we want to set new current value then we have to disconnect and connect
