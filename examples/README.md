# Examples

All the examples currently correspond reimplementation of samples from [htmx.org](https://htmx.org/examples/lazy-load/).

## Running

Make sure you are using Python 3.12+ and have Ludic and Uvicorn installed:

```bash
pip install "ludic[full]"
pip install uvicorn
```

Now you can run any example with the following command (you must run the command from the root of the repository):

```bash
uvicorn examples.<name_of_example>:app --reload
```

Visit `http://127.0.0.1:8000` in your browser to see the example.
