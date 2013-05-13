Presentation
============

A Thor script to setup Beamer presentations from templates.

**Disclaimer**: this is a [readme-driven][readme-driven-development] project, while contributions are welcome in the code, they are even more welcome in the README! On the other hand, some feature may be described in the README which are not yet available, don't hesitate to [ask][ask].

  [readme-driven-development]: http://tom.preston-werner.com/2010/08/23/readme-driven-development.html
  [ask]: https://github.com/gonzalo-bulnes/presentation/issues

Setup
-----

```bash
git clone git://github.com/gonzalo-bulnes/presentation.git
cd presentation
# trust the .rvmrc file so RVM can create a new gemset for you
bundle install
thor install presentation

# now you can use presentation from any directory
cd ~
thor presentation # display some help
```

Usage
-----

```bash
# create a new presentation providing its title
thor presentation new "Free Software to Develop Free Robotics"

# see inline help for options
thor presentation help
```

License
-------

    Presentation
    Copyright (C) 2013 Gonzalo Bulnes Guilpain

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.
