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
