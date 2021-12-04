Project 1: Threads => Alarm clock
Project 2: User program => System calls

# Pintos - Alarm Clock

## Modified Files:
1) timer.c   

modified timer_sleep()

2) thread.c   

add thread_sleep()

add thread_wake()


3) thread.h

add void thread_sleep (int64_t);

add void thread_wake (void);


## Code has been add like:

/* my code begins */

CODE HERE

/* my code ends */



# Pintos - System call

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


# Nhiệm vụ
## Alarm clock
- Sửa file timer.c
+ Hàm timer_sleep() =========> Nhiệm vụ của ...
- Sửa file thread.c & thread.h
+ Hàm thread_sleep() ========> Nhiệm vụ của ...
+ Hàm thread_wake() =========> Nhiệm vụ của ...
## System call
Tự mỗi thành viên chọn 4 hoặc 5 hàm

 
