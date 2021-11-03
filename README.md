# ani-cli-fork

Fork designed to make better use of dependancies and mirrors for Arch-systems. 

    git clone https://github.com/NovaDoesBass/ani-cli-fork

    cd ani-cli

    sudo make

run ani-cli in terminal and search for anime 

Usage

watch anime

    ani-cli <query>

download anime

    ani-cli -d <query>

resume watching anime

    ani-cli -H

set video quality

    ani-cli -q 360

By default ani-cli would try to get the best video quality available
You can give specific qualities like 360/480/720/..

You can also use special names:

    best: Select the best quality available
    worst: Select the worst quality available

Multiple episodes can be viewed/downloaded by giving the episode range like so

Choose episode [1-13]: 1 6

This would open/download episodes 1 2 3 4 5 6
Dependencies

    grep
    curl
    sed
    mpv
