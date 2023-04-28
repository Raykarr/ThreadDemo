# ThreadDemo
Explanation:

* The ThreadDemo class extends the Thread class and overrides its run() method. This is the code that will be executed when the thread is started.
* In the main() method, we create an instance of ThreadDemo and start the thread using the start() method. This will call the run() method in a separate thread.
* We use the isAlive() method to check if the thread is still running. Since we started the thread, it should be alive at this point.
* We use the join() method to wait for the thread to finish. This will block the main thread until the ThreadDemo thread has completed.
* After joining, we check again if the thread is alive. Since it has completed, it should no longer be alive

## The program demonstrates the use of several methods of the Thread class:

* start(): This method is used to start a new thread by calling its run() method in a separate thread.
* isAlive(): This method is used to check if the thread is still running. In the program, we use this method to check if the ThreadDemo thread is still alive after starting it.
* join(): This method is used to wait for the thread to finish. In the program, we use this method to block the main thread until the ThreadDemo thread has completed.

By using these methods, we can create and manage threads in Java.
