To use, attach the role to a host or group, and define a hash in the format:

```
trac:
  instances:
    <instance nam>:
      path: "<path for trac instance"
      config:
        <section heading>:
          <option>: <value>
```

Tested on Debian Jessie with Trac 1.0.