# electron-atm

A timestamp service used by [Electron ATM](https://github.com/timgabets/electron-atm) and [ATM State Navigator](https://github.com/timgabets/states-navigator) applications. The get() method of the service returns current time string in HH:MM:ss.mmm format (e.g. '14:52:50.007'), which may be used in traces, logs etc.

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