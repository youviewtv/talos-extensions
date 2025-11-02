# yvrig-control
## Installation

See [Installing Extensions](https://github.com/siderolabs/extensions#installing-extensions).

## Usage

Copy the udev rules into the `udev/rules.d` directory in the immutable filesystem.

## Verifiying

You can verify the rules are in place by listing the udev rules directory:

```
❯ talosctl -n <node> ls /usr/lib/udev/rules.d
NODE            NAME
<node>          60-yvrig.rules
```


You can also verify everything in dmesg
