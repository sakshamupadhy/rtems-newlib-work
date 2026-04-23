# rtems-newlib-work
exploration of Newlib (libc) with ARM toolchain and custom function integration 
# RTEMS Newlib Work (POSIX Exploration)

## What I did
- Set up RTEMS + Newlib environment
- Explored libc structure
- Created custom function: my_special_func
- Generated patch using git

## Patch Details
- File modified: newlib/libc/stdlib/abs.c
- Function added:
```c
int my_special_func(int x) {
    return x * 2;
}
