# About

Configuration files and scenarios for creating set Arch Linux instance.

# Install

Either follow [Arch Installation guide](https://wiki.archlinux.org/title/Installation_guide)
or use [archinstall](https://github.com/archlinux/archinstall)
~~or write your own ansible playbook and then give up on maintaining it and fallback to manual install or archinstall~~
for creating mostly pre-set instance. Then finetune with dotfiles etc.

## Live arch iso

```shell
$ archinstall --config user_configuration.json --disk_layout user_disk_layout.json
# inside tui set root password, double-check disk layout and encryption, create user(s)
```

# TODO

- section about iso install emulation (for testing)
- dotfiles
- probably ansible-playbook for fine-tuning after archinstall
- pre-installed minimal arch vagrant box for testing UI, dotfiles etc
- CI for `archinstall --dry-run` ?
