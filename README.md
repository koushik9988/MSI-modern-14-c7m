# MSI Modern 14 C7M Mute LED Fix

I have created a simple systemd service to toggle the mute LED using the following command:

```bash
echo 'Master Playback Switch' | sudo tee /sys/class/sound/ctl-led/speaker/card1/attach

souce :[MSI EC GitHub Discussion](https://github.com/BeardOverflow/msi-ec/discussions/130#discussioncomment-11010018)

