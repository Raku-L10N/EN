[![Actions Status](https://github.com/Raku-L10N/EN/actions/workflows/linux.yml/badge.svg)](https://github.com/Raku-L10N/EN/actions) [![Actions Status](https://github.com/Raku-L10N/EN/actions/workflows/macos.yml/badge.svg)](https://github.com/Raku-L10N/EN/actions) [![Actions Status](https://github.com/Raku-L10N/EN/actions/workflows/windows.yml/badge.svg)](https://github.com/Raku-L10N/EN/actions)

NAME
====

L10N::EN - English localization of Raku

SYNOPSIS
========

```raku
use L10N::NL;           # or any other non-English localization
zeg "Hallo wereld";
{
    gebruik L10N::EN;   # Note: -use- is -gebruik- in L10N::NL
    say "Hello World";  # now back to "normal" english syntax
}
```

DESCRIPTION
===========

L10N::EN contains the logic to provide a English localization of the Raku Programming Language.

Note that this is the same mapping as the core. This localization is mainly intended to allow switching back to the core language in a scope, while being in another localization.

AUTHORS
=======

Elizabeth Mattijsen <liz@raku.rocks>

COPYRIGHT AND LICENSE
=====================

Copyright 2023, 2025 Raku Localization Team

This library is free software; you can redistribute it and/or modify it under the Artistic License 2.0.

