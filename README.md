# google-maps-timeline-viewer
Open Source Google Maps Timeline Viewer

| File | About |
| --- | --- |
| ***index.html*** | the viewer
| ***location-history.json*** | sample data - you can upload your own in the viewer interface


## How to use:
* Access the viewer at https://r-li.com/google-maps-timeline-viewer
<br>or<br>
Download ***index.html*** to use locally or customize it as needed.
* Click **Upload Data** to upload the exported JSON file from Google Maps (usually named ***location-history.json*** or similar)


## About Google Maps Timeline and how to export the data:

**Official Instructions:** https://support.google.com/maps/answer/6258979

**Note:** Timeline is no longer available on computers

**For iPhone & iPad:**
* Open the Google Maps app
* Tap profile picture or initial (top right) → *Settings* → *Location & privacy* → *Export Timeline data* (under *Timeline*) → *Save to Files*
* Select your preferred storage location → *Save*

**For Android:**
* Open the device's Settings app
* Tap *Location* → *Location services* → *Timeline* → *Export Timeline data* (under *Timeline*) → *Continue*
* Select your preferred storage location → *Save*


## Preview:
Click ***lines*** or ***points*** to view details:
![Preview-1](pics/pic-1.png "Preview-1")

Filter data by ***date***, ***categories***, and ***detailed types*** & change the ***basemap***:
![Preview-2](pics/pic-2.png "Preview-2")


## About the data:

| Category | Geo Data | For | Detailed Types |
| :-: | --- | --- | --- |
| ***visit*** | point | places visited | *Home*, *Work*, *Searched Address*, *Unkonwn*, etc. |
| ***activity*** | start point + end point | activities from one point to another | *walking*, *cycling*, *flying*, *in subway*, etc. |
| ***timelinePath*** | path - collection of all recorded points along the path | movements paths | n/a |

## Acknowledgement:
Coded with assistance from *Google Gemini 3 Pro*
