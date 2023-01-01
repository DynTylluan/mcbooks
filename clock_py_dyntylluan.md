# clock.py by DynTylluan

## About
`clock_py_dyntylluan.md`, as written by [DynTylluan](https://namemc.com/profile/DynTylluan.1), is a book that takes code directly from [TrainClock](https://github.com/oKay-S/TrainClock/blob/master/clock.py).

The book itself was found in the overworld of [mc.neozones.club](https://mc.neozones.club) at -55 / 81 / -154 on a lectern.

## Contents
```
from datetime import datetime #imports datetieme package
class Clock: #constructs the clock class
  now = 0
  def time(): #constructs the time method
    now = datetime.now()
    now = str(now)
    now = now [11:-10] #trunctuates the time out of datetime
    return now
  def date(): #constructs the date method
    today = datetime.now()
    today = str(today)
    today = today [0:10] #trunctuates the date out of datetime
    return today
```