# writeapaper

This is a template repository to write scientific papers with latex and git. 

A github action will compile the paper at every commit. The latest version is made available at this permanent URL

> [github.com/dgerosa/writeapaper/blob/build/draft.pdf](https://github.com/dgerosa/writeapaper/blob/build/draft.pdf)


#### Instructions: 

- Click on "use this template", top right corner. Create your repository.
- Remove the placeholders in the `draft` directory.
- Pick your journal from the `template` directory and copy its content into `draft`.
- Make sure GitHub actions have write permissions. Go to `Settings` / `Actions` / `General` / `Workflow permissions` and tick the box `Read and write permissions`.

There are two variables in `.github/workflows/writeapaper.yml` that you might want to change, which set the directory (`DIR`) and the filename (`FILE`) of the tex file you want to compile.

If you need some common journal abbreviations, you can copy `more/journals.sty` in your working directory.
