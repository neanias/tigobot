# tigobot

Enhanced hubot

## Deploy

Note to self:

```
sudo docker run -it -v /opt/tigobot/tigobot:/root/mybot rhiaro/hubotplus
```

```
HUBOT_IRC_SERVER=irc.imaginarynet.org.uk \
HUBOT_IRC_ROOMS="#oreos, #yourface, #compsoc" \
HUBOT_IRC_NICK="tigo" \
HUBOT_IRC_PORT="6667" \
HUBOT_IRC_UNFLOOD="true" \
bin/hubot -a irc --name tigo
```