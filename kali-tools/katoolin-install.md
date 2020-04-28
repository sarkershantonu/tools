# Install via katoolin in ubuntu (TODO)

# Step 1 : Preapere Ubuntu for installation

    sudo apt-get update && sudo apt-get install -y software-properties-common python git
    sudo add-apt-repository universe

# Step 2 : Get katoolin installer from Github

    git clone https://github.com/LionSec/katoolin.git
    sudo cp katoolin/katoolin.py /usr/bin/katoolin.py
    suco chmod +x /usr/bin/katoolin.py
# Step 3 : Install 
- Run Katoolin installer 

    sudo katoolin

![First Menu to choose](katoolin-1.JPG)

- From first menu, choose 1 => Add kali repositories & update , you should see this 

![Submenu of selection 1](katoolin-2.JPG)
