## Azure Mobile Apps Cordova Client Quickstart Instructions ##

To use the quickstart:

  1. Change to the Cordova quickstart directory:

        cd ./ZUMOAPPNAME
        
  2. Edit ./www/js/index.js and replace the **_ZUMOAPPURL_** placeholder with your Mobile App cloud backend URL.
  3. Add the platform you want to build the quickstart for:

        cordova platform add [android | ios | windows | wp8]
  4. Run the quickstart:

        cordova run [android | ios | windows | wp8]

### Prerequisites

* [Cordova CLI](https://cordova.apache.org/docs/en/latest/guide/cli/index.html)
* Target platform SDK.
