# FFTA-Level-Calculator
Via Excel
=SE($E6="Minimum";((F$4)-(INT(F$4/20)))+((INT(F$5))*($D6-1));SE($E6="Average";((F$4)+(INT(F$4/20)))+(INT((INT(F$5))*($D4+$D5+$D6-1)+((($D4+$D5+$D6-1)/100)*((((F$5)-((INT(F$5))))*100)))));SE(E($E6="Maximum";((F$5)-(INT(F$5)))>=0,1);((F$4)+(3*INT(F$4/20)))+(((INT(F$5))*($D4+$D5+$D6-1))+($D4+$D5+$D6-1));((F$4)+(3*INT(F$4/20)))+(((INT(F$5))*($D4+$D5+$D6-1))+($D4+$D5+$D6-1)-1))))
