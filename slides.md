---
theme: default
background: /background.png
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# page transition
transition: slide-left
---

# Coding Conventions and Beyond

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Let's start <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <a href="https://github.com/Smotherer007/coding-conventions" target="_blank" alt="GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
---

# Why Coding Conventions

Coding conventions provide a set of consistent guidelines for how code should be written within a team. By following these conventions, developers can ensure that their code is of high quality and consistency, making it easier for other team members to understand, collaborate on, and maintain. This can help reduce the risk of errors, improve overall code quality, and make it easier to onboard new team members. Additionally, coding conventions can help enforce best practices for security, performance, and maintainability, ensuring that code is scalable and maintainable over the long term.

- **YAGNI** - You Ain't Gonna Need It
- **KISS** - Keep It Simple, Stupid
- **DRY** - Don't Repeat Yourself
- **SRP** - Single Responsibility Principle
- **Clean Code**
- **Developer Principals**

---
transition: fade-out
layout: two-cols
---

# YAGNI

YAGNI stands for 'You Ain't Gonna Need It'. This coding convention encourages developers to avoid coding features or solutions that aren't necessary for the current problem. YAGNI helps developers focus on the most important features and avoid bloat.
YAGNI helps developers keep their codebase clean and maintainable. It encourages developers to think through their solutions before coding, and to consider the overall impact of the code they write. This helps developers create more efficient code that is easier to maintain.

:: right ::

<img src="/YAGNI.png" style="max-height: 80%; float:right" />

---
transition: fade-out
layout: two-cols
image: /KISS.png
---

# KISS

KISS stands for 'Keep It Simple, Stupid'. This coding convention encourages developers to use the simplest solution to solve a problem. KISS helps developers avoid overcomplicating their code, which can lead to code that is difficult to maintain.
KISS helps developers create code that is easy to read and understand. It encourages developers to think about the overall impact of their code and to avoid using overly complex solutions. This helps developers create code that is efficient and maintainable.

:: right ::

<img src="/KISS.png" style="max-height: 90%; float:right" />

---
transition: fade-out
layout: two-cols
---

# DRY

DRY stands for 'Don't Repeat Yourself'. This coding convention encourages developers to avoid repeating code and to use functions, methods, and classes to reduce duplication. DRY helps developers create code that is easier to maintain and debug.
DRY helps developers create code that is efficient and maintainable. It encourages developers to think about the overall impact of their code and to avoid using overly complex solutions. This helps developers create code that is easier to read and understand.

:: right ::

<img src="/DRY.png" style="max-height: 80%; float:right" />

---
transition: fade-out
layout: two-cols
---

# SRP

SRP stands for 'Single Responsibility Principle'. This coding convention encourages developers to keep their code organized and to separate different tasks into different functions or classes. SRP helps developers create code that is easier to maintain and debug.
SRP helps developers create code that is efficient and maintainable. It encourages developers to think about the overall impact of their code and to avoid using overly complex solutions. This helps developers create code that is easier to read and understand.

:: right ::

<img src="/SRP.png" style="float:right" />

---
transition: fade-out
layout: two-cols
---

# Clean Code

Clean code is a coding convention that encourages developers to write code that is easy to read and understand. Clean code helps developers create code that is efficient and maintainable. It encourages developers to think about the overall impact of their code and to avoid using overly complex solutions.
Clean code helps developers create code that is easier to read and understand. It encourages developers to use the simplest solution to solve a problem and to avoid bloat. Clean code also encourages developers to use functions, methods, and classes to reduce duplication. This helps developers create code that is easier to maintain and debug.


[Learn More](https://clean-code-developer.de/die-grade/)

:: right ::

<img src="/CleanCode.png" style="max-height: 90%; float:right" />

---
transition: fade-out
layout: iframe-right

# the web page source
url: http://localhost:8080

# a custom class name to the content
class: my-cool-content-on-the-left
---

# Developer Principals

The Developer Principles are intuitive guidelines. They are the deduction from the experiences made in our projects and should be a source of arguments and basis for discussions.

Their adaption in everyday life increases the quality of our projects. Practices and examples make them comprehensible and useful for all developers.

---
transition: fade-out
layout: two-cols
---

# Design Types

Software developers often argue due to different perspectives on software design, which is influenced by differences in people's backgrounds, experiences, and values. While valuable discussions can arise from these differences, endless arguments about equally good solutions can harm productivity and team morale.


[Let's find out!](https://design-types.net/test_yourself.html)

:: right ::

<img src="/Design_Types_logo.png" style="max-height: 90%; float:right" />