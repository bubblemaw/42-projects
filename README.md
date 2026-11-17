# 42-projects

This repository gathers the projects I completed during the **42 common core**.
 
The projects start with the fundamentals of C (memory, file descriptors, algorithms), move on to UNIX system programming (processes, pipes, threads), then to larger projects such as a shell, a ray tracer and object-oriented C++, and end with a final full-stack web application.
 
Each project lives in its own repository, with its own README and build instructions. Follow the links in the table below to explore them.


## Common Core

| Project | Description | Language | Skills acquired | Repository |
|---------|-------------|----------|-----------------|------------|
| get_next_line | Reads a file one line at a time, with any buffer size | C | File descriptors, `read`, static variables, dynamic memory management, leak-free code | [GNL](https://github.com/bubblemaw/GNL) |
| ft_printf | My own re-implementation of `printf` | C | Variadic functions (`stdarg`), string parsing, number base conversion, library building with a Makefile | [printf](https://github.com/bubblemaw/printf) |
| push_swap | Sorts a stack of integers using the fewest possible operations | C | Sorting algorithms, complexity analysis, linked lists, optimization, input validation | [push_swap](https://github.com/bubblemaw/push_swap) |
| pipex | Reproduces how the shell pipe works | C | Processes (`fork`, `wait`), pipes, file descriptor redirection (`dup2`), `execve`, `PATH` and environment handling | [pipex](https://github.com/bubblemaw/pipex) |
| so_long | A small 2D game built with MiniLibX | C | Graphical programming, event handling, sprites, map parsing and validation, flood fill | [so_long](https://github.com/bubblemaw/so_long) |
| Philosophers | The dining philosophers problem, with no data races or deadlocks | C | Multithreading (`pthread`), mutexes, synchronization, data race and deadlock prevention, precise timing | [Philosophers](https://github.com/bubblemaw/Philosophers) |
| minishell | A simplified Bash-like shell | C | Lexing and parsing, pipes and redirections, environment variables, signal handling, built-in commands, process management | [minishell](https://github.com/bubblemaw/minishell) |
| miniRT | A ray tracer that renders 3D scenes | C | Ray tracing, vector math, lighting and shadows, geometric shapes (sphere, plane, cylinder), scene file parsing, MiniLibX | [miniRT](https://github.com/bubblemaw/miniRT) |
| Inception | A small web infrastructure deployed with Docker Compose (NGINX, WordPress, MariaDB) | Docker, Shell | Containerization, Dockerfiles, Docker Compose, networking and volumes, NGINX with TLS, database and WordPress setup, system administration | [Inception](https://github.com/bubblemaw/inception) |
| CPP Modules | A series of exercises introducing object-oriented C++ | C++98 | Classes and encapsulation, inheritance and polymorphism, operator overloading, templates, exceptions, STL containers and algorithms | [00](https://github.com/bubblemaw/CPP-Module-00) [01](https://github.com/bubblemaw/CPP-Module-01) [02](https://github.com/bubblemaw/CPP-Module-02) [03](https://github.com/bubblemaw/CPP-Module-03) [04](https://github.com/bubblemaw/CPP-Module-04) [05](https://github.com/bubblemaw/CPP-Module-05) [06](https://github.com/bubblemaw/CPP-Module-06) [07](https://github.com/bubblemaw/CPP-Module-07) [08](https://github.com/bubblemaw/CPP-Module-08) [09](https://github.com/bubblemaw/CPP-Module-09) |
| ft_transcendence | The final project: a full-stack web application | Javascript, Nodejs, Postgresql, Prisma, React | Authentication, real-time communication, Geolocation, Public REST API  | [ft_transcendence](https://github.com/transcendance-42/P23_transcendance) |
<!-- Add your other projects here, one row per project -->

## Overall skills

- **Languages:** C, C++, Makefile, Shell, Javascript
- **Tools:** Git, Valgrind, GDB
- **Concepts:** memory management, UNIX system programming, algorithms, concurrency, object-oriented programming, computer graphics

## Links

- GitHub profile: [@bubblemaw](https://github.com/bubblemaw)
