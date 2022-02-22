# OpenRefine grel commands

## Crosswalking data to data entry sheets
grel:	cell.cross('ArctosData_44F5D62F4E_2020-01-09', 'GUID').cells['Genus_HigherClassificationGBIF_Family-Kingdom'].value[0].toString()
 
grel:	cell.cross('ArctosData_44F5D62F4E_2020-01-09', 'GUID').cells['SCIENTIFIC_NAME'].value[0].toString()

