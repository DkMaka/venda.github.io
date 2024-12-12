COM1321PROJECT

#Description A project based on helping an individual make informed financial decision based on their form of income.
Participants GroupA

    
    MAKATSHABA KD 23026624
    GAMA SIZOLWETHU.C 24053119.
    
#Compilation And Run

    Open CMD command prompt window
    Use the command <cd C:\Users\YourUsername\IDE_Default_project_storage\Projects\YourProjectName\folderWithClasses + enter> to locate the exact location of the files you want to compile
    Alternative with a device synced to a cloud <C:\Users\YourUsername\TheCloudYouSynced\IDE_Default_project_storage\Projects\YourProjectName\folderWithClasses + enter>
    Use command <javac *.java + enter> to compile all the <.java> files into <.class> files.
    Use the command <java MainClass.java + enter> command to run you application.

#Classes involved

    main class budgeting-all executions took place here(method calls and instantiations)
    input-involved in taking inputs of various datatypes
    abstract class expense - where the abstract calculateLoan(), method was created
    homeloan subclass of expense(overrides the calculate loan and implements it)
    Vehicle - parent class of car to ensure good use of inheritance and encapsulation
    Car class-to just ask the user if they want a car, or not then the main class executes the tasks per car choice or decision.
    interface percentile to create classes that implement the method in percentile for the decision of percentage control and decision.
    classes to implement the interface are PercentageOver, PercentageUnder, and PercentageControl and all these worked together with PercentageControl delegating the task of notifying the user.

#Concepts Involved

    Package imports, for lists and Scanners.
    Variable usage alongside the operators.
    control flow by while, for, and if else.
    Classes
    Inheritance, encapsulation and abstraction
    object passing
    type casting
    method overrides
    exception handling to avoid lossy conversions

#functionallity The program asks for the income input, and all the deductions an average adult is prone to experience. The program enquires whether the user wants to purchase property or rent. The program proceeds to add the value to the other expenses and display that and proceed to ask if the user wants to purchase a car and does tasks by decision in choice of transportation. Through the choice it will workout certain inputs and terminate when done.
