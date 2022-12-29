# How To Replicate the Project
Demo

![demo video](./screenshots/0.gif)



## Technology


- [Metamask](https://metamask.io/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Laravel](https://laravel.com/)
- [Verbwire API](https://www.verbwire.com/)
- [Xampp](https://www.apachefriends.org/index.html)
- [Composer](https://getcomposer.org/download/)
## Running the demo

Use the following steps to run this project:


## Step 1
1. Install [xampp](http://apachefriends.org/download.html) on your computer.
2. Start the xampp services (Apache, MySQL).
3. Open [localhost/phpmyadmin](http://localhost/phpmyadmin)
4. Create a database called `afromint`
5. Download this SQL file and import it into the `afromint` database.

If done correctly your file structure should look like the image below.

![MySQL database structure](https://paper-attachments.dropboxusercontent.com/s_5770B4B695BC2DB4686E7360F4E17DB3C11412DAEEE97850FD326C28EA772182_1672317867180_Screenshot+2022-12-29+134403.jpg)

## Step 2

On your workspace clone this Github project using the codes below.


    # Make sure you have the above prerequisites installed already!
    git clone https://github.com/Uhiene/AfroMint_Hackathon_Challenge.git afroMint
    cd afroMint # Navigate to the new folder.
    yarn install # Installs all the dependencies.


## Step 3
1. Install [composer](https://getcomposer.org/download/) on your computer.
2. Using your terminal navigate to the `afroMint` project folder.
3. Run `composer` update to install the `laravel`  dependencies.


## Step 4
1. Visit [verbwire](https://www.verbwire.com/) and sign up for an account.
2. On the dashboard, navigate to the API Keys tab and copy your secret Key.
3. On the Deploy tab, create a Simple NFT Contract, and copy contract address
4. Paste these two keys in your environment variable, see the step below.
## Step 5

Use the following steps to create and update your `**.env**` file.


1. Create a `.env` file at the root of your project.
2. Copy and paste the contents from [**this file**](https://github.com/Uhiene/AfroMint_Hackathon_Challenge/blob/master/.env.example) into your `.env` file
3. Replace the keys below with the ones from Verbwire.


    VERBWIRE_API_KEY=*******************************************
    VERBWIRE_CONTRACT=******************************************
    DB_CONNECTION=mysql
    DB_HOST=127.0.0.1
    DB_PORT=3306
    DB_DATABASE=afromint
    DB_USERNAME=root 
    DB_PASSWORD=''

Your database connections should remain the same unless it is secured.

## Step 6

Open two terminals on the project folder. 

On the first terminal run the code below.

    php artisan serve #terminal 1

On the second terminal run the code below.

    yarn dev #terminal 2

Copy the link on the first terminal.

![terminal 1: laravel address url](https://paper-attachments.dropboxusercontent.com/s_5770B4B695BC2DB4686E7360F4E17DB3C11412DAEEE97850FD326C28EA772182_1672319605549_Screenshot+2022-12-29+141231.jpg)



## Step 7

Open your browser and paste the address.

![AfroMint NFT](https://paper-attachments.dropboxusercontent.com/s_5770B4B695BC2DB4686E7360F4E17DB3C11412DAEEE97850FD326C28EA772182_1672323787602_Screenshot+2022-12-29+152211.jpg)



