---
title: "Automatically Connect to VPN At Startup"
layout: post
date: 2021-06-07
image: /assets/images/markdown.jpg
headerImage: false
tag:
- Linux
- Fedora
- VPN
- OpenVPN
- Privacy
category: blog
author: Reza
---


Few days ago, I was surfing on the Internet and I got annoyed by personalized ads and felt my privacy was being invaded constantly so I decided to set up my machine in a way that would connect to a VPN automatically when the machine boots.

To do this, I did a quick search and found out an easy way to make this happen. First we must launch a terminal and then we're going to type:

{% highlight raw %} $ nm-connection-editor {% endhighlight %}

This command launches the editor for NetworkManager. If you're interested in reading more about this command, read the man page.

When we press enter we'll see a graphical user interface. In this step find the network connection you want to modify and click on the settings gear at the bottom. Go to General tab and tick 'Automatically connect to VPN'. If you haven't created a VPN profile before, you'll have to do that first. You can do this by going to Network > VPN and creating a profile which is quite straightforward.

Click save and go back to your terminal. Reboot your system by entering reboot command to see the effects.

