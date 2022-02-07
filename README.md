# Boilerplate
**NOTE: THIS IS MY TIME WORKING WITH MONOREPO, HENCE THE CODE/CONFIG MAY NOT BE THE BEST/OPTIMIZED.**
___
### Configured With
- Lerna (Monorepo)
- Typescript
- ESLint
- Prettier
___
### Commands
Adding dependency to a package
```
lerna add dependency --scope=package
```
Adding dependency to all packages
```
lerna add dependency
```
Adding dependency to main project
```
yarn add -W dependency
```
Removing dependency
```
lerna exec -- yarn remove dependency
```
