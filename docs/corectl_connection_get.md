## corectl connection get

Show the properties for a specific connection

### Synopsis

Show the properties for a specific connection

```
corectl connection get <connection-id> [flags]
```

### Examples

```
corectl connection get CONNECTION-ID
```

### Options

```
  -h, --help   help for get
```

### Options inherited from parent commands

```
  -a, --app string               App name, if no app is specified a session app is used instead
  -c, --config string            path/to/config.yml where parameters can be set instead of on the command line
  -e, --engine string            URL to the Qlik Associative Engine (default "localhost:9076")
      --headers stringToString   Http headers to use when connecting to Qlik Associative Engine (default [])
      --no-data                  Open app without data
  -t, --traffic                  Log JSON websocket traffic to stdout
      --ttl string               Qlik Associative Engine session time to live in seconds (default "30")
  -v, --verbose                  Log extra information
```

### SEE ALSO

* [corectl connection](corectl_connection.md)	 - Explore and manage connections
