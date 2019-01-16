# Whitney Young High School Clubs
An informational guide to the amazing clubs at Whitney Young High School.

### links:
* [Live Website](https://X-Ry.github.io/wyclub/)

### How To Add More Clubs
1. Goto the clubs folder and create a new json file with the title of the club you are proposing.
2. Copy/paste a preexisting json file into your new one and replace the data with the correct info for that club.
3. When you think you have finished making your json file, compare with a preexisting one to make sure that you did not forget anything.
4. Now, make sure that your syntax is correct by pasting your entire json file into [JSON Formatter](https://jsonformatter.curiousconcept.com/) and they will tell you if your json is valid and where your mistakes are if you have any.
5. You may have noticed a place in the json file called "imgsrc"; this stands for *image source*, which should link to a media file located in the "cgi-bin" folder. So, what you need to do in order to add a picture for the club is to upload a file to "cgi-bin" and link and use its file name in the "imgsrc" field in the json file.
6. When you have completed adding your image and your json file, goto clubs/clubs.json and you will find an array of the names of the json files in the clubs folder. This is because we need a list of what json files to include when the webpage is loaded. So all you need to do here is add the name of your club to the bottom of the array. The text that you use should exactly match your json file.
7. Let me know if you have questions, we are here to help. 
