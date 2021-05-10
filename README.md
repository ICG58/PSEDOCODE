Write a program that calculates the amount of money the beauty shop receives per month,display and output the money.
START
Prompt the amount of money
IF amount of money < invested money THEN
Write 'LOSS'
ELSE
IF amount of money > invested money THEN
Write 'PROFIT MADE'
ENDIF
STOP

Write a program that shows how many products are needed so that they can be transported to the beauty shop.
START
Order products from suppliers
Get products from suppliers
If products are >= 35 THEN
Execute'PRODUCT SHOULD BE TRANSPORTED TO DESTINATION'
ELSE
Execute 'THE AMOUNT OF PRODUCT YOU SELECTED DOES NOT MEET THE MINIMUM VALUE,PLEASE WAIT TILL IT DOES'
ELSE
Execute'ERROR,PLEASE TRY AGAIN LATER'
ENDIF
STOP

Write a program to calculate the store values and include the VAT
START
Enter num
For e = 1 to num DO
Enter item(e)
Enter price
Enter Bprice
Enter code
IF code = 1 THEN
Sprice(e)= Bprice * 2.00 * 1.05
ELSE
Sprice(e)= Bprice * 1.00
endif
ENDFOR
For e = 1 to num DO
Print item(e)
ENDFOR
STOP
