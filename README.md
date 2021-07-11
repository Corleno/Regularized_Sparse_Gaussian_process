# template_paper_repo
Template repository for a repo for a paper/project (not a module/library)

## Installation
To install, you can clone the repository and `cd` into the `template_paper_repo` folder.

```bash
# use ssh
$ git clone git@github.com:BouchardLab/template_paper_repo.git
# or use https
$ git clone https://github.com/BouchardLab/template_paper_repo.git
$ cd template_paper_repo
```

If you are installing into an active conda environment, you can run

```bash
$ conda env update --file environment.yml
$ pip install -e .
```

If you are installing with `pip` you can run

```bash
$ pip install -e . -r requirements.txt
```
