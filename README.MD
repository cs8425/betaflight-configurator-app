# Betaflight Configurator Cordova-based app

### Build you self
1. create a cordova project: `cordova create hello com.example.hello HelloWorld`
2. cd in to project directory
3. add platforms: `cordova platform add android --save`
4. add plugin: `cordova plugin add https://github.com/cs8425/cordova-plugin-chrome-apps-sockets-tcp.git#fix-tcp-read-stuck`
5. remove sample `www`: `rm -rf www`
6. clone modified Configurator: `git clone https://github.com/cs8425/betaflight-configurator.git --branch cordova-based-app www`
7. build project: `cordova build android`


