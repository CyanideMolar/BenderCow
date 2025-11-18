# BenderCow
Bender Bending Rodriguez, the precocious little scamp, is a role model to many.  Now you can have him insult you in your terminal.

# Installation and Use
Copy the bender.txt and *.cow files to your cowsay directory (This is usually /usr/share/cowsay/).  I use this by simply adding a line in ~/.bashrc that randomly pulls a line of text from bender.txt and outputs it using cowsay.

    shuf -n 1 '/usr/share/cowsay/bender.txt' | cowsay -f bender -W 85
<img width="637" height="409" alt="image" src="https://github.com/user-attachments/assets/70c16dad-2aef-471d-8ebf-fd8550c9d16b" />
