# Clip2Zero

## Concept

Inspired by [Baphometrix's clip to zero mixing strategy](https://www.youtube.com/watch?v=5UT42-ur080&list=PLxik-POfUXY6i_fP0f4qXNwdMxh3PXxJx) Clip2Zero is a simple plugin that clips an audio signal to 0dbfs. No special processing to make the clipping transparent or anything. This is an early mixing tool that is meant to be replaced with more advanced processing during the later point of a mixdown.

## Parameters
- Input
   Input gain, allows you to control how clipped your signal is.

- Compensate
   Allows you to compensate the output gain based on the input gain to help the user refrain from over-clipping their track.

## Building

After installing [Rust](https://rustup.rs/), you can compile Clip2Zero as follows:

```shell
cargo xtask bundle clip2zero --release
```
