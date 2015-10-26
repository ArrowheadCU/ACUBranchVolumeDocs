.. BranchVolume documentation UserGuide file, created by
   Justin Hanley on 10/13/2015

User Guide
==========

Why a Branch Volume Dashboard?
------------------------------
 This Branch Volume Dashboard gives a multilayered view of individual branch traffic within a given time period. 
 It was built to assist Management in efficiently schedule team members to satisfy the demand of the 
 branch on a monthly, weekly, and daily basis.

________________________________________________________________________________________________________________

Features
--------
 The data to construct this dashboard is taken from Symitar and updated daily. The report only counts monetary 
 transactions that are done by a team member in the same minute on the same day and under the same sequence number. It then categorizes the data by year, month, and date, and separates 
 it by branches and departments. This dashboard features parameters that can be customized to retrieve the 
 desired data.

.. figure:: _static/FeaturesParameters.png
   :align:  center

________________________________________________________________________________________________________________

How it Works
------------
 The Dashboard evaluates all of the parameters and displays the average transaction counts that occurred in the 
 chosen Period Type.

 Example: The following illustrates the average daily transactions for a branch, with a budgeted weekly FTE of 10.5 (420 hours) 

.. figure:: _static/HowitWorks_ResultsGraph.png
   :align:  center
 

.. figure:: _static/HowitWorks_ResultsTable.png
   :align:  center

The table splits up the data by event (All, Normal, Payroll, Holiday) to show their distribution and comparison within the chosen time period.

   * **Transaction Count**: Average monetary transactions that occurred within the selected period type, over the selected timeframe
   * **% of Total**: Relative average transaction count to total averaged transaction count within the selected timeframe. Divides the 'Transaction Count (Avg.)' of the event by the 'Total' Transaction Count.
   * **Sample size**: Counts how many available events (transaction count > 0) occurred within the given start and end times.
   * **Estimated FTE**: Provided a 'Period Budgeted FTE', calculates the necessary FTE hours based on the weight of the transactions per day ('% of Total').