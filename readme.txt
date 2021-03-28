
#1
update: devcontainer.json for <tlspack-build-path>
"workspaceMount": "src=<tlspack-build-path>/srcdir/,dst=/srcdir,type=bind"

----

#2

cd srcdir
git clone https://github.com/shpal2000/tlspack-socket.git
git clone https://github.com/shpal2000/tlspack-traffic.git
git clone https://github.com/nodejs/llhttp.git
cd subprojects
https://github.com/nlohmann/json.git


---


#3
Open Folder in Container ..
Folder: tlspack-build

Go to terminal (/srcdir)
meson build
ninja -C build


cd ../
meson build
ninja -C build


---

