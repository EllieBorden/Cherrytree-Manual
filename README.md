
# Cherrytree User Manual

This is the official user manual for [Cherrytree](https://www.giuspen.com/cherrytree/), a free and open source note-taking application. 

## Contributing

There are two versions of the user manual.

### Web Version

**Requirements**

- [Asciidoctor](https://asciidoctor.org/)

The web version is written using Asciidoc and is in the `master` branch. Build the static site by executing [build.sh](build.sh).

### Downloadable Version

**Requirements**

- [Cherrytree](https://www.giuspen.com/cherrytree/)

The downloadable version is a Cherrytree file and is maintained in the `ctb-download` branch.

When working on the downloadable version, export the modified Cherrytree file to HTML by executing [export.sh](export.sh).

Alternatively:

1. In the project directory, delete the `cherrytree_manual.ctb_HTML` folder.
2. In the Cherrytree file, select **Export to HTML** from the **Export** menu. 
3. Choose **All of Tree**.
4. Enable **Include Node Name** and **Links Tree in Every Page**.
5. Click **OK**.


## Related

- [Cherrytree Repository](https://github.com/giuspen/cherrytree)

## License

This program is free software; you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation; either version 3 of the License or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General
Public License for more details.

You should have received a copy of the GNU General Public License along with this program; if not, write to the Free Software Foundation, Inc., 51 Franklin Street, Fifth Floor, Boston, MA 02110-1301, USA.
