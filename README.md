# LLM Literature Review
## Author Details
Author: Jesse Arevalo Baez <br>
E-Mail: arevalobaez@chapman.edu <br>
Course Section: CPSC 354 - Section 3 <br>
LLM Model: Microsoft Copilot <br>

## Summary
There is an abundence of various, unique programming languages out there, but why do a lot of developers prefer to stick with certain, prominent industry-standard languages instead? What is the point of other languages existing while there are other much more powerful and widely supported languages out there that dominate the industry? These are various questions that I have asked Microsoft Copilot (powered by GPT-4) to answer in hopes of gaining a better understanding of the advantages these languages hold over the others, and understanding why many developers still continue to improve on these other niche languages while the more prominent ones continue to be preferred by many companies and studios.

## Learned Concepts
- Various different programming languages have certain advantages over other
- Each programming language has a specific use case that they specialize in
- It is good practice to integrate multiple different programming languages to function together and handle the specific tasks they are most commonly used for in software

## References

[Polyglot Programming](http://theuntitledblog.com/wp-content/uploads/2008/08/polyglot_programming-a_business_perspective.pdf)<br>
[Comparison of Java and C++ Programming](http://utpedia.utp.edu.my/id/eprint/6883/1/2006%20-%20COMPARATIVE%20STUDY%20BETWEEN%20JAVA%20AND%20C%2B%2B%20PROGRAMMING%20LANGUAGES.pdf)<br>
[Python vs. C++ In Machine Learning](https://www.netguru.com/blog/cpp-vs-python)


## Conversation
### Section 1 - What Makes C++ and C# Stand out Compared to Other Languages in Games?
Me: There is an extensive variety of programming languages, notably being languages such as C++ and C# used within the video game industry. What makes these two languages stand out compared to the other many available languages such as Java, Python, and Haxe in the industry?

Copilot: Great question! C++ and C# are indeed prominent in the video game industry, and they stand out for several reasons:
C++

    Performance: C++ is known for its high performance and efficiency, which is crucial for game development where real-time processing and fast execution are essential.
    Memory Management: It provides fine-grained control over memory management, allowing developers to optimize resource usage, which is vital for complex game environments.
    Low-Level Programming: C++ allows for low-level programming, giving developers the ability to interact closely with hardware, which can be beneficial for performance optimization.
    Industry Standard: Many game engines, like Unreal Engine, are built using C++, making it a go-to language for game developers.

C#

    Ease of Use: C# is known for its simplicity and ease of use, which can speed up the development process.
    Unity Engine: C# is the primary language for Unity, one of the most popular game development engines. This makes it a preferred choice for many developers.
    Managed Code: C# runs on the .NET framework, which handles many low-level tasks like garbage collection, reducing the complexity for developers.
    Cross-Platform: With tools like Xamarin, C# can be used for cross-platform development, making it versatile for developing games on multiple platforms.

Comparison with Other Languages

    Java: While Java is also cross-platform and has good performance, it doesn’t offer the same level of control over hardware and memory management as C++.
    Python: Python is excellent for rapid development and prototyping due to its simplicity, but it lacks the performance needed for high-end game development.
    Haxe: Haxe is versatile and can compile to multiple languages, but it doesn’t have the same level of industry support or performance optimization as C++ and C#.
### Section 2 - Java vs. C++ in Video Games
Me: The game "Minecraft" has two versions, one comprised of C++ and the other with Java. They are both very similar at their core when it comes to gameplay, however time and time again many people would prefer to play the Java version over the cross-platform version in C++. Why is this the case? If C++ appears to be more manageable, powerful, and preferred over Java when it comes to game development, why do people still prefer to play on Java?

Copilot: The preference for the Java version of Minecraft over the C++ (Bedrock) version can be attributed to several factors:
Modding Community

    Ease of Modding: Java’s architecture makes it easier for developers to create and implement mods compared to C++

Performance and Flexibility

    Performance Perception: While C++ is generally more performant, Java’s performance has improved significantly over the years. Many players find the Java version’s performance satisfactory for their needs


While the Bedrock version (C++) offers cross-platform play and some performance advantages, the Java version’s modding capabilities, community support, and flexibility make it a favorite for many players. 

Me: Tell me more about Java's architecture. Why is it that it makes things easier for users and developers to create game modifications and other such unofficial content for the game compared to developing with C++?

Copilot: Java's architecture offers several features that make it particularly conducive to creating game modifications and unofficial content:

    Platform Independence
    1. Write Once, Run Anywhere: Java's platform independence means that code written in Java can run on any device with a Java Virtual Machine (JVM). This makes it easier for developers to create mods that work across different systems without needing to rewrite code.

    Memory Management
    2. Automatic Garbage Collection: Java handles memory management automatically through garbage collection, which reduces the complexity for developers. They don't need to manually manage memory allocation and deallocation, as they would in C++.

    Rich Standard Library
    3. Extensive Libraries: Java comes with a comprehensive standard library that provides a wide range of pre-built functionalities. This allows developers to leverage existing tools and frameworks, speeding up the development process.

    Ease of Use
    4. Simplified Syntax: Java's syntax is designed to be straightforward and easy to learn, which lowers the barrier to entry for new developers. This simplicity makes it easier for hobbyists and modders to start creating content.

    Community and Ecosystem
    5. Strong Community Support: Java has a large and active community, which means there are plenty of resources, tutorials, and forums available for developers. This community support is invaluable for troubleshooting and learning.

    Development Tools
    6. Integrated Development Environments (IDEs): Java benefits from powerful IDEs like IntelliJ IDEA, Eclipse, and NetBeans, which provide robust tools for coding, debugging, and testing. These tools make the development process more efficient and user-friendly.

    Security
    7. Sandboxing: Java's security model includes a sandboxing mechanism that allows code to run in a restricted environment. This is particularly useful for mods, as it can prevent malicious code from causing harm.

    Comparison with C++
    - Manual Memory Management: In C++, developers must manually manage memory, which can lead to errors and increased complexity.
    - Platform-Specific Code: C++ code often needs to be tailored for different platforms, which can complicate cross-platform development.
    - Complex Syntax: C++ has a more complex syntax and steeper learning curve, which can be a barrier for new developers.

Me: If Java is so much simpler then why can't industries put more emphasis on Java development? If it can get enough backing, wouldn't be as good, if not, better than using C++ or C#?

Copilot: Java is indeed a powerful and versatile language, and it is widely used in many industries. However, there are several reasons why C++ and C# are still preferred in certain domains, particularly in game development:

    Performance and Control
    1. High Performance: C++ offers superior performance and low-level control over hardware, which is crucial for resource-intensive applications like video games. This level of control allows developers to optimize performance in ways that are not possible with Java.
    2. Memory Management: C++ provides manual memory management, which can be more efficient for high-performance applications. While Java's automatic garbage collection simplifies development, it can introduce latency that is unacceptable in real-time applications.

    Industry Standards and Ecosystems
    3. Established Ecosystems: Many game engines, such as Unreal Engine, are built using C++. This creates a strong ecosystem and community around C++ for game development.
    4. Platform-Specific Optimizations: C++ allows for platform-specific optimizations, which can be critical for achieving the best performance on different hardware configurations.

    Language Features
    5. Low-Level Programming: C++ supports low-level programming, which is essential for tasks that require direct hardware manipulation, such as graphics rendering and physics calculations.
    6. Concurrency and Parallelism: C++ offers robust support for concurrency and parallelism, which are important for modern game development to utilize multi-core processors effectively.

    ava's Strengths in Other Domains
    7. Enterprise Applications: Java excels in enterprise applications, web development, and Android app development due to its platform independence, security features, and extensive libraries.
    8. AI/ML and Microservices: Java is also strong in AI/ML and microservices architectures, where its portability and robust frameworks like Spring Boot are highly valued.

    Conclusion
    While Java is simpler and highly effective in many areas, the specific requirements of game development—such as performance, low-level hardware access, and established ecosystems—make C++ and C# more suitable for this domain. Java continues to thrive in other areas where its strengths are more aligned with the needs of the applications being developed.
### Section 3 - Beyond Game Development
Me: Let's see the scope outside of game development, as java and C++ is widely used in general. If this is such the case, what is the point of other programming languages being used or continuously being developed when these languages (Java, C++, and C#) dominate the industry in development?

Copilot: While Java, C++, and C# are indeed dominant in many areas, there are several reasons why other programming languages are used and continue to be developed:
Specialization and Optimization

    Task-Specific Languages: Some languages are designed for specific tasks or domains. For example, Python is widely used in data science, machine learning, and artificial intelligence due to its simplicity and powerful libraries like TensorFlow and Pandas1R is another language specialized for statistical analysis and data visualization.
    Web Development: JavaScript is essential for web development, especially for client-side scripting. Frameworks like React, Angular, and Vue.js are built around JavaScript3Ruby and PHP are also popular for web development due to their ease of use and strong community support.

Ease of Use and Learning Curve

    Beginner-Friendly Languages: Languages like Python and Scratch are often used in educational settings because they have a gentle learning curve and are easy for beginners to understand.
    Rapid Development: Languages like Ruby (with its Rails framework) and Python allow for rapid development and prototyping, making them ideal for startups and projects that need to iterate quickly.

Performance and Efficiency

    High-Performance Computing: Fortran and CUDA are used in high-performance computing and scientific computing due to their efficiency and ability to handle complex mathematical computations.
    System Programming: Rust is gaining popularity for system programming because it offers memory safety without sacrificing performance, making it a strong alternative to C and C++.

Community and Ecosystem

    Community Support: Languages with strong communities and ecosystems can be more attractive for certain projects. For example, Elixir is known for its robust concurrency support and is used in scalable web applications.
    Legacy Systems: Some industries rely on legacy systems written in languages like COBOL. These languages continue to be used and maintained because rewriting the entire system in a modern language would be costly and risky.

Innovation and Experimentation

    New Paradigms: New languages often introduce innovative features or paradigms. For example, Kotlin offers modern features and improved syntax over Java, making it a preferred choice for Android development.
    Functional Programming: Languages like Haskell and Scala promote functional programming paradigms, which can lead to more predictable and maintainable code.

Conclusion

While Java, C++, and C# are powerful and versatile, the diversity of programming languages allows developers to choose the best tool for the job, optimize for specific tasks, and innovate with new paradigms. This variety ultimately drives the evolution of technology and software development.
### Section 5 - Unifying Different Languages
Me: That makes much more sense in that perspective. Since there are different languages that specialize or have specific use cases that are much more efficient for those jobs, do developers tend to try to unify these languages together into one project? As someone who is studying software engineering and game development, is that a practice that is common within the industry? I do not mean it in a sense where developers will create one big programming language, but moreso to mend different languages together for their specific use cases and integrating it into one software? i.e. Using a mix of Java, C++, and CUDA to create a specific program?

Copilot: Yes, integrating multiple programming languages within a single project is a common practice in the software industry, including game development. This approach, often referred to as polyglot programming, allows developers to leverage the strengths of different languages for specific tasks. Here are some ways this is typically done:
Interfacing and Integration Techniques

    APIs and Libraries: Different parts of a project can be written in different languages and communicate through APIs. For example, a game might use C++ for performance-critical components and Python for scripting and AI1.
    Inter-Process Communication (IPC): Separate programs written in different languages can communicate via IPC mechanisms like sockets, pipes, or shared memory2. This is useful for modular systems where different components need to interact.
    Foreign Function Interfaces (FFI): Languages like Python and Java provide FFIs that allow them to call functions written in C or C++. This is often used to integrate high-performance C/C++ libraries into higher-level languages2.
    Embedded Interpreters: Some languages can embed interpreters for other languages. For example, a C++ application might embed a Python interpreter to run Python scripts2.

Common Use Cases

    Web Development: A web application might use JavaScript for the frontend, Python or Ruby for the backend, and SQL for database queries3.
    Game Development: A game might use C++ for the core engine, Lua for scripting, and HLSL/GLSL for shader programming.
    Data Processing: A data pipeline might use Java for data ingestion, Python for data analysis, and R for statistical modeling3.

Benefits

    Best Tool for the Job: Using the most suitable language for each task can lead to more efficient and maintainable code1.
    Flexibility: Developers can choose languages based on their strengths and the specific requirements of the project1.
    Performance Optimization: Critical components can be written in high-performance languages, while less performance-sensitive parts can use more developer-friendly languages1.

Challenges

    Complexity: Managing a project with multiple languages can be complex, requiring careful coordination and integration2.
    Skill Requirements: Developers need to be proficient in multiple languages, which can increase the learning curve and development time2.
    Tooling and Debugging: Different languages may require different development tools and debugging techniques, which can complicate the development process2.

Conclusion

Polyglot programming is a powerful approach that allows developers to use the best tools for each part of a project. It’s common in many industries, including game development, where different languages are used to optimize performance, flexibility, and maintainability.