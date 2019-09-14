# AgenaRisk 10 API Application Dependencies
## About
This repo provides an easy way to get the latest AgenaRisk 10 libraries and product files to use when setting up your own non-maven application image.

## Usage Example
Assuming your app executable is installed on a server to `/opt/myapp/myapp.jar`
````
mvn clean install "-Dcom.agenarisk.product=enterprise"
cp -r target/lib/. /opt/myapp/lib/
````
