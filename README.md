# The Go Programming Language - BCS Hacked version

Loris Cro (the Zig guy) has a video where he does this:

- Hack Go source code to look for ".zig" files in the same execution flow as
  it looks for ".c" files. (So, the Go build process is compiling any .zig
  files it finds like they are "C".
  - Which doesn't work, of course.
- But! When he changes `CC="zig cc"` it actually works!!!!!

He also pointed out a few other things to checkout in this regard:

- [Maintain it with Zig](https://kristoff.it/blog/maintain-it-with-zig/)
- ['zig cc': A powerful drop-in](https://andrewkelley.me/post/zig-cc-powerful-drop-in-replacement-gcc-clang.html)
- [Building SQLite with CGO...](https://zig.news/kristoff/building-sqlite-with-cgo-for-every-os-4cic)
- [Cross Compilation 'Just Works' with Zig](https://dev.to/kristoff/zig-makes-go-cross-compilation-just-work-29ho)

# Back to Your _'The Go Programming Language'_

Go is an open source programming language that makes it easy to build simple,
reliable, and efficient software.

![Gopher image](https://golang.org/doc/gopher/fiveyears.jpg)
*Gopher image by [Renee French][rf], licensed under [Creative Commons 4.0 Attributions license][cc4-by].*

Our canonical Git repository is located at https://go.googlesource.com/go.
There is a mirror of the repository at https://github.com/golang/go.

Unless otherwise noted, the Go source files are distributed under the
BSD-style license found in the LICENSE file.

### Download and Install

#### Binary Distributions

Official binary distributions are available at https://go.dev/dl/.

After downloading a binary release, visit https://go.dev/doc/install
for installation instructions.

#### Install From Source

If a binary distribution is not available for your combination of
operating system and architecture, visit
https://go.dev/doc/install/source
for source installation instructions.

### Contributing

Go is the work of thousands of contributors. We appreciate your help!

To contribute, please read the contribution guidelines at https://go.dev/doc/contribute.

Note that the Go project uses the issue tracker for bug reports and
proposals only. See https://go.dev/wiki/Questions for a list of
places to ask questions about the Go language.

[rf]: https://reneefrench.blogspot.com/
[cc4-by]: https://creativecommons.org/licenses/by/4.0/
