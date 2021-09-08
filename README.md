# nix-shell for Node.js

> WIP

## What is it?

A [nix-shell](https://nixos.org/manual/nix/stable/#description-13) template to set a [Node.js](https://nodejs.dev/) development environment up with [direnv](https://github.com/direnv/direnv) integration (if installed).

Built gathering inspiration from several [sources](#resources), it makes available:

- [Node.js](https://nodejs.dev/) itself
  - from [nixos.org/packages](https://search.nixos.org/packages?channel=unstable&from=0&size=50&sort=relevance&type=packages&query=nodejs)
    - in version `16_x` (currently `16.8`)
- [TypeScript Language Server](https://github.com/typescript-language-server/typescript-language-server#readme) ([LSP](https://microsoft.github.io/language-server-protocol/))
  - from [nixos.org/packages](https://search.nixos.org/packages?channel=unstable&from=0&size=50&sort=relevance&type=packages&query=tsserver)
- both tools are the installed from the `unstable` channel (latest packages available)
- [Jest](https://jestjs.io/) basic initialization (`setup` file)
  - also, some `npm` sugarness can be added

## Resources

### Direnv

- [direnv wiki page about Nix](https://github.com/direnv/direnv/wiki/Nix)
- [Automating development environment set-up with Direnv](http://www.futurile.net/2016/02/03/automating-environment-setup-with-direnv/)
- [More prac­ti­cal direnv](https://rnorth.org/more-practical-direnv/)

  - [rnorth/.direnvrc](https://gist.github.com/rnorth/0fd5048da85957da39c17bd49c4ca922)

### Miscellaneous

- [About using Nix in my development workflow - Jean-Philippe Cugnet - Medium](https://medium.com/@ejpcmac/about-using-nix-in-my-development-workflow-12422a1f2f4c)
- [A Web Developer Walks into a Nix expression...](https://dev.to/scotttrinh/a-web-developer-walks-into-a-nix-expression-2pg1)
- [mu2: 📦 A template to build javascript package with nix config that creates isolated development environment with node and yarn installed. : Nix](https://www.reddit.com/r/Nix/comments/hpqt4g/mu2_a_template_to_build_javascript_package_with/)
- [NixOS: For developers](https://myme.no/posts/2020-01-26-nixos-for-development.html)
- [myme.no - NixOS: For developers](https://myme.no/posts/2020-01-26-nixos-for-development.html)
- [O que é Nix e por que você deveria experimentar? - DEV Community](https://dev.to/mdsp9070/o-que-e-nix-e-porque-voce-deveria-experimentar-34ll)
- [Your first react project](https://dev.to/code_jedi/your-first-react-project-206n)

## TODO

- [lorri](https://github.com/nix-community/lorri) integration
- [niv](https://github.com/joefiorini/niv)
- ...
