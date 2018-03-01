# Aardwolf Plugins

### training_extended.xml (replaced: practice_all.xml)
```
Allow you to train in the following ways:

  xtrain all             - Trains all stats 1 time
  xtrain # all           - Train all stats # of times
  xtrain str dex luck    - Train specific starts once
  xtrain # str dex luck  - Train specific starts # of times
  xtrain sdl             - Train specifc stats using short code (s)tr, (i)nt, (w)is, (d)ex, (c)con, (l)uck one time
  xtrain # sdl           - Train specifc stats using short code (s)tr, (i)nt, (w)is, (d)ex, (c)con, (l)uck # of times
  xtrain ssddllc         - Same as above, but lets multiple stats in a short way
  xtrain max str         - Train str to max
  xtrain max str dex     - Max can take multiple stats
  xtrain max sdl         - And short versions as well
  xprac all              - Practices all available skills/spells

Suggested alias: #alias {tra *} {xtrain %1}

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
