# Part 1: Research and Tool Identification

## 1. Cursor

**Company:** Anysphere

**Main Features:**

* AI-first code editor built on VS Code
* Full-project context awareness
* Inline code generation, refactoring, and debugging
* Chat with your codebase

**Pricing:**

* Free tier (limited)
* Pro subscription (monthly)

**Supported Languages:**

* JavaScript / TypeScript
* Python
* Java
* C/C++
* Go
* And most VS Code supported languages

---

## 2. Windsurf (Codeium)

**Company:** Codeium

**Main Features:**

* Agentic IDE (AI plans and executes changes)
* Deep repository understanding
* Multi-file edits
* Strong autocomplete + chat

**Pricing:**

* Free plan
* Paid plans for advanced usage

**Supported Languages:**

* JavaScript / TypeScript
* Python
* Java
* C#
* Go
* Rust

---

## 3. Replit Agent

**Company:** Replit

**Main Features:**

* AI agent that builds apps from natural language
* Runs code instantly in the browser
* Automatic deployment
* Beginner-friendly

**Pricing:**

* Free tier
* Paid plans with higher limits

**Supported Languages:**

* JavaScript
* Python
* HTML / CSS
* Java
* C++

---

## 4. v0.dev

**Company:** Vercel

**Main Features:**

* AI-powered UI generation
* Focus on React + Tailwind
* Generates production-ready components
* Excellent for frontend design

**Pricing:**

* Free tier
* Paid plans

**Supported Languages / Frameworks:**

* React
* Next.js
* TypeScript
* Tailwind CSS

---

## 5. Bolt.new

**Company:** StackBlitz

**Main Features:**

* Full-stack AI development in the browser
* Generates frontend + backend
* Instant previews
* No local setup required

**Pricing:**

* Free tier
* Paid plans

**Supported Languages:**

* JavaScript / TypeScript
* React
* Node.js
* HTML / CSS

---

## 6. GitHub Copilot Workspace 

**Company:** GitHub

**Main Features:**

* Task-based AI development
* Plans, codes, and tests features
* Integrated with GitHub repositories

**Pricing:**

* Requires GitHub Copilot subscription

**Supported Languages:**

* Most major programming languages supported by GitHub Copilot

---

## 7. Lovable 

**Company:** Lovable AI

**Main Features:**

* Builds full applications from prompts
* Strong focus on UX and product thinking
* Fast prototyping

**Pricing:**

* Free tier
* Paid plans

**Supported Technologies:**

* Web-based applications
* JavaScript frameworks

---
Part 2: Comparative Analysis of Vibe Coding Tools

In recent years, software development workflows have changed significantly with the rise of artificial intelligence. Developers no longer rely only on traditional code editors and basic autocomplete features. Instead, new tools known as vibe coding tools aim to create a more conversational, context-aware, and agent-based development experience. In this section, vibe coding tools are compared with traditional code completion, GitHub Copilot, and using large language models such as ChatGPT or Claude in a separate window.

Vibe Coding Tools vs Traditional Code Completion

Traditional code completion tools are usually limited to suggesting variable names, method signatures, or simple syntax completions based on the current line of code. While they are fast and lightweight, they lack deep understanding of the overall project. They do not understand developer intent, application architecture, or long-term goals. Vibe coding tools, on the other hand, operate with full-project context. Tools like Cursor or Windsurf can analyze multiple files, understand dependencies, and apply changes across the entire codebase. Instead of only completing code, they can refactor files, fix bugs. This makes vibe coding much more suitable for medium to large projects where understanding context is critical. However, traditional code completion still has advantages. It is predictable, lightweight, and does not introduce unexpected changes. For beginners or for very small tasks, traditional autocomplete may feel safer and less overwhelming compared to agentic AI behavior.

Vibe Coding Tools vs GitHub Copilot

GitHub Copilot represents an important step forward compared to traditional code completion. It uses large language models to generate entire functions, classes, and logic blocks. Copilot is very effective for speeding up routine coding tasks and reducing boilerplate code. Despite these strengths, Copilot usually works at the file or function level and reacts mainly to the current cursor position. It does not fully plan tasks or autonomously manage multi-step development processes. Developers still need to guide Copilot closely and manually integrate its suggestions. Vibe coding tools go beyond this reactive approach. They are often agent-based, meaning they can plan a solution, explain the steps, and then apply changes across multiple files. For example, a vibe coding tool can create a full feature by updating frontend components, backend logic, and configuration files in a coordinated way. This makes vibe coding tools more suitable for complex tasks, rapid prototyping, and full-stack development. On the downside, vibe coding tools may feel slower or less controllable than Copilot for simple tasks. Some developers may also prefer Copilot’s minimal interference and direct integration into existing IDE workflows.


Vibe Coding Tools vs ChatGPT or Claude in a Separate Window

Using ChatGPT or Claude in a separate window is a very common workflow among developers. These tools are excellent for explanations, debugging help, learning new concepts, and generating example code. They are flexible and powerful, especially when developers know how to ask good questions. However, this workflow requires constant context switching. Developers must manually copy code into the chat, explain the project structure, and then paste the generated solution back into the editor. This process is time-consuming and prone to mistakes, especially in larger projects. Vibe coding tools solve this problem by integrating the AI directly into the development environment. The AI has access to the repository context and can directly modify files. This leads to a smoother workflow, fewer interruptions, and faster iteration. Instead of asking for code snippets, developers collaborate with the AI as if it were a team member working inside the project. That said, ChatGPT and Claude still remain superior for high-level reasoning, conceptual discussions, and learning-focused interactions. Many developers benefit from combining both approaches: using vibe coding tools for implementation and ChatGPT or Claude for deeper explanations and planning.

Conclusion

In conclusion, vibe coding tools represent a significant evolution in AI-assisted software development. Compared to traditional code completion, they offer deeper understanding and broader capabilities. Compared to GitHub Copilot, they provide more autonomous and context-aware workflows. Compared to standalone AI chat tools, they reduce friction by integrating intelligence directly into the coding environment. Each approach has its own strengths, and the best choice depends on the task, project size, and developer experience. Nevertheless, vibe coding tools show strong potential to become a standard part of future development workflows, especially for rapid prototyping and full-stack projects.

Experience: Using Replit Agent to Build a Todo List App

For this assignment, I used Replit Agent to build a simple Todo List web application. First, I described the application idea in natural language, explaining that I wanted a Todo List app where users can add tasks, mark them as completed, and delete them. Replit Agent automatically created a development plan and listed the features before starting the build.

After confirming the plan, I used the “Build the entire app” option. The agent generated all necessary files, including HTML, CSS, and JavaScript, without requiring manual setup. The application runs directly in the browser, and tasks are saved using localStorage, so they persist after refreshing the page.

The experience was very beginner-friendly. I did not need to manually write boilerplate code, and the agent handled both the logic and the user interface. This showed how vibe coding tools can speed up development and reduce friction, especially for simple applications and rapid prototyping. Overall, Replit Agent felt like collaborating with an AI teammate rather than just using autocomplete, which clearly demonstrates the idea of vibe coding.
