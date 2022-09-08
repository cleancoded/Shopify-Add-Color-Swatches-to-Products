# CLEANCODED Shopify Add Color Swatches to Products

Version: 1.0

Author: CLEANCODED

URI: https://cleancoded.com

## Introduction

This gem is used for importing Shopify Add Color Swatches to Products.

## Requirements

> **Rails compatibility** 
> * Use Shopify App `<= v7.2.8`

## How to use

1. Install the database
    - Create the database named "project" on Mysql Server
    - Import the project.sql into the Database "project"
    
2. Source Code Configuration
    - Extract the source.zip in your dedicated http running folder
    - Config the application path values in /application/config/config.php at Line 17, 18
	$config['base_url']    = '';   // Web Alias
	$config['app_path']    = '';   // Application Phyical Path
    
    - Config the Database connectoin in /application/config/database.php at line 51~54
	$db['default']['hostname'] = 'localhost';   // Database Host
	$db['default']['username'] = 'root';        // Database user 
	$db['default']['password'] = '';            // Database password
	$db['default']['database'] = 'project';     // Database name
	
3. Run the application on the address of "$config['base_url']" from your browser.
    
4. Login Account is 
	user name : admin
	password : admin
	
5. Manage Users
	Once you login to the dashboard you can add/delete users on "Settings->Manage User" on the top-right of the page.
    
6. Change Password
	You can change your password on the "Admin/Change Password" on the top-right of the page
	
7. Access the Short URL Management
	You can click "Short URL" on the Top menu.