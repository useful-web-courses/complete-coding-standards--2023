# File naming

Rules:
- Only lower case letters
- If longer than one word add dash (-) wherever a space would be

Examples:
- index.php
- url-parser.php


# Code structure

Rules for every file:
- Should have a namespace (except for index.php where the autoloader is initialised)
- Strict type checking should be enabled
- No functional code should be written, all class based
- Primitive types (string, int, float, ...) are only allowed to be used for "Value objects", for example: personal_number class
- All classes should have interfaces
- If no values are sent to the constructor of a class, the class should only have static methods

---


# Example (code)

```HTML
<?php

declare(strict_types=1);

namespace templating\data_builder;

class FormData {
    
}

```


# Example (graphic)
![Graphic explaining php structure](/media/images/php.jpg)
