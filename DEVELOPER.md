# padeage

### Prerequisite

- Python: 3.7.16
- Jupyter Notebook: 6.4.12

### Environment

1. Install python virtual environment:

```shell
pyenv virtualenv 3.7.16 padeage_3.11.3
```

2. Activate python virtual env

```shell
pyenv activate padeage_3.7.16
```

3. Install python dependencies from requirements.txt:

```shell
pip install -r requirements.txt
```

4. Setup `pre-commit` to make hook with `.git`:

```shell
pre-commit install
pre-commit run --all-files
```

### Vim/NeoVim users:

5. Install pynvim to enable coc:

```shell
python -m pip install --upgrade pynvim
```
