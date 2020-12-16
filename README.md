# Dotfiles

Uses [chezmoi](https://github.com/twpayne/chezmoi)

## Using chezmoi across multiple machines

Setup chezmoi on a second machine:

```bash
chezmoi init https://github.com/username/dotfiles.git
```

This will check out the repo and any submodules and optionally create a chezmoi config file for you. It won't make any changes to your home directory until you run:

```bash
chezmoi apply
```

On any machine, you can pull and apply the latest changes from your repo with:

```bash
chezmoi update
```
