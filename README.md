# Radiokot's Umbrel apps

App store URL:
```
https://github.com/Radiokot/umbrel-radiokot-app-store.git
```

To it to your Umbrel, follow the steps shown in this demo:


https://user-images.githubusercontent.com/10330103/197889452-e5cd7e96-3233-4a09-b475-94b754adc7a3.mp4


Alternatively, you can use the Umbrel CLI as described below:

To add an app store:
```
sudo ~/umbrel/scripts/repo add https://github.com/Radiokot/umbrel-radiokot-app-store.git

sudo ~/umbrel/scripts/repo update
```

To install an app from the app store
```
sudo ~/umbrel/scripts/app install app-name
```

To remove an app store:
```
sudo ~/umbrel/scripts/repo remove https://github.com/Radiokot/umbrel-radiokot-app-store.git
```
