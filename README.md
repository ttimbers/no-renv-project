## Creating an `renv` environment from scratch

What if a collaborator hasn't setup an environment for you, 
you then need to set it up yourself! 

### Let's try it out!

1. Click the green "Use this template" button in 
[this repository](https://github.com/ttimbers/no-renv-project) 
to obtain a copy of it for yourself.

2. Clone this repository to your computer using RStudio's version control tools.

3. Examine `script.r` to see what packages the project depends on.

4. Run `renv::init()` to initialize a new project-local 
environment with a private R library.

5. Put the `.Rprofile`, `renv.lock` and `renv/activate.R` files under local 
and remote version control.

Examine the `renv.lock` file - 
do the packages there match what you saw at the top of `praise-the-learn.r` - 
that's neat... How does that work???

See the [dependency discovery section of the `renv` docs](https://rstudio.github.io/renv/articles/renv.html#dependency-discovery) to find out!

## License

Software licensed under the [MIT License](https://spdx.org/licenses/MIT.html), 
non-software content licensed under the 
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0) License](https://creativecommons.org/licenses/by-nc-sa/4.0/). 
See the [license file](LICENSE.md) for more information.
