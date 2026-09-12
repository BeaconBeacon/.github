# How to access a computer's BIOS remotely

*Every remote access tool you already have runs inside the operating system. The BIOS runs before there is an operating system — which is why none of them can get you there.*

## Why remote desktop can't do it

RDP, VNC, TeamViewer, AnyDesk and SSH are all programs. They start after the
operating system starts, and they send you a picture that the operating system
draws.

Press Delete or F2 during boot and none of that exists yet. There is no
network stack, no service to accept your connection, and nothing running that
could send an image anywhere. The machine is drawing to its HDMI output and
listening to a USB keyboard, and that is all it is doing.

So the only way in is to be that monitor and that keyboard.

---

This is the opening of the article. **[Read it in full at beacon-kvm.com →](https://beacon-kvm.com/blogs/use-cases/access-bios-remotely)**

More: [all articles](README.md) · [Beacon KVM](https://beacon-kvm.com) · [Raspberry Pi build](https://github.com/BeaconBeacon/KVM) · [Discord](https://discord.gg/jjXN7H6WcH)
