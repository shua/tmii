# A tmux based frontend for ii

multitail probably would have been a better choice...

# Install

configuration is some vars at the top of tmii

    TCONF=~/.config/tmux_tmii.conf  # path to tmux_tmii.conf for custom key-binds
    IRCPATH=~/irc               # path to ii working directory, why change default?
    HINICKS="shuall_ shuall"    # "nick" will highlight "nick:" "nick     :" "nick :" etc
    HILIGHT=""                  # "word" will highlight all occurances of "word"

    # internal vars
    TSES="irc"      # tmux session name, change to something unique if you already use irc
    SNONE="(none)"  # option text for no channel in channel selection (attach to server)

custom keybinds added for comfort in tmux_tmii.conf

