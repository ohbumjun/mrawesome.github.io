---
title: "BumJun Oh"
layout: single
excerpt: "Introduction of Bum Jun Oh, a Software Engineer <br><br><br>"
header:
  overlay_image: /assets/images/Dream_BackGround.jpg
classes: wide
author_profile: true
---

![BumJunOh_Introduction](/Images/home/BumJunOh_Intro_Small.jpg)

I am a C/C++/C# software developer currently working as a Game Engine Programmer at Com2us. My focus is on creating high-performance, secure software, with a strong interest in advancing my expertise in graphics APIs and network programming.

I hold a bachelor's degree from Chung-Ang University, where I majored in Psychology and double majored in Statistics-based AI. This multidisciplinary program encompassed a range of courses in statistics and computer science, equipping me with analytical and technical skills. To further expand my knowledge, I pursued a degree in Information and Communications Engineering, deepening my understanding of computer networks.

My primary interests lie in software development with C/C++/C#, and I am passionate about optimizing systems and tackling complex technical challenges.


# Education

## Chung-Ang University

* Bachelor of Arts in Psychology (2022)
* Double-Major in Statistical Artificial Intelligence (2022)

Please refer to [this post](/professionalprojects/CollegeProjects) for more details about my college projects.

# Career

## *Com2us*
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing
  * As a Game Engine programmer, I designing and implementing core engine systems such as
  
  @ Real time Build System using Multi-Process : A feature similar to Unreal Engine's Hot Reload, which reflects real-time changes made to the client user project without restarting the application
  
  @ Image Compression System (DXT, ASTC, ETC2) : Reduced a image size to 1/8 of original
  
  @ Event System: A mechanism that allows developers to efficiently trigger predefined functions or behaviors in response to specific in-game events or conditions, enabling seamless communication between different systems within the game engine
  
  @ Realtime Filewatcher System : A system designed to track real-time changes to files or assets, ensuring the game engine dynamically updates and reflects modifications without requiring a restart.
  
  @ Audio System using <miniaudio> library
  
  @ Persistent Object System : A feature inspired by Unity's DontDestroyOnLoad, designed to ensure specific objects or data persist across scene transitions or game states
  
  @ C++ to C# Interoperability System: A framework enabling seamless invocation of functions from a C# project within a C++ project using the CoreCLR runtime.
  
  @ C/C++ Runtime Reflection System: A system implemented using the Clang Compiler API to bring C#-like runtime reflection capabilities to C/C++. This enables dynamic access to and manipulation of program metadata, such as classes, functions, and properties, at runtime
  
  @ Allocator System (Fixed Size, Variant Size, Redblack Tree Combination) : reduced 1.5 GB of memory usage

  @ Multithreading System: A robust framework designed to optimize performance and resource utilization in the game engine by leveraging multithreading techniques.

  Example 1: Multi-threaded Updates with Job System:
  Implements a Job System to distribute tasks such as physics calculations, AI updates, or gameplay logic across multiple threads, ensuring efficient parallel execution and     reduced frame times.

  Example 2: Asynchronous Asset Loading:
  Utilizes background threads to load assets such as textures, models, and audio files asynchronously, preventing stalls in the main thread and ensuring smooth gameplay         experiences.

  @ C# to C++ Conversion Tool Using Roslyn API: A powerful tool that utilizes the Roslyn C# Compiler API to automate the conversion of Unity C# game source code to C++ code     for use in your own game engine. This tool significantly accelerates the porting process by automatically translating key gameplay logic, systems, and scripts, reducing the   development period by at least 2 weeks compared to manual code migration.
  
  @ Custom Garbage Collector with Safe Raw Pointer Handling: A custom garbage collection system developed with its own format, ensuring safe management of raw pointers. This     system tracks memory allocations and deallocations in a way that prevents issues commonly associated with raw pointer usage, such as dangling pointers or memory leaks

  @ Custom Parser and Serialization System: A tailored parser and serialization logic designed to handle multiple data formats such as JSON, YAML, MessagePack, and CMake.       This system provides efficient and flexible serialization/deserialization of game data, ensuring compatibility with various external data structures and configuration files

  @ Object Management System (Object Database and Object Handle): A robust system designed to manage game objects using an object database and object handles, with a focus on solving reference issues such as dangling pointers.
  
  @ Entity Component System (ECS): A highly efficient architecture for managing game entities and their components, designed to optimize performance and scalability.

    Example 1: SparseSet:
    A memory-efficient data structure used to store and access entity-component associations. It minimizes memory overhead by providing fast lookups and handling sparse entity-component mappings without excessive memory usage, especially in large-scale games.

    Example 2: Archetype:
    A system that organizes entities based on their component composition, allowing for efficient data access and iteration. By grouping entities with the same set of components into archetypes, this system enables cache-friendly access patterns, significantly improving performance for large numbers of entities with similar component types.

  @ Prefab System: A system designed to manage and instantiate reusable game objects or components, known as prefabs, within the game engine

  @ Game Asset System: A comprehensive system for managing, organizing, and optimizing game assets such as textures, models, sounds, animations, and scripts.

  @ Stack-based C++14 Coroutine System: A coroutine system implemented in C++14, designed to efficiently manage asynchronous operations using a stack-based approach
  
  * If you want to learn more about my experience, please take a look at [the post](/professionalprojects/Com2usKorea/).



