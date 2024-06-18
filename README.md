# composite-action-sample-python

the `action.yml` calls the `logic.py` using the `${{ github.action_path }}` env variable

this allows you to build/test/debug the "logic" of the Action natively and locally with Python

Can simply run the `logic.py` like:

```sh
python3 logic.py <directory-input> <token-input>
```
