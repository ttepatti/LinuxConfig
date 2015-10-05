# Lemonbar

Lemonbar is the name of the upper status bar used in this i3 config. This README
file outlines how to modify and change all of the different values and things on
it.

### Path

All of Lemonbar's config files are located within ~/.i3/lemonbar

Check there if you can't find something or want to modify something :)

### Lemonbar Networking

Getting the networking features of lemonbar working can be a pain due to new
Linux adapter naming conventions. Due to a hypothetical race condition, adapter
names are no longer "wlan0" and "eth0", but new things based on hardware
positions, hardware IDs, and device manufacturers. For example, my ThinkPad T60
has wls3 as my Wireless adapter and ens2 as my Ethernet adapter.

Because of this, you can't leave the default device names in the config, you
have to edit them yourself.

```
cd ~/.i3/lemonbar
```
