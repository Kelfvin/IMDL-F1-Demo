# A demonstration for Controversial $F_1$ Metrics

This demonstration was created for evaluation metrics in the field of forged image localization to evaluate the reasonableness of various rating methods. 

## Usage

### environment

we recommend using the uv to create a virtual environment and manage the dependencies. 

1. Install uv

on ubuntu:

```shell
sudo apt install pipx
pipx install uv
```

on windows:

```shell
scoop install pipx
pipx install uv
```

2. use uv to get the environment

```shell
uv sync
```

3. open the `main.ipynb` file in Jupyter Notebook and run the code.

you need to select the .venv kernel in Jupyter Notebook.


## Results

| ID  | Method            | F1 score |
| :-- | :---------------- | :------- |
| 1   | binary_common     | 0.84     |
| 2   | macro_common      | 0.92     |
| 3   | binary_black      | 0        |
| 4   | macro_black       | 0.49     |
| 5   | binary_no_overlap | 0        |
| 6   | macro_no_overlap  | 0.47     |


## License

This project is licensed under the MIT License.