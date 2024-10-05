
# Atomix Kernel

**Atomix Kernel** is a personal operating system kernel project aimed at building a lightweight, modular, and efficient kernel from scratch for the x86 architecture. This project is currently in its early stages of development.

## Project Status

As of now, the project is in its initial setup phase. The following is the planned project structure, but no files or code have been implemented yet.

## Planned Project Structure

```
atomix-kernel/
├── boot/
├── kernel/
│   ├── arch/
│   ├── drivers/
│   ├── fs/
│   ├── include/
│   ├── mm/
│   ├── scheduler/
│   ├── syscall/
├── libs/
│   ├── libk/
│   └── libc/
├── scripts/
```

Currently, there are no actual files in the repository, only this basic project structure.

## Future Plans

- Implement a Multiboot-compliant bootloader.
- Set up memory management (paging, heap allocation).
- Implement basic interrupt handling and drivers (VGA, keyboard).
- Introduce task scheduling and basic system calls.

## Getting Started

At this stage, there's no code to build or run. However, the setup for cross-compiling and running in QEMU will be detailed once the initial components are in place.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
