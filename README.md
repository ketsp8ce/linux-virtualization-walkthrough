# Linux Virtualization: Easy Guide for Absolute Beginners

Welcome! This guide is for **absolute beginners**. Why am I making this? I hope that you will **not make the same mistake as I did** — trying to install Linux on your own machine as a total beginner… and breaking things.

If you are curious like me, you might accidentally **delete core metadata** or do something that renders your entire personal computer unable to operate. 😅

This is where **virtual machines (VMs)** come in:

- You can set one up just to **break it**  
- Do all the things you’ve always wanted to try  
- Be impulsive, irresponsible, and experiment freely

I was intimidated by the Linux community for too long — **everyone starts somewhere!**

---

## 🚀 Required Software

### ✅ Virtualization Software

This tutorial is based on **VirtualBox**, but **VMware** works well too. Use whichever one you prefer.

- [Download VirtualBox](https://www.oracle.com/virtualization/technologies/vm/downloads/virtualbox-downloads.html)  
- [Download VMware Workstation Player or Fusion](https://www.vmware.com/products/desktop-hypervisor/workstation-and-fusion)

---

### ✅ ISO Files

For this tutorial, we’ll be setting up virtual machines for:

- **Debian**  
- **Arch Linux**  
- **Kali Linux**

You can find 1–3 ISO files here:  
🔗 [https://www.linuxlookup.com/linux_iso](https://www.linuxlookup.com/linux_iso)

---

## 🌀 Arch Linux via Torrent

- [Arch Linux Download Page](https://archlinux.org/download/)  
- Download the **torrent file** — it helps seed the file, which is a nice thing to do for the community. (Yes, Linux users can be pretentious, but you wouldn’t be here if you didn’t want to be one of us 😎)

![Arch Torrent Screenshot](images/prereqs/arch_torrent.png)

If you don’t already have a torrent client, I recommend **qBittorrent**, a free and open-source torrent agent.

- [Download qBittorrent](https://www.qbittorrent.org/download)  
> ⚠️ **Tip:** Don’t confuse this with the original BitTorrent client — they are different!

---

## 🛡️ Kali Linux for Virtual Machines

Kali provides **specialized ISO images for virtual machines**, making setup easy.

- Go to [Kali VM downloads](https://www.kali.org/get-kali/#kali-virtual-machines)  
- Click on **VirtualBox**, or choose your preferred alternative

![Kali VM Screenshot](images/prereqs/kali_virtualbox.png)

---

## Debian lightweight

Debian has several options but I went with the lightweight version. I have good internet and as long as you are not offline you should choose this one too.

- Go to [Debian's downloads page](https://www.debian.org/distrib/)

- Choose Debian small image

![Debian Small Screenshot](images/prereqs/debian_small.png)

This is confusing or exciting as you may want to actually think about your computers architecture now. If you click on this ![more info](images/prereqs/debian_moreinfo)

it will take you here: https://www.debian.org/CD/netinst/ for the option of extra reading if you are curious. 

However you should most likely be ok selecting [amd64](screenshots/debian_amd64)

Next, move onto

[Debian](https://github.com/ketsp8ce/linux-virtualization-walkthrough/tree/main/debian)

[Arch](https://github.com/ketsp8ce/linux-virtualization-walkthrough/tree/main/arch)

[Kali](https://github.com/ketsp8ce/linux-virtualization-walkthrough/tree/main/kali)