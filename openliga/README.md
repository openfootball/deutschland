# OpenLigaDB.de Samples & How-To

(auto-)converted from openligadb.de json to Football.TXT samples

for example, see 

- <https://api.openligadb.de/getmatchdata/bl1/2026> => [2026-27_de.1.txt](2026-27_de.1.txt) & online @ [openliga_2026-27_de.1](https://openfootball.github.io/deutschland/openliga_2026-27_de.1.html)
- <https://api.openligadb.de/getmatchdata/dfb/2026> => [2026-27_de.cup.txt](2026-27_de.cup.txt) & online @ [openliga_2026-27_de.cup](https://openfootball.github.io/deutschland/openliga_2026-27_de.cup.html)

and many more



**How-to Update**

use the openliga command-line (part of the openliga gem package, see [gems/openliga](https://www.rubydoc.info/gems/openliga)). after installation try:

```
$ openliga -h                #  print help and version info
```

resulting in:

```
Usage: openliga [options] CODE
    -o, --output=PATH                write football.txt conversion to output path (default: none)
        --season=SEASON              season (default: latest)
    -m, --metal                      use openligadb.de shortcuts/codes and seasons/years (default: false)
```

how-to update / (re)generate. for the 2026/27 season try:

```
$ openliga de.1   -o openliga/2026-27_de.1.txt
$ openliga de.2   -o openliga/2026-27_de.2.txt
$ openliga de.1   -o openliga/2026-27_de.3.txt
$ openliga de.cup -o openliga/2026-27_de.cup.txt
```
