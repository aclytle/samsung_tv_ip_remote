Emulates an IP remote for Samsung TVs. Requires python3 and websocket-client:
https://pypi.python.org/pypi/websocket-client
pip install websocket-client

Currently only tested on model UN50JU6400

Still haven't figured out how the key encoding works. Currently all I can do
is capture and replay the commands sent by the mobile app. More investigation
is required. Still a WIP.

<MTMarkdownOptions output='raw'>
Usage: samsung-client.py [ip] [command]
Available commands:
back
down
exit
ff
info
keepalive
left
menu
pause
play
poweroff
poweroff2
right
rr
search
select
shub
skipb
skipf
soft_a
soft_b
soft_c
soft_d
stop
tools
up
</MTMarkdownOptions>
