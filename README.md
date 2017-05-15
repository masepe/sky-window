# sky-window
Web application to allow people plan astronomy observation regarding weather and sky illumination conditions.
 
Licensed under Apache License Version 2.0 so do not forget refer on initial project on you page :)

## Installation requirements ##
- NodeJS - http://nodejs.org/do (ubuntu: sudo apt-get install npm && sudo ln -s /usr/bin/nodejs /usr/bin/node)
- Bower - 'npm install -g bower'
- Maven - https://maven.apache.org/ (tested with 3.3.1)

## Installation ##
On the command line, in the root directory run:
    bower install // installs all third party libraries needed for our app, creates 'vendor' dir
    
## Build ##   
    mvn clean compress install
    
## Project directory structure(after installation) ##


    target/                 # build directory
        min/                # built app for prod. deployment
        classes/            # built app for dev. deployment
    src/ 
        main/resources/     # source root dir
          js/               # application source code, all subdirs are separate components
          assets/           # app resources
          styles/           # .scss files
          html/             #
          webapp/           # .war application support
        test/               # automatic tests
    vendor/                 # bower lib installation directory
    
## Run ##

TODO how to for apache and tomcat
    
## Adding third party libraries ##
Run 
    bower install <lib name> --save // saves as a dependency
    
## Versions and features
### Planned

### Released   
-- Version 0.0.1