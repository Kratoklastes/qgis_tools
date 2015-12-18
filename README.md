# qgis_tools
Experimental dev of workflow-oriented tools for QGIS

Put simply, there are tasks I do every day that take too damn long. 

My least favourite thing in the world is not using a snippet for PostgreSQL queries that include 
'where (100*(ST_Area(ST_Intersection(a.g1, b.g1))/ST_Area(a.g1))::INT > 30' 

(and other things like that). my second least favourite is iterating through an attribute table, clicking 'zoom to next feature', and making edits if required (and 98% of the time, they're not requried - and you know that within 2 seconds of seeing the feature).

So... I wanted a plugin that would behave as if a Mechanical Turk was sitting there, clicking the next row of the attribute table, and hitting the 'zoom to next feature' button (and then dialling the zoom back maybe a just a squootch)... then giving you 4 seconds to decide whether to pause the Turk (can I say 'Turk'? Yep, I kinda think I can).

As you can see, as of now there's almost nothing in this repository: the first few iterations of stuff going into it will be complete garbage as I feel my way around the interstices of QGIS Plugin creation.

 Lasciate ogni speranza, voi ch'entrate...
