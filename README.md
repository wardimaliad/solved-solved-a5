Download Link: https://assignmentchef.com/product/solved-solved-a5
<br>
Consider class Complex shown in Figs. 10.14–10.16(attached). The class enables operations on so called complex numbers. These are numbers of the form realPart + imaginaryPart * i, where i has the value of square root -1

The following are requirement for this assignment.

a). Modify the class to enable input and output of complex numbers through the overloaded and &lt;&lt; operators, respectively. The “&lt;&lt;” operator provides print ability. So the print function in the original Complex class can be removed. The “” operator provides the ability to change the private data members of the Complex class object.

b). Overload the multiplication operator to enable multiplication of two complex numbers as in algebra.

c). Overload the division operator to enable division of two complex numbers as in algebra. In here we need handle “divide by zero” situation.

d). Overload the == and != operators to allow comparisons of complex numbers.

e).Overload the = operator to allow assign a Complex object to the other Complex object.

f) Create CISP400V9A5.cpp to test all the functions designed in the assignment.

The following is an explanation on the complex number calculation.

Adding two complex numbers. The real parts are added together and the imaginary parts are added together. So, if we have (a + bi) + (c + di)), the result should be (a + c) + (b + d) i.Subtracting two complex numbers. The real part of the right operand is subtracted from the real part of the left operand, and the imaginary part of the right operand is subtracted from the imaginary part of the left operand. So, if we have (a + bi) – (c + di)), the result should be (a – c) + (b – d) i.Multiplying two complex numbers. The real part of the result is the real part of the right operand multiplies the real part of the left operand minus the imaginary part of the right operand multiply the imaginary part of the left operand. The imaginary part of the result is the real part of the left operand multiply the imaginary part of the left operand plus the imaginary part of the left operand multiply the real part of the right operand. So, if we have (a + bi) * (c + di)), the result should be (ac – bd) + (ad + bc) i.Dividing two complex numbers. We set the value of square real part of the denominator plus square imaginary part of the denominator is A. The real part of the result is the real part of the numerator multiplies the real part of the denominator plus the imaginary part of the numerator multiply the imaginary part of the denominator and divided by A. The imaginary part of the result is the real part of the left operand multiply the imaginary part of the left operand plus the imaginary part of the left operand multiply the real part of the right operand. So, if we have (a + bi) / (c + di)), the result should be (ac+bd)+i(bc-ad))/(c2+d2).If you have question regarding the calculation of complex numbers you can refer to Complex numbers.doc file which is attached with this assignment. Or you can search the internet for information.

CISP400V9A5.cpp

In CISP400V9A5.cpp we need to do the following

1. Instantiate 6 Complex objects ( x, y( 4.3, 8.2 ), z( 3.3, 1.1 ), k, l, and m(0, 0.1)).

2. Use “cin k:” statement to provide k object data.

3. Display all the object data by using “cout &lt;&lt; “
x: ” &lt;&lt; x &lt;&lt; “
y: ” &lt;&lt; y &lt;&lt; “
z: ” &lt;&lt; z &lt;&lt; “
k: ” &lt;&lt; k &lt;&lt; “
l: ” &lt;&lt; l &lt;&lt; “
m: ” &lt;&lt; m &lt;&lt; ‘
’;”

4. Use “x = y + z;” statement to demonstrate overloading + and = operators. And use “cout &lt;&lt; “
x = y + z:
” &lt;&lt; x &lt;&lt; ” = ” &lt;&lt; y &lt;&lt; ” + ” &lt;&lt; z &lt;&lt; ‘
’;” statement to display the result.

5. Use “x = y – z;” statement to demonstrate overloading – and = operators. And use “cout &lt;&lt; “
x = y – z:
” &lt;&lt; x &lt;&lt; ” = ” &lt;&lt; y &lt;&lt; ” – ” &lt;&lt; z &lt;&lt; ‘
’;” statement to display the result.

6. Use “x = y * z;” statement to demonstrate overloading * and = operators. And use “cout &lt;&lt; “
x = y * z:
” &lt;&lt; x &lt;&lt; ” = ” &lt;&lt; y &lt;&lt; ” * ” &lt;&lt; z &lt;&lt; ‘
’;” statement to display the result.

7. Use “x = y / z;” statement to demonstrate overloading / and = operators. And use “cout &lt;&lt; “
x = y / z:
” &lt;&lt; x &lt;&lt; ” = ” &lt;&lt; y &lt;&lt; ” / ” &lt;&lt; z &lt;&lt; ‘
’;” statement to display the result.

8. Use “x = y / l;” statement to demonstrate overloading / and = operators. And use “cout &lt;&lt; “
x = y / l:
” &lt;&lt; x &lt;&lt; ” = ” &lt;&lt; y &lt;&lt; ” / ” &lt;&lt; l &lt;&lt; ‘
’;” statement to display the result. This is a divide by zero situation.

