# cisc275-fall2019-first-git
1. Create java files to make this code compile and run.

Wrote 2 needed clases in the MyCompare3.java

2. What five objects are created in the main?

The dogs arraylist is created, 3 dog objects are created and the comparator object

3. Can you spot the Comparator constructor call? Where is the class definition for the Comparator?

In the Collections.sort method call  new Comparator<Animal>() is the Comparator constructer call.  Comparator is an interface but when that line is called it makes an instance of animal that implements Comparator so you can implement its methods.
