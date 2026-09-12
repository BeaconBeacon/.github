# A remote machine won't boot. Now what?

*The moment a machine stops booting is the moment every tool you use to reach it stops working. That is not a coincidence — they all live inside the thing that just failed.*

## First, work out which kind of dead it is

You cannot fix what you cannot see, but you can usually narrow it down by what
still responds.

| Symptom | What is probably true | Reachable remotely? |
|---|---|---|
| Pings, no SSH | OS is up, service or disk problem | Yes, with a KVM |
| No ping, fans spinning | Stuck in POST, bootloader, or filesystem check | Only with a KVM |
| No ping, no fans | Power supply, or the machine is off | No. Somebody has to go |
| Boots, then reboots | Overheating, bad update, failing disk | Yes, with a KVM |

The second and fourth rows are where most of the wasted trips happen. The
machine is fine — it is sitting at a prompt nobody can read.

---

This is the opening of the article. **[Read it in full at beacon-kvm.com →](https://beacon-kvm.com/blogs/use-cases/server-wont-boot-remote)**

More: [all articles](README.md) · [Beacon KVM](https://beacon-kvm.com) · [Raspberry Pi build](https://github.com/BeaconBeacon/KVM) · [Discord](https://discord.gg/jjXN7H6WcH)
