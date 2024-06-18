# composite-action-sample-python

the `action.yml` calls the `main.py` using the `${{ github.action_path }}` env variable

this allows you to build/test/debug the "logic" of the Action natively and locally with Python

Can simply run the `main.py` like:

```sh
python3 main.py <directory-input> <token-input>
```
