# enumerate

Fork of the stringer tool with very basic support for removing the prefix of a value if it matches the type.

This includes removing a leading underscore if present at the start after the type name is removed.

Usage is the same as stringer with the additional -ltrim flag

Without the -ltrim flag this should behave like stringer
