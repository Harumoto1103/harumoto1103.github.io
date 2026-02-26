---
layout: default
lang: en
title: Academic Works
---

# Academic Works & Projects

Below are the primary projects I have completed during my university courses.

> ### Deep Learning
>
> #### Food Recognition & Calorie Calculation
>
> **A Diet Inquiry System via Lightweight Models**
> A project completed for the "Deep Learning" course. It is an end-to-end system designed to track dietary intake and provide health advice, specifically built to operate locally on mobile devices without an internet connection to protect user privacy.
>
> **Key Technologies:**
>
> - **Computer Vision & Validation:** A YOLO neural network detects food within images, estimating volume using the Shoelace formula. A CLIP model then validates these detections (acting as a _Gatekeeper_) to prevent misclassification.
> - **Data Retrieval:** TF-IDF and Word2Vec algorithms are employed to search massive local databases ("RecipeNLG" and "USDA Food Central").
> - **LLM Reasoning:** A lightweight SmolLM2-360M language model (with 4-bit quantization and a LoRA adapter) is used to estimate calories and provide personalized advice in JSON format. The total memory footprint is only about 2.75 GB, making it highly suitable for mobile deployment.
>
> <span class="badge">Python</span> <span class="badge">YOLOv5</span> <span class="badge">CLIP</span> <span class="badge">SmolLM2</span> <span class="badge">NLP</span>
>
> <div style="display: flex; gap: 15px; justify-content: center; margin: 1.5rem 0; flex-wrap: wrap;">
>   
>   <a href="/assets/pdf/23302010090-黄浩源-个人.pdf" target="_blank" class="btn btn-red">
>     <svg height="18" width="18" viewBox="0 0 24 24"><path d="M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm-8.5 7.5c0 .83-.67 1.5-1.5 1.5H9v2H7.5V7H10c.83 0 1.5.67 1.5 1.5v1zm5 2c0 .83-.67 1.5-1.5 1.5h-2.5V7H15c.83 0 1.5.67 1.5 1.5v3zm4-3H19v1h1.5V11H19v2h-1.5V7h3v1.5zM9 9.5h1v-1H9v1zM4 6H2v14c0 1.1.9 2 2 2h14v-2H4V6zm10 5.5h1v-3h-1v3z"></path></svg>
>     Academic Report (PDF)
>   </a>
> </div>

> ### Object-Oriented Programming (OOP)
>
> **"MineMatching" Game in JavaFX**
> "MineMatching" is a tile-matching game built with a "Minecraft" theme. The software architecture clearly demonstrates object-oriented principles (such as encapsulation and polymorphism). An abstract `Piece` class is extended by derived classes (like `Eliminator` or `Wall`), allowing all elements to be managed seamlessly within a single 2D array matrix.
>
> - **Board & Elements:** Includes five types of elements: Normal, Eliminators, Special (e.g., a diamond sword to clear columns), Walls (introduced in Level 6, which cannot be moved), and empty slots (Nulls).
> - **Tools & Levels:** Features six playable levels. Players can use a "Hammer" tool to destroy a single block (earned by matching five blocks simultaneously) and a "Restoration Potion" to undo the last move.
> - **Interface:** Comprises four GUI views (Start, Game, Menu, End), allowing users to play by clicking or dragging the mouse.
>
> You can review the code and documentation (in Chinese) below:
>
> <div style="display: flex; gap: 15px; justify-content: center; margin: 1.5rem 0; flex-wrap: wrap;">
>   <a href="https://github.com/Harumoto1103/MineMatching" target="_blank" class="btn">
>     <svg height="18" width="18" viewBox="0 0 16 16"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
>     Code on GitHub
>   </a>
>   
>   <a href="/assets/pdf/MineMatching 用户手册.pdf" target="_blank" class="btn btn-red">
>     <svg height="18" width="18" viewBox="0 0 24 24"><path d="M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm-8.5 7.5c0 .83-.67 1.5-1.5 1.5H9v2H7.5V7H10c.83 0 1.5.67 1.5 1.5v1zm5 2c0 .83-.67 1.5-1.5 1.5h-2.5V7H15c.83 0 1.5.67 1.5 1.5v3zm4-3H19v1h1.5V11H19v2h-1.5V7h3v1.5zM9 9.5h1v-1H9v1zM4 6H2v14c0 1.1.9 2 2 2h14v-2H4V6zm10 5.5h1v-3h-1v3z"></path></svg>
>     Game Manual (PDF)
>   </a>
> </div>
>
> <div style="text-align: center; margin: 1rem 0;">
> <img src="/assets/img/mine-matching.png" alt="MineMatching Game Board" style="max-width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);" />
> <p style="font-size: 0.9em; color: #666; font-style: italic; margin-top: 10px">Image: The MineMatching game board showcasing various elements and items.</p>
> </div>

