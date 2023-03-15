# Git

A zero-dependency, isomorphic Git API, tree-shaken from [Isomorphic Git](https://isomorphic-git.org).

```shell
npm install @jsxtools/git
```

```js
import * as git from '@jsxtools/git'

// import * as fs from 'node:fs' // or... fs = new LightningFS('fs')
// dir = '/tutorial'

await git.add({ fs, dir, filepath: 'README.md' })
await git.status({ fs, dir, filepath: 'README.md' })
```
