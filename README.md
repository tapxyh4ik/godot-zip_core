# godot "zip core GDNative" 
zip archive core for godot

How to build:
```
git init 
git submodule add -b 3.2 https://github.com/godotengine/godot-cpp
cd godot_cpp
git submodule update --init
cd ..
git clone https://github.com/tapxyh4ik/godot-zip_core
cmake ..
```
