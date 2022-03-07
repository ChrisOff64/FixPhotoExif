# FixPhotoEXIF

Utility to correct photo EXIF data with the help of Google Takeout JSON files.

## Before use: backup your photos

It works, but you know... always have a backup, just in case.

## Description

If you downloaded all the photos from Google Photo using Google Takeout, and you spent quite some time fixing dates in Google Photo, well, you will see your files do not have the information attached to it.

You will get Modify Dates with unreliable information, and JSON files for each file, with somewhat better information.

This utility offers a quick way to analyze the actual EXIF information to get the photo date and the JSON information. It also displays the Modified Date of the file. The software will make a simple guess based on the JSON information to calculate a New Datetime to write in the files.

You will have the opportunity to review the New Datetime, change it manually or in batch, and even initialize it in trying to extract the Date part from the photo filename.

When you are ready, you can ask to write the New Datetime into the EXIF and or Modified Date of all the selected photos.