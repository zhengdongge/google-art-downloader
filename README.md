 # Google Art Downloader beta v0.1.3-beta
This utility is from https://github.com/mewforest/google-art-downloader/, allows you to save all of the images from [Google Art Project](https://artsandculture.google.com) in high quality, and i change the resolution up to 8K (need at least 16gb of RAM). 

## Using utility（not update）
Just download [google-art-downloader.zip](https://github.com/mewforest/google-art-downloader/releases/download/v0.1.2-beta/google-art-downloader-0-1-2.zip) from [releases](https://github.com/mewforest/google-art-downloader/releases), unzip it to any folder and run **google-art-downloader.exe**. Then insert link to the text field using `CTRL+V` or button **"Paste url"** (yes, you can delete example link), click **"Download"** and wait until the image is ready.

![Screenshot of the interface](http://up.mewf.ru/ga/images/04_scr.png)

## Dependencies
Compiled release requires just connection to Internet.

Source code has written in Python 3.6 and has the following dependencies: Selenium, PIL and added chromedriver.exe to PATH.

## Problems
In old release elongated vertical images had cropped incorrectly, now you can fix it with option "Check this, if your image cropped wrongly". Unfortunately with this options quality may deteriorate. Sometimes this option causes artifacts on the image, I haven't uderstanding why.

## Bugs
Sometimes can't detected artist name. Bug from original version(guess mainly Xpath problems).

2018.08.08

