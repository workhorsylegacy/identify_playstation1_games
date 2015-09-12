identify_playstation1_games
==========

A module for identifying Sony Playstation 1 games with Python 2 &amp; 3

Works with CD ISO, and Binary files.

WARNING!!!! This is project is new, and does not work yet!


Example use:
-----
~~~python

from identify_playstation1_games import *

info = get_playstation1_game_info("C:/Users/matt/Desktop/ps1/Castlevania - Symphony of The Night/castlevania_sotn.bin")
print(info['serial_number'])
print(info['region'])
print(info['disc_type'])
print(info['title'])


# outputs:
# "???"
# "USA"
# "Binary"
# u"Castlevania - Symphony of The Night"
~~~


