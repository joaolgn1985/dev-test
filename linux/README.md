
# Commands Linux Basic

1. Change the SHELL for Joao from bash to Bourne Shell 
- R. sudo chsh -s /bin/sh joao

2. Create a new environment variable called PROJECT=MERCURY and make it persistent by adding the variable to the ~/.profile
- R. export PROJECT=MERCURY and add the value to the .profile by running `echo 'export PROJECT=MERCURY' >> /home/joao/.profile`

3. Set an alias called `up` for the command `uptime` and make it persistent by adding to `~/.profile`file.
- R. `alias up=uptime` and `echo 'alias up=uptime' >> ~joao/.profile`

4. Update Joao prompt so that it displays the `date` as per the format below: Example: [Wed APr 22]joao@caleston-lp10:~$
- R. `PSI='[\d]\u@uh:\w$'` and add this to the `~/.profile` file `echo 'PSI="[/d]/u@/h: /w$"' >> ~/.profile`
