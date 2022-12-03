# brunau-traffic

View data here:
https://lite.datasette.io/?url=https%3A%2F%2Fraw.githubusercontent.com%2Fdarndt%2Fbrunau-traffic%2Fmain%2Ftraffic.db#/traffic?sql=select%0A++++commits.commit_at+as+t%2C%0A++++duration_in_traffic+%2F+60+as+mins_in_traffic%0A++from%0A++++item_version%0A++++join+commits+on+item_version._commit+%3D+commits.id%0A++order+by%0A++++commits.commit_at
