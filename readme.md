Test 'drug_container' concerning minimum number of pills for each medicine that is in accordance with 'drug_dosage' per day;
If there is one of them about to became 'zero' pills - resupply it using the 'stock_medicine_box';
Check if there is a 'stock_medicine_box' to resupply 'drug_container';(let´s think about this check be the first one)

Remarks: the supply and resupply process have to be made using quantity of pills in a pills pack inside each box.

All the check points above should be made before updating the medic_user.db by the user when inform about taking all set of pills.
This process should be made just after one day at least after the 'last_update' time. (The user can update at least once a week)

Let´s try to work of medicine box as a constant where you can declare if pills are in pack or no.

eg. LT_box = 2 (1x15) / AA_box = 120 / AN_box = 3(1x10) / HI_box = 1(1x30) / AT_box=3(1x10)

Other way is to setup the minimal number of pills when supplying/resupplying.