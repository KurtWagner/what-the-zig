# What the zig?

This repo proposes `README.md` badges for open source Zig projects to indicate what Zig version(s) the project intends to support. This enables users to make informed decisions when adopting and contributing to a Zig project.

## Why does this matter?

Zig is continously changing, often with breakages, which makes depending on another Zig project a risky and often confusing endeaver. 
This adds friction to the open source community as it's hard to depend on one another when everyone is dealing with changes in their own time (or maybe never).

A badge in projects `README.md` doesn't solve the underlying work required to maintain a zig project but will **clearly document the intent of the maintainers so dependants can make informed decisions**.

Hopefully one day this will be irrelevant and Zig will be truly stable, where every project supports "zig" (which implicitly means 1.x.x) but it's not there yet, and Zig projects and the community need to exist in the meantime to help test and shape Zigs future.

## What are the badges?

View source to see the markdown used

| Example | Kind |
| ----- | ---- |
| [![Zig support](https://img.shields.io/badge/Zig-0.14.1-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig) | Supports a single fixed version |
| [![Zig support](https://img.shields.io/badge/Zig-master-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports the latest under development version (i.e., the future versions) |
| [![Zig support](https://img.shields.io/badge/Zig-0.14.1%20%7C%200.15.0%20%7C%20master-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports multiple fixed versions |
| [![Zig support](https://img.shields.io/badge/Zig-0.14.x-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports all within the patch range |
| [![Zig support](https://img.shields.io/badge/Zig-0.x.x-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports all within the minor range |
| [![Zig support](https://img.shields.io/badge/Zig-%E2%89%A50.14.0-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports a minimum version |
| [![Zig support](https://img.shields.io/badge/Zig-%E2%89%A50.14.0%20%E2%89%A40.15.1-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports a minimum to maximum range |
| [![Zig support](https://img.shields.io/badge/Zig-no_guarantees-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Experimental, no guarantees to support any version |
| [![Zig support](https://img.shields.io/badge/Zig-all-color?logo=zig&color=%23f3ab20)](http://github.com/kurtwagner/what-the-zig)  | Supports every version, [tell them you're dreamin'](https://www.youtube.com/watch?v=jL2DH-nKBeA) |


## Acknowledgments

These badges are rendered by [shields.io](https://img.shields.io) - go check them out and offer support if feasible.
