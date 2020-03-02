# MALDI-Calculation

MALDI Calculation is a program to calculate possible polymer structures with a combination of known/predicted monomer structures. The user needs to provide molecular weights (MWs) of monomer structures – “monomer_weight”, found polymer MWs by MALDI or any MassSpec tools – “polymer_weight”, possible numbers of monomer units – “range_bottom” (minimum) and “range_top” (maximum), and error range – “error_number”.

Please note that due to the computational complexity, it is recommended to only input one “polymer_weight” value every time, eliminate repeated or unnecessary “monomer_weight”, and most importantly reduce “range_top” as much as possible.

This program is under constant improvement for better efficiency. 