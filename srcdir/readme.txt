
Go to terminal (/srcdir)
git clone https://github.com/shpal2000/tlspack-socket.git
git clone https://github.com/shpal2000/tlspack-traffic.git
https://github.com/nodejs/node.git
cd subprojects
git clone https://github.com/nlohmann/json.git

cd .. 
(/srcdir)
meson build
ninja -C build

