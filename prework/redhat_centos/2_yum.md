### Update YUM

Now that your Terminal is setup, it's time to update CentOS's **Yellowdog Updater, Modified** or [YUM](https://access.redhat.com/documentation/en-US/Red_Hat_Enterprise_Linux/6/html/Deployment_Guide/ch-yum.html) for short. If you've never heard of a package manager, think of it as an App Store of **free** command line programs.

To get started, run the following commands.

```
sudo yum-config-manager --add-repo http://fishshell.com/files/linux/RedHat_RHEL-6/fish.release:2.repo
sudo apt-add-repository -y ppa:webupd8team/sublime-text-3
sudo add-apt-repository -y ppa:git-core/ppa
sudo apt-get update
```

**TIP:** This may require your account password which **will not** appear on the screen as you type.


### [⇐ Previous](1_terminal.md) | [Next ⇒](3_fish.md)
