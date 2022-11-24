# smell detection with deep learning
A code smell is a surface symptom that possibly indicates a more serious problem in the application, the code hindering the maintenance, development and progress of the application. Sometimes code smells are caused by poor design and programming style. So it is necessary to detect smells in the code. In the past years, several cases have been made for a car design model or design for identification. These models are carefully built using machine algorithms, such as RF, SVM, Decision Tree, Logistic Regression, Naive Bayes, DNN, NN, CNN, RNN, LSTM and GRU.
 The purpose of this research is to provide a method to improve the result of detecting smells in code using machine methods. Because the methods of using the machine are growing and are constantly improved with methods that have better efficiency and accuracy in terms of performance and processing power.
 
 The term code smell is used to indicate the existence of quality problems in the code. A large number of smells in a software system is associated with a high level of technical problems that hinder the evolution of the system.
First, the smell smells as the name suggests, so it is something that is quickly recognized. A long method or a class with lots of data but no behavior are good examples of this. The second point is that the smell is not always a sign of a problem. For example, some long methods are very good. You have to look deeper into them to find out if there is an underlying problem. Odors are not inherently bad. They often indicate a problem rather than the problem itself. The existence of a bad smell in the code definitely does not mean that the software does not work, the software still gives its output despite the bad smell of the code. But this stench may slow processing, increase the risk of crashes and software errors. Bad smelling code lowers the quality of the code and thus increases the technical debt.
Some examples of smells in the code are as follows.
Long Methods: Methods that contain many lines. We usually consider methods with more than 10 lines as large methods.
Feature Envy: When a method, in addition to its own data, accesses the data of another object.
God Class: Classes that contain a large number of variables and functions.
Long Parameter List: A function has more than three or four input parameters.
Switch Statements: When there is a complex switch operator or a sequence of if statements in the code.
Data Class: Data class contains only fields and simple methods to access these fields. getters and setters These classes simply become containers for data used by other classes.
These classes have no other functionality and cannot independently use the data that belongs to them.
