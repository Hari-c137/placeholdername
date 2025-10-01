
### developer build guide <hr>

install bun(package manager) and rust

```sh
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh
curl -fsSL https://bun.sh/install | bash
```
clone the repo 

```sh
cd placeholdername
bun install
bun tauri dev
bun tauri build # this will build the binaries, packages(deb,rpm) and appimage
```
