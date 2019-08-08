The goal of the wiki is to cover a wide range of topics related to game development.

When building a game engine from scratch, there are several valid approaches and there is no perfect way of doing things.

For a given topic, multiple strategies will be covered with their advantages and pitfalls.

The advantage of building a wiki instead of a blog is that the information can be better organized, and improved over time.

- 📖[References](#-references)
- 🏰[History](#-history)
- 💻[Hardware](#-hardware)
- 🖥[Software](#-software)
  - ⚙️[System](#system)
  - 🌀[C++](#cpp)
  - 🌀[C#](#csharp)
  - 🧱[Build](#build)
- 🖥[Core](#-core)
- 🧮[Mathematics](#-mathematics)
- 🌄[Graphics](#-graphics)
- 🎮[Game Runtime](#-game-runtime)
- 🎨[Game Editor](#-game-editor)
- 🎓[Tutorials](#-tutorials)

# 📖 References

[💬 Glossary](Glossary.html){:target="_blank"}

[ℹ️ Terminology](Terminology.html){:target="_blank"}

# 🏰 History

A retrospective on the different versions of DirectX.

☢️[DirectX](History/DirectX.html){:target="_blank"}


A review of the different implementations of SIMD.

🔢[SIMD](History/SIMD.html){:target="_blank"}


# 💻 Hardware

An overview of the architecture of a computer system and its fundamental components.

💻[Computer](Hardware/Computer.html){:target="_blank"}


A review of the CPU's cache memory, and best practices.

🚅[Cache Memory](Hardware/Cache Memory.html){:target="_blank"}


To debug programs compiled for an Intel x86 architecture, some fundamental knowledge of the processor and its instructions is necessary.

⚙️[Intel x86](Hardware/Intel x86.html){:target="_blank"}

# 🖥 Software

## System

Every programming language provides fundamental data types.

🔢[Numeric Types](Software/Numeric Types.html){:target="_blank"}

🔟[Endianness](Software/Endianness.html){:target="_blank"}


The code translation process that includes the compilation and linking of source code to a binary executable.

🔤[Code Translation](Software/Code Translation.html){:target="_blank"}


The storage of a program's executable on different plaforms.

▶️[Executable](Software/Executable.html){:target="_blank"}


A program uses a portion of heap memory known as the stack.

[📚 Stack](Software/Stack.html){:target="_blank"}

## C++ {#cpp}

C++ does not support Bit Flags as a fundamental type. There are different methods to implement this functionality.

🚩[Bit Flags](Software/Bit Flags.html){:target="_blank"}


There are different methods to handle errors in C++.

⚠️[Error Handling](Software/Error Handling.html){:target="_blank"}


C++ and best practices.

👑[C++ Best Practices](Software/CPP Best Practices.html){:target="_blank"}

## C# {#csharp}

Fundamental information on C# and best practices.

🌀[C#](Software/CS.html){:target="_blank"}

👑[C# Best Practices](Software/CS Best Practices.html){:target="_blank"}


Information on the internals of .NET.

👾[.NET Internals](Software/NET Internals.html){:target="_blank"}


A review of best practices that are mostly platform-independent.

👑[Best Practices](Software/Best Practices.html){:target="_blank"}


An overview of multithreading and platform-dependent functionalities.

🔀[Multithreading](Software/Multithreading.html){:target="_blank"}

## 🧱 Build

A review of build systems and build tools.

🔨[Build Systems](Software/Build Systems.html){:target="_blank"}


CMake is one of the most popular open-source cross-platform build toolset, and it can be used for game development with a minimal set up.

🔨[CMake](Software/CMake.html){:target="_blank"}

# Core

A review of SIMD on different platforms, and best practices on their usage.

🔢[SIMD](Core/SIMD.html){:target="_blank"}


A review if the different kind of memory, and the best practices for writing efficient programs.

🗄[Memory](Core/Memory.html){:target="_blank"}


A review of different allocation strategies and their use in a game engine.

⛓[Allocators](Core/Allocators.html){:target="_blank"}


An overview of the fundamental container types and their usage.

📦[Collections](Core/Collections.html){:target="_blank"}


Different strategies to implement a reflection system in C++.

🔖[Reflection](Core/Reflection.html){:target="_blank"}


Different strategies to serialize and deserialize data in C++.

💾[Serialization](Core/Serialization.html){:target="_blank"}

# 🧮 Mathematics

The principles of trigonometry that are necessary for graphics programming.

📐[Trigonometry](Core/Trigonometry.html){:target="_blank"}

# 🌄 Graphics

Introduction to the Graphics Pipeline and the different stages.

🏭[Graphics Pipeline](Game/Graphics Pipeline.html){:target="_blank"}


Introduction to Shader programming.

🎨[Shaders](Game/Shader.html){:target="_blank"}

# 🎮 Game Runtime

An overview of the recommended project configurations for a game engine.

🛠[Project Configuration](Runtime/Project Configuration.html){:target="_blank"}

Strategies to provide a platform abstraction for the low-level functionality of the engine.

💻[Cross-Platform](Runtime/Cross Platform.html){:target="_blank"}


Overview of platform-independant and platform-spefic features for the low-level functionality of the engine.

🖥[Platforms](Runtime/Platforms.html){:target="_blank"}


Best practice on multithreading.

🔀[Multithreading](Core/Multithreading.html){:target="_blank"}


Review of platform-dependent Timing functionalities.

⏰[Time](Game/Time.html){:target="_blank"}


Best practices on implementing loading and saving in a game engine.

🗂[Storage](Runtime/Storage.html){:target="_blank"}


Review of Object Models for games.

🌍[Object Model](Game/Object Model.html){:target="_blank"}


Gamma correction and linear workspace.

🌈[Gamma](Game/Gamma.html){:target="_blank"}


Overview on Lighting models.

💡[Lighting](Game/Lighting.html){:target="_blank"}


Overview on Textures.

🖼[Texture](Game/Texture.html){:target="_blank"}


Overview on Shader programs.

💡[Shader](Game/Shader.html){:target="_blank"}

# 🎨 Game Editor

A review of popular version control systems, and how they can be integrated into a game pipeline.

🏷[Version Control](Editor/Version Control.html){:target="_blank"}


An overview of an asset pipeline for games.

🖼[Assets](Editor/Assets.html){:target="_blank"}

# 🎓 Tutorials

An introduction to WebGL.

🌐[WebGL](Runtime/WebGL.html){:target="_blank"}


An introduction to programming for macOS.

🍎[macOS](Runtime/macOS.html){:target="_blank"}


An introduction to Metal for macOS and iOS.

🔩[Metal](Runtime/Metal.html){:target="_blank"}


Overview and tutorials on the Windows platforms and the APIs that are required in a game engine.

🖥[Windows](https://www.notion.so/juliendelezenne/Windows-850f22698c5d46079f5b42c2ef1298f1){:target="_blank"}


Tutorials on HLSL.

✨[HLSL](https://www.notion.so/juliendelezenne/HLSL-8cf24e8312464ccd90dd10a21b07d200){:target="_blank"}


Internal information on the Unreal Engine 4.

[Unreal Engine 4](https://www.notion.so/juliendelezenne/Unreal-Engine-4-26e5e04f5bc140698c5db867532a9634){:target="_blank"}
