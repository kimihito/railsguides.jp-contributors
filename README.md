# Rails Contributors

This is the application behind https://contributors.railsguides.jp/.

## Ruby

Needs Ruby 2.2.7.

## System dependencies

PostgreSQL, and rugged dependencies.

In Ubuntu:

```
# PostgreSQL
sudo apt-get install postgresql postgresql-contrib libpq-dev

# rugged dependencies
sudo apt-get install cmake libgit2-0 libgit2-dev
```

## How to run the tests

Use the setup script to configure your application to be able to run the tests:

```
bin/setup
```

After this you can use the Rails rake tasks:

```
bin/rails test
```

## License

Forked from [fxn/rails-contributors](https://github.com/fxn/rails-contributors), Copyright (c) 2012–<i>ω</i> Xavier Noria.

Customized for [railsguides.jp](https://railsguides.jp/), released under the MIT License &copy; 2017 [YassLab](https://yasslab.jp).

[![YassLab Logo](https://yasslab.jp/img/logo_800x200.png)](https://yasslab.jp/)
