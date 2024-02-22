# Automation Library

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Code Annotation Examples


## Code Blocks

Sample `codes`

### Plain codeblock

A plain codeblock:

```
Check Expand Button
    Check Expand Button
    ${hidden} =  get element attribute  ((//div[contains(@class,'h7')])[last()]//*[contains(@aria-label,'content')])[1]    aria-expanded
    log  ${hidden}
    IF  "${hidden}" == "false"
        Force Click  ((//div[contains(@class,'h7')])[last()]//*[contains(@aria-label,'content')])[1]
    END

```

#### Python Code

``` py
import tesorflow as tf
def testing()
```

#### With a title

``` py title="bubble_sort.py"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

#### With line numbers

``` py linenums="1"
def bubble_sort(items):
    for i in range(len(items)):
        for j in range(len(items) - 1 - i):
            if items[j] > items[j + 1]:
                items[j], items[j + 1] = items[j + 1], items[j]
```

