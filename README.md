# Espi's TypeScript Template

Template repository for my TypeScript projects.

This is meant as quick-and-easy way for me to quickly get started with any TypeScript projects, but you're free to use it!

# Notes

- I use [pnpm][pnpm] for any projects I have control over.

  - If you use Yarn or NPM, comment the gitignored lockfiles in .gitignore and add pnpm-lock.yaml

- My configs are _extremely_ strict with the exception of a few annoying errors

  - You will probably want to pull your hair out if you've never used them

- Consider using [TOML][toml] as an application config format

  - You will need to add [another dependency][toml-npm], but it's well worth it.

- You can use [My Eslint Config][eslint] directly if you really want to

# License

[MIT][license]

[pnpm]: https://pnpm.io/ "PNPM's Website"
[toml]: https://toml.io/ "TOML Specification"
[eslint]: https://github.com/sysdotini/eslint-config "My Eslint config"
[toml-npm]: https://github.com/iarna/iarna-toml "The TOML dependency I suggest using"
[license]: LICENSE "Licensed under the MIT license"
