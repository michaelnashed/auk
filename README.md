# AUK; Archives Unleashed Cloud
[![Build Status](https://travis-ci.org/archivesunleashed/auk.svg?branch=master)](https://travis-ci.org/archivesunleashed/auk)
[![codecov](https://codecov.io/gh/archivesunleashed/auk/branch/master/graph/badge.svg)](https://codecov.io/gh/archivesunleashed/auk)
[![Contribution Guidelines](http://img.shields.io/badge/CONTRIBUTING-Guidelines-blue.svg)](./CONTRIBUTING.md)
[![LICENSE](https://img.shields.io/badge/license-Apache-blue.svg?style=flat-square)](./LICENSE.txt)

![King Auk](https://camo.githubusercontent.com/148a43ac461f352346f8cd894af8bb5845a831fb/68747470733a2f2f7777772e6f6c64626f6f6b696c6c757374726174696f6e732e636f6d2f77702d636f6e74656e742f686967682d7265732f313836372f6772616e6476696c6c652d61756b2d313630302e6a7067)

Rails application for the Archives Unleashed Cloud.

## Requirements

* [Ruby](https://www.ruby-lang.org/en/) 2.2 or later
* [Rails](http://rubyonrails.org) 5.1.2 or later

## Installation

### Run the test suite

Ensure Rails is _not_ running (ports 3000), then:

```sh
$ bundle exec rake
```

### Run a development server

```sh
$ rails s
```

Then visit http://localhost:3000.

**N.B.** This application makes use of the [dotenv-rails](https://github.com/bkeepers/dotenv) gem. You will need a `.env` file in the root of the application with `TWITTER_KEY`, `TWITTER_SECRET`, `GITHUB_KEY`, and `GITHUB_SECRET` set in order to login. You will also need a 32bit `WASAPI_KEY` declared in that file for Archive-It credential encryption.

### Run a console

You can also run `bin/console` for an interactive prompt that will allow you to experiment.

## Contributing

Please see [contributing guidelines](https://github.com/archivesunleashed/auk/blob/master/CONTRIBUTING.md) for details.
* [Bug reports](https://github.com/archivesunleashed/auk/issues)
* [Pull requests](https://github.com/archivesunleashed/auk/pulls) are welcome on AUK

## License

This application is available as open source under the terms of the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Acknowledgments

This work is primarily supported by the [Andrew W. Mellon Foundation](https://uwaterloo.ca/arts/news/multidisciplinary-project-will-help-historians-unlock). Any opinions, findings, and conclusions or recommendations expressed are those of the researchers and do not necessarily reflect the views of the sponsors.
