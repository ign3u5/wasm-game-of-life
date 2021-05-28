# Getting Started
Click [here](https://wasm.ws311471.remote.ac/) to see the hosted example
1. Download [wasm-pack](https://rustwasm.github.io/wasm-pack/installer/)
2. Open a command prompt at the project root and run `wasm-pack build`
3. Open a command prompt inside the www directory and run `npm install`
4. Then run `npm run start` and navigate to [localhost:8080](localhost:8080)
## Useful Commands
- `npm init wasm-app www` to get started. (must input name of the project)
- `npm install` in **www** directory to install all of the depedencies. Any update to the package.json requires an npm install.
- `npm run start` inside of the **www** directory to get the web server running.
- `wasm-pack build` inside the route directory to rebuild the Rust and update the **pkg** files