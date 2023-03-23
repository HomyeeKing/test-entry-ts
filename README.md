# what
to reproduce how `--moduleResolution nodenext`  affect `/// <reference />`

# steps
- pnpm i 
- change `tsconfig > compilerOptions > moduleResolutino` to `nodenext`
- `src/index.tsx` will emit error

