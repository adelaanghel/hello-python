## hello-python
Example Predix.io python application.
```
  $ git clone https://github.com/adelaanghel/hello-python.git
  $ cd hello-python
  $ cf push      - to push the python app to Cloud
```

## Useful CF CLI commnads:
```
  $ cf login        -- login with Predix credentials
  $ cf buildpacks   -- buildpacks for manifest.yml file
  $ cf apps  
```
  see also                                                                                                                  
           http://docs.cloudfoundry.org/cf-cli/cf-help.html                                                                
           http://cli.cloudfoundry.org/en-US/cf/

## CloudFoundry Files
**Manifest.yml**
- used to tell CF what container it needs to build                                                                           
- see also http://docs.cloudfoundry.org/devguide/deploy-apps/manifest.html

**Procfile**
- used to declare required runtime processes, called process types, for the web app. Process managers in a server use the process types to run and manage the workload

**requirements.txt**
- contains the required Python packages

**hello.py**
- Python script that contains a flask rest service


## References:
https://devcloud.swcoe.ge.com/devspace/display/TBNPM/WMBU+and+Forecast+Analytics+Microservices+Design                     
http://docs.cloudfoundry.org/devguide/deploy-apps/manifest.html                                                             
http://docs.cloudfoundry.org/cf-cli/cf-help.html                                                                            
http://cli.cloudfoundry.org/en-US/cf/
