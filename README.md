A library for splitting apart a large file with multiple modules into the idiomatic rust directory structure, intended for use with svd2rust.
Creates a lib.rs as well as a subdirectory structure in the target directory.
It's advised (but not necessary) to use scalafmt afterwards.
Usage:
```
    -f, --force         force the overwriting of the old lib.rs file
    -i, --input FILE    input file to read instead of stdin
    -o, --outdir DIR    set output directory
    -h, --help          print this help menu
```

Does not create the cargo project or the cargo manifest file.

TODO:
    - --force argument doesn't work
    - better error handling
