# nosleep
Mac no sleep commands


# Useful to prevent Macbooks to go to sleep when closing the lid instead of running tools that requires a Kernel Extension (e.g. InsomniaX) and more

# Before doing anything, save your current configuration using
pmset -g

# To disable sleep
sudo pmset -a sleep 0;

# To enable sleep
sudo pmset -a sleep 1;
