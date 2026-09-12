# IP KVM vs remote desktop: when you need hardware

*These two things look similar in a browser window and are not remotely the same underneath. The difference only shows up on the day something breaks.*

## The one difference everything else follows from

Remote desktop software is a program running on the machine you are
controlling. An IP KVM is hardware plugged into that machine, pretending to be
a monitor and a keyboard.

So the question is never "which gives a nicer picture". It is: **when the
operating system is not running, is your remote access still there?**

| | Remote desktop | IP KVM |
|---|---|---|
| Installed on the target | Yes, an agent | Nothing |
| Works before the OS loads | No | Yes |
| BIOS and UEFI setup | No | Yes |
| Bootloader, recovery, safe mode | No | Yes |
| After a failed OS update | No | Yes |
| Machine with no network of its own | No | Yes |
| Copy and paste, file transfer | Yes | No |
| Multiple monitors | Yes | One HDMI output |
| Cost per machine | Often free | Hardware per machine |
| Picture quality for daily work | Better | Good enough |

---

This is the opening of the article. **[Read it in full at beacon-kvm.com →](https://beacon-kvm.com/blogs/use-cases/ip-kvm-vs-remote-desktop)**

More: [all articles](README.md) · [Beacon KVM](https://beacon-kvm.com) · [Raspberry Pi build](https://github.com/BeaconBeacon/KVM) · [Discord](https://discord.gg/jjXN7H6WcH)
