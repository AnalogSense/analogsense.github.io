# udev rules for analog keyboards

If you want programs to be able to access your analog keyboard without having to run them as root, you need to set up udev rules that allow access to it.

This can easily be done with these 3 commands:
```bash
wget -qO- https://analogsense.org/udev-rules/70-analogsense.rules | sudo tee /etc/udev/rules.d/70-analogsense.rules > /dev/null
sudo udevadm control --reload-rules
sudo udevadm trigger 
```

To explain what this does:
1. Download the rules allowing access to all analog keyboards from [https://analogsense.org/udev-rules/70-analogsense.rules](https://analogsense.org/udev-rules/70-analogsense.rules)
2. Tell udev to reload all rules (including newly created ones)
3. Tell udev to apply the rules on the kernel
