# Tauri + React + Typescript

This template should help get you started developing with Tauri, React and Typescript in Vite.

## Recommended IDE Setup

- [VS Code](https://code.visualstudio.com/) + [Tauri](https://marketplace.visualstudio.com/items?itemName=tauri-apps.tauri-vscode) + [rust-analyzer](https://marketplace.visualstudio.com/items?itemName=rust-lang.rust-analyzer)

sudo apt update
sudo apt install libsoup-3.0-dev
pkg-config --modversion libsoup-3.0
find /usr -name "libsoup-3.0.pc"
export PKG_CONFIG_PATH=/path/to/libsoup-3.0.pc:$PKG_CONFIG_PATH

sudo apt install libjavascriptcoregtk-4.1-dev
pkg-config --modversion javascriptcoregtk-4.1
find /usr -name "javascriptcoregtk-4.1.pc"
export PKG_CONFIG_PATH=/path/to/directory:$PKG_CONFIG_PATH

sudo apt update
sudo apt install libwebkit2gtk-4.1-dev
pkg-config --modversion webkit2gtk-4.1
find /usr -name "webkit2gtk-4.1.pc"
export PKG_CONFIG_PATH=/usr/lib/x86_64-linux-gnu/pkgconfig:$PKG_CONFIG_PATH