9. Use “x = y / m;” statement to demonstrate overloading / and = operators. And use “cout &lt;&lt; “
x = y / m:
” &lt;&lt; x &lt;&lt; ” = ” &lt;&lt; y &lt;&lt; ” / ” &lt;&lt; m &lt;&lt; ‘
’;” statement to display the result. This is a divide by a close to zero situation.

10. Use “if ( x != k ) cout &lt;&lt; x &lt;&lt; ” != ” &lt;&lt; k &lt;&lt; ‘
’;” statement to demonstrate overloading ! = operator and to display the result.

11. Use “x = k;” statement to demonstrate overloading = operator.

12. Use “if (x == k ) cout &lt;&lt; x &lt;&lt; ” == ” &lt;&lt; k &lt;&lt; ‘
’;” statement to demonstrate overloading == operator and to display the result.

The assignment comes with a CISP400V9A5.zip file. It includes four files (CISP400V9A5.exe, Complex.h, Complex.cpp, and fig10_16.cpp). The CISP400V9A5.exe file is an executable file. You can double click the file to get to the expecting result (see the picture below) of this assignment. The Complex.h, Complex.cpp, and fig10_16.cpp are files coming from the textbook examples which you can use so you don’t need to start from scratch. You also need to follow the specification for the CISP400V9A5.cpp to do the driver to test the Complex class. After you finish your implementation for the Complex class and CISP400V9A5.cpp, you can put the CISP400V9A5.cpp, Complex.h and Complex.cpp in a project and then you can run to the same result as the CISP400V9A5.exe.

The following is a display of the expecting results.

Please document CISP400V9A5.cpp, Complex.h and Complex.cpp properly and zip them into a proper named zip file for an assignment (refer to the assignment section of the class syllabus) and submit it to the A5 dropbox of the D2L Website.

Worth 150 points

AD5

Create an inheritance hierarchy that a bank might use to represent customers’ bank accounts. All customers at this bank can deposit (i.e., credit) money into their accounts and withdraw (i.e., debit) money from their accounts. More specific types of accounts also exist. Savings accounts, for instance, earn interest on the money they hold. Checking accounts, on the other hand, charge a fee per transaction (i.e., credit or debit). When an account is setup the date is recorded. When there is an update the date is recorded.

Create an inheritance hierarchy containing base class Account and derived classes SavingsAccount and CheckingAccount that inherit from class Account. Account class has Date class as compositions.

Account class

Base class Account should include one data member of type double to represent the account balance, two string objects to represent first name and last name, and two Date objects to represent account starting date and last account update date.

The class should provide a constructor that receives an initial balance, first name, last name, starting date and last account update date and uses it to initialize the data members. The constructor should validate the initial balance to ensure that it is greater than or equal to 0.0. If not, the balance should be set to 0.0 and the constructor should display an error message, indicating that the initial balance was invalid.

The class should provide several member functions. The following is just a list of four. You can add more function as needed.

Member function credit should add an amount to the current balance.Member function debit should withdraw money from the Account and ensure that the debit amount does not exceed the Account’s balance. If it does, the balance should be left unchanged and the function should print the message “Debit amount exceeded account balance.” Either way the last account update date will be changed.Member function getBalance should return the current balance.Print function displays customer’s name, A/C Open date, A/C Update date, and A/C balance.

SavingsAccount class

Derived class SavingsAccount should inherit the functionality of an Account, but also include a data member of type double indicating the interest rate assigned to the Account.

SavingsAccount’s constructor should receive the initial balance, first name and last name of a customer, account starting date, last account update date, as well as an initial value for the SavingsAccount’s interest rate.

SavingsAccount should have four member functions. You can create more functions when there is a need.

A public member function calculateInterest that returns a double indicating the amount of interest earned by an account. Member function calculateInterest should determine this amount by multiplying the interest rate by the account balance. [Note: SavingsAccount should inherit member functions credit and debit as is without redefining them.]addInterest function add interest to the balance, update the last update date information and display customer name, interest rate , old balance, new balance information.Print function prints out “Savings Account:”, calls the base class print function and display the interest rate information.setinterestRate function validates the interest rate and set the interest rate to the private data member. If the rate is less than zero, set the rate to zero and display the rate and customer information.

CheckingAccount class

Derived class CheckingAccount should inherit from base class Account and include an additional data member of type double that represents the fee charged per transaction.

CheckingAccount’s constructor should receive the initial balance, first name and last name of a customer, account starting date, last account update date, as well as a parameter indicating a fee amount.

Class CheckingAccount should redefine member functions credit and debit so that they subtract the fee from the account balance whenever either transaction is performed successfully. CheckingAccount’s versions of these functions should invoke the base-class Account version to perform the updates to an account balance. CheckingAccount’s debit function should charge a fee only if money is actually withdrawn (i.e., the debit amount does not exceed the account balance). [Hint: Define Account’s debit function so that it returns a bool indicating whether money was withdrawn. Then use the return value to determine whether a fee should be charged.] If a transaction is a credit there is no transaction fee.

