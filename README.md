This experimental plug-in has been superceded by changes in the official [`asdf-erlang`](https://github.com/asdf-vm/asdf-erlang) plug-in. It is recommended to install that one directly by running `asdf plugin-add erlang`.

# ~~asdf-kerl~~
Experimental Erlang plugin for the
[asdf version manager](https://github.com/asdf-vm/asdf) backed by
[kerl](https://github.com/kerl/kerl).

The best of both worlds. kerl's compatibility and build scripts, together
with asdf's easy version switching and support for the `.tool-versions`
file. You need both asdf and kerl installed.

## Install

```
asdf plugin-add erlang https://github.com/eproxus/asdf-kerl
```

***NOTE***: *This conflicts with the normal Erlang plugin if you have that
installed. Either use a different name or remove the default Erlang plugin.*

## Use

Check [asdf](https://github.com/asdf-vm/asdf) for instructions on how to
install & manage versions of Erlang. See [kerl](https://github.com/kerl/kerl)
for customization options.
