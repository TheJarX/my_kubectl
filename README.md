# My Kubectl

Created this script basically because had to remember some kubectl so I can work lol. Well, I'm lazy enough (and had no too much experience with kube) to code this basic script.

## Instalation
Well you could add the script to the bin folder then make some stuff with the PATH. But, let's face it, that's too much trouble (if you're lazy as I am) so let's create an alias in your `~/.bashrc` or `~/.zshrc` or whatever you have.

```
alias kb="path/to/this/repo/kb" # kb is the name of the script, so keep it
```
> Important: Give execution permissions to the script running `chmod +x path/to/kb`
and that's it! ✌🏻

## Supported commands
using this format: `kubect` -> `my_kubectl`

* `exec -it POD_ID -- bash` -> `bash POD_ID`
* `get pods` -> `pods`
* `get pods | grep Foo` -> `find_pod Foo`

> Coming soon (I mean soon, when I need to use it several times)
* `use-context` -> `ctx` (problably will need some config file, 🐻 w/ me)