CheckingAccount should have three member functions. You can create more functions when there is a need.

chargeFee function subtracts fee from the account balance , displays the fee charge information, updates the last update date information.Print function displays “Checking Account:”, calls base class print function and shows transaction fee information.settransactionFee function validates the fee and set the fee to the private data member. If the fee is less than zero, set the fee to zero and display the fee and customer information.

Date class

The Date class comes from Figs. 9.17- 9.18(attached) is a good start. You need to incorporate this Date class into the Account class as private data members. The Date class needs to have setDate function which provides a tool to update a Date object private data member. It also needs to validate the data.

CISP400V9AD5.cpp

In the CISP400V9AD5.cpp file we need to declare 10 element array (account) pointer points to Account objects.Then declare some SavingsAccount’s and CheckingAccount’s object and assign them to the array pointer based on the following schedule and information.Array elementObject typeParameters information1SavingsAccount( 25.0 , .03, “Susan”, “Baker”, (1, 1, 2009), (2,19,2010))2SavingsAccount( 100 , .04, “Chao”, “Zulueta”, (5, 31,2013), (6,14,2014))3CheckingAccount( 80.0, 1.0, “Robert”, “Jones”, (2,29,2011), (3,19,2011))4CheckingAccount( 250.0, 2.0, “Kenneth”, “Ramirez”, (6,6,2009), (12,12,2013) )5SavingsAccount( 125 , .02, “Vue”, “Thomas”,(11, 30, 2010), (2,24,2011) )6CheckingAccount( 180.0, 3.0, “Angela”, “Wilma”, (3, 27, 2008), (2,19,2010) )7SavingsAccount( 600 , .04, “Romeo”, “Turner”, (4,19,2005), (3,19,2009) )8SavingsAccount( 95 , .02, “Oscar “, “Udonkanga”, (10,10,2003), (5,6,2007))9CheckingAccount( 255.0, 3.0, “Jimmy “, “Untalasco”, (7, 32,2009), (7,32,2009))10CheckingAccount( 80.0, 1.0, “Terrence”, “Trocino”, (11, 16, 2009), (4,4,2011))

Use “cout &lt;&lt; “

***Initial Accounts information***
”;” and “for (int i=0; i&lt;10; i++) account[i]-print();” to display the accounts’ information.Adjust accounts on 5/5/2011 based on the following schedule, call functions to update the account information:Array elementObject typeParameters information1SavingsAccountSusan Baker had a $40 debit.2SavingsAccountChao Zulueta had a $30 credit3CheckingAccountRobert Jones had a $40 debit.4CheckingAccountKenneth Ramirez had a $50 credit.5SavingsAccountVue Thomas had an accrued interest for a period.6CheckingAccountAngela Wilma had a transaction fee charged.7SavingsAccountRomeo Turner had an accrued interest for a period.8SavingsAccountOscar Udonkanga had a $60 debit.9CheckingAccountJimmy Untalasco had a transaction fee charged10CheckingAccountTrocino Terrence had a $100 debit.

Use “cout &lt;&lt; “

***After the 5/5/2014 update, 
the Accounts information***
;” and “for (int i=0; i&lt;10; i++) account[i]-print();” to display the accounts’ information.On 8/8/2013 all the saving used the same interest rate(0.05) and all the checking used the same transaction fee($5). Use program to decide the object is saving or checking to do the adjustment. No man made adjustment allowed.Use “cout &lt;&lt; “

***After the 8/8/2013 update,
the Accounts information***
” and “for (int i=0; i&lt;10; i++) account[i]-print();” to display the accounts’ information.

The assignment comes with a CISP400V9AD5.zip file. It includes three files (CISP400V9AD5.exe, Date.h, and Date.cpp). The CISP400V9AD5.exe file is an executable file. You can double click the file to get to the expecting result (see the picture below) of this assignment. The Date.h, and Date.cpp are files coming from the textbook examples which you can use so you don’t need to start from scratch. You also need to follow the specification for the CISP400V9AD5.cpp to do the driver to test this program. After you finish your implementation for the SavingsAccount class, CheckingAccount class, and Account class and CISP400V9AD5.cpp, you can put the CISP400V9AD5.cpp, SavingsAccount.h , SavingsAccount.cpp, CheckingAccount.h, CheckingAccount.cpp, Account.h, and Account.cpp in a project and then you can run to the same result as the CISP400V9AD5.exe.

The following is a display of the expecting results.

Please document CISP400V9AD5.cpp, SavingsAccount.h , SavingsAccount.cpp, CheckingAccount.h, CheckingAccount.cpp, Account.h, and Account.cpp files properly and zip them into a proper named zip file for an advance assignment (refer to the assignment section of the class syllabus) and submit it to the A5 dropbox of the D2L Website.

Worth 180 points