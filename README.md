bmosh
=====

## The Bash Mobile Shell - "Mosh Lite"

Super fast command prompt for remote shells over slow or even fast comms!

### Usage: bmosh ssh_server_name

- Provides local echo of ssh commands
- Provides a terminal, top, less etc work
- Provides remote prompt
- Works great for many tasks over slow connections like Tor Hidden Servers

### Unlike [Mosh](https://github.com/keithw/mosh):
- Uses 100% ssh and socat with their security reviews/reputation
- Uses TCP - Works great for many tasks using Tor Hidden Servers
- Is under 100 bytes of smuggler inspired genuis.

### Issues
- Confusing: Tab completion pulls results from local paths etc. 
- Rebind ctrl-c key to kill remote process and not bmosh - maybe with bash key rebinding with 'bind' or term params to readline/socat?


### If you find useful please send donations to Anarplex Bitcoin Address: Agora Anonymous: 1P6hciM8LNTJ5skarDB6CPdjZuBYA37uiT 




