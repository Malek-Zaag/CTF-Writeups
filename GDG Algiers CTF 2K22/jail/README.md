# Red Diamond

<img src="https://github.com/Malek-Zaag/CTF-Writeups/blob/main/GDG%20Algiers%20CTF%202K22/jail/1.png">
This is a jail challenge so the objective is to gain access to shell , by simply reading the description we notice that the task is written
in Ruby language . By reading the documentation of Ruby, we know that by typing system(COMMAND HERE) we can run shell command from within the script .

First we run the ls command , we notice the file name flag.txt then we execute the second command cat flag.txt

<img src="https://github.com/Malek-Zaag/CTF-Writeups/blob/main/GDG%20Algiers%20CTF%202K22/jail/2.png">

And the flag was {CyberErudites{I_Th0ugh7_CAlcul4t0rs_C4n_OnlY_b3_eXploited_in_PYY}}
