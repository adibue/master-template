# Useful defaults for macOS

## Touch ID for sudo

Touch ID can be used for `sudo` as an alternative to the user password.
For this to work, just run [this config script](https://github.com/0xmachos/macos-scripts/blob/fe5e3153f3ef1f499aaaa150222da700e6eeb6da/enable-touchid-sudo) or add the file `/etc/pam.d/sudo_local` with the following content:

```
# sudo_local: local config file which survives system update and is included for sudo
auth       sufficient     pam_tid.so
```
