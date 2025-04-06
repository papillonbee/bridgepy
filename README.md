# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgepy/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                  |    Stmts |     Miss |   Cover |   Missing |
|---------------------- | -------: | -------: | ------: | --------: |
| bridgepy/bid.py       |       28 |        5 |     82% |16, 21, 25-27 |
| bridgepy/bridge.py    |       44 |       44 |      0% |      1-56 |
| bridgepy/card.py      |       73 |        6 |     92% |28, 33, 50, 71, 76, 80 |
| bridgepy/datastore.py |       17 |       17 |      0% |      1-25 |
| bridgepy/entity.py    |        6 |        0 |    100% |           |
| bridgepy/exception.py |       80 |       12 |     85% |17, 21, 57, 61, 77, 81, 85, 89, 93, 97, 101, 105 |
| bridgepy/game.py      |      336 |      165 |     51% |21, 31-42, 45-47, 50, 53, 70-72, 86-116, 134, 177, 200, 209, 221, 225, 231, 244-250, 258, 263-273, 276-278, 285-297, 300-316, 319-323, 328-334, 342-357, 362-364, 367-370, 373-381, 384-385, 388, 391-399, 402 |
| bridgepy/player.py    |       72 |        8 |     89% |14, 17, 35, 60-61, 69-71 |
|             **TOTAL** |  **656** |  **257** | **61%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/papillonbee/bridgepy/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgepy/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/papillonbee/bridgepy/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgepy/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Fpapillonbee%2Fbridgepy%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/papillonbee/bridgepy/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.