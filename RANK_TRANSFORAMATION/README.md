## Rank Transformation
The Rank transformation selects the top or bottom range of data. Use the Rank transformation to return the largest or smallest numeric values in a group. You can also use the Rank transformation to return strings at the top or bottom of the mapping sort order.

## Steps to create rank transformation
* Bring emp table in source analyzer
* In target designer drag emp table from source,rename the source table and click on generate/execute sql to create the structure of the target table.
* Creae mapping,drag source and target table into the mapping designer.Create rank transformation by default it is in Rank Index state.
* Map the source qualifier output to the rank transformation and rank transformation output to target of input.
* Double click on Rank transformation-->go to properties-->select Top/Bottom--->Number of rank as 5--->Case sensitive string comparision as
* Save the mapping and go to workflow designer,in that create session and workflow,save the workflow and click on start workflow

## Mapping
![RANK](https://user-images.githubusercontent.com/98802184/236690537-ba96bcb6-0603-415f-a3ed-2aee540dbdfd.PNG)

## Conditions
![RANK_CONDITION](https://user-images.githubusercontent.com/98802184/236690589-aad8dfe5-9058-4faa-88d1-788381e6a743.PNG)

## Session Output
![RANK_SESSION](https://user-images.githubusercontent.com/98802184/236690645-0c685857-2b6c-400e-9cc8-b869800381e3.PNG)

## ORACLE OUTPUT
![RANK_OUTPUT](https://user-images.githubusercontent.com/98802184/236690656-d8b08c60-b3e9-4cd4-a9c4-20e3bea6ba46.PNG)



