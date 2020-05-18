# Oasis Quickstart

http://oasis.forge.ocamlcore.org/quickstart.html

## Resources

[Oasis Quickstart](http://oasis.forge.ocamlcore.org/quickstart.html)
[Setting up with Oasis](https://ocaml.org/learn/tutorials/setting_up_with_oasis.html)

## Output

```sh

~/Downloads/oasis-quickstart
❯ oasis quickstart
The program will ask some questions to create the `_oasis` file. If you
answer '?' to a question, an help text will be displayed.

y: yes
n: no

File '_oasis' already exists, overwrite it? y

Field: Name
Name of the package.
No default exists, you need to answer this question.

Value for field 'Name'? Alain Armand

Field: Version
Version of the package.
No default exists, you need to answer this question.

Value for field 'Version'? 0.1

Field: Plugins
Extra plugins to use.
Default is ''

Choices:

1: META (0.4)
2: StdFiles (0.4)
3: DevFiles (0.4)

Value for field 'Plugins'? 1

Field: License
DEP-5 license of the package (See [DEP-5](http://dep.debian.net/deps/dep5/#index6h3)).
No default exists, you need to answer this question.

Choices:

1: LGPL-2.1 with OCaml linking exception
2: BSD-3-clause
3: GPL-3.0
4: AGPL-3.0
5: QPL-1.0
6: MIT
...

Value for field 'License'? 6

Field: Authors
Real people that had contributed to the package.
No default exists, you need to answer this question.

Value for field 'Authors'? Alain Armand

Field: Synopsis
Short description of the purpose of this package.
No default exists, you need to answer this question.

Value for field 'Synopsis'? Hello world with OCaml and OASIS

General package definition is complete. You can now create sections to
describe various objects shipped by this package:

n: stop
l: create a library
e: create an executable
f: create a flag
s: create a source repository
t: create a test
d: create a document

Create a section? e


Executable name? helloworld

Field: MainIs
OCaml file (.ml) containing main procedure for the executable.
No default exists, you need to answer this question.

Value for field 'MainIs'? main.ml

Field: Path
Directory containing the section
No default exists, you need to answer this question.

Value for field 'Path'? .

Section definition is complete. You can now now create additional sections:

n: stop
l: create a library
e: create an executable
f: create a flag
s: create a source repository
t: create a test
d: create a document

Create another section? n

Package definition is complete. Possible actions:

d: display the generated file
e: edit the generated file
w: write and exit
r: write, run 'oasis setup' and exit
q: exit without saving

What do you want to do now? r

~/Downloads/oasis-quickstart 1m 44s
❯ ocaml setup.ml -configure 
File "./setup.ml", line 1775, characters 22-40:
1775 |         let compare = Pervasives.compare
                             ^^^^^^^^^^^^^^^^^^
Alert deprecated: module Stdlib.Pervasives
Use Stdlib instead.

If you need to stay compatible with OCaml < 4.07, you can use the 
stdlib-shims library: https://github.com/ocaml/stdlib-shims
File "setup.ml", line 3467, characters 16-34:
Alert deprecated: module Stdlib.Pervasives
Use Stdlib instead.

If you need to stay compatible with OCaml < 4.07, you can use the 
stdlib-shims library: https://github.com/ocaml/stdlib-shims

Configuration:
ocamlfind: ........................................... /Users/mandalarian/.opam/4.08.1/bin/ocamlfind
ocamlc: .............................................. /Users/mandalarian/.opam/4.08.1/bin/ocamlc.opt
ocamlopt: ............................................ /Users/mandalarian/.opam/4.08.1/bin/ocamlopt.opt
ocamlbuild: .......................................... /Users/mandalarian/.opam/4.08.1/bin/ocamlbuild
Package name: ........................................ Alain Armand
Package version: ..................................... 0.1
os_type: ............................................. Unix
system: .............................................. macosx
architecture: ........................................ amd64
ccomp_type: .......................................... cc
ocaml_version: ....................................... 4.08.1
standard_library_default: ............................ /Users/mandalarian/.opam/4.08.1/lib/ocaml
standard_library: .................................... /Users/mandalarian/.opam/4.08.1/lib/ocaml
bytecomp_c_compiler: ................................. cc -O2 -fno-strict-aliasing -fwrapv  -D_FILE_OFFSET_BITS=64 -D_REENTRANT
native_c_compiler: ................................... cc -O2 -fno-strict-aliasing -fwrapv -D_FILE_OFFSET_BITS=64 -D_REENTRANT
model: ............................................... default
ext_obj: ............................................. .o
ext_asm: ............................................. .s
ext_lib: ............................................. .a
ext_dll: ............................................. .so
default_executable_name: ............................. a.out
systhread_supported: ................................. true
Install architecture-independent files dir: .......... /usr/local
Install architecture-dependent files in dir: ......... $prefix
User executables: .................................... $exec_prefix/bin
System admin executables: ............................ $exec_prefix/sbin
Program executables: ................................. $exec_prefix/libexec
Read-only single-machine data: ....................... $prefix/etc
Modifiable architecture-independent data: ............ $prefix/com
Modifiable single-machine data: ...................... $prefix/var
Object code libraries: ............................... $exec_prefix/lib
Read-only arch-independent data root: ................ $prefix/share
Read-only architecture-independent data: ............. $datarootdir
Info documentation: .................................. $datarootdir/info
Locale-dependent data: ............................... $datarootdir/locale
Man documentation: ................................... $datarootdir/man
Documentation root: .................................. $datarootdir/doc/$pkg_name
HTML documentation: .................................. $docdir
DVI documentation: ................................... $docdir
PDF documentation: ................................... $docdir
PS documentation: .................................... $docdir
findlib_version: ..................................... 1.8.1
is_native: ........................................... true
suffix_program: ......................................
Remove a file.: ...................................... rm -f
Remove a directory.: ................................. rm -rf
Turn ocaml debug flag on: ............................ true
Turn ocaml profile flag on: .......................... false
Compiler support generation of .cmxs.: ............... true
OCamlbuild additional flags: .........................
Create documentations: ............................... true
Compile tests executable and library and run them: ... false


~/Downloads/oasis-quickstart
❯ ocaml setup.ml -configure 

Configuration:
ocamlfind: ........................................... /Users/mandalarian/.opam/4.08.1/bin/ocamlfind
ocamlc: .............................................. /Users/mandalarian/.opam/4.08.1/bin/ocamlc.opt
ocamlopt: ............................................ /Users/mandalarian/.opam/4.08.1/bin/ocamlopt.opt
ocamlbuild: .......................................... /Users/mandalarian/.opam/4.08.1/bin/ocamlbuild
Package name: ........................................ Alain Armand
Package version: ..................................... 0.1
os_type: ............................................. Unix
system: .............................................. macosx
architecture: ........................................ amd64
ccomp_type: .......................................... cc
ocaml_version: ....................................... 4.08.1
standard_library_default: ............................ /Users/mandalarian/.opam/4.08.1/lib/ocaml
standard_library: .................................... /Users/mandalarian/.opam/4.08.1/lib/ocaml
bytecomp_c_compiler: ................................. cc -O2 -fno-strict-aliasing -fwrapv  -D_FILE_OFFSET_BITS=64 -D_REENTRANT
native_c_compiler: ................................... cc -O2 -fno-strict-aliasing -fwrapv -D_FILE_OFFSET_BITS=64 -D_REENTRANT
model: ............................................... default
ext_obj: ............................................. .o
ext_asm: ............................................. .s
ext_lib: ............................................. .a
ext_dll: ............................................. .so
default_executable_name: ............................. a.out
systhread_supported: ................................. true
Install architecture-independent files dir: .......... /usr/local
Install architecture-dependent files in dir: ......... $prefix
User executables: .................................... $exec_prefix/bin
System admin executables: ............................ $exec_prefix/sbin
Program executables: ................................. $exec_prefix/libexec
Read-only single-machine data: ....................... $prefix/etc
Modifiable architecture-independent data: ............ $prefix/com
Modifiable single-machine data: ...................... $prefix/var
Object code libraries: ............................... $exec_prefix/lib
Read-only arch-independent data root: ................ $prefix/share
Read-only architecture-independent data: ............. $datarootdir
Info documentation: .................................. $datarootdir/info
Locale-dependent data: ............................... $datarootdir/locale
Man documentation: ................................... $datarootdir/man
Documentation root: .................................. $datarootdir/doc/$pkg_name
HTML documentation: .................................. $docdir
DVI documentation: ................................... $docdir
PDF documentation: ................................... $docdir
PS documentation: .................................... $docdir
findlib_version: ..................................... 1.8.1
is_native: ........................................... true
suffix_program: ......................................
Remove a file.: ...................................... rm -f
Remove a directory.: ................................. rm -rf
Turn ocaml debug flag on: ............................ true
Turn ocaml profile flag on: .......................... false
Compiler support generation of .cmxs.: ............... true
OCamlbuild additional flags: .........................
Create documentations: ............................... true
Compile tests executable and library and run them: ... false


~/Downloads/oasis-quickstart
❯  ocaml setup.ml -build
Finished, 1 target (0 cached) in 00:00:01.
Finished, 3 targets (0 cached) in 00:00:00.

~/Downloads/oasis-quickstart
❯ ocaml setup.ml -install

~/Downloads/oasis-quickstart
❯ which helloworld
/usr/local/bin/helloworld

~/Downloads/oasis-quickstart
❯ helloworld
Hello world!

~/Downloads/oasis-quickstart
❯ 
```