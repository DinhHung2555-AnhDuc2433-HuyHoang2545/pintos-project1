# Project 1: Alarm clock


## Running pintos:

$>need pintos (optional)

$>cd pintos/src/threads

$>make

$>cd build

$>pintos

$>pintos -v -k -T 60 --qemu -- -q run alarm-single

# Pintos - Alarm Clock

## Modified Files:
1) timer.c   

modified timer_sleep()

2) thread.c   

3) thread.h

## Code has been add like:

/* that code my here begin */

CODE HERE

/* that code my here end */



# Pintos 2: System call

## Modified file userprog/syscall.c & syscall.h

1. System Call: void halt (void)

2. System Call: void exit (int status)

3. System Call: pid_t exec (const char *cmd_line)

4. System Call: int wait (pid_t pid)

5. System Call: bool create (const char *file, unsigned initial_size)

6. System Call: bool remove (const char *file)

7. System Call: int open (const char *file)

8. System Call: int filesize (int fd)

9. System Call: int read (int fd, void *buffer, unsigned size)

10. System Call: int write (int fd, const void *buffer, unsigned size)

11. System Call: void seek (int fd, unsigned position)

12. System Call: unsigned tell (int fd)

13. System Call: void close (int fd)



 
