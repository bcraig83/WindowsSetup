# WindowsSetup

A repo containing scripts / steps on wetting up a new Windows developer environment.

## First steps

- Partition your hard disk. Leave the OS on the C: with maybe 80/100 gig, then the rest into a D:
- Install Chocolatey and Boxstarter
- Run the boxstarter scripts in this repo.

To run the boxstart script, see the details (here)[https://boxstarter.org/weblauncher#step-3].

Command will be something like

```bash
START https://boxstarter.org/package/nr/url?https://github.com/bcraig83/WindowsSetup/blob/main/01-Basics.txt
START https://boxstarter.org/package/nr/url?https://github.com/bcraig83/WindowsSetup/blob/main/02-TaskbarAndExplorer.txt
START https://boxstarter.org/package/nr/url?https://github.com/bcraig83/WindowsSetup/blob/main/03-Libraries.txt
START https://boxstarter.org/package/nr/url?https://github.com/bcraig83/WindowsSetup/blob/main/04-InstallSoftware.txt
START https://boxstarter.org/package/nr/url?https://github.com/bcraig83/WindowsSetup/blob/main/05-Cleanup.txt
```

Run each of the scripts in numbered order