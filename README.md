# Community Templates

A place for us to colloborate around templates & snippets for various OSes

# Repo metadata

So that the templates can eventually be updated automatically in Foreman, we are
adding metadata to the top of every template. This metadata can be read by a plugin
(such as [foreman_templates](http://github.com/GregSutcliffe/foreman_templates)) to
determine information abut the template. The metadata is read until the first non-comment
line, and contains, the template name, template kind, and any appropriate OS
associations. For example:

    #kind: provision
    #name: My Preseed
    #oses:
    #- Debian 6.0
    #- Debian 7.0

Because all the data is contained in the metadata, filenames are arbitrary, however,
for consistency we ask that they be grouped appropriately, and end in `.erb`.

Have a look around the repo for examples.

# Contributing

Please fork and send a pull request. Thanks!

# License

Copyrights are retained by their owners

This entire repository is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.