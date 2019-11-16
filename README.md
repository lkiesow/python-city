python-city
===========

[![MIT license](https://img.shields.io/github/license/elan-ev/opencast-studio)
](https://github.com/elan-ev/opencast-studio/blob/master/LICENSE)

Python package containing list of world and mega cities


Example
-------

```python                                                                                                                                                                                     (git)-[master] [0]
>>> from city import fields, worldcities
>>> for k, v in zip(fields, worldcities[10]):
...     print(k, v)
...
name Milan
asciiname Milan
country Italy
countrycode ITA
latitude 45.4699751984
longitude 9.20500890976
elevation 120.0
timezone Europe/Rome
```


Data Source
-----------

This package is based on data from Natural Earth, a public domain map dataset.

[<img alt="Made with Natural Earth."
      src="https://www.naturalearthdata.com/wp-content/uploads/2009/08/NEV-Logo-Black.png"
		width="200" />
](https://naturalearthdata.com)
