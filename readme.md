Setup Filewatchers in PhpStorm

Open the filewatchers panel in your preferences

Menu PhpStorm
    -> Preferences
        -> Tools
            -> File Watchers
            
                at the bottom of the panel click on the "Import" icon and select the
                watchers.xml file located in the /utils folder of this project
                
                This will setup the following filewatchers:
                    sass ( using libsass )
                    jade
                    coffeescript
                
Initialize the Bower Dependencies

Open the "Terminal" panel at the bottom of the PhpStorm window
type "bower install". All the necessary bower components will be 
loaded into the src/bower_components directory