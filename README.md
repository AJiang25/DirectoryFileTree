# Directory and File Trees

The following repository represents a project in three parts:

In Part 1, you are given object files for a series of faulty Binary Directory Tree implementations, as well as for a correct implementation. You are also given the source for a minimalist BDT client that exhibits errors when run after building with any of the faulty implementations. You will locate the bugs in each faulty implementation by debugging the client program using gdb, and will also report a transcript of a gdb session that appropriately shows how the debugger can identify the location of the bug.

In Part 2, you are given object files for a series of faulty Directory Tree implementations, as well as the source for a correct implementation and a minimalist DT client. This time the client (a) does not necessarily exhibit errors when built with the faulty implementations, and (b) the object files were not configured to facilitate stepping through the code in those files while debugging in gdb. So instead of the approach from Part 1, here you will write an internal validation module that will verify the validity of the data structure such that it correctly identifies the invalid state of the data structure and terminates the program when checked at the leading and trailing edges of each API function.

In Part 3, you are given an expanded API that is appropriate for hierarchies that contain both directories and files. You will implement the File Tree interface, using the Directory Tree implementation from Part 2 as a jumping off point. But the given Part 2 code may not have made the best design choices! Thus, along the way, you will need to reassess the program design and modularity for your expanded version.
