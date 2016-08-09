# Footmali Vagrant

## Development
- Update /etc/hosts file on your machine with these entry

``` 192.168.19.88 footmali.local

192.168.19.88 cms.footmali.local

192.168.19.88 dmt.footmali.local

192.168.19.88 api.footmali.local ```


- Start the vagrant machine  ` vagrant up `

When you update this project you'll need to provision the vagrant box
``` vagrant reload --provision ```
