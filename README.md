# homebrew-tap

Homebrew tap for CLI tools.

```sh
brew install litebitus/tap/<tool>
```

| Tool | Install | Is |
|---|---|---|
| [tfgen](https://github.com/litebitus/yaml-dsl-terraform-generator) | `brew install litebitus/tap/tfgen` | a YAML DSL over Terraform |

A tool's shell completion is installed with it. For zsh, Homebrew's completion directory goes in `fpath` before `compinit`, in `~/.zshrc`:

```zsh
fpath=(/opt/homebrew/share/zsh/site-functions $fpath)
autoload -Uz compinit && compinit
```

`brew upgrade` takes each tool to its latest release.

The casks are written by each tool's release; edit them in the tool's repo, not here.
