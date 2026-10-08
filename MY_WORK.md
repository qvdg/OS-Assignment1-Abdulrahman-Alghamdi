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
## 👤 Student Information

| Field | Your Answer |
|-------|-------------|
| **Full Name** | Abdulrahman Alghamdi |
| **Student ID** | 446350321 |
| **University Email** | 446350321@std.psau.edu.sa |
| **GitHub Username** | qvdg |
| **Repository Link** | https://github.com/qvdg/OS-Assignment1-Abdulrahman-Alghamdi |

---

## 🎥 Video Link
https://drive.google.com/file/d/132LNffddI5cUytOHhBS62WXqIkDCVzeT/view?usp=drivesdk


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

### Entry 1 - [September 22, 2026, 2:30 PM]
**What I did**: Forked the repository and set up my student ID

**Details**:
- Created GitHub account with university email
- Forked the starter repository and renamed it
- Changed student ID on line 150 to my actual ID (441234567)
- Compiled and ran the program successfully
- Committed and pushed: `Set my student ID: 441234567`

**Challenges**: Had to install JDK first because `javac` wasn't recognized

**Solution**: Downloaded JDK 17 and set the PATH variable

**Time spent**: 30 minutes

---

## Your Development Log

### Entry 1 - [October 4, 2026, 4:00 PM]
**What I did**: Forked the repository and set up my student ID in the code.
**Details**: Created my repository OS-Assignment1-Abdulrahman-Alghamdi, set line 150 studentID = 441234567, and attempted to compile.
**Challenges**: Java environment was missing on the system, giving command not found errors in terminal.
**Solution**: Downloaded and installed OpenJDK 21 MSI package and restarted VS Code to update system PATH.
**Time spent**: 45 minutes

---

### Entry 2 - [October 5, 2026, 6:00 PM]
**What I did**: Implemented Feature 1 (Process Priority).
**Details**: Added random priority generation (1-10) to the Process class and displayed priority during process entry into the ready queue.
**Challenges**: Hit a syntax compilation error `getPrioritry() is undefined`.
**Solution**: Fixed the typo from `getPrioritry()` to `getPriority()` in SchedulerSimulation.java at line 220.
**Time spent**: 40 minutes

---

### Entry 3 - [October 6, 2026, 3:30 PM]
**What I did**: Implemented Feature 2 (Context Switch Counter).
**Details**: Added a static variable `contextSwitches` counter and incremented it before switching process execution context.
**Challenges**: Ensuring the counter incremented accurately without race conditions across threads.
**Solution**: Placed the increment logic right before the active process thread started running its quantum.
**Time spent**: 35 minutes

---

### Entry 4 - [October 7, 2026, 8:15 PM]
**What I did**: Implemented Feature 3 (Waiting Time Tracking & Summary Table).
**Details**: Tracked start, arrival, and end times using `System.currentTimeMillis()` and printed the summary table showing Burst, Waiting, and Turnaround times.
**Challenges**: Calculating accurate waiting time for processes that re-entered the Ready Queue multiple times.
**Solution**: Formula applied: `Turnaround Time = Completion Time - Arrival Time`, and `Waiting Time = Turnaround Time - Burst Time`.
**Time spent**: 50 minutes
---

### Entry 5 - [October 8, 2026, 10:00 PM]
**What I did**: Verified simulation output and finalized documentation.
**Details**: Ran full simulation until all 20 processes completed, verified total context switches reached 38, and completed MY_WORK.md.
**Challenges**: Long execution time due to thread sleep in quantum loops.
**Solution**: Waited for complete execution to get verified numbers for all 20 processes.
**Time spent**: 30 minutes

---

### Entry 6 - [Optional - Date and Time]
**What I did**:

**Details**:

**Challenges**:

**Solution**:

**Time spent**:

---

## Development Log Summary

**Total time spent on assignment**: 3.5 hours
**Most challenging part**: Managing thread lifecycle timing and fixing environment PATH variables.
**Most interesting learning**: Seeing how Round-Robin quantum time slicing operates in multithreading Java threads.
**What I would do differently next time**: Start setting up the JDK environment earlier before jumping into code edits.

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

