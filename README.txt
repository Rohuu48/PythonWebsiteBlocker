This is a Website Bloccker program coded using Python
Works for all Operating Systems

The difference in the code for the different operating systems lies in the hosts_path variable.
For Windows Users:
hosts_path=r"C:\Windows\System32\drivers\etc\hosts"
For Mac Users:
hosts_path=/private/etc/hosts
For Linux Users:
hosts_path=r"/etc/hosts"

Update the website list with websites of your own choice and work hassle free without any distractions.
**Don't forget to run your python script from the terminal after updating

For Linux and Mac users:
You can update your website list from the terminal as well.
Go to the directory where the python file is present from your terminal. Follow it up with the command:

sudo crontab -e

You can update your list after running:
sudo nano /etc/hosts
Follow the commands for overwriting or replacing or adding and start working again!!


