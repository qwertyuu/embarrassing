# Embarrassing

[![PyPI version](https://badge.fury.io/py/embarrassing.svg)](https://badge.fury.io/py/embarrassing)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A package to embarrassingly parallelize your code.

## Installation

You can install embarrassing using pip:

```shell
pip install embarrassing
```

## Usage

```python
from embarrassing import embarrassing

# Define your callback function
def my_callback(item):
    # Perform some operations on the item
    return result

# List of contents to process
contents = [...]

# Process the contents using the embarrassing function
results = embarrassing(contents, my_callback)

# Print the results
for result in results:
    print(result)
```

## To Deploy

`python setup.py sdist bdist_wheel`

`twine upload dist/*`

## LICENSE

This project is licensed under the MIT License.

Feel free to modify and expand this template to provide more information about your package, its features, installation instructions, and how to use it. Replace "my_package" with the actual name of your package throughout the README.md file.

Ensure that you have a LICENSE file in the root directory of your project, and update the `[![PyPI version](https://badge.fury.io/py/my_package.svg)](https://badge.fury.io/py/my_package)` and `[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)` badges with the appropriate links and package name.

Including a README.md file with relevant information helps users understand and effectively utilize your package.
