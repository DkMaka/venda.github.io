COM1321PROJECT

#Description A project based on helping an individual make informed financial decision based on their form of income.
Participants GroupA

    
    MAKATSHABA KD 23026624
    GAMA SIZOLWETHU.C 24053119.
    
#Compilation And Run

    1. Open CMD command prompt window
    2. Use the command <cd C:\Users\YourUsername\IDE_Default_project_storage\Projects\YourProjectName\folderWithClasses + enter> to locate the exact location of the files you want to compile
    3. Alternative with a device synced to a cloud <C:\Users\YourUsername\TheCloudYouSynced\IDE_Default_project_storage\Projects\YourProjectName\folderWithClasses + enter>
    4. Use command <javac *.java + enter> to compile all the <.java> files into <.class> files.
    5. Use the command <java MainClass.java + enter> command to run you application.

#Classes involved

    1. main class budgeting-all executions took place here(method calls and instantiations)
    2.input-involved in taking inputs of various datatypes
    3. abstract class expense - where the abstract calculateLoan(), method was created
    4. homeloan subclass of expense(overrides the calculate loan and implements it)
    5. Vehicle - parent class of car to ensure good use of inheritance and encapsulation
    6. Car class-to just ask the user if they want a car, or not then the main class executes the tasks per car choice or decision.
    7. interface percentile to create classes that implement the method in percentile for the decision of percentage control and decision.
    8. classes to implement the interface are PercentageOver, PercentageUnder, and PercentageControl and all these worked together with PercentageControl delegating the task of notifying the user.

#Concepts Involved

    1. Package imports, for lists and Scanners.
    2. Variable usage alongside the operators.
    3. control flow by while, for, and if else.
    4. Classes
    5. Inheritance, encapsulation and abstraction
    6. object passing
    7. type casting
    8. method overrides
    9. exception handling to avoid lossy conversions

#functionallity The program asks for the income input, and all the deductions an average adult is prone to experience. The program enquires whether the user wants to purchase property or rent. The program proceeds to add the value to the other expenses and display that and proceed to ask if the user wants to purchase a car and does tasks by decision in choice of transportation. Through the choice it will workout certain inputs and terminate when done.
