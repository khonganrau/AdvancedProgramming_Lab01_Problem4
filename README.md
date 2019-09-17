# **AdvancedProgramming_Lab01_Problem4**
Person Class
> _**NOTE:**_ We created a namescape _**AP_Lab01_Problem4**_ in each class.
## Problem 04- _Create a Person Class_
We create a sub-class  with a name is _**Person.cs**_, it contains:
* The private fiels for the following properties:  
  * name: string  
  * age : int
  * accounts: List`<BankAccount>`
* The class also have constructors:  
  * Person(string name, int age)  
  * Person(string name, int age, List`<BankAccount>` accounts)
* The class also have the following public method:
  * GetBalance(): decimal
## **Solution**  
1. Created the private fields for these properties that mentions on the requirement of the _**Problem04**_  
   ![Imgur](https://i.imgur.com/eaPIGAJ.png)  
2. Added the constructors into the _**Person.cs**_ class  
   ![Imgur](https://i.imgur.com/DbSKw99.png)
3. Created the public method for _**GetBalance(): decimal**_ into _**Person.cs**_ class  
   ![Imgur](https://i.imgur.com/2dyI1WL.png)
4. Used the _**BankAccount**_ class that created in previously problem in _**Lab01**_. Howerver, we added the namescape _**AP_Lab01_Problem4**_ for this class.
5. In _**Program.cs**_, we called _**BankAccount**_ class to create new account, and called GetBalance() method to display the information of the account that created, beside that we create new objects by using _**Person**_ class.  
   ![Imgur](https://i.imgur.com/jx1kg8U.png)
