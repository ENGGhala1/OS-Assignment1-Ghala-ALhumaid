# 📝 MY_WORK: Student Information, Development Log, Reflection & Answers

> This is the **only file** your instructor reads to grade Parts 3 and 4 (documentation and video). Everything you write here must be **in your own words**.

---

## 🛑 STOP: Read This Before You Do Anything Else

> ### 1️⃣ Read the whole `README.md` first
> The `README.md` in this repository contains the full instructions: class descriptions, feature specifications, question prompts and the video script. **If you skip it, you will lose marks.**
>
> ### 2️⃣ Understand the full code before answering any question
> Open `SchedulerSimulation.java` and read it **from top to bottom**. You must be able to explain what `Process`, `run()`, `runToCompletion()`, `addProcessToQueue()`, `Thread.start()`, `Thread.join()` and `Thread.sleep()` do **before** you write a single answer in Parts B and C. Run the program at least once and watch the output.
>
> ### 3️⃣ Commit many times, not once
> A single commit, or all commits made in the last hour, costs you **-0.5 mark**. See the [Commit Rules](#-commit-rules-mandatory) below.

**How to use this file:**
1. Fill in your **Student Information** (below) right now.
2. Follow the steps in the **Work Roadmap** in order.
3. Update the **Development Log** *every time* you work on the assignment, not at the end.
4. Do not delete any section header. Replace the `[...]` placeholders with your own text.

---

## 👤 Student Information

> ⚠️ **WARNING:** Fill this in first. Your name and ID must match the student ID you set in `SchedulerSimulation.java` (line 150) and the one you say in your video.

| Field | Your Answer |
|-------|-------------|
| **Full Name** | [Write your full name here] |
| **Student ID** | [Write your student ID here] |
| **University Email** | [yourid]@std.psau.edu.sa |
| **GitHub Username** | [your-github-username] |
| **Repository Link** | [Paste your repository link here] |
 
---

## 🎥 Video Link

**Video Link**: [Paste your video link here]

> ⚠️ **WARNING:** The video must be **publicly accessible** ("Anyone with the link can view") on **Google Drive**, **YouTube (Unlisted or Public)** or any other cloud file-sharing system. A private, restricted or broken link counts as a **missing video (-1 mark)**.
>
> 💡 **TIP:** Open the link in a **private/incognito window** before you submit. If it asks you to log in or request access, it is not public.
>
> 📌 **NOTE:** The link goes in **this file only** (`MY_WORK.md`), **not** in `README.md`. Name your video file `StudentID_Assignment1_Demo.mp4`. It must last **2 to 3 minutes**.

---

## 🗺️ Work Roadmap (follow in this order)

| Step | What to do | Where | Marks |
|:----:|------------|-------|:-----:|
| 0 | Read `README.md`, then read and run the full code | Your IDE | – |
| 1 | Fork, rename, keep the repo **PUBLIC**, set your student ID (line 150), **commit** | GitHub + code | Part 1 (1) |
| 2 | Feature 1: Process Priority, **commit** | Code | Part 2 (0.25) |
| 3 | Feature 2: Context Switch Counter, **commit** | Code | Part 2 (0.25) |
| 4 | Feature 3: Waiting Time Tracking, **commit** | Code | Part 2 (0.5) |
| 5 | Development Log (5+ entries, different dates) | This file, Part A | Part 3 (0.5) |
| 6 | Reflection (4 questions) | This file, Part B | Part 3 (0.5) |
| 7 | Technical Answers (4 questions) | This file, Part C | Part 3 (0.5) |
| 8 | Record the video, upload it, paste the link above | Video + this file | Part 4 (1.5) |
| 9 | Final check, then submit the repo link on Blackboard | Blackboard | – |

> 💡 **TIP:** Tick each step off as you go. Do not leave the log, the reflection or the video for the last day.

---

## 🔁 Commit Rules (MANDATORY)

> ### ⚠️ MANY COMMITS ARE REQUIRED. A single bulk commit is penalized (-0.5 mark).

**Minimum: 3 meaningful commits. Aim for 6 or more.**

| # | Commit | Example message |
|:-:|--------|-----------------|
| 1 | Student ID set | `Set my student ID: 441234567` |
| 2 | Feature 1: Priority | `Feature 1: Added priority field to Process class` |
| 3 | Feature 2: Context switches | `Feature 2: Implemented context switch counter` |
| 4 | Feature 3: Waiting time | `Feature 3: Added waiting time tracking and summary table` |
| 5 | Development log entries | `Docs: Added development log entries 1-3` |
| 6 | Reflection and answers | `Docs: Completed reflection and technical answers` |
| 7 | Video link | `Docs: Added demo video link` |

**Rules:**
- ✅ **One commit per feature.** Do not put all three features in one commit.
- ✅ **Commit after each work session**, and after each part of this file.
- ✅ **Spread your commits over different dates.** Not all in one day.
- ❌ **Do not make all commits in the last hour** before the deadline.
- ❌ **No vague messages** like `done`, `update` or `final version`.

> 💡 **TIP:** Your commit history is checked and you **show it in your video** (at least 3 commits visible). Your development log dates should match your commit dates.
>
> 💡 **TIP:** **Use VS Code** (see *Recommended Development Environment* in `README.md` for the full setup). Sign in to GitHub in VS Code, then commit from the Source Control panel (Ctrl+Shift+G) → stage → write a message → Commit → Sync/Push. You can edit and commit this file the same way. **Pushing** matters: commits that are not pushed to GitHub are invisible to the instructor.

---

# Part A: Development Log (0.5 mark)

> ⚠️ **WARNING:** Minimum **5 entries**, spread over **different dates**. Five entries written on the same day, or written all at once at the end, will lose marks and look like a copy. Entry dates should be **between the start of the assignment and the deadline (October 10, 2026)**.
>
> 💡 **TIP:** Write an entry at the **end of each work session**, while you still remember what happened. It takes 5 minutes.
>
> 💡 **TIP:** Be specific. "Worked on the code" is a weak entry. "Added a `static int contextSwitches` counter and incremented it before `currentThread.start()`" is a strong one.
>
> 📌 **NOTE:** Each entry needs: date and time, what you did, details, challenges, solution, and time spent. Real challenges are fine (and expected). Do not invent fake ones.

## Example Entry (do not copy it, write your own)

### Entry 1 - October 10, 2026, 2:30 PM

**What I did:**  
Set up my project and prepared it for running.

**Details:**
- Opened the starter repository on GitHub.
- Created my own copy of the repository.
- Updated the student ID in the Java code.
- Ran the program to make sure it worked correctly.
- Saved my changes and uploaded them to GitHub.

**Challenges:**  
I had trouble compiling the code because Java was not configured properly on my computer.

**Solution:**  
I installed the JDK and updated the PATH variable so I could compile and run the program.

**Time spent:** 30 minutes
---

## Your Development Log

### Entry 1 - October 10, 2026

**What I did:**  
I worked on my CPU Scheduler Simulation assignment and ran the Java program.

**Details:**  
I tested the Round-Robin scheduling algorithm and observed how processes take turns using the CPU. I also reviewed the ready queue and learned more about threads and the thread lifecycle.

**Challenges:**  
I had some difficulty understanding how threads work and how processes return to the ready queue when they do not finish within the time quantum.

**Solution:**  
I ran the program, checked the output, and reviewed the code step by step to understand how the scheduler works.

**Time spent:** 1 hour

---

### Entry 2 - October 10, 2026

**What I did:**  
I studied the multithreading concepts used in my CPU Scheduler Simulation assignment.

**Details:**  
I learned the difference between threads and processes, how the ready queue works, and how the Round-Robin algorithm distributes CPU time among processes.

**Challenges:**  
I found it difficult to understand the thread lifecycle and the difference between `Thread.sleep()` and `Thread.join()`.

**Solution:**  
I reviewed the code and followed the execution step by step to understand when a thread starts, waits, and finishes.

**Time spent:** 1 hour

---
### Entry 3 - October 10, 2026

**What I did:**  
I completed the assignment questions and reviewed what I learned from the CPU Scheduler Simulation.

**Details:**  
I wrote about multithreading, the difference between threads and processes, the ready queue, and real-world applications of Round-Robin scheduling.

**Challenges:**  
The main challenge was explaining the concepts in my own words and connecting them to my program.

**Solution:**  
I reviewed my program output and the code to understand the concepts better and write clear answers.

**Time spent:** 45 minutes

--- 
### Entry 4 - October 10, 2026

**What I did:**  
I reviewed my final answers and checked my CPU Scheduler Simulation assignment.

**Details:**  
I revised my answers about multithreading, thread lifecycle, and Round-Robin scheduling. I also checked that my explanations matched the concepts used in my Java program.

**Challenges:**  
I found it a little difficult to explain some technical concepts clearly and make sure my answers were accurate.

**Solution:**  
I went through the questions again, reviewed the code, and corrected my answers where needed.

**Time spent:** 1 hour 

---
### Entry 5 - October 10, 2026

**What I did:**  
I did a final review of my CPU Scheduler Simulation project and development log.

**Details:**  
I checked my understanding of how threads execute, how processes move through the ready queue, and how the Round-Robin algorithm works.

**Challenges:**  
I needed to make sure I understood the main concepts well enough to explain them during the assignment discussion.

**Solution:**  
I reviewed my notes and program output and practiced explaining the concepts in simple words.

**Time spent:** 1 hour 

---
### Entry 6 - October 10, 2026

**What I did:**  
I practiced explaining my project to prepare for the assignment discussion.

**Details:**  
I reviewed the main Java methods, including `Thread.start()`, `Thread.sleep()`, and `Thread.join()`, and how they relate to the thread lifecycle.

**Challenges:**  
I found it difficult to remember the purpose of each method and explain the differences between them.

**Solution:**  
I reviewed each method in the code and practiced explaining its purpose using simple examples from my project.

**Time spent:** 2 hour

---

---
## Development Log Summary

**Total time spent on assignment:** 2 Days

**Most challenging part:**  
The most challenging part was understanding how threads work and how the Round-Robin algorithm moves processes in and out of the ready queue.

**Most interesting learning:**  
The most interesting thing I learned was how multithreading works and how the CPU gives each process a chance to execute.

**What I would do differently next time:**  
Next time, I would study the code earlier, test each change separately, and write down the important concepts while working on the project.
---

# Part B: Reflection (0.5 mark)

> 🛑 **STOP:** Do **not** start this part until you have read the `README.md`, read the **entire** `SchedulerSimulation.java`, run it, and finished the three features.
>
> ⚠️ **WARNING:** Each answer must be **5 to 7 sentences**, in **your own words**. Copied or AI-generated answers without understanding get **0 marks for the whole assignment**. You may be asked to explain them in person.
>
> 💡 **TIP:** Mention concrete things you actually did: a method you wrote, an error you hit, a line of output you saw. Generic answers score low.
>
> 💡 **TIP:** Draft your answer in a few bullet points first, then turn them into sentences.

## Question 1: What did you learn about multithreading?

> 💡 **TIP:** Talk about thread creation (`Runnable`, `Thread.start()`), waiting with `Thread.join()`, simulating work with `Thread.sleep()`, and what surprised you.

**Your Answer:** I learned how multithreading allows multiple threads to run in a program. I learned how to use `Runnable` to define the task and `Thread.start()` to start a thread. I also learned that `Thread.join()` makes a thread wait until another thread finishes. I used `Thread.sleep()` to pause a thread for a short time and simulate the work of a process. One thing that surprised me was that threads can run at different times, so their output may not always appear in the same order. This helped me understand how threads work together and how they can be useful in real-world applications.

[Write your answer here.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** The most challenging part of this assignment was understanding how the threads work together in the CPU Scheduler Simulation. At first, I found it difficult to understand how each process gets its turn to use the CPU. I also needed to understand how the ready queue changes when a process finishes or needs more time. I solved this by running the program and observing the output step by step. This helped me understand how the Round Robin algorithm works. After practicing, I became more comfortable with the code and how the processes are scheduled.

[Write your answer here.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** I overcame the challenges by taking my time and working on the code step by step. I read the code carefully to understand what each part does. I ran the program several times and checked the output to see if everything was working correctly. When I did not understand something, I searched for an explanation and asked for help. I also tested the program after making changes to make sure they did not cause new problems. This approach helped me understand the code better and become more confident in solving programming problems.

[Write your answer here.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** Multithreading is useful in many applications that we use every day. For example, a web browser can load a page while downloading files at the same time. In a music player, one thread can play music while another handles the buttons. In games, multithreading helps manage graphics, sounds, and player actions. This is similar to my CPU Scheduler project, where processes take turns using the CPU. I learned that multithreading helps applications perform different tasks more efficiently. It also makes applications more responsive and improves the user experience.

[Write your answer here.]

### Optional: What would you like to learn more about?

[Any topics related to threading or operating systems that you're curious about?]

### Optional: How confident do you feel about multithreading concepts now?

[Beginner / Intermediate / Confident. What do you understand well? What needs more practice?]

### Optional: Feedback on the assignment

[Any comments? Was it helpful? Too easy or hard? Suggestions?]

---

# Part C: Technical Answers (0.5 mark)

> 🛑 **STOP:** You cannot answer these questions without understanding the code. Re-read `SchedulerSimulation.java` and **run it** first. Your answers must reference **your own code and your own output** (your student ID makes your output unique).
>
> ⚠️ **WARNING:** Each answer must be **3 to 5 sentences**, with specific examples from your code or output. Use correct terms: thread, process, time quantum, ready queue, context switch, burst time.
>
> 💡 **TIP:** Keep your program output in a text file or screenshot so you can copy real snippets for Question 2.

## Question 1: Thread vs Process

**Question**: Explain the difference between a **thread** and a **process**. Why did we use threads in this assignment instead of creating separate processes? Mention at least **TWO** specific differences (e.g., memory sharing, creation overhead, communication speed), and reference relevant parts of `SchedulerSimulation.java`.

> 💡 **TIP:** Note that the class named `Process` in our code is a *simulated* process, and it is run by a real Java *thread*. Explain that distinction and point to the `new Thread(process)` line in `addProcessToQueue()`.

**Your Answer:** A process has its own memory, while threads share memory within the same program. Threads are also faster to create and use fewer resources than separate processes. In our assignment, the `Process` class represents a simulated process, while a real Java thread executes it. In `addProcessToQueue()`, the line `new Thread(process)` creates a thread to run the process. We used threads to simulate how processes take turns using the CPU.

[Write your answer here.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** In Round-Robin scheduling, if a process does not finish within its time quantum, it is added back to the ready queue to wait for another turn. For example, in my program, P1 had a burst time of 12411ms and a time quantum of 5000ms, so it needed more than one turn to finish. I need to check my console output to count exactly how many times P1 was added back to the ready queue before it finished. Re-queueing is important because it gives every process a fair chance to use the CPU.

[Write your answer here.]

Example from my output:
```
[Paste a relevant snippet from your program output here showing a process being re-queued]
```

**Explanation of example:**
[Explain what is happening in the output snippet you pasted.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** P1 is in the **New** state when `new Thread(process)` creates its thread in `addProcessToQueue()`. It enters the **Runnable** state when `Thread.start()` is called, and it becomes **Running** when the CPU scheduler executes it. P1 enters the **Waiting** state when `Thread.sleep()` pauses it during execution, while the main thread waits when it calls `Thread.join()`. Finally, P1 enters the **Terminated** state when its `run()` method finishes executing. These states show how P1 moves through its lifecycle during the simulation.
1. **New**: [When is P1 in the New state?]

2. **Runnable**: [When does P1 become Runnable?]

3. **Running**: [When is P1 Running?]

4. **Waiting**: [When and why would a thread be Waiting?]

5. **Terminated**: [When is P1 Terminated?]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** **Example 1: Operating System**  
An operating system can use Round-Robin scheduling to share CPU time among multiple processes or threads. Each process gets a time quantum, and if it does not finish, the scheduler switches to another process. This is similar to my simulation, where each process gets a turn to use the CPU. It improves fairness because one process cannot use the CPU for too long without giving others a chance.

**Example 2: Web Server**  
A web server can use multiple threads to handle requests from different users. Each thread can receive CPU time for a short period before another thread gets a turn. The time quantum helps distribute CPU time, while context switching allows the CPU to work on another thread. This approach can improve responsiveness and prevent one request from taking all the CPU time.

**Why Round-Robin works well here**:
[Fairness, responsiveness, predictability?]

## Summary

**Key concepts I understood through these questions:**
1. I learned the difference between threads and processes and how they work in Java.
2. I understood how Round-Robin scheduling works and how the ready queue gives each process a fair chance to use the CPU.
3. I learned the thread lifecycle and how methods like `Thread.start()`, `Thread.sleep()`, and `Thread.join()` work.

**Concepts I need to study more:**
1. I need to understand thread synchronization and how to avoid problems when multiple threads share data.
2. I need to learn more about context switching and how operating systems manage CPU time.
---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [ ] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [ ] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [ ] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [ ] Student ID is set in `SchedulerSimulation.java` (line 150)
- [ ] Code compiles and runs with no errors
- [ ] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [ ] Each feature has clear comments

**Commits**
- [ ] **At least 3 meaningful commits, ideally 6 or more**
- [ ] **One commit per feature**
- [ ] Commits are spread over **different dates** (not all in the last hour)
- [ ] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [ ] Full name and student ID filled in at the top
- [ ] Development log has **5+ entries** on different dates
- [ ] Reflection: 4 questions, 5-7 sentences each
- [ ] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [ ] No `[...]` placeholders left
- [ ] No section headers deleted

**Video**
- [ ] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [ ] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [ ] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [ ] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
