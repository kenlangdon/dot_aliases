# dot_aliases
Repo of alias files for use with .zsh_rc or .bash_rc

## Usage
1.  Clone this repo into your home directroy.
2.  Rename the repo to .aliases
3.  Place the following block in your .zshrc file:
```
if [ -d ~/.aliases ]
  then
    for file in `ls ~/.aliases/*_aliases`
      do
        source $file
    done
fi
```
