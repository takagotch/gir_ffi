### gir_ffi
---
https://github.com/mvz/gir_ffi

```rb
require 'gif_ffi'
GirFFI.setup :Gio
inet_address = Gio::InetAddress.new_from_string

inet_address.is_loopback
inet_address.is_multicast

Gio.dbus_is_name
```

```sh
gem install gir_ffi
```

```
```


