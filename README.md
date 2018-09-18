# shutdownpi

This service lets you shut down a remote Raspberry or any other Unix system when
you shut down your main system.

## Instructions

1. Log in as root in your main system, and generate a pair of SSH keys.
2. `ssh-copy-id` the root user's public key into the remote Raspberry.
3. Edit and place the `shutdownpi.service` file in `/etc/systemd/system`.
4. Enable the service with `systemctl enable shutdownpi.service`.
