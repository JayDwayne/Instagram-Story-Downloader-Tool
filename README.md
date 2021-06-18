# Story Downloader
Story Downloader by Jay Dwayne
# Nairobi
# Kenya

## How to use
To use this repository, make sure you're using the same IP address that you use often for login to Instagram to avoid get Challenge from Instagram. Make sure you change **lib/config.php** with your account, database, and target. When you got a Challenge, please activate the database from the config files. So, when you do verification with email, this script will save your own cookies to your database.

Run this code below in your terminal.
```bash
chmod +x run.sh
./run.sh
php run.php
```

If you have Google Cloud Platform account, you can use it for the detection of a face from the image you get before.
Make sure you have configured the environment variable. Please check the link below for the detail.  
[Before you begin | Cloud Vision API](https://cloud.google.com/vision/docs/before-you-begin)
```bash
php checkFace.php
```

## Warning
Please don't run **composer install** or **composer update** because library mgp25 has been takedown from DMCA.
