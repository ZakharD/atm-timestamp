# electron-atm

A timestamp service used by [Electron ATM](https://github.com/timgabets/electron-atm) and [ATM State Navigator](https://github.com/timgabets/states-navigator) applications.

## Install
```bash
npm install atm-timestamp
```

## To Use:

```javascript
> var Timestamp = require('atm-timestamp');
> var t = new Timestamp();
> t.get()
'14:52:01.548'
> t.get()
'14:52:50.007'
```