[![Build Status](https://travis-ci.org/zoffixznet/perl6-Temp-Path.svg)](https://travis-ci.org/zoffixznet/perl6-Temp-Path)

# NAME

Temp::Path -

# SYNOPSIS

```perl6
use Temp::Path;

with make-temp-path {

}
```

# DESCRIPTION

# EXPORTED TERMS

## `&term:<make-temp-path>`

Defined as:

```perl6
```

**Note** that at the moment, `:chmod` is set *after* the file is created and
its content is written. This will be fixed once a way to create a file
with a specific mode is available in Rakudo. While it will work at the moment,
it might not be the best idea to assume `:$content` will be successfully written
if you set `:$chmod` that does not let the current process write to the file.


## SEE ALSO

[`File::Temp`](https://modules.perl6.org/repo/File::Temp)

----

#### REPOSITORY

Fork this module on GitHub:
https://github.com/zoffixznet/perl6-Temp-Path

#### BUGS

To report bugs or request features, please use
https://github.com/zoffixznet/perl6-Temp-Path/issues

#### AUTHOR

Zoffix Znet (http://perl6.party/)

#### LICENSE

You can use and distribute this module under the terms of the
The Artistic License 2.0. See the `LICENSE` file included in this
distribution for complete details.

The `META6.json` file of this distribution may be distributed and modified
without restrictions or attribution.
