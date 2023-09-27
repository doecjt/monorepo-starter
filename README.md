# 🎁monorepo-starter
## Clone to local
```shell
degit doecjt/monorepo-starter
```
## CheckList
- [x] Change the information in LICENSE
- [x] Change package-name and author etc. in package.json
- [x] Change the information in README.md
## CLI
### install all dependencies
```shell
pnpm install
```
### initialize app
```shell
pnpm --filter [app-name] i
```
### install packages from workspace
```shell
pnpm --filter [app-name] add [package-name] -workspace
```
### install packages in the workspace
```shell
pnpm add [package-name] -w
```
### build all dependencies
```shell
pnpm build
```
