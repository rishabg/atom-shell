# power-monitor

The `power-monitor` module is used to monitor the power state change. You can
only use it on the main process.

An example is:

```javascript
require('power-monitor').on('suspend', function() {
  console.log('The system is going to sleep');
});
```

## Event: suspend

Emitted when the system is suspending.

## Event: resume

Emitted when system is resuming.
