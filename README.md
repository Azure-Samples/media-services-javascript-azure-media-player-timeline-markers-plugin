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

```<link href="timelineMarkers.css" rel="stylesheet">```<br />
```<script src="timelineMarkers.js"></script>```

See example.html for how to enable the plugin 
## Options
Plugin currently receives input in the form of an array of times see below: 

    plugins: {
    
    	timelineMarker: {
    		markertime: ["0:00","1:30", "1:48"]
    
    	}
    
    }

##To-Do
remove current markers when source switch occurs 
 