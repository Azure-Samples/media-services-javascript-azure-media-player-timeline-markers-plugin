---
services: media-services
platforms: javascript
author: saraje
---
# Media Services: Timeline Marker Plugin for Azure Media Player


##Information
Attributions: 

#Introduction
This plugin adds small markers onto your timeline at the configured times. 

## Getting Started
Include the plugin CSS/javascript*after* the AMP script in the `<head>` of your html page:

```<link href="timelineMarkers.css" rel="stylesheet">```

```<script src="timelineMarkers.js"></script>```

**important: this sample plugin's video id is azuremediaplayer and is hardcoded in the timelinemarkers.js in the following line:**

```var elements = document.getElementById("azuremediaplayer").getElementsByClassName(className);```

**if you change the video id in your own code, be sure you update it in the javascript file as well (this will be fixed soon)**

See example.html for how to enable the plugin 
## Options
Plugin currently receives input in the form of an array of times see below: 

    plugins: {
    
    	timelineMarker: {
    		markertime: ["0:00","1:30", "1:48"]
    
    	}
    
    }

##To-Do
- remove current markers when source switch occurs 
- remove hardcoded video id 
 
