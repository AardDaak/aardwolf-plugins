# Aardwolf Plugins

### training_extended.xml (replaced: practice_all.xml)
```
Allow you to train in the following ways:

  dtrain all             - Trains all stats 1 time
  dtrain # all           - Train all stats # of times
  dtrain str dex luck    - Train specific starts once
  dtrain # str dex luck  - Train specific starts # of times
  dtrain sdl             - Train specifc stats using short code (s)tr, (i)nt, (w)is, (d)ex, (c)con, (l)uck one time
  dtrain # sdl           - Train specifc stats using short code (s)tr, (i)nt, (w)is, (d)ex, (c)con, (l)uck # of times
  dtrain ssddllc         - Same as above, but lets multiple stats in a short way
  dtrain max str         - Train str to max
  dtrain max str dex     - Max can take multiple stats
  dtrain max sdl         - And short versions as well
  dprac all              - Practices all available skills/spells

Suggested alias: #alias {tra *} {dtrain %1}

Passing any unmatched parameters to in-game train command.
```

### tier_who.xml
```
Help for Daak's tier who:

  twho <params>: For valid params, see: help who
  twho help : You're looking at it
```

### Daak_Slot_Tracker.xml
```
Help for Daak's Slot Tracker:

  dslot status  : Show your spins and winnings/losings
  dslot reset   : Reset the spins/amounts
  dslot help    : You're looking at it
```

### StatMonitor.xml
```
Copy over Bast's StatMonitor.xml
 - Adds levelstats to: statmn report <duration>
 - Includes levels, trains, trains per level, hp, mv, mp
```
