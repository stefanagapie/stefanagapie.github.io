# Examples

## Code Annotation Examples

### Codeblocks

Some `code` goes here.

### Plain codeblock

```python
import tensorflow as tf

def myfunction():
    # some comment
```

### With a title, line numbers and highlight lines 2 and 3

```python title="bubble_sort.py" linenums="1" hl_lines="2 3"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

### Icons and Emojis

:smile: :fontawesome-regular-face-laugh-wink: :octicons-heart-fill-24:{.heart}

