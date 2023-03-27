Civity changes:

- `ckan/cli/__init__.py`: implemented reading of multiple sections in the configuration file. Now it will read not only the `[app:main]` sections, but also any sections starting with `plugin:` which makes it possible to structure the configuration options by plugin.
