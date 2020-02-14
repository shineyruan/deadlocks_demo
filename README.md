# deadlocks_demo

## Getting Started
1. SSH into CAEN
2. `git clone git@github.com:eecs482/deadlocks_demo.git` (Requires SSH key added to github)
  Alternatively, `git clone https://github.com/eecs482/deadlocks_demo.git`
3. `cd deadlocks_demo`
4. `make`
5. `./deadlock` This should freeze. Hit `Control+C` to exit
6. Run in gdb: `gdb deadlock`
  Recall: use `r` to run the program
7. The program should also freeze in gdb (same behavior as before!) Hit `Control+C`
8. This should give you a gdb prompt. Use `i threads` and `t <thread number>` and `thread apply all ...` to figure out where each thread is at the time of deadlock
9. Profit?
