# Exploit Farm #

The utility for CTF hacker competition for lauching sploits for all teams
and submitting flags.

## Prepare ##
1. Set FLAG_FORMAT regexp in flag_format.py
2. Set TEAMS in team_list.py
3. Edit submit_flags in start_posting.py for the checking system

## Usage ##
### Starting sploit ###
    ./start_sploit.py <sploit>

Launches sploit for all teams.
Sploit should take team ip as first arg. Its output should contain flags.
Flags will be saved in **flags/\<sploit\_name\>\_\<team\_name\>.txt**

### Starting poster ###
    ./start_posting.py

Posts the flags in flags\*.txt to checking system.
Saves posted flags in **posted_good_flags.txt** and **posted_bad_flags.txt**.
