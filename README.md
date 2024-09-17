# Deutschland (Germany) - Deutsche Bundesliga, DFB Pokal

## What's `football.db`?

A free open public domain football database & schema
for use in any (programming) language (e.g. uses plain text datasets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for Deutschland (Germany).
National club leagues and cup tournaments include:

| Level |                                |            |
| ----- | ------------------------------ | ---------- |
| I     |  Deutsche Bundesliga           |  18 Clubs  |
| II    |  Deutsche 2. Bundesliga        |  18 Clubs  |
| III   |  Deutsche 3. Liga              |  20 Clubs  |
|       |
| Cup   |  DFB Pokal (Cup) |



Example:

```
= Deutsche Bundesliga

1. Spieltag

[Fr 22.8.]
  20.30  Bayern München        -  VfL Wolfsburg
[Sa 23.8.]
  15.30  1899 Hoffenheim       -  FC Augsburg
  15.30  Hannover 96           -  FC Schalke 04
  15.30  Hertha BSC            -  Werder Bremen
  15.30  Eintracht Frankfurt   -  SC Freiburg
  15.30  1. FC Köln            -  Hamburger SV
  18.30  Borussia Dortmund     -  Bayer Leverkusen
[So 24.8.]
  15.30  SC Paderborn 07       -  1. FSV Mainz 05
  17.30  Bor. Mönchengladbach  -  VfB Stuttgart
...
```

```
= Bayern München

 1  Manuel Neuer                GK  2011-
22  Tom Starke                  GK  2012-

 4  Dante   (BRA)               DF  2012-
13  Rafinha (BRA)               DF  2011-
17  Jérôme Boateng              DF  2011-
18  Juan Bernat (ESP)           DF  2014-
21 (c) Philipp Lahm             DF  1995-
26  Diego Contento (ITA)        DF  1995-
27  David Alaba (AUT)           DF  2008-
28  Holger Badstuber            DF  2002-

 6  Thiago Alcántara (ESP/BRA)  MF  2013-
 7  Franck Ribéry    (FRA)      MF  2007-
 8  Javi Martínez    (ESP)      MF  2012-
10  Arjen Robben     (NED)      MF  2009-
11  Xherdan Shaqiri  (SUI)      MF  2012-
19  Mario Götze                 MF  2013-
20  Sebastian Rode              MF  2014-
23  Mitchell Weiser             MF  2012-
31  Bastian Schweinsteiger      MF  1998-
34  Pierre Emile Højbjerg (DEN/FRA)  MF  2012-

 9  Robert Lewandowski (POL)    FW  2014-
14  Claudio Pizarro (PER)       FW  2012-
25  Thomas Müller               FW  2000-
```


## Build Your Own `deutschland.db` Copy

Use the `sportdb` command line tool to build your own `deutschland.db` copy
from the plain text datasets. [More »](https://github.com/openfootball/datafile)


### Alternative I - Use the Quick Starter Templates

Use the quick starter datafile templates to start from scratch. Examples:

Build the database for all German clubs, leagues and seasons:

    $ sportdb new de

Build the database for the 2020/21 season:

    $ sportdb new de2020-21

[More »](https://github.com/openfootball/quick-starter)



### Alternative II - Do-It-Yourself (DIY) - Downlad and Unpack Zip Archive or Git Clone

Download and unpack the zip archive with the datasets or if you have git installed use the `git clone` command to
get a local copy.

Try in your working folder (that is, `/deutschland`):

```
$ sportdb build
$ sportdb --verbose build     # or for more (verbose) details incl. debug info
```

This will

- setup a new single-file SQLite database e.g. `./sport.db` and
- read in all datasets in plain text (`.txt`)

That's it.




## License

The football.db schema, data and scripts are dedicated to the public domain. Use it as you please with no restrictions whatsoever.



## Questions? Comments?

Yes, you can. More than welcome.
See [Help & Support »](https://github.com/openfootball/help)

