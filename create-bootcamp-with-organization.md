* Create a new Github organization with name template `swcarpentry-YYYY-MM-DD-INST`, where `INST` is institution name
* Add all your collaborators as owners of the organization
* for the https://github.com/swcarpentry/bc repository under the organization account
* create an empty repository under the organization named `swcarpentry-YYYY-MM-DD-INST.github.io` that will host the build website
* Now clone the `bc` repository of your organization locally
* Add the website as the `publish` remote:

        git add remote publish https://github.com/swcarpentry-YYYY-MM-DD-INST/swcarpentry-YYYY-MM-DD-INST.github.io.git
    
* Then publish the website by pushing to that remote

        git push publish
    
* The website will be available 10 minutes later on: swcarpentry-YYYY-MM-DD-INST.github.io 

see for example the organization https://github.com/swcarpentry-2014-07-07-esu and the published bootcamp website at http://swcarpentry-2014-07-07-esu.github.io/
