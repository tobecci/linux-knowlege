# Use the below command to create a new terminal session that can be pushed to the background #

screen -S desired_session_name

# note: session name can be skipped, use the below to list all sessions

screen -ls

# use the below to resume a session

screen -r session_id or session_name

# use the below commands to exit a session #

exit or use Ctrl+A and press K

## note: screen must be installed first ##

# Debian based: sudo apt install screen
# Arch base: sudo pacman -Sy screen
# Redhat: sudo dnf install screen
