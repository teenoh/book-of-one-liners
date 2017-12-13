---
layout: page
title: Template
permalink: /template
---

Use the following template to create a one-liner page
```
    ---
    layout: page
    title: Swap Variables
    permalink: /Python/swap-variables
    ---

    **Python**

    Easily swap the values of two variables without using a temporary/extra variable.

    ## Init
    ```
    a, b = 5, 6
    ```

    ## One-liner
    ```
    a, b = b, a
    ```

    ## Out
    ```
    print(a, b)
    ```
```

Notes:
- Give a short and descriptive title.
- Use the permalink format: `/{language}/{title}`.
- Explain what the one-liner does and how to use it.
- Add variable initializations and/or preliminary code in the **Init** section (optional).
- Avoid boilerplate code (e.g class declarations, main methods etc) and comments as much as possible.
- The one-liner must be one line of code.
- Write prints or show code output in the **Out** section (optional).
