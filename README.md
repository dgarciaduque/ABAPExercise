# ABAPExercise
Please follow these steps to test this ABAP program in your SAP system:
1. Create an exception class in transaction SE24 and call it ZCX_ABAPTEST_DGD. Make sure the instance generation is set to 'Public' and the checkbox 'With messages of message classes as exception texts' is checked.
2. In transaction SE91, create a new message class 'ZABAPTEST_DGD'. After that, create the following messages, with the corresponding message numbers:
    1. 000 Please choose at least one field
    2. 001 Error building the database syntax
    3. 002 Insufficient or incorrect import parameters
4. Go to transaction SE38 and create the include programs ZABAPTEST_DGD_SCR and ZABAPTEST_DGD_CLA, copying and pasting the code from the corresponding .txt files
5. In transaction SE38, create a new report and call it ZABAPTEST_DGD. After that, copy and paste the code from ZABAPTEST_DGD.txt. Finally, create the following text symbols:
    1. 001	ABAP test: Exercise 3
    2. B01	Free selection
    3. B02	Fields shown in the ALV
6. Make sure all the objecs are active and run your tests.
