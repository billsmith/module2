# module2

This is an example of a project that depends on modules with a major version of 2.  The Go 1.11 docs describe two ways to
publish a v2 module: you can use a v2 branch, or you can put the v2 code in a v2 subdirectory with its own go.mod.

module2 depends on module1 (which uses a v2 subdirectory) and module3 (which uses a v2 branch).
