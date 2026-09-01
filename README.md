# Lab 1 · Setup + Hello World

**Week 01 · Setup & Hello World**  
**Theme:** Get unblocked  
**Type:** Setup week


## Demo video (required)

Paste a link to a short video of you running this assignment (tool + code + run).
Work without a working video link is incomplete.

**Your demo:**[ _add your link here_](https://youtu.be/u7I06CVfOKA)


## Scenario
You cannot learn C++ without a working toolchain. This lab proves your pipeline: create → compile → run → push → record.

## Goals
- Finish environment setup on **one** path you will actually use (VS 2022, GitHub Codespaces, Replit, or library)
- Create, compile, and run a program that prints `Hello World!`
- Record a short demo video showing the tool, the code, and the running output
- Push the `.cpp` to GitHub and submit the link on Canvas

## Starter
Use `main.cpp` in this folder. Put your name in the file-top comment.

## Environment
VS 2022 · **GitHub Codespaces** · Replit · library machines

## Procedure
1. Pick **one** reliable path (prefer finish one install over three half-installs)
2. Follow class setup videos click-by-click until green Run works
3. Open/create `main.cpp` (or the starter), ensure it prints `Hello World!`
4. Build → run → change the string → rebuild → prove the console changed
5. Commit, push, record short demo (tool + code + run), submit Canvas links

## Sample output
```
Hello World!
```

## Definition of done
- Compiles with zero errors on your chosen path
- Console shows Hello World
- Repo link opens for grading
- Short demo video recorded
- Canvas submission filed

## Rubric (100)
| Criterion | Pts |
|-----------|----:|
| Environment works end-to-end | 30 |
| Hello World correct | 30 |
| GitHub repo usable | 20 |
| Short demo video | 20 |

## Scope fence
No loops, functions, or arrays required. One file is enough.

## Tips
- Follow class setup videos click-by-click
- If setup videos fail you, `/ring` the same day — not Sunday of Week 2
- Prefer **one** reliable path over three half-installs

## Help (`/ring`)
After a real try, include: goal · what you tried · exact error · screenshot/repo · OS + tool.

## Getting started

1. Fork this repo on GitHub.
2. Clone your fork.
3. Compile and run:

```bash
g++ -std=c++17 -o program main.cpp && ./program
```

On Windows (Visual Studio), open `main.cpp` and use **Local Windows Debugger**.
4. Record a short demo that shows your tool, your code, and a real run.
5. Paste the video link in the **Demo video** section above.
6. Submit your fork URL on Canvas.
