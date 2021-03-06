ios_samples
===========
# Google Maps SDK for iOS samples #

Some samples I build while testing  Google Maps SDK for iOS 


## Using samples ##


1. Get an API key  and add it to the app delegate.
  
  Go to [Google APIs Console](https://code.google.com/apis/console/) get a key and register the AppID(bundle identifier). 
  More on this [in the docs](https://developers.google.com/maps/documentation/ios/start)
  Go to the app delegate and add your key just under the TODO comment entry.


2. Add GoogleMaps Framework to the project.
   
   The project has most of the steps completed, but you need to get and add the GoogleMaps.framework

    1. Get the [SDK](https://developers.google.com/maps/documentation/ios/start) and 
    
    2. Drag the GoogleMaps.framework bundle to the Frameworks group of your project.
    When prompted, select Copy items into destination group's folder.
    
    3. Right-click GoogleMaps.framework in your project, and select Show In Finder.
    
    4. Drag the GoogleMaps.bundle from the Resources folder to your project. We suggest putting it in the Frameworks group. 
    When prompted, ensure Copy items into destination group's folder is not selected.

  After that you should be good to build your project.


3. If something goes wrong

   You should be go, because the rest of the setup is in the configuration alrady, 
   but in case you have any problems follow the instructions from [the setup guide](https://developers.google.com/maps/documentation/ios/start#adding_the_google_maps_sdk_for_ios_to_your_project)

## About ##

author: Kasia Derc-Fenske