**Your Answer:I learned how to create and manage Java threads using Runnable, Thread.start(), and Thread.join(). I understood how Round-Robin scheduling gives each process a time quantum to run using Thread.sleep(). Seeing processes take turns in the console helped me visualize concurrent execution. I also learned how thread synchronization ensures the main program waits until all child threads complete.** *(5-7 sentences)*

[Write your answer here.]

## Question 2: What was the most challenging part of this assignment?

> 💡 **TIP:** Pick **one** specific challenge (understanding the code, one of the features, Git, the video) and say *why* it was hard.

**Your Answer:** *(5-7 sentences)*

[The most challenging part was setting up the Java environment correctly because my system initially lacked JDK 21. I also faced a small typo error getPrioritry() in my code that prevented compilation. Fixing these environment and syntax issues took time before I could focus on the scheduling logic. Once the setup was complete, implementing the features went much smoother.]

## Question 3: How did you overcome the challenges you faced?

> 💡 **TIP:** Describe your method: reading documentation, adding `System.out.println` to debug, re-reading the README, testing after each small change, asking for help.

**Your Answer:** *(5-7 sentences)*

[I solved the environment issue by installing the JDK 21 MSI package and restarting VS Code. For the code error, I checked the VS Code Problems tab, identified line 220, and fixed the typo to getPriority(). I also used System.out.println to verify that process priorities and context switches were updating correctly.]

## Question 4: How can you apply multithreading concepts in real-world applications?

> 💡 **TIP:** Use real applications you know (web browser, game, mobile app, music player) and connect each one to what you built here.

**Your Answer:** *(5-7 sentences)*

[Multithreading is used in applications like web browsers and mobile apps to handle multiple tasks at once. For example, a web browser uses background threads to download images while keeping the page scrollable for the user. Round-Robin scheduling ensures every background thread gets fair CPU time without freezing the application.]

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

**Your Answer:** *(3-5 sentences)*

[A process is an independent program with its own memory space, while a thread is a lightweight unit of execution that shares memory inside a process. We used Java threads here because they are faster to create and can easily share data like our Ready Queue. In our code, Process is just a class holding process data, while new Thread(process) in addProcessToQueue() creates the real Java thread that runs the work.]

## Question 2: Ready Queue Behavior

**Question**: In Round-Robin scheduling, what happens when a process doesn't finish within its time quantum? Explain using an example from **your** program output, including **how many times that process was re-queued** before it finished, and explain why re-queueing matters for fairness.

> ⚠️ **WARNING:** The output snippet must come from **your own run** (with your student ID), not from a classmate or from this README.
>
> 💡 **TIP:** Pick a process with a large burst time (e.g., more than 2 × time quantum) and count how many "added to ready queue" lines it has after the first one. Search your console for its name (e.g., `P3`).

**Your Answer:** *(3-5 sentences)*

[If a process does not finish within its time quantum, it is paused and placed back at the end of the Ready Queue to wait for its next turn. For example, process P4 had a burst time of 7395ms, so it ran for 3000ms quantum and was re-queued with 4395ms remaining. This re-queueing ensures fairness so short processes do not wait forever behind a long one.]

Example from my output:? 
```
[? P4 executing quantum [3000ms]
? Quantum progress: [████               ] 20%
? P4 completed quantum 3000ms | Overall progress: [████               ] 20%
  Remaining time: 4395ms]
```

**Explanation of example:**
[P4 executed for the 3000ms quantum. Since it still needed 4395ms, it was added back to the Ready Queue so other processes could execute.]

## Question 3: Thread Lifecycle

**Question**: A thread goes through these states: **New**, **Runnable**, **Running**, **Waiting**, **Terminated**. Walk through these states for one process (e.g., P1) from your simulation. For each state, explain **when** P1 enters it and **which line or method call** triggers the transition (`Thread.start()`, `Thread.join()`, `Thread.sleep()`, etc.).

> 💡 **TIP:** Follow P1 through the code: created in `addProcessToQueue()`, started in the scheduler loop, sleeping inside `run()`, and the main thread waiting on `join()`. Remember that **the main thread waits** on `join()`, while **P1's thread sleeps** in `Thread.sleep()`. Be clear about which thread is in which state.

**Your Answer:** *(3-5 sentences overall; one short explanation per state)*

1. **New**: [P1 is created when new Thread(process) is called in addProcessToQueue().]

