# Openshift Automatic NFS Provisioner

Automate the nfs provisioner for the baremetal/libvirt OCP installations [NO Production environment ready]

This role will provision an NFS server and create an nfs-provisioner class on an Openshift Cluster

## Openshift Persistent Storage Types

Understanding OpenShift Persistent Storage Types
------------------------------------------------
Access Mode  |  CLI Abbreviation  | Description
--|---|--
ReadWriteOnce  |  RWO  | The volume can be mounted as read-write by a single node.
ReadOnlyMany  | ROX  | The volume can be mounted as read-only by many nodes.
ReadWriteMany  | RWX  | The volume can be mounted as read-write by many nodes.
