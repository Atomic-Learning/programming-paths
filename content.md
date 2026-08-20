In programming, a path is a text-based description of a location in a file system. It is comprised of a sequence of directory names and, possibly, a filename at the end of the path. These components are separated by a forward slash `/` on Unix-like systems (Linux, macOS) or a backslash `\` on Windows systems.

# Special Path References

In addition to regular directory and file names, paths can include special references:

    * `.` refers to the current working directory.

    * `..` refers to the parent directory.

# Example Structure

In this page we will use the following example structure:

```
home
└── user
    ├── documents
    │   └── file.txt
    └── downloads
        └── image.jpg
```

where `home` is found in the root directory of the file system, `user` is a subdirectory of `home`, and so on.

# Absolute and Relative Paths

An absolute path specifies the complete location of a file or directory from the root of the file system. For example, `/home/user/documents/file.txt` is an absolute path on Unix-like systems. This typically starts with a slash to denote the root directory.

A relative path specifies the location of a file or directory relative to the current working directory. For example, :

* If `/home/user` is the current working directory, `./documents/file.txt` (or `documents/file.txt` as a shorthand) refers to `/home/user/documents/file.txt`.
* If `/home/user/documents` is the current working directory, `../downloads/image.jpg` refers to `/home/user/downloads/image.jpg`.
