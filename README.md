shell-tools
===========

UNIX shell tools

---

fij - Find In Jars
------------------

### usage

`fij searchstring [jarfile [jarfile ...]]`

If no jarfile arguments are given, program will
search all jar files found beneath the current directory.

### examples

* `fij com.example.Example lib/file1.jar lib/file2.jar`

  will look for com.example.Example in `lib/file1.jar`
  and `lib/file2.jar`, and print out the names of any
  jar file which contains com.example.Example

* `fij com.example.Example`

  will look for `com.example.Example` in any jar files
  found beneath the current directory (recursively),
  and print out the names of any jar file which
  contains com.example.Example

### dependencies

* find
* unzip

---