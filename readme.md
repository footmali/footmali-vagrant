# Footmali Vagrant

## Setup
1. Update /etc/hosts file on your machine with these entries:

``` 192.168.19.88 footmali.local ```

``` 192.168.19.88 cms.footmali.local ```

``` 192.168.19.88 dmt.footmali.local ```

``` 192.168.19.88 api.footmali.local ```

2. Start the vagrant machine  ` vagrant up `

## FYI
Whenever the file Homestead.yaml is updated you'll need to provision the vagrant box
``` vagrant reload --provision ```
