Installation is often the trickiest part!

If you got to [the Siegfried homepage](https://github.com/richardlehane/siegfried?tab=readme-ov-file#install) you should be able to find some installation instructions for the _Ubuntu_ Linux platform we're using here. It should look like this:

```
curl -sL "http://keyserver.ubuntu.com/pks/lookup?op=get&search=0x20F802FE798E6857" | gpg --dearmor | sudo tee /usr/share/keyrings/siegfried-archive-keyring.gpg
echo "deb [signed-by=/usr/share/keyrings/siegfried-archive-keyring.gpg] https://www.itforarchivists.com/ buster main" | sudo tee -a /etc/apt/sources.list.d/siegfried.list
sudo apt-get update && sudo apt-get install siegfried
```{{copy}}

You should be able to copy and paste that text into the console on the right, and various logs and notices will spill out.  At the end, you should be able to run this command: `sf --help` and see some information about how to use Siegfried. 

If that works, then Siegfried is installed, and we can move on to the next step!
