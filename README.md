# WindowsSetup

A repo containing scripts / steps on wetting up a new Windows developer environment.

## First steps

- Partition your hard disk. Leave the OS on the C: with maybe 80/100 gig, then the rest into a D:
- Install Chocolatey and Boxstarter
- Run the boxstarter scripts in this repo.

To run the boxstart script, see the details (here)[https://boxstarter.org/weblauncher#step-3].

Command will be something like

```bash
START https://boxstarter.org/package/nr/url?https://github.com/bcraig83/WindowsSetup/blob/main/InitialSetup.txt
```