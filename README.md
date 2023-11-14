# SHA checksums in base64

The `sha256sum` utility produces a hex string.
This tool is less sophisticated; it produces a base64 string instead.

Right now, this only respects the `-z` flag and doesn't do any of the checking functions (the `-c` flag).
