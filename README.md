# ppabam-check-os-ver
- Detects and outputs the os version.

```bash
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%%@@@%%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%%%##+++*###%%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#*##%#####%%%#####%%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%+**#%%#%%%%##%%%####***%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%@@@*=*##%%**%%%%##%%%%%%###***#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%-+##*#%%++#%%%%%%%%%%%%%##***+%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%#=+#**#%%%+=*#%#%%%%%%%%%%#***+++#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%@%+**+***#*=---=*##%#%##%%%%#%****++%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%**#*#**+--:::::--=**#%%#%%%%#*+****+%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%*+%%#%#+-:::...:::::=+##%%##%##*****+=@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%+@%%%#=::::.........:==+####%###**#**=#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#%@%%%+::::...........:+=**##%###***#*+*@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
@@@@@@@@@@@@@@@@@@@@@@@@@@@@@%#@@%%%-::::...........:-=*##*####**###**%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
%%%%%%%%%%%@@@@@@@@@@@@@@@@%%#%@@%%*--=====-::...::-==+*##*##*#######*%@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
***********#####%%%@@@@@@%%###%@=%%+:::::::::::.::::::=+##**#*#%##%%%*#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
++++++++++++++**##%%@@@@%###*%%@=##=::=+:##=:::.::::+=##*#**#*#%##%%%#*@@@@@@@@@@@@@@@@@@@@@@@@@@@@@
=============++**#%%@@@%%##*%%%%%+*-:::::---::..:::::::-+##***#%%#%%%%#*@@@@@@@@@@@@@@@@@@@@@@@@@@@@
++++++++=====++**#%%@@@@%###%@%%#+=-:...........::::..::-*#***#%%##%%%#+@@@@@@@@@@@@@@@@@@@@@@@@@@@@
+++++++++++=+++*##%%@@@@%%#%%%%%#*--:...........::::....:=#**#%%%%#%%%##*@@@@@@@@@@@@@@@@@@@@@@@@@@@
====+++++++=+++*##%%@@@@@#%@%%%###=-::.......:..::-:.....:+*##%%%@%#%@%#*%@@@@@@@@@@@@@@@@@@@@@@@@@@
--======+++++++*##%@@@@%%%%@%%%##%%%:::......:-:-=--:...::-+%#%%%%@%#%@%##@@@@@@@@@@@@@@@@@@@@@@@@@@
------====+++++*##%@@@%%%#%%@%%##%%%*:::........::::::::::-+#%#%%%@@##%%*#@@@@@@@@@@@@@@@@@@@@@@@@@@
------===++++++*##%@@%@%%#%%%#%=.:*%%=::::::----------:::--=#%#%%%%@@##%##%@@@@@@@@@@@@@@@@@@@@@@@@@
==-======++++++*#%%%@@%%%%#+=*%=.:+#-::::::.----====-::::-=+%%%%%%%%@%#%%#%@@@@@@@@@@@@@@@@@@@@@@@@@
+++++++++++++++*#%%%@%%%%%#::-#=..+*.:--::...::---::::::--+#%%@%@%%%%@%%%#%@@@@@@@@@@@@@@@@@@@@@@@@@
++++++++++++++**#%%%%@%%%%#:.-#-..=*.:-%+:::.......::::--+*#@@@@@%%%%%@%%%%@@@@@@@@@@@@@@@@@@@@@@@@@
++++++++++++++**#%%%%@%%%%#:.:*:..=+.:-%%=-::.....:::--++=+%@%%@@%%%%#@@%%%%%@%%%%%%%%@@@@@@@@@@@@@@
--==++++++++++**#%%%*:-%###:..*:..+:.:=%%+::-:::::--======#%%%%@@###%#%@%%%%%%%%%%%%%%%%%%%%%%%%%%%%
:::-==++++++++**##%%#-::#%*-..=:..+:.:+#%=::::::--::-----+*%%%%@##*###%*%%%%%%%%%%%%%%%%%%%%%%%%%%%%
...:-==+++++++**###%%#-.:**+..--::=:.:+%:..:::....::::--+***##%%*##%#%%#+#%%%%%%%%%%%%%%%%%%%%%%%%%%
...::-=++++++++**##%###:.:+#.....:..::**..::::..:...:::-%%#+###*%%%##%%@**#%%%%%%%%%%%%%%%%%%%%%%%%%
...::-=++++++++**#######..::....::.:::=-::::::::::..:::*#%*#%%#%%%%%#%@@%*#*#%%%%%%%%%%%%%%%%%%%%%%%
::::--==+++++++***#####++:.::.:.::::::::..:::.::::..:::#*#*%*%%%%%%%%%%@%###%#%%%%%%%%%%%%%%%%%%%%%%
-::----=+++++++**#####**%+..:::::.....::..::::::::...::+*##*#%%@%@@@%@%%%%%%#%%%####%%%%%%%%%%%%%%%%
-::----=++++++***####**###-.:::::.....::::::::::::..::.*-%#%%%@%@@@@%%%@@%%%##*+=:::-*#%%%%%%%%%%%%%
:::---=+++++++***#####*#@%=:.::::......::-::::::::::::::**%#@%%%@@@@@%%%@%#%%%##++-.-::-###%%%%%%%%%
:::--=+++++++***####**#=-=:::.:::.....::-:::::::::::::::-##%@%@%%@@@@%%@%%%#*%%###++=-:::=#%%%%%%%%%
:::-=+**+++++****=:=#*=-...::::::....::-::::::::::::::::-*###%%%%%@@@@%%%%%%#+*%%#****=:::=#%%%%%%%%
.:--++******+**=:+-::::::...:::::::::--:::::::::::::::::-+#%%##%%%@@@@@%%%@%%%*:*%%**+++--:*#####%%%
.:--+*******+*==::::::::::..::::::::--::::::::....::::::-=*%++%#%%%@@@%%%%%%%%%%++##*=+*=--.%##%####
.::-=++*****++-:::::::::::::.::::::--:::::::.......::::::-+%++**%%%%%@@@%%%%%%%%%**##+=++=-:-%######
.::--=++***+*+:.:....:::::::.:::::--:..:::...........:::::-+#+++*#%%#%%@%%%%%%%%%%####===---:+%#####
.:::-==+***++=.......:::::::.::::--:...........:::::....::-:-*++-**%%%%%%@@%%%%%%%%%*#=-=-:::-#%%%%%
.:::--=++**++-.......::::::..:::--:..........:::::::....:::::=-*+++*+%%%%%%@%@%@@%%%#*--::::::+%%%%%
.::----=++*++:......::::::..:::--:............::::::::..:...-::-++++=*%%%#%%@@%%%@%*#=-:::::::-%%%%%
..::::--==+++......:::::...::::--...............::::::....::::::=-=--=+%%%*#@%%#@@%#*--::::::::#%%%%
..::::---===+.....:::::...::::--:................::--:....::.:::---:::-=%%%+@%%*@@%##=-::::::::=%%%%
...:::---====....:::::....::::--..................:::::::::.:::::::.::--*%%#%@%%*%%##=-:::::::::%%%%
..:::---=====....::::....::::--:................::::.::::::::.::..:.:::--#%%%@%%#%%%**-:::::::::##%%
...::---=+++=....::::..::::::--...................................:..::--+%%%@%%%%%#**=:::::::::+###
....::---==+=....:::::::::::--:.................................:.::::::-=#%%%@%%%%***=-::::::::-###
.....::---===....:::::::::::---:.................................::::.::-=#%##%#####**+-:::::::::#*#
.:::::----===...:::::::::::-----:.................................::::::-*%**#%%%%##**+-:::::::::+**
:----=====+++..:::::::::::-------:...........................::.:..:::-=#%+*+#%%%%##+*=-:::::::::-++
====+++++++++::::::::::::------=-::...........................:-=-:-=+#%+=+*%%*%@#***+--:::::::::-==
==+++++++++++=::::::::::-----=-=::::.::.........................:-=++---*+*#%#%@%**=*=--::::::::::-=
==============:::::::::-----++--::::::..........................::::++==+*#%#%@%*+++==--::::::::::-=
==============-:::::::-----=++-:::::::...........................::--+***#%%%%#*+=++=---::::::::::-+
===============:::::------====-::::::::...........................::-=*****++++++++++=--:::::::::::+
================--:------=====-:::::::.............................:::-::==+-:=====++=--:::::::::::=
=-================---=++=====+=::::::::.............................:::..::::.-========--:::::::::::
-------------=-==============+-::::::::...............................:.::::.:=========--:::::::::::
----------------------------==-:::.:::.....::......................:::...::.::-========--:::::::::::
-------------------------------....................:................:....::.::-=========--::--::::::
-------------------------------............................................:.:-=========-------:-:::
-------------------------------:..................................:..........:-==========--:--::::::
-------------------------------:..............................:..::....:..:.::-----------:.:::::::::
--------------------------------:............................................:----------:.::::::::::
------------------------------:.........................................:::::-----------.:::::::::::
------------------------------..........................................:......--------.:::::::::::-
:::--------------------------.................................................::------:::::::::::---
``` 

### Use
```python
$ pip install ppabam-check-os-ver
$ python
>>> from ppabam_check_os_ver.hi import hi
>>> hi()
```

### Development environment setting
```bash
# install PDM
# git clone ...
# pdm venv create
$ source .venv/bin/activate
$ pdm install
# $ vi ...

# TEST
$ pdm install
$ pdm test
$ pip install .

$ git add <FILE_NAME>
$ git commit -a
$ git push
$ pdm publish
Username: __token__
```
