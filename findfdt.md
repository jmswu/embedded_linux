findfdt=
echo board_name=[$board_name] ...; 

if test $board_name = A335BLGC; 
then setenv fdtfile am335x-beaglelogic.dtb; 
fi; 

if test $board_name = A335BONE; 
then setenv fdtfile am335x-bone.dtb; 
fi; 

if test $board_name = A335BNLT; 
then echo board_rev=[$board_rev] ...; 

if test $board_rev = GH01; 
then setenv fdtfile am335x-boneblack.dtb;
 
elif test $board_rev = BBG1; 
then setenv fdtfile am335x-bonegreen.dtb; 

elif test $board_rev = BP00; 
then setenv fdtfile am335x-pocketbone.dtb; 

elif test $board_rev = GW1A; 
then setenv fdtfile am335x-bonegreen-wireless.dtb; 

elif test $board_rev = GG1A; 
then setenv fdtfile am335x-bonegreen-gateway.dtb; 

elif test $board_rev = AIA0; 
then setenv fdtfile am335x-abbbi.dtb; 

elif test $board_rev = EIA0; 
then setenv fdtfile am335x-boneblack.dtb; 

elif test $board_rev = ME06; 
then setenv fdtfile am335x-bonegreen.dtb; 

elif test $board_rev = OS00; 
then setenv fdtfile am335x-osd3358-sm-red.dtb; 

elif test $board_rev = OS01; 
then setenv fdtfile am335x-osd3358-sm-red-v4.dtb; 

else setenv fdtfile am335x-boneblack.dtb;


# BB FDT file 
am335x-boneblack.dtb