# Deutschland (Germany)

## What's `football.db`?

A free open public domain football (soccer) database & schema
for use in any (programming) language
(e.g. uses plain text fixtures/data sets).
More [`football.db` Project Site »](http://openfootball.github.io)

## Intro

Free open public domain football data for Deutschland (Germany) / Europe. Events include:

| Level |                                |            |
| ----- | ------------------------------ | ---------- |
| I     |  Deutsche Bundesliga           |  18 Clubs  |
| II    |  Deutsche 2. Bundesliga        |  18 Clubs  |
| III   |  Deutsche 3. Liga              |  20 Clubs  |
|       |
| Cup   |  DFB Pokal (Cup) |


Example:

~~~
### Deutsche Bundesliga Teams

bayern,      FC Bayern München|Bayern München,    FCB, city:muenchen
dortmund,    Borussia Dortmund|Bor. Dortmund,     BVB, city:dortmund
...
~~~

~~~
### Deutsche Bundesliga 2013/14

1. Spieltag

Fr, 09.08.2013 20:30  Bayern München  Bor. Mönchengladbach
Sa, 10.08.2013 00:00  FC Augsburg     Borussia Dortmund
...
~~~


## Build Your Own `football.db` Copy

To build your own `football.db` copy from the plain text fixtures
use the sportdb command line tool. Example:

Step 1:  Get a copy of the `world.db` fixtures

    $ git clone git://github.com/geraldb/world.db.git

Step 2:  Get a copy the `de-deutschland` fixtures

    $ git clone git://github.com/openfootball/de-deutschland.git

Step 3:  Let's build the `football.db`

    $ sportdb setup --include ./de-deutschland --worldinclude ./world.db

That's it. For more
see the [`sportdb` command line tool project](https://github.com/geraldb/sport.db.ruby).


## Links


### Web Admin App

Try the `football.db` Web Admin app running on Heroku
[`footballdb.herokuapp.com/de`](http://footballdb.herokuapp.com/de).

### Deutsche Bundesliga

Official Site - [`bundesliga.de` (de)](http://bundesliga.de)

- 18 Teams
- 306 + 2 Relegationsspiele

#### Wikipedia

- [Fußball-Bundesliga_2012/13 (de)](http://de.wikipedia.org/wiki/Fußball-Bundesliga_2012/13)
- [Fußball-Bundesliga_2013/14 (de)](http://de.wikipedia.org/wiki/Fußball-Bundesliga_2013/14)


### Deutsche 2. Bundesliga

Official Site - [`www.bundesliga.de/de/liga2` (de)](http://www.bundesliga.de/de/liga2)



#### Wikipedia

- [2._Fußball-Bundesliga_2012/13 (de)](http://de.wikipedia.org/wiki/2._Fußball-Bundesliga_2012/13)
- [2._Fußball-Bundesliga_2013/14 (de)](http://de.wikipedia.org/wiki/2._Fußball-Bundesliga_2013/14)


### Deutsche 3. Liga

#### Wikipedia

- [3._Fußball-Liga_2013/14 (de)](http://de.wikipedia.org/wiki/3._Fußball-Liga_2013/14)


### DFB Pokal (Cup)

- 64 Teams
- 63 Spiele

#### Wikipedia

- [DFB-Pokal_2012/13 (de)](http://de.wikipedia.org/wiki/DFB-Pokal_2012/13)
- [DFB-Pokal_2013/14 (de)](http://de.wikipedia.org/wiki/DFB-Pokal_2013/14)



### Wikipedia

- [German_football_league_system](http://en.wikipedia.org/wiki/German_football_league_system)


### Sports Newspapers

- Kicker (2x week)
- Sport Bild (1x week)



## Questions? Comments?

Send them along to the
[Open Sports & Friends Forum/Mailing List](http://groups.google.com/group/opensport).
Thanks!