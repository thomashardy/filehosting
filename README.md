# filehosting

A simple, minimalist, personal file/image hosting script

This is a fork of [*filehosting*](https://sebsauvage.net/wiki/doku.php?id=php:filehosting), a tool originally developed by [Sebsauvage](https://github.com/sebsauvage).

Here is a copy of the description:

> ### Presentation
> I'm tired of image hosting services. Sites like imageshack.us are riddled with advertising. Sites like *imgur.com* delete images with no warning (Yes, it has
> happened to me several times). And some of them even want to sign-up for “premium” accounts ? WTF ?
> 
> I decided to create my own, minimalist image hosting script for my own website. In fact, this script can be used to upload & host any kind of file.
> 
> This is very simple.
> 
> - Only you can upload files (using the password)
> - Anybody can see the images or download the files.
> 
> ### Instructions
> 
> 1. Save the following script as `upload.php`.
> 2. Change the password `($PASSWORD='toto';)`
> 3. Put the file in the root of your website.
> 4. Enjoy !
>
> Files will be saved in the files subdirectory. You can change the directory name in the source ($SUBDIR='files').
> 
> Please note that you are limited by the php upload file size limit (see php.ini) and the maximum POST size accepted by Apache (see you apache configuration). > You can use `phpinfo()` to find this limit `(Search for post_max_size and upload_max_filesize)`.
> 
> #### Version history
>
> - 0.1 : First version.
> - 0.2 : Moved php script out of the data directory. Added proper htaccess file for better security (prevent execution of uploaded files such as .php).
> - 0.3 : Accessing the data directory now redirects to the upload script.
> - 0.4 : Added a sleep() to reduce brute-force attack effectiveness.
> - 0.5 : Path correction (thanks to Elouan Pignet)
>
> #### Screenshots
> 
> ![Screenshot 1](https://sebsauvage.net/wiki/lib/exe/fetch.php?media=php:filehosting_1.png)
> 
> ![Screenshot 2](https://sebsauvage.net/wiki/lib/exe/fetch.php?media=php:filehosting_2.png)

Source: https://sebsauvage.net/wiki/doku.php?id=php:filehosting
