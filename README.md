# conan

State delta-debugging in Java. See Andreas Zeller's paper: [Isolating Cause-Effect Chains from Computer Programs](http://swtv.kaist.ac.kr/courses/cs750b-sw-model-checking-fall-06/cs750b-sw-model-checking-fall-06/p201-zeller.pdf)

To launch Conan, you have to put a correct challenge in src/main/resources/challenges folder.

What is a correct Challenge ?

A correct challenge has to implements all the methods from the interface in /src/main/java/fil/iagl/opl/conan/model/Challenge
The challenge also have to import this interface "import fil.iagl.opl.conan.model.Challenge;"

What is a good Challenge ?

A good Challenge needs two different inputs, one which is passing and one which leads to the failure in order to have a different execution trace.

To launch Conan :

After choosing your challenges, run the main method.