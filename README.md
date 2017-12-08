# Ultimate IoT Platform Comparison

[![Build Status](https://travis-ci.org/ultimate-comparisons/ultimate-IoT-platform-comparison.svg?branch=master)](https://travis-ci.org/ultimate-comparisons/ultimate-IoT-platform-comparison)

This is an ultimate comparison of IoT platforms.

## Test it
1. Install [node.js](https://nodejs.org/en/)
2. Intall [Java JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html)
3. Update npm (sudo): `npm install -g npm`
4. Test dependencies:

        java -version
        npm -version

4. `npm install`
5. `npm start` (starts the web page)
6. [Setup automatic deployment of `www` directory using Travis CI](https://github.com/ultimate-comparisons/ultimate-comparison-BASE/wiki/Build-and-deploy-project-with-Travis-CI)


## IoT Platform Specification
A full list of all criteria and their values can be found [here](https://github.com/ultimate-comparisons/ultimate-IoT-platform-comparison/blob/master/comparison-configuration/description.md).

The code below shows a sample element.

    # Default Platform - http://default-platform.com
    Default short desciption.
    
    ## Support of heterogeneous devices
    - Yes
    - No
    - Needs gateway
    - RFID
    - Embedded devices
    - Home devices
    - Ehternet enabled
    
    ## Type
    - M2M 
    - SaaS
    - PaaS
    - Server
    - P2P
    - Hub
    - client/Server
    - OS
    - Robots
    
    ## Architecture
    - Cloud-based
    - Centralized
    - Decentralized
    
    ## Open source
    - Yes
    - Libraries only
    - Client open source
    - Gateway firmware open source
    - No
    - Apache 2.0
    - LGPLv3
    - Affero GNU Public License
    
    ## REST
    - n.a.
    - No
    - Yes
    - CoAP
    
    ## Data access control
    - OAuth2
    - Secured access
    - n.a.
    - Role-based
    - User's choice
    - 4 levels
    - Locally stored
    - No storage
    - 3 levels
    - User-based privileges
    - Facebook like privacy settings
    - Fine-grained
    - 2 levels
    
    ## Service discovery
    - No
    - Yes
    - Limited
    
    ## Description
    Default __platform__ description in markdown.



## License

The code is licensed under [Apache 2.0], the content (located at `comparison-elements`) under [CC-BY-SA-4.0].

  [Apache 2.0]: http://www.apache.org/licenses/LICENSE-2.0
  [CC-BY-SA-4.0]: http://creativecommons.org/licenses/by-sa/4.0/

<hr />
