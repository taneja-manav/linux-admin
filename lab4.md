Create the /home/consultants directory. 
Add write permission to the consultants group. Use the 
symbolic method for setting the appropriate permissions.  
Forbid others from accessing files in 
the /home/consultants directory. Use the octal method for 
setting the appropriate permissions. 

implementation
----------------------------------------------

mkdir  -p home/consultants
sudo chmod g+w consultants
sudo chmod 770 consultants
ls -ld

![WhatsApp Image 2025-03-19 at 18 26 55_1cd48cfc](https://github.com/user-attachments/assets/82c2df10-54fc-4167-a513-7da00dd98311)


![WhatsApp Image 2025-03-19 at 18 30 52_54cb9ac0](https://github.com/user-attachments/assets/10c6d507-473d-4ff6-852c-217ed0d345c3)



