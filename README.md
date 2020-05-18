# Oasis Quickstart

http://oasis.forge.ocamlcore.org/quickstart.html

```sh
~/Downloads/oasis-quickstart
❯ oasis quickstart
The program will ask some questions to create the `_oasis` file. If you
answer '?' to a question, an help text will be displayed.

Field: Name
Name of the package.
No default exists, you need to answer this question.

Value for field 'Name'? helloworld

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
7: AGPL
8: AGPL-3
9: Apache
10: Apache-1
11: Apache-1.0
12: Apache-1.1
13: Apache-2
14: Apache-2.0
15: Artistic
16: Artistic-1
17: Artistic-1.0
18: Artistic-2
19: Artistic-2.0
20: BSD-2-clause
21: BSD-4-clause
22: CC-BY
23: CC-BY-NC
24: CC-BY-NC-ND
25: CC-BY-NC-SA
26: CC-BY-ND
27: CC-BY-SA
28: CC0
29: CDDL
30: CeCILL
31: CeCILL-1
32: CeCILL-2
33: CeCILL-B
34: CeCILL-C
35: CPL
36: CPL-1
37: CPL-1.0
38: Eiffel
39: Eiffel-2
40: Expat
41: FreeBSD
42: GFDL
43: GFDL-1.1
44: GFDL-1.2
45: GFDL-1.3
46: GFDL-NIV
47: GFDL-NIV-1.1
48: GFDL-NIV-1.2
49: GFDL-NIV-1.3
50: GPL
51: GPL-1
52: GPL-1.0
53: GPL-2
54: GPL-2.0
55: GPL-3
56: ISC
57: LGPL
58: LGPL-2
59: LGPL-2 with OCaml linking exception
60: LGPL-2.0
61: LGPL-2.0 with OCaml linking exception
62: LGPL-2.1
63: LGPL-3
64: LGPL-3 with OCaml linking exception
65: LGPL-3.0
66: LGPL-3.0 with OCaml linking exception
67: LPPL
68: LPPL-1.3c
69: MPL
70: MPL-1
71: MPL-1.0
72: MPL-1.1
73: PD
74: Perl
75: PROP
76: PSF
77: PSF-2
78: QPL
79: QPL-1
80: W3C-Software
81: W3C-Software-20021231
82: WTFPL
83: ZLIB
84: ZLIB-1.2.2
85: Zope
86: Zope-1
87: Zope-1.0
88: Zope-2
89: Zope-2.0
90: Zope-2.1

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

Create a section? n

Package definition is complete. Possible actions:

d: display the generated file
e: edit the generated file
w: write and exit
r: write, run 'oasis setup' and exit
q: exit without saving

What do you want to do now? w

~/Downloads/oasis-quickstart 2m 4s
❯ cat _oasis 
OASISFormat: 0.4
Name:        helloworld
Version:     0.1
Synopsis:    Hello world with OCaml and OASIS
Authors:     Alain Armand
License:     MIT
Plugins:     META (0.4)

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
7: AGPL
8: AGPL-3
9: Apache
10: Apache-1
11: Apache-1.0
12: Apache-1.1
13: Apache-2
14: Apache-2.0
15: Artistic
16: Artistic-1
17: Artistic-1.0
18: Artistic-2
19: Artistic-2.0
20: BSD-2-clause
21: BSD-4-clause
22: CC-BY
23: CC-BY-NC
24: CC-BY-NC-ND
25: CC-BY-NC-SA
26: CC-BY-ND
27: CC-BY-SA
28: CC0
29: CDDL
30: CeCILL
31: CeCILL-1
32: CeCILL-2
33: CeCILL-B
34: CeCILL-C
35: CPL
36: CPL-1
37: CPL-1.0
38: Eiffel
39: Eiffel-2
40: Expat
41: FreeBSD
42: GFDL
43: GFDL-1.1
44: GFDL-1.2
45: GFDL-1.3
46: GFDL-NIV
47: GFDL-NIV-1.1
48: GFDL-NIV-1.2
49: GFDL-NIV-1.3
50: GPL
51: GPL-1
52: GPL-1.0
53: GPL-2
54: GPL-2.0
55: GPL-3
56: ISC
57: LGPL
58: LGPL-2
59: LGPL-2 with OCaml linking exception
60: LGPL-2.0
61: LGPL-2.0 with OCaml linking exception
62: LGPL-2.1
63: LGPL-3
64: LGPL-3 with OCaml linking exception
65: LGPL-3.0
66: LGPL-3.0 with OCaml linking exception
67: LPPL
68: LPPL-1.3c
69: MPL
70: MPL-1
71: MPL-1.0
72: MPL-1.1
73: PD
74: Perl
75: PROP
76: PSF
77: PSF-2
78: QPL
79: QPL-1
80: W3C-Software
81: W3C-Software-20021231
82: WTFPL
83: ZLIB
84: ZLIB-1.2.2
85: Zope
86: Zope-1
87: Zope-1.0
88: Zope-2
89: Zope-2.0
90: Zope-2.1

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