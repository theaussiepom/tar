# @theaussiepom/tar
Type definition based on a merge of `index.d.ts` files from:
* [@types/tar](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/tar)
* [minipass](https://github.com/isaacs/minipass)


See [[@types/tar] is incompatible with new minipass types](https://github.com/DefinitelyTyped/DefinitelyTyped/discussions/60901) for context and discussion.

**Only consider the appropriateness of this type definition while waiting for the *@types/tar vs minipass* conflict to be addressed.**

**Once the *@types/tar vs minipass* conflict has been addressed, use the @types/tar type definition instead.**

# Using @theaussiepom/tar type definition
1. Uninstall [@types/tar](https://github.com/DefinitelyTyped/DefinitelyTyped/tree/master/types/tar)
```
npm uninstall @types/tar
```
2. Install @theaussiepom/tar
```
npm install @theaussiepom/tar
```
3. Add `node_modules/@theaussiepom/tar` typeroot to `tsconfig.json`. You must also reference `node_modules/@types` as it will no longer be included by default (see [TypeScript typeRoots](https://www.typescriptlang.org/tsconfig#typeRoots) for further information).
```
"typeRoots": [
  "../node_modules/@theaussiepom",
  "../node_modules/@types"
]
```