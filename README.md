# ThreadDemo
Explanation:

* The ThreadDemo class extends the Thread class and overrides its run() method. This is the code that will be executed when the thread is started.
* In the main() method, we create an instance of ThreadDemo and start the thread using the start() method. This will call the run() method in a separate thread.
* We use the isAlive() method to check if the thread is still running. Since we started the thread, it should be alive at this point.
* We use the join() method to wait for the thread to finish. This will block the main thread until the ThreadDemo thread has completed.
* After joining, we check again if the thread is alive. Since it has completed, it should no longer be alive
