Clone a repository and configure it with multiple pushurl values, in a single step.

Design goals:
1. provide a single step for cloning a repository and configuring "origin" as
   multiple urls, user care less about what git hosting service (or services) she uses
2. Accomplish 1. with minimal dependencies
  - this could mean wrapping the git command line utility in shell
  - this could also mean a statically-linked binary
  - this probably means no curses interface and maybe not even an interactive
    command-line interface.