> ### Computer Vision
>
> **TriStreamNet: A Model for Detecting AI-Generated Images**
> This project performs binary classification (Real vs. AI-Generated). The _TriStreamNet_ architecture utilizes three distinct streams:
>
> 1. **RGB Spatial Stream:** Employs a ResNet18 network to capture colors and textures.
> 2. **Frequency Stream:** Utilizes Fast Fourier Transform (FFT) to detect periodic artifacts.
> 3. **Noise Stream:** Applies SRM filters to extract anomalies in noise distribution.
>    The final accuracy on the test dataset was 75.90%.
>
> <div style="text-align: center; margin: 1rem 0;">
> <img src="/assets/img/cv-detect.png" alt="TriStreamNet Architecture" style="max-width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);" />
> <p style="font-size: 0.9em; color: #666; font-style: italic; margin-top: 10px">Image: The TriStreamNet architecture featuring three streams and CBAM attention.</p>
> </div>

> ### Principles of Programming Languages
>
> **KanbunSE: An S-Expression Programming Language**
> _KanbunSE_ (Kanbun S-Expression) is a language I created to bridge Classical Chinese literature and modern computation. It elegantly combines the syntax of Classical Chinese with an S-Expression structure.
>
> #### Key Features:
>
> - **Object-Oriented System (OOP):** Fully supports abstract and inherited classes, polymorphism, and the keyword `此` (this) for self-reference in methods.
> - **Numbers & Data Types:** Automatically converts Arabic numerals into Traditional or Formal Chinese numerals (e.g., 三百一十四點一五 for 314.15) via Python integration. Boolean values are represented as 陽 (Yang, True) and 陰 (Yin, False).
> - **Error Handling:** Contextual errors are reported entirely in Classical Chinese. For example, an index out-of-bounds error reads: "索驥圖外、其轍亂矣" (Seeking a steed beyond the map, its tracks are lost).
> - **Internal Architecture:** The interpreter is built in Racket. It features lexical analysis, a recursive descent parser, and an Environment Chain for lexical scoping.
>
> You can review the code and documentation (in English) below:
>
> <div style="display: flex; gap: 15px; justify-content: center; margin: 1.5rem 0; flex-wrap: wrap;">
>   <a href="https://github.com/Harumoto1103/KanbunSE" target="_blank" class="btn">
>     <svg height="18" width="18" viewBox="0 0 16 16"><path d="M8 0C3.58 0 0 3.58 0 8c0 3.54 2.29 6.53 5.47 7.59.4.07.55-.17.55-.38 0-.19-.01-.82-.01-1.49-2.01.37-2.53-.49-2.69-.94-.09-.23-.48-.94-.82-1.13-.28-.15-.68-.52-.01-.53.63-.01 1.08.58 1.23.82.72 1.21 1.87.87 2.33.66.07-.52.28-.87.51-1.07-1.78-.2-3.64-.89-3.64-3.95 0-.87.31-1.59.82-2.15-.08-.2-.36-1.02.08-2.12 0 0 .67-.21 2.2.82.64-.18 1.32-.27 2-.27.68 0 1.36.09 2 .27 1.53-1.04 2.2-.82 2.2-.82.44 1.1.16 1.92.08 2.12.51.56.82 1.27.82 2.15 0 3.07-1.87 3.75-3.65 3.95.29.25.54.73.54 1.48 0 1.07-.01 1.93-.01 2.2 0 .21.15.46.55.38A8.013 8.013 0 0016 8c0-4.42-3.58-8-8-8z"></path></svg>
>     Code on GitHub
>   </a>
>   <a href="/assets/pdf/KanbunSE Guide.pdf" target="_blank" class="btn btn-red">
>     <svg height="18" width="18" viewBox="0 0 24 24"><path d="M20 2H8c-1.1 0-2 .9-2 2v12c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2zm-8.5 7.5c0 .83-.67 1.5-1.5 1.5H9v2H7.5V7H10c.83 0 1.5.67 1.5 1.5v1zm5 2c0 .83-.67 1.5-1.5 1.5h-2.5V7H15c.83 0 1.5.67 1.5 1.5v3zm4-3H19v1h1.5V11H19v2h-1.5V7h3v1.5zM9 9.5h1v-1H9v1zM4 6H2v14c0 1.1.9 2 2 2h14v-2H4V6zm10 5.5h1v-3h-1v3z"></path></svg>
>     Language Guide (PDF)
>   </a>
> </div>
> <div style="text-align: center; margin: 1rem 0;">
> <img src="/assets/img/exec-flow.png" alt="KanbunSE Execution Flow" style="max-width: 100%; border-radius: 8px; box-shadow: 0 4px 6px rgba(0,0,0,0.1);" />
> <p style="font-size: 0.9em; color: #666; font-style: italic; margin-top: 10px">Image: Interpreter structure and execution flow of KanbunSE.</p>
> </div>

> ### Database Design
>
> **Car Repair Management System**
> A database system designed for car repair businesses. It features three user roles: Customers, Mechanics, and Administrators. The system utilizes SQL transactions to maintain data integrity and triggers to handle cascade deletions safely.

> ### Software Engineering
>
> **Restaurant Review Website**
> I built a web application where users can search, locate, and leave reviews for restaurants. The system is fully operational and backed by a robust design.
