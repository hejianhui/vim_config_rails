# vim_config_rails
the .vimrc file in the repo is my vim config for coding rails

I use ctags in rails projects.

the command below will generate tags for a rails project and the gems invloved in that project.
```bash
ctags -R --languages=ruby --exclude=.git --exclude=log . $(bundle list --paths)
```
