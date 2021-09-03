# Bullet

[Bullet Physics](https://github.com/bulletphysics) wrapper for Heaps

Supports both HashLink and JS output thanks to [WebIDL](https://github.com/ncannasse/webidl)

## Compilation

run `make gen_hl`
run `cmake .. -A x64 -G "Visual Studio 15 2017" -DBULLET_SRC_DIR="C:/Projects/RyanCleven/bullet3/src" -DHL_DIR="C:/HaxeToolkit/HashLink/hl-1.11.0-win"`
open and build build/Project.sln
copy build/Debug/bullet.hdll -> ../path/to/HashLink/...  Add this together with the other hdll files

## Run example

navigate to /sample
run `haxe compile.hxml`
run `hl hello.hl`
