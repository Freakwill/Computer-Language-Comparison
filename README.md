# Comparison of Computer Languages

[Wiki](https://en.wikipedia.org/wiki/Comparison_of_programming_languages_(syntax))

* /: does not have such keyword or function
* -: same with Python
* a/b: both a and b

## Also See
[Hyperpolyglot](http://hyperpolyglot.org/)

## Comparison of Keywords

| Lang           | C/C++      | Java    | Python       | Ruby              | javaScript | go      | swift   | scala   | php             | julia              |
| -------------- | ---------- | ------- | ------------ | ----------------- | ---------- | ------- | ------- | ------- | --------------- | ------------------ |
| variable       | /         | /      | /           | /                | var/let    | var     | var     | var     | /              | /                 |
| constant       | const      | /      | /           | /                | /         | const   | let     | val     | define          | /                 |
| function       | /         | /      | def          | def-end           | function   | func    | func    | def     | function        | function-end       |
| class          | class      | class   | class        | class-end         | class      | /      | class   | class   | class           | /                 |
| object         | new        | new     | /           | .new()            | new        | /      | /      | new     | new             | /                 |
| if-else        | if-else    | if-else | if-elif-else | if-elsif-else-end | if-else    | if-else | if-else | if-else | if-elseif-else  | if-elseif-else-end |
| library/module | `#include` | import  | import       | require/include   | import     | import  | import  | import  | include/require | import/using       |
| inheritance    | :          | extends | /           | <                 | extends    | /      | :       | extends | extends         |                    |
| Weird Degree   | 3          | 4       | 1            | 4                 | 3          | 5       | 2       | 3       | 5               | 4                  |



## Operating Arrays

| Languages   | C/C++ | Java    | Python            | Ruby                    | javaScript    | go   | swift         | scala | php  | julia         |
| ----------- | ----- | ------- | ----------------- | ----------------------- | ------------- | ---- | ------------- | ----- | ---- | ------------- |
| Define      | {}    | {}      | []                | [],Array.new,Array[]    | [],Array()    | var  | var           |       |      | [],Array{}    |
| referance   | -     | -       | -                 | -/.at                   | -             | -    | -             | -     | -    | -/getindex    |
| sum         | -     | -       | sum               | .sum                    | -             | -    | -             | -     | -    | -             |
| product     |       |         |                   |                         |               |      |               |       |      | prod          |
| minimum/max |       |         | min/max           | .min/.max               | -             | -    | -             | -     | -    | -             |
| sorting     |       |         | sorted/.sort      | .sort                   | .sort         |      |               |       |      | sort          |
| deleting    |       |         | del/.remove/.pop  | .delete/.pop/.delete_at | .pop/.shift   |      | .remove(,at:) |       |      |               |
| concatenate |       | extends | +/.append/.extend | +/.push/.concat/<<      | .push/.concat |      |               |       |      |               |
| mapping     |       |         | map               | .map/.each              | .map          |      |               |       |      | map           |
| finding     |       |         | index             | .index/.values_at       |               |      |               |       |      | cat/vcat/hcat |
| containing  |       |         | in                | .include?               |               |      |               |       |      | in            |
| insert      |       |         | .insert           | -                       |               |      | .insert(,at:) |       |      |               |



## About Strings

| Languages   | C/C++ | Java    | Python           | Ruby                    | javaScript    | Swift | Julia | Lua |
| ----------- | ----- | ------- | ---------------- | ----------------------- | ------------- | ---- | ----- | ----------- |
| Define      | "" | "" | ""/''/""""""/str() | -/%q/ `<<~DOC ... DOC`/String.new | -/String.new() | -/String() | - | ""/''/[[]] |
| referance  | -     | -       | []               | -                   | -             | [Index] | - | string.sub |
| mutable | Yes  | Yes    | No |Yes|No| Yes | No | No |
| deleting    |       |         | .strip | .chomp |    |  |  |  |
| concatenate |       |  | +                | +/.concat/<< | - | +/.append | */string | .. |
| mapping     |       |         | map              | .each_byte           |                |  |  |  |
| finding     |       |         | index            | .index       | .search |  | findnext | string.find |
| containing  |       |         | in               | .include?               | - |  | occursin |  |
| split | | | .split | - | - |  |  |  |
| join | | | .join | list.join(str) | list.join(str) |  | join |  |
| replace | | | .replace | s[...]=.../.sub/.gsub | - | | replace | string.gsub |



## Package Manager

| Python           | Ruby    | C/C++    | javaScript | Lua      | Julia | Haskell         | R                  | Java  | Swift |
| ---------------- | ------- | -------- | ---------- | -------- | ----- | --------------- | ------------------ | ----- | ----- |
| pip/conda        | gem     | conan    | npm        | luarocks | Pkg   | Cabal/stock/nix | install.packages() | maven | spm   |
| requirements.txt | GemFile | MakeFile |            |          |       |                 |                    |       |       |

