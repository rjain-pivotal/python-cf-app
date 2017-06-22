# Simple Hello World Python app

  If you have python 3.5+ version locally installed and you want to vendor your packages, you can do the following
  
  ````
  pip download -r requirements.txt -d vendor
  ````

  To push the app to cloud foundry, do the following
  
  ````
  cf push -f manifest.yml
  ````
  To change the version of python, you can change the runtime.txt
  
  
