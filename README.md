# Create-VM-manually-or-automatically-using-Vagrant-by-HashiCorp
## simple way to create linux machines on your local for research and development ##

1. Download and install VirtualBox from the official website: https://www.virtualbox.org/

2. Download and install Vagrant from the official website: https://www.vagrantup.com/


3. Create a new directory on your local machine where you want to store your Vagrant project
    (preferably a folder and sub-folder on your desktop).

4. Open your command-line interface (CLI) and navigate to the directory you created.

5. Run the command 'vagrant init'. 
    This will initialize a new Vagrantfile in your directory.


6. Open the Vagrantfile in a text editor(im using VScode).

    Customize the configuration according to your requirements. 
    
    For example, I used an eurolinux-centos base box. Vagrant boxes can be found [here](https://app.vagrantup.com/boxes/search):

    ![vagrant box](image.png)

    Create a private and public bridged network to allow access to the machine by simple removing the "#" infront of configurations in the image.

    ![network settings](image-1.png)

    Customize the memory and cpu size using this example 

    ![memoryandcpu](image-2.png)