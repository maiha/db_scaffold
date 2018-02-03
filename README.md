# db_scaffold

DB Scaffold is an Amber plugin utility to generate scaffolding from an existing database.  The goal is to simplify the the development of Amber applications.

## Installation

Add this to your application's `shard.yml`:

```yaml
target:
  db_scaffold: lib/db_scaffold/src/db_scaffold.cr

dependencies:
  db_scaffold:
    github: drujensen/db_scaffold
```

## Usage

```crystal
shards build db_scaffold
./bin/db_scaffold (table_name | *)
```

## Contributing

1. Fork it ( https://github.com/drujensen/db_scaffold/fork )
2. Create your feature branch (git checkout -b my-new-feature)
3. Commit your changes (git commit -am 'Add some feature')
4. Push to the branch (git push origin my-new-feature)
5. Create a new Pull Request

## Contributors

- [drujensen](https://github.com/drujensen) Dru Jensen - creator, maintainer