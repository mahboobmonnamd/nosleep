# nosleep
Mac no sleep commands


# Useful to prevent Macbooks to go to sleep when closing the lid instead of running tools that requires a Kernel Extension (e.g. InsomniaX) and more

# Before doing anything, save your current configuration using
pmset -g


<img width="435" alt="PMSet global Values" src="https://user-images.githubusercontent.com/6184262/158826433-87bea204-6cdd-4299-b12d-9fad1171d9ae.png">


# To disable sleep
sudo pmset -a sleep 1; sudo pmset -b disablesleep 0;
  
# To enable sleep
sudo pmset -a sleep 0; sudo pmset -b disablesleep 1;
