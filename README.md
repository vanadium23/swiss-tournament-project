Swiss-system Tournament Project
=============

This is second project for Full Stack Developer Nano-Degree

## Requirements
  - Vagrant
  - VirtualBox (as a provider)

## Install and usage
  - Clone this repository: `git clone https://github.com/vanadium23/swiss-tournament-project`
  - Start vagrant using `vagrant up`
  - Connect to vagrant using `vagrant ssh`
  - Go to tournament dir `cd /vagrant/tournament`
  - Run test files `python tournament_test.py`
 
After this you should see this results:

    vagrant@vagrant-ubuntu-trusty-32:/vagrant/tournament$ python tournament_test.py 
    1. Old matches can be deleted.
    2. Player records can be deleted.
    3. After deleting, countPlayers() returns zero.
    4. After registering a player, countPlayers() returns 1.
    5. Players can be registered and deleted.
    6. Newly registered players appear in the standings with no matches.
    7. After a match, players have updated standings.
    8. After one match, players with one win are paired.
    Success!  All tests pass!
  
