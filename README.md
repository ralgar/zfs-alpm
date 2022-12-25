# alpm-zfs

A libalpm script and hook that automatically creates a new ZFS snapshot before
 committing any transactions. This greatly increases data security during
 system upgrades, especially on desktop systems without a UPS.

## Installing

An AUR package is coming soon, but for now just install manually:
- Copy the hook to `/usr/share/libalpm/hooks`
- Copy the script to `/usr/share/libalpm/scripts`

## License

Distributed under the MIT License. See `LICENSE` for more info.
