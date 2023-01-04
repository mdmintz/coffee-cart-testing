# coffee-cart-testing

Test the Coffee Cart App at https://seleniumbase.io/coffee/

1. Install dependencies:

```bash
pip install -U seleniumbase
```

2. Run the script with ``pytest``:

```bash
pytest test_coffee_cart.py --demo
```

<p>(<code>--demo</code> mode slows down tests and highlights actions)</p>

<p align="left"><a href="https://seleniumbase.io/coffee/" target="_blank"><img src="https://seleniumbase.github.io/cdn/gif/coffee_cart.gif" width="480" alt="SeleniumBase Coffee Cart Test" title="SeleniumBase Coffee Cart Test" /></a></p>

3. To run that faster, remove ``--demo``:

```bash
pytest test_coffee_cart.py
```

4. For more Coffee Cart tests, run:

```bash
pytest coffee_cart_tests.py
```
