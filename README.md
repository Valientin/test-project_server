## Use production OSRM and Geocoding servers

OSRM:
```bash
$ ssh -f eurotaxi-staging -L 5000:192.168.0.3:5000 -N
```

Geocoding:
```bash
$ ssh -f eurotaxi-staging -L 5001:192.168.0.3:80 -N
```

*192.168.0.3* - is OSRM server address in server internal network.
*eurotaxi-staging* - You must configure it in `~/.ssh/config` or use actual settings. You can use any server instead of *eurotaxi-staging*.