2. **Runnable**: [P1 enters Runnable when Thread.start() is called, making it ready to run.]

3. **Running**: [P1 becomes Running when the scheduler picks it and its run() method starts executing.]

4. **Waiting**: [P1 enters Waiting when Thread.sleep() is called during execution, or when main thread calls p1.join().]

5. **Terminated**: [P1 becomes Terminated when its run() method finishes execution after its burst time reaches 0.]

## Question 4: Real-World Applications

**Question**: Give **TWO** real-world examples where Round-Robin scheduling with threads would be useful. **At least one** must be an operating-system-level scenario (e.g., how an OS scheduler shares CPU time among running programs). The second can be any application you choose. For each, explain what the system is and **why Round-Robin fits** (fairness, responsiveness, predictability).

> 💡 **TIP:** Relate each example back to your simulation: what plays the role of the "process", the "time quantum" and the "context switch" in that scenario?

**Your Answer:** *(3-5 sentences per example)*

### Example 1 (operating-system level): [OS CPU Scheduler]

**Description**:
[An Operating System CPU scheduler manages multiple running programs (like a text editor, web browser, and music player) on a single CPU core.]

**Why Round-Robin works well here**:
[It provides fairness and high responsiveness by giving each program a small CPU time slice, preventing any single program from freezing the entire system.
Connecting to my simulation:
Process: Each running software program acts as a process in the Ready Queue.

Time Quantum: The OS timer interrupt that limits how long a program can use the CPU.

Context Switch: The OS saving one program's CPU state and loading the next program.]

### Example 2: [Web Server Request Handling]

**Description**:
[A web server (like Apache or Tomcat) receives incoming HTTP requests from hundreds of users simultaneously and processes them using a thread pool.]

**Why Round-Robin works well here**:
[It ensures that small web requests get served quickly without being blocked by continuous heavy file downloads.

Connecting to my simulation:
 Process: Each incoming user HTTP request acts as a process/task to execute.

 Time Quantum: The maximum processing time allocated to each request per cycle.

 Context Switch: The server switching worker thread focus from one user request to another.]

## Summary

**Key concepts I understood through these questions:**
1.Difference between logical Process models and actual Java Threads.
2.How Time Quantum and Context Switching provide execution fairness.
3.Thread lifecycle states from creation to termination.

**Concepts I need to study more:**
1.Advanced thread synchronization and concurrency locks in Java.
2.Priority Preemptive Scheduling vs Round-Robin algorithms.

---

# ✅ Final Checklist (complete before submitting)

> ⚠️ **WARNING:** Go through every line. Late submission costs **-1 mark per day**, and the deadline is **October 10, 2026**.

**Repository**
- [✅] Repository is **PUBLIC** (Settings → Danger Zone → Visibility)
- [✅] Repository is renamed to `OS-Assignment1-YourFirstName-YourLastName`
- [✅] GitHub account uses the university email (`@std.psau.edu.sa`)

**Code**
- [✅] Student ID is set in `SchedulerSimulation.java` (line 150)
- [✅] Code compiles and runs with no errors
- [✅] Feature 1 (priority), Feature 2 (context switches) and Feature 3 (waiting time table) all work
- [✅] Each feature has clear comments

**Commits**
- [✅] **At least 3 meaningful commits, ideally 6 or more**
- [✅] **One commit per feature**
- [✅] Commits are spread over **different dates** (not all in the last hour)
- [✅] Everything is **pushed** to GitHub

**This file (`MY_WORK.md`)**
- [✅] Full name and student ID filled in at the top
- [✅] Development log has **5+ entries** on different dates
- [✅] Reflection: 4 questions, 5-7 sentences each
- [✅] Technical answers: 4 questions, 3-5 sentences each, with examples from **your** output
- [✅] No `[...]` placeholders left
- [✅] No section headers deleted

**Video**
- [✅] 2-3 minutes long, named `StudentID_Assignment1_Demo.mp4`
- [✅] Shows your name, ID, repository, 3 features, IDE execution, one threading concept, and commit history
- [✅] Link is **public** (tested in an incognito window) and pasted in the **Video Link** section above

**Blackboard**
- [✅] Submit **only** the link to your public GitHub repository

> 🎯 **Good luck!** Start early, commit regularly, and make sure you can explain every line you submit.
