# writeapaper

This is a template repository to write scientific papers with latex. 

First pick your journal from the `template` directory and copy its content into `draft`.  A github action will compile the paper at every commit. The latest version is made available at this permanent URL

> [github.com/dgerosa/writeapaper/blob/build/draft.pdf](https://github.com/dgerosa/writeapaper/blob/build/draft.pdf)

There are two variables in `.github/workflows/writeapaper.yml` that you might want to change, which set the directory (`DIR`) and the filename (`FILE`) of the tex file you want to compile.

After you created a new repository using this template, you need to make sure GitHub actions have write permissions. Go to `Settings` / `Actions` / `General` / `Workflow permissions` and tick the box `Read and write permissions`.


TODO: 
- [x] Deploy pdf to fixed url
- [ ] Add more templates for common journals (at least those I care about)  

