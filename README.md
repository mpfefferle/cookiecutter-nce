Cookiecutter: Network Configuration Examples
============================================

This is a cookiecutter template for defining network configuration
examples.  The examples live in this repo: https://github.com/jeremyschulman/NCE.

Prerequisites
-------------

### Cookie Cutter ###

On OS X:

```sh
brew install cookiecutter
```

Usage
-----

1. cd to the NCE repo `cd $GITHUB_HOME/NCE`
2. Run cookiecutter script `cookiecutter
   https://github.com/mpfefferle/cookiecutter-nce`
3. Fill in the prompts
    * `repo-name`: Used for both the folder name and the name of the
       script
    * `title`: Title of the example, used in the README
    * `link`: Link to source documentation
    
