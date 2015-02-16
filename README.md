# bootstrap-atftpd

This is the build and configuration for the atftpd container used within bootstrapping a k8s master on bare-metal upon CoreOS.

As k8s currently doesn't support exposing UDP ports this is ran directly via fleet using the service file provided.

This is normally deployed as part of a OEM cloud config on a USB key.
