
## 0x05. Processes and signals


In Python, processes and signals can be used to handle concurrent execution and interprocess communication. 
Here are some key concepts and modules related to processes and signals in Python:

1. `multiprocessing`: This module provides support for spawning processes using an API similar to threading module. 
It allows you to create and manage processes, and provides various mechanisms for interprocess communication, 
such as pipes, queues, and shared memory.

2. `subprocess`: The `subprocess` module allows you to spawn new processes, 
connect to their input/output/error pipes, and obtain their return codes. 
It provides a high-level interface for working with subprocesses.

3. Process Creation and Management: Python provides different methods for creating and managing processes. 
The `multiprocessing.Process` class allows you to create new processes, start them, and control their execution. 
You can also use functions like `os.fork()` and `subprocess.Popen()` to create child processes.

4. Interprocess Communication: Processes in Python can communicate with each other using various mechanisms. 
Some common options include pipes, queues, shared memory, and sockets. 
The `multiprocessing` module provides classes like `Pipe` and `Queue` for interprocess communication.

5. Signals: Signals are used for process-to-process communication in Unix-like systems. 
The `signal` module in Python allows you to handle signals sent to a process. 
You can register signal handlers to catch specific signals and perform custom actions in response.

6. `os.kill` and `signal` module: The `os.kill` function is used to send a signal to a process. 
The `signal` module provides functions to handle signals, including `signal.signal()` 
to set signal handlers and `signal.pause()` to pause the program until a signal is received.

7. Signal Handling: Python provides the ability to handle and respond to various signals,
 such as `SIGINT` (interrupt signal), `SIGTERM` (termination signal), and `SIGUSR1` (user-defined signal 1).
 You can define signal handlers using the `signal.signal()` function.

These are some of the fundamental concepts and modules related to processes and signals in Python. 
By utilizing these features, you can effectively manage concurrent execution, 
interprocess communication, and handle signals in your Python programs.
