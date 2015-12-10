# Definition of canonical JSON

This is a summary of the ideas at http://wiki.laptop.org/go/Canonical_JSON.

* Whitespace is not permitted between tokens
* Likewise, leading/trailing whitespace is disallowed
* Object members are sorted lexicographically and appear in quotes
* Strings should be UTF-8, but could contain arbitrary byte content
* No floats, leading zeros or "minus zero"
* No trailing commas

# Base ontology

The base ontology is `http://github.com/juztamau5/ontology/#`. The slash was
added to fix misbehavior with some programs.
