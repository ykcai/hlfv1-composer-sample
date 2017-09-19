# My Commodity Trading network

## Start Fabric 
```
cd ~/fabric-tools
./downloadFabric.sh
./startFabric.sh
./createComposerProfile.sh
```
```
npm install "https://github.com/fabrice102/node-hashtable.git"
```
```
npm install
```
## Deploy to Fabric
```
composer network deploy -a dist/my-network.bna -p hlfv1 -i PeerAdmin -s randomString
```
## Ping Deployed Network
```
composer network ping -n my-network -p hlfv1 -i admin -s adminpw
```
## Update Deplyed Network
```
composer network update -a dist/my-network.bna -p hlfv1 -i PeerAdmin -s randomString
```
## Create REST API
```
composer-rest-server
```
## End Fabric
```
cd ~/fabric-tools
./stopFabric.sh
./teardownFabric.shcd ~/fabric-tools
./stopFabric.sh
./teardownFabric.sh
```
