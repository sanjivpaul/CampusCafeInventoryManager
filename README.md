## Questions
1. **What did you predict for Warmup.java, and what did it actually print? Explain the lines that surprised you.**

   I've predicted ***Warmup.java*** as same as output, 
   - **(int)** holds only whole number so int of 7.9 is 7.
   - And in switch case statement we have set day = 2, and after case 2 there is no break statement so case 3 will also print.

2. **What is the difference between the static variable totalProducts and the instance variable name?**

***Static variable totalProducts***

- totalProducts is value is same for all the instances of Product class.
- We can directly access totalProducts variable without creating a instance of Product class.
- If we modify or update totalProducts value then it will reflect all the instance of Product classes.

***Instance variable***

- Instance variables are only accessible to that instance.
- If we modify in instance variable then it will not reflect all the instances of Product class.

3. **What does the copy constructor do, and why does changing p2.name not change p1.name?**

- Copy constructor create new object by copying the values and properties of existing object.
- After copying p2 is a new object have same value as p1 and when we modify p2 so it does not change p1 because both object have their own instance variables.

4. **Why does Java force you to write (int) average when converting a double to an int, and what happens to the decimal part?**

- We use (int) to convert decimal number into a whole number it explicit typecasting, and decimal part is discarded not rounded. 