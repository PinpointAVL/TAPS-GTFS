# TAPS-GTFS Information
Published GTFS Feed for UCSC Transportation and Parking Services.
Created using the RTAP's GTFS workbook. For feed production, use the dev branch. 

You can visualize the routes using [GTFS-GO for QGIS](https://plugins.qgis.org/plugins/GTFS-GO-master/) and the schedules using [GTFS-to-HTML](https://gtfstohtml.com/docs/). And of course, you can look at UCSC on Google Maps to see the GTFS feed in action!

# Spring 2023 Changes
 
 - Adjusted stop locations for Bay & High (Main Entrance), High & Tosca Terrace, and Coastal Biology Building in coordination with SCMTD
 - Updated run times
 - Added trips.direction_id so that Transit App groups routes correctly

# Winter 2023 Changes

 - Returned to the full school-term schedule
 - Adjusted passing period run times to better model bus bunching
 - Set `stop_times.stop_headsign` for the the last stop in each sequence to "Drop Off Only" if there is more than five minutes until the next trip of the block in order to provide a visual distinction between trips going into and out of service at common route terminals
 - Renamed "Main Gate" to "Main Entrance" to improve legibility
 - Added a new stop at the Barn Theater as the last stop in the sequence for trips followed by a holdover in lot 122
 - Updated `stops.stop_name` for all stops to be consistent with TAPS' published materials
 - Changed feed contact email so that our validation errors are sent to us instead of the TAPS director
 - Added McHenry NUC
 
