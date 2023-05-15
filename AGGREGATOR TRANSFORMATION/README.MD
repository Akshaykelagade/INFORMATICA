## AGGREAGATOR TRANSFORMATION
Aggregator transformation is an active transformation. And it is used to perform calculations on the data such as sums, averages, counts, etc. The integration service stores the group of data and row data in the aggregate cache. The Aggregator Transformation is more beneficial in comparison to the SQL.

## Steps to exhicute Aggegator Transformation
* Bring source table to source analyazer from database.
* Drag source table to target designer and add required number of columns according to STM doc,rename the target table and go for generate and exhicute sql .
* Create mapping in mapping desiger and Drag source and target table to mapping designer.
* Take expression transformation,map all columns of source qualifier to expression transformation.Add 4 new columns which are highlighted in yellow colour in STM doc.Create first two         columns as varible port and later two as output port. In description column add condition as shown in the expression condition image.
* Take Aggregator transformation and map all columns from expression transformation.Give the condtions for required columns as shown in below aggregator condition image.
* Take Filter transformation and map all the colomns from aggregator transformer.Give the condition for description column as shown in below filter condition image.
* Map required columns from filter transformer to target table and save the designer .
* Go to work flow and run the session.

## STM DOCUMENT
![1684152762863](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/f202a5a8-5316-42bd-b32a-f515c7fe01cb)



## Mapping
![Agretator_mapping](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/842d8bad-18ba-485e-a6b9-ddc4ca23a0ab)

## Expression Condition
![AGRE_EXP_CONDI](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/dfb9bb84-3a22-4186-b48e-6716e7032ccf)

## Aggegator Condition
![AGRE_AGRE_CONDI](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/a88e76fb-2642-428b-acb6-e039b6901a8f)

## Filter Condition
![AGRE_FILTER_COND](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/3952d019-4036-4ae3-8df0-cf61981f2f7b)

## Session Output
![AGREGATOR_SESSION](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/89ea612d-25de-4013-92d6-b0f052e3e07c)

## ORACLE Output
![agreGATOR_TARGET OUTPUT](https://github.com/Akshaykelagade/INFORMATICA/assets/98802184/9348373f-bb6a-49a7-a8ff-d867aeee5302)


## Interview Questions
*
*
*
