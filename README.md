# Nordvpn container

short howto:

1.
```
git clone $REP
cd $REP
```
2.
check home NETWORK ENV

```
ip route | awk '!/ (docker0|br-)/ && /src/ {print $1}'
```
3.
set NETWORK evn to docker-compose.yml

4.
build'n'run container
```
docker-compose build
docker-compose up -d

```

leaked accs can be founded here
(for test only)
https://t.me/s/nordvpn_trial?before=194

