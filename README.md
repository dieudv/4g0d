# 4G 0đ với Termux và SocksDroid trên Android

## Requirements

**Android:**

Download Termux and SocksDroid 

    - Termux: git
    - SocksDroid

## Install

**Open termux and run:**

    pkg install git && git clone https://github.com/dieudv/4gfree.git && clear && cd 4gfree && chmod a+x tun && chmod a+x psiphon-tunnel-core && echo 'PATH="$PATH:$HOME/4gfree"' >> $HOME/.bashrc && source $HOME/.bashrc && echo 'PATH="$PATH:$HOME/4gfree"' >> $HOME/.zshrc && source $HOME/.zshrc && clear && cd
    
## Configuration & Usage:
-----
**Android (Termux)**

### Step1 - SocksDroid Setup:
    $ DNS Server: 203.113.131.6
    $ App List: Include com.termux.
    $ Enable: Connect on Boot, Pre-app proxy, Bypass Mode.
    $ Activate SocksDroid.
    
### Step2 Termux:
    $ Execute: type `tun` and enter
    $ Enjoy!