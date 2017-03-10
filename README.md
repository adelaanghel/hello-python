## hello-python
Example Predix.io python application.
```
  - $ git clone https://github.com/adelaanghel/hello-python.git
  - $ cd hello-python
  - $ cf push      - to push the python app to Cloud
```

## Useful commnads:
```
  - $ cf login        -- login with Predix credentials
  - $ cf buildpacks   -- buildpacks for manifest.yml file
  - $ cf apps
```

## CloudFoundry Files
**Manifest.yml**
--used to tell CF what container it needs to build. Most importantly, you will need to specify the buildpack (as you have already done).--

**Procfile**
--used to declare required runtime processes, called process types, for your web app. Process managers in a server use the process types to run and manage the workload.--

**requirements.txt**
--contains the required Python packages--

**hello.py**
--Python script that contains a flask rest service.--
