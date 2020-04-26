# Info
    Usage: parsesudoers -u user
           parsesudoers -u user1,user2
           parsesudoers -u user1 -u user2
           parsesudoers -u user -f file
           parsesudoers -u user [-deFPp]
           parsesudoers -a
           parsesudoers -h
           parsesudoers -V
    
    Parses sudoers file and expands aliases and groups for given users to determine who and what can run commands as that user.
    
    Arguments:
     -a, --all              match all sudoers rules
     -d, --debug            print debugging information
     -e, --expand-group     expand group names into member lists
     -f, --file             path to sudoers file
     -F, --fqdn             prefix fully qualified hostname
     -H, --human-readable   will not expand groups and prints commands on several lines
     -h, --help             print this help and exit
     -P, --prefix-text      prefix arbitrary text
     -p, --prefix-user      prefix query user
     -u, --user             user(s) to query
     -V, --version          output version information and exit
    
    Report bugs to <david@soinkleined.com>
     

## Acknowledgments


