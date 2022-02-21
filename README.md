# horas -- A python program to print the hours according to the ancients' conception of time

In the ancient and medieval ages, time was measured differently than it is today. Instead of each hour being a strict and unchanging quantity of time, the daylight of each day was split into twelve hours of equal length, regardless of how much actual daylight there would be. Hence the "hours" in winter would be shorter (at the time of this writing in Minnesota, 54 minutes) and the summer hours longer (up to about 1 hour and 18 minutes in Minnesota). This is the meaning of the sayings often found in the Bible and other antique texts, e.g. "it was the third hour," or, "when the ninth hour had passed ... ". The third hour means that one-quarter of today's daylight has passed; the sixth hour, one-half, etc.
This program was written to easily calculate the "clock-times" of the hours according to this classical method of timekeeping, by downloading, extracting and caching the sunrise and sunset times for the month and providing a simple text-based interface to access the needed values.

## Usage

```

    Usage: horas [flags]
        -h    show this help message and exit
        -n    show when the noonday devil attacks today, i.e. from the
              fourth hour to the eighth hour
        -s    print only sunrise and sunset times for today
        -t    print only the dawn and dusk times for today
        -c    print the times of dawn and all twelve hours for today
        -p    print today's prayer hours (Lauds, Prime, Terce, etc.)
        -a    print everything for today. This is the default
        -w    print times in 12-hour time instead of 24-hour
              If any argument except -h or -w is capitalized,
              data for the whole month will be returned

```
## License

The script is in the public domain.
