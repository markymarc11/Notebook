So starting to use the scann3D has been an interesting experience
nto sure why but the picture kept on adding extra eyes to the scan
tried taking out some of the blurry pictures, but that didn't work out very well at all
still not sure what is wrong with it

-Started work on 3d project today Tuesday 16th
-took pictures of Terry Fox statue in front of parliament hill
-had to get on Matt's shoulders to take some of the higher pictures, hopefully they turn out well
-weather was a crappy out, lit bits of blowing snow, and a bit cloudy, could end up affecting the overal image

Regard3D
Terry Fox File
TRied adding photo set
opens other window was hidden behind
selected all and added
picture set name Terry Fox
Unknown focal length for far too pictures, try using pictures with better focal lengths

Picture set, recognizes camera make and model, but not sensors, had to add in the sensors by googling the sensors for phone
sensors were 4.69 X 3.52 mm or 0.23 inches (5.8 mm)
Tried changing the focal point and sensory width to make it work
-nothing changed

Starting over
file place
/Users/johnw/Documents/test4/test4.r3d
retried adding the picture set again, still did not work, came up with the same warning
changed Motorola to motorola, see if uppercase lower cchanges
changes still did not work

changing metadata, using exiftool, google search it phil harvey

if having problems on mac, click control, then click open

electricarchaeology.ca Shawns personal website

Shawn does computer type commmands to try and change the senors, it doesnt work

tried changing things through multiple different ways, still now showing up as changes through regard3D

trying to use submlime text, it is a text editor, shows you precisely what is on a file,
Excel is by microsoft and it is the devil, they were adding some form of little infor which we could not see
we copied the model number and info directly, and it finally showed the sensory width 
Computing the picture matches
-takes a long time
-finally worked after 27 minutes
compute matches
-wait more
TRiangulate, we decided to try Global triangulation because it fit our setting needs (used the came camera and same amount of zoom)
we realized at this point that it was not showing us an image that we wanted, went back tmo computing the pictures, and changed the keypoint sensitivity and keypoint matching ratio to ultra
-shit takes too long....
-may need to edit pictures
-ended up having to leave because it was taking too long, was at 30 minutes and looked like only 50% loaded

Jan 22
-Users/marcbitar/Documents/Terry/Terry.r3d
going through the command terminal
  -ls for list
  -cd for change directory
  make: new
  Camera model: XT1650
  Focal l;ength 3.7 mm
sensors 5.8 mm
had to change the settings, the commands used are on shawns website 
https://electricarchaeology.ca/2018/01/20/3d-models-from-archival-film-video-footage/ step 2
Compute matches
  -ultra settings for all
 Triangulate
  - used incremental structure from Motion
  Densification
  -Used CMVS/PMVS and preset settings, then tried chagning settings level 0 Cells size 1 Threshold 0.79 wsize 8 min num image 3
  Create Surface
  Tried one with texture and one with colour (thing) the one with colour seemed to look better
  exported it
  then went back to try and play with some of the pictures
-took too long, so had to stop and export the primary image
Opened up Meshlab
-Opened up the new 3D rendering that had been produced
-getting rid of the extra bits around the image
--Used the select vertexes tool, dragged around what i didn;t want
--then used the tool "delete the current set of selected vertices" button
--repeated until i got rid of everything i didnt want
-with the new image that was produced the file was saved as a .ply file
-tried uploading to sketchfab
-file uploaded but there were parts of the image that were missing
-not sure eactly what occured
-tried using the file in a different format and exported as an .obj file
-same problem occured
--i hate sketchfab currently
-tried again and the file now has a colourful background
-where did the colour come from
-still hate sketchfab
