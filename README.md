# Checkiday sopel plugin

[![pypi status](https://img.shields.io/pypi/v/sopel-modules.checkiday.svg)](https://pypi.org/project/sopel-modules.checkiday/)
[![Build Status](https://travis-ci.org/shanedabes-sopel/sopel-checkiday.svg?branch=master)](https://travis-ci.org/shanedabes-sopel/sopel-checkiday)
[![pyup status](https://pyup.io/repos/github/shanedonohoe/poku/shield.svg)](https://pyup.io/account/repos/github/shanedabes-sopel/sopel-checkiday/)

A plugin that returns today's holidays from checkiday.com

![Screenshot](screenshot.png)

## Installation

Can be installed from the pip using:

    pip install sopel_modules.checkiday


## Testing

If you would like to make a contribution, be sure to run the included tests. Test requirements can be installed using:

    pip install -r requirements_dev.txt

run tests using:

    make test

and start up a test sopel instance with docker by using:

    docker-compose up -d
    docker attach weechat
