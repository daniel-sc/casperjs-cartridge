# OpenShift CasperJS Cartridge

This cartridge installs [PhantomJS](http://phantomjs.org/) and [CasperJS](http://casperjs.org/).

## Get Started

Install cartridge via "Install your own Cartridge" using the link https://raw.githubusercontent.com/daniel-sc/casperjs-cartridge/master/metadata/manifest.yml .

SSH into your gear and check if its working:
```
`echo $OPENSHIFT_CASPERJS_BIN_DIR`casperjs --version
`echo $PHANTOMJS_EXECUTABLE` -v
```
(You might need to restart the app to have the environment variables available)
