# Process

## What is a program? What is a process?

A program is a set of instructions stored on a computer that does not do anything by itself. A process is a running instance of that program, created and managed by the operating system and executed by the CPU.

## What happens underneath when your computer runs many program at the same time?

For example, you might have a browser, text editor, and music player open. They appear to be running at the same time. But one CPU core can execute only one process at a particular moment. The operating system rapidly switches the CPU core between processes. It might run the browser briefly, pause it, run the music player, pause it, and then run the text editor. Because these switches happen very quickly, we usually do not notice it pausing one process and resuming another. This is part of CPU virtualization. It creates the illusion that each process has its own CPU. If your computer has multiple CPU cores, multiple processes can actually run at the same time.