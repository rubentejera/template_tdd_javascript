# README


### Install
```
npm install
```

### Init test
```
npm test
```

### FAQ
If error ENOSPC ([Stackoverflow](https://stackoverflow.com/questions/22475849/node-js-error-enospc/32600959#32600959)):
```
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
```
