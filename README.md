# devops-notes

# Setting Up Your Mac

## Configuring your shell and Terminal

This section is just my personal preference. I used to use ZSH. Do what you like. Here is how to use latest bash on Mac.

  * **Install Bash:** Mac doesn't ship with the latest version of bash you find in containers and cloud servers. In fact, the default shell is now zsh on Mac. You can easily [Install latest bash on Mac](https://www.ioannispoulakas.com/2019/03/10/how-to-install-bash-5-on-macos/)
    * On the latest version of bash you'll want to also use the latest `bash-completion@2` in homebrew.
  * Customize your shell prompt. 
    * [Starship](https://starship.rs/) minimal, blazing-fast, and infinitely customizable prompt for any shell!
  * [iterm2](https://iterm2.com/) The terminal you wish Mac shipped with.

# Development Process

## Code Review

My advice here is to automate everything you can about code review (format, syntax, security checks, license checks...). 

Here are some other tips that have worked in my experience:

* The team should create the team's code review process and make it part of a published team member agreement. 
* Don't create rules for them. Let the team put the rules together, own them, and regularly review them (hint: retro) and put their fingerprints on it. 
* As new scenarios and disagreements arise during the code review process, the team should be encrouraged to review and update the rules as needed even outside the retro schedule.
* https://www.michaelagreiler.com/ has done a lot of research on this topic.
  * [YOUTUBE: 10 tips for productive code review](https://www.youtube.com/watch?v=NNXk_WJzyMI)
* Something that teams seemed to like was practical tips like in this format of [helpful and unhelpful code review behaviors](https://medium.com/@sandya.sankarram/unlearning-toxic-behaviors-in-a-code-review-culture-b7c295452a3c)

# Containers

[Distroless](https://github.com/GoogleContainerTools/distroless)

## Python Docker

https://pythonspeed.com/docker/

### Notify Slack

node.js
https://github.com/novalu/ci-build-notifier

### Get Environment Variables Exposed by CI Services

node.js
https://github.com/pvdlg/env-ci

## AWS

### Security Governance and Management

[Cloud Custodian](https://cloudcustodian.io/)

### Ec2 Instances
https://ec2instances.info/

### AMIs

### AMI Quick Links

|  Name  | Link                                                                 |
| :----: | -------------------------------------------------------------------- |
| Ubuntu | [Ubuntu Image Locator](https://cloud-images.ubuntu.com/locator/ec2/) |
| CentOS | [CentOS Docs: AWS Images](https://wiki.centos.org/Cloud/AWS)         |

# Automating Operations

Work Management

* [NextUp.ai](https://www.nextup.ai)


