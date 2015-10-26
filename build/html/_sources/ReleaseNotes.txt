.. BranchVolume documentation Release Notes file, created by
   Justin Hanley on 10/14/2015


Release Notes
=============


Branch Volume 0.0.2
-------------------
*October 14, 2015*

Event Identification
^^^^^^^^^^^^^^^^^^^^
 The Branch Volume has been improved to identify normal, payroll, and holiday event types. Within our database backend logic,
 we have been able to match event days and weeks associated to a transaction. This means you now have the ability to
 identify and compare varying event types to the total transaction average, for a given time period. 

________________________________________________________________________________________________________________

Caveats with Event Dates
^^^^^^^^^^^^^^^^^^^^^^^^
 The Branch Volume Dashoboard focuses on factual data with as minimal assumptions as possible. As a result, 
 events dates are strictly defined and event transactions are flagged, only if, they truly correspond to a given event date.
 If there are no transactions on a given day, in the case of many holiday events, there will be no data provided.
