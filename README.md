# The Open Source Car Charging Station software in a snap

EVerest is an open source modular framework for setting up a full stack environment for EV charging.
  
The modular software architecture fosters customizability and lets you configure your dedicated charging scenarios based on interchangeable modules. All this is glued together by MQTT.
  
EVerest will help to speed the adoption to e-mobility by utilizing all the open source advantages for the EV charging world. It will also enable new features for local energy management, PV-integration and many more.
  
The EVerest project was initiated by PIONIX GmbH (Pionix at LinkedIn) to help with the electrification of the mobility sector and is an official project of the Linux Foundation Energy.

See the [Everest Upstream pages](https://everest.github.io/nightly/) for more information.

## Building (on Ubuntu)

Just clone this git tree and run `snapcraft` in the toplevel of the source tree, this will create a snap package, i.e. `everest_0.1_amd64.snap` on an amd64 system.
To install this snap, just run `sudo snap install --dangerous everest_0.1_amd64.snap`

## Usage

To see the demo UI, open a browser and navigate to http://localhost:1880/ui 

<img src="https://everest.github.io/nightly/_images/quick-start-sil-gui.png" alt="Everest demo UI" width="30%">

The demo also comes with an admin panel that cou can access with a browser through http://localhost:8849

For more details on how to use the demo see the [Everest quick start guide](https://everest.github.io/nightly/general/03_quick_start_guide.html)
