# 8-1-Journal-Portfolio-Submission

<body>

<h1>Course Planner Project - Reflection</h1>

<h2>1. What was the problem you were solving in the projects for this course?</h2>
<p>
    In both projects, the primary problem was designing a course planning system that allows users to load course data, search for specific courses and their prerequisites, and print an ordered list of all available courses. The challenge involved choosing appropriate data structures to efficiently store, retrieve, and manage this course information, especially as the data set grows.
</p>

<h2>2. How did you approach the problem? Consider why data structures are important to understand.</h2>
<p>
    I began by evaluating the requirements: efficient course lookup, validation of prerequisites, and displaying courses in alphanumeric order. I approached the solution by implementing multiple data structures—vectors, hash tables, and binary search trees—in pseudocode for Project One to analyze their strengths and trade-offs. For Project Two, I implemented a fully functional version using a hash table (<code>unordered_map</code>) in C++ because it provides constant-time access for lookups and validation, which is ideal for this use case. Understanding data structures is critical because the performance, scalability, and maintainability of software are directly tied to how well the data is organized and accessed.
</p>

<h2>3. How did you overcome any roadblocks you encountered while going through the activities or project?</h2>
<p>
    One of the main roadblocks I faced was managing user input and file parsing in a robust way, especially when dealing with variations in formatting or unexpected input. I resolved these issues by adding input validation, using <code>getline</code> to safely handle strings, and testing the parser with different file structures. Another challenge was ensuring that the hash table maintained usability despite its unordered nature, which I addressed by sorting the keys before displaying the course list.
</p>

<h2>4. How has your work on this project expanded your approach to designing software and developing programs?</h2>
<p>
    These projects taught me the value of planning data structures early in the design process and thinking about how users will interact with the program. It helped me recognize the trade-offs between simplicity and efficiency, and I learned to select the most suitable structure based on the problem domain. Additionally, it pushed me to separate functionality into reusable, testable functions, which is a critical aspect of clean software design.
</p>

<h2>5. How has your work on this project evolved the way you write programs that are maintainable, readable, and adaptable?</h2>
<p>
    Working on this project refined my approach to code organization, modularity, and naming conventions. I focused on writing clean, well-commented code that clearly separates logic (e.g., parsing, searching, printing). I also ensured that each function had a single responsibility, which makes the code easier to update or expand in the future—such as switching out the data structure or adding new features like course filtering or exporting results. This experience has improved my ability to write software that is not only functional but also maintainable and scalable.
</p>

</body>
