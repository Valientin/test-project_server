## Use OSRM service

Init osrm service - downloading map, docker and installing them:
```bash
$ npm run init-osrm
```
Then you need to reboot the system and start the service using the command:

```bash
$ npm run start-osrm
```
*127.0.0.1:5000* - is local service OSRM in browser. Also you must add it to `/ etc / hosts` as `127.0.0.1  taxi-osrm`.