# Projects

## Indie Game Projects
* Here are some demo reels for the project. Check them out!
  * [Trailer 1](https://www.youtube.com/watch?v=zgcS1foEgOA)
  * [Trailer 2](https://www.youtube.com/watch?v=b9b-6MzOAi0)

* A top-view strategy game set in Korean war.
* Unity, C#, and several 3D modeling tools.
* Designed, programmed, and produced art assets.
* [This category](/personalprojects/) embraces introductions of the project itself and techniques applied.

# Skills
## Programming Languages    
![C++Logo](../Images/home/C++Logo.png "C++"){: width="60"}  
* C++ is my primary programming language. I am a professional game programmer and use it every day.
* I am knowledgeable of modern C++; STL, move semantics, template, and many other recent features. I can apply advanced features to design and construct games and other applications with high performance.
* C++ is compiled into native code and supports an object-oriented programming paradigm, which makes it the most suitable language for developing real-time applications. I have a deep understanding of the philosophy of C++.

<br />
![CSharpLogo](../Images/home/CSharpLogo.png "C#"){: width="60"}  

* I use C# frequently for a personal game project along with Unity. I have been using C# for a long time; thus I have a deep understanding of its features.
* C# features well-designed and concise functionality and keywords. I know how to utilize them to boost the software development process fully.  
* As to a few weaknesses of C#, like performance issues due to garbage collection, I am experienced with optimizing those codes.

## Game Engine
![UnityLogo](../Images/home/UnityLogo.png "Unity"){: width="160"}
* I have been developing my own game with Unity for over three years. 
* Since the project is aimed at commercial success, I have encountered numerous challenges while developing each disparate part. With deep considerations about how to formulate Unity components, I was able to make a breakthrough.
* Not only do I use functionality offered by Unity, but in order to enrich my game project, I have also been highly customizing terrain, animation system, shader, and the multiplayer API(Mirror).

## Graphics API
![VulkanLogo](../Images/home/VulkanLogo.png "Vulkan"){: width="150"}
* Vulkan is my way of presenting graphical ideas along with GPU programming.
* I am capable of managing various Vulkan resources to establish complicated rendering pipelines, eventually building up complicated applications upon them.
* Compute shader along with Vulkan is my favorite way of boosting parallel computation. Take a look at my [fluid simulation with Vulkan compute shader](https://youtu.be/SPOenCZRLrk)!
* I am engaging Vulkan to develop a high-performance in-house fluid simulation tool powered by Vulkan, GLSL, and ImGUI.



# Education

## Chung-Ang University

* Bachelor of Arts in Psychology (2022)
* Double-Major in Statistical Artificial Intelligence (2022)

Please refer to [this post](/professionalprojects/CollegeProjects) for more details about my college projects.

# Certificates

## *Linux Master**
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing
## *Net**
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing
## *Com2us**
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing
## *Com2us**
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing
## *Com2us**
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing
## *Com2us**
* Seoul, Republic of Korea
* *Gane Engine Programmer* at Com2us proprietary Game Engine Team
  * January 2023 - ing


## Theoretical Knowledge
* **Computer Graphics** - I have implemented and optimized real-time rendering systems for games. Also, I have a strong interest in researching various graphics techniques and realizing them with graphics API, shaders, and a good knowledge of 3D mathematics.
