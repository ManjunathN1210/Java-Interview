# JAVA INTERVIEW QUESTIONS

1. **What is JAVA?**

Java is a high-level, object-oriented programming language developed by Sun Microsystems (acquired by Oracle Corporation) in the mid-1990s. It is designed to be platform-independent, meaning that Java programs can run on any device or operating system that has a Java Virtual Machine (JVM) installed.

2. **Where is JAVA used?**
- **Web Development:** Java is widely used for building dynamic and interactive web applications. Frameworks like Spring, Java Server Faces (JSF), and Play Framework make it easier to develop robust web applications.
- **Mobile App Development:** Java is the primary programming language for developing Android applications. Android Studio, the official Android IDE, uses Java as the default language for Android app development.
- **Enterprise Applications:** Java is a popular choice for building large-scale, enterprise-level applications due to its scalability, security features, and strong community support. Many enterprise systems, including customer relationship management (CRM) software, enterprise resource planning (ERP) solutions, and banking applications, are built using Java.
- **Desktop Applications:** Java can be used to create desktop applications with graphical user interfaces (GUIs). JavaFX and Swing are two popular frameworks for building desktop applications in Java.

3. **Which memory does java use and what are the differences between them?**

Java uses two types of memory for different purposes: the stack and the heap.

   **Stack:**
   - **Purpose:** The stack is used for storing method invocations, local variables, and method call frames.
   - **Allocation:** Memory for stack variables is allocated in a last-in-first-out (LIFO) manner. When a method is called, a new stack frame is created and pushed onto the top of the stack. When a method returns, its stack frame is removed (popped) from the stack.
   - **Size and Speed:** The stack is generally smaller in size compared to the heap, and memory allocation and deallocation on the stack are faster because of the LIFO structure.
   - **Lifetime:** Variables and references in the stack have a limited lifetime, tied to the scope of the method they are declared in. They are automatically deallocated when the method returns.

   **Heap:**
   - **Purpose:** The heap is used for dynamic memory allocation and is where objects (instances of classes) and arrays are stored.
   - **Allocation:** Memory for objects in the heap is allocated and managed by the garbage collector. Objects in the heap can be accessed by multiple parts of the program, and their lifetime extends beyond the scope of the method that created them.
   - **Size and Speed:** The heap is typically larger in size compared to the stack, and memory allocation and deallocation on the heap are relatively slower than on the stack due to the more complex memory management processes.
   - **Lifetime:** Objects in the heap can have a longer lifetime, determined by the garbage collector based on reachability (whether the object is still referenced by any part of the program).