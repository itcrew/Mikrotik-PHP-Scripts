
mktsetwg - Set up Mikrotik's Walled Garden

The parameter list is:

-r file_routers           File with the list of Mikrotik routers.
                          Each line of the file must have ip, username and password separated by space.

-h file_hosts             File with the list of hosts to setting in Mikrotik's Walled Garden. 
                          Each line of the file must have a host. 

-v                        Enable verbose ( debug )


Example:

mktsetwg -r exemplos/roteadores -h exemplos/hosts

