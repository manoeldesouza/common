# common
Common command executer for multiple hosts


Version: 1.0.2

Release: 02-Feb-2020

Author: Manoel de Souza manoel.desouza@outlook.com.br


Simple unix shell script to enable a single command to be quickly executed at multiple unix hosts



USAGE:
 
    common init
    common edit
    common add_host <user>@<host>
    common run "<unix command>"


How it looks like:

    ./common run ls
    # osmc@192.168.100.32:
    Movies
    Music
    Pictures
    TV Shows

    # manoel@192.168.100.99:
    Desktop
    Documents
    Downloads
    Music
    Pictures
    Public
    Templates
    Videos

    # pi@192.168.100.30:
    Documents

    # pi@192.168.100.34:
    Desktop
    Documents
    Downloads
    MagPi
    Music
    Pictures
    Public
    Templates
    Videos
