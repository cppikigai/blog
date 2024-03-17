### March 10, 2024. Day 0.
Today I'll start with an introductory note where I'll outline my plan for tomorrow.
Firstly, I'm going to describe the projects I'll be working on. There will be at least 4 repositories:
* [algorithms_kata](https://github.com/cppikigai/algorithms_kata): This repository will showcase my solutions to algorithmic problems from websites like [LeetCode](https://leetcode.com/). It's for practicing problem-solving skills often required in interviews.
* [tiny_software_renderer](https://github.com/cppikigai/tiny_software_renderer): This project will help me understand the basics of rendering. I'll be implementing rendering functionalities similar to popular graphics APIs but with my implementation on CPU.
* [common_tasks](https://github.com/cppikigai/common_tasks): This project will contain typical problems and their solutions. It will include interesting concepts that deserve attention and can be solved within a single file or function.
* Lastly, I'll work on a renderer using one of the modern APIs, or maybe multiple at once.

Over the 365 days, or one year, I plan to study all the fundamental algorithmic problems and write a software renderer. Through these projects, I aim to learn the essential skills required for my future job.

**Now, onto tomorrow's plan:**
* Implement window creation using [GLFW](https://github.com/glfw/glfw) and rendering the screen buffer via the OpenGL API for my software renderer.
* Add primitive helper classes for drawing lines based on coordinates and displaying them on the screen.
* Add basic classes for working with 2D and 3D vectors. I intentionally want to use my own math library to refresh my understanding of the underlying mathematics.
* Besides these tasks, I'm also reading [Bjarne Stroustrup's book on C++11](https://www.amazon.com/C-Programming-Language-4th/dp/0321563840) to refresh my knowledge. I'm reading it cover to cover, so this task will take around two weeks or more. I highly recommend this book for anyone looking to get acquainted with the language.
This is just the beginning of my journey, and I'm excited to see where it takes me. Stay tuned for more updates!

### March 11, 2024. Day 1.
- Created a LeetCode account and purchased a one-year premium subscription for $159.
- Did some setup for the repositories mentioned yesterday.
- Begun the beginner's guide on LeetCode and solved the first 6 tasks for warm-up. They were all quite easy, so I managed to submit them without assistance.
- Encountered a task involving bit manipulation techniques, so I decided to refresh my knowledge in this area. Added several tricks and approaches for working with bitwise operations to the common tasks repository.
- Didn't get to the renderer yet; I'm going to start tomorrow.
- I'm going to spend the remaining time today reading Stroustrup's C++ book (about 60 pages covering pointers, arrays, and references).

**Plans for tomorrow:**

- Finish the beginner's guide on LeetCode and start the bit manipulation course.
- Begin work on the software renderer. Write implementation for creating a window and drawing lines onto the screen buffer.

### March 12, 2024. Day 2.
Today I mostly focused on preparing the base of my software renderer.

- I added the GLFW library for creating the application window. Writing this from scratch for multiple platforms is quite laborious and not very engaging for me. So, I decided not to reinvent the wheel and opted for a good existing library.
- I also added Glad for simplified interaction with the OpenGL API. The files are generated directly on the [website](https://glad.dav1d.de/), which allows easy configuration of the required version and extensions.
- I configured the project and dependencies using CMake to avoid tying it to any specific IDE and keep it as simple as possible.
- Additionally, I implemented a simple rendering of a textured full-screen quad, and now it's possible to draw lines onto it based on coordinates. This is still a draft version. I just wanted to quickly get something working.
- Towards the end of the day, I completed a beginner course on LeetCode.

**Plans for tomorrow:**

- I want to continue refreshing my memory on bitwise manipulation tricks within LeetCode problems.
- I'll try to refactor the rendering to the texture on the screen.
- Additionally, I plan to write my own loader for object meshes, which I didn't have time to do today. I could use [Assimp](https://github.com/assimp/assimp), but I want to write my own implementation to remember how vertices and triangles are stored in the obj format.

### March 13, 2024. Day 3.
Today, by chance, I spent almost all my free time on one simple problem on LeetCode. I spent a long time thinking about how to find the optimal solution. As a result, all my plans got disrupted. Tomorrow, I'll be doing what I had planned to do today.

### March 14, 2024. Day 4.
Today, I decided to focus only on solving problems on LeetCode. I'm taking a course there covering the top 150 interview questions. I've set a goal to solve at least 3 problems per day. Right now, I'm taking the easier problems, but progress isn't very fast, but I'm starting to get the hang of it. I think it will get easier in two or three weeks.

### March 15, 2024. Day 5.
I'm still solving problems on LeetCode and started reading the book [Cracking the Coding Interview](https://www.amazon.com/Cracking-Coding-Interview-Programming-Questions/dp/0984782850). I also managed to solve 4 more problems.

**Plans for tomorrow:**
- I'll dedicate the day to implementing model loading and wireframe rendering.
- Also, I'll continue reading Stroustrup's book on C++11.
- Read about the KMP algorithm for a better way to solve problem 28, "Find the Index of the First Occurrence in a String."

### March 16, 2024. Day 6.
So, my plan for the day is to cover all the areas in which I'm developing:

- English
- Algorithms
- Rendering engine
- Books about C++ and rendering
  
I want to solve 1000 problems within a year.
Read 10 books about C++ and rendering.
Write software renderer and engine using modern graphics APIs.
Also, learn 5000 English words.

And I usually have no more than 4 hours a day. So, I'll try to fit everything within these limits.
For example, an hour for each direction. Today I'll check approximate measurements of how much I can accomplish.

### March 17, 2024. Day 7.
Today and yesterday, I gathered approximate statistics on the speed of various activities in my learning.

- Solving 4-5 problems, including preparing tests, takes on average 1 hour 40 minutes. It's hard to do it any faster. Ideally, I want to finish 4 tasks in an hour. That's what I'm aiming for.
- Spending an hour reading technical literature allows me to study and read no more than 15 pages.
- Spending an hour studying English flashcards allows me to go through 250-260 cards. On average, this adds about 10 new words.

So, that's the statistics. Ideally, I'd like to read 20 pages, solve 4 tasks, and go through 250 flashcards per day, all while spending a total of 3 hours, leaving time for pet-projects.
