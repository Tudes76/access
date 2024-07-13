# access - noseh

A simple syscall wrapper that requires no handles to perform operations with `PROCESS_ALL_ACCESS` privilege.

This branch is the modified version that uses no SEH, but still does safe operations (results in slower execution). This branch also utilizes a different syscall hook for communication via a `.data` section modification in the kernel.

## Usage

1. Load the driver.
2. Load the DLL (wrapper) into a program that needs to open a handle to a protected process.
3. The program can now perform privileged operations without creating a real handle.

## Demo

![Demo with Fortnite and Cheat Engine](demo.gif)

## Note the vacation are note preparet

- note to the last dev i push some comments for you
- The wrapper is designed to be loaded in a x64 process and only implements the syscalls that pertain to my workflow.
- Only tested on Windows 10 1903, 1809, and 1803.

## not updated

we are going to update this soon

### where a you i am here to me

not today, patch note fn with go alone

## sorry i came back after so long

i am going to find a way to make some noie gate for this app

## number 1 verity is the work

ok lets go today i need some people for help

## vlog early thing