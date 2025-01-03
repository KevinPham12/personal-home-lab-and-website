# Setup Guide

## Step 1: Install Ubuntu Using the Ubuntu App on Windows
1. Open the Microsoft Store on your Windows system.
2. Search for "Ubuntu" in the search bar.
3. Select the official Ubuntu app and click "Get" to install it.
4. Once installed, launch the Ubuntu app from the Start menu.
5. Follow the on-screen instructions to set up Ubuntu:
   - Create a username and password for your Ubuntu environment.

## Step 2: Initial System Update  
1. Log into Ubuntu with the username and password you created.
2. Run the following commands to update the system:
    sudo apt update
    sudo apt upgrade
## Step 3: Install and Configure Apache on WSL
1. Run the following command to install Apache:
    sudo apt install apache2
2. Start Apache manually using the following command:
    sudo apache2ctl start
3. Verify the Apache installation by visiting `http://localhost` or `http://127.0.0.1`. 
    - A default Apache page should appear ("It works!").
4. To stop Apache, use the following command:
    sudo apache2ctl stop

## Step 4: Website Development
1. coming soon!