Usage
=====

Installation
------------



Creating recipes
----------------

<br>

The `kind` parameter should be either `"meat"`, `"fish"`, or `"veggies"`.
Otherwise, [`get_random_ingredients`][lumache.get_random_ingredients] will raise an exception [`lumache.InvalidKindError`](/api#lumache.InvalidKindError).

For example:

```python
>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']
```
