# tzlocale-data
A list of hopefully correct linux locales paired with specific time zones. To be used in bash scripting to set locale based on chosen time zone. Please contribure if you have time!

List of time zones: 

    awk '/\// {print $3}' /usr/share/zoneinfo/zone.tab | sort -ud 

List of locales: /etc/locale.gen

Resources:

https://docs.moodle.org/dev/Table_of_locales

