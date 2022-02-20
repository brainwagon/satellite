# satellite
A very simple python program using the pyephem library to predict passes of satellites

By default, it uses the name fo the satellite that you specify, and prints the next
three predicted passes as viewed from San Francisco.  It's fairly straightforward,
and so could be easily modified.

{{{
markv@legion:~$ python satellite NORBI FEES 
NORBI
+---------------------+----------+---------------------+----------+---------------------+---------+
|      Rise Time      | Rise Azi |     Transit Time    | Altitude |       Set Time      | Set Azi |
+---------------------+----------+---------------------+----------+---------------------+---------+
| 02/20/2022 01:14:32 |   24.9   | 02/20/2022 01:20:31 |   25.5   | 02/20/2022 01:26:27 |  167.0  |
| 02/20/2022 02:49:24 |  356.8   | 02/20/2022 02:55:10 |   21.7   | 02/20/2022 03:00:55 |  224.5  |
| 02/20/2022 11:59:11 |  121.1   | 02/20/2022 12:04:15 |   12.4   | 02/20/2022 12:09:22 |   10.4  |
+---------------------+----------+---------------------+----------+---------------------+---------+
FEES
+---------------------+----------+---------------------+----------+---------------------+---------+
|      Rise Time      | Rise Azi |     Transit Time    | Altitude |       Set Time      | Set Azi |
+---------------------+----------+---------------------+----------+---------------------+---------+
| 02/19/2022 21:58:28 |   43.1   | 02/19/2022 22:02:50 |    7.1   | 02/19/2022 22:07:10 |  135.6  |
| 02/19/2022 23:31:41 |    8.4   | 02/19/2022 23:37:48 |   66.2   | 02/19/2022 23:43:50 |  199.3  |
| 02/20/2022 01:08:05 |  334.0   | 02/20/2022 01:11:29 |    3.8   | 02/20/2022 01:14:52 |  265.3  |
+---------------------+----------+---------------------+----------+---------------------+---------+
}}}
