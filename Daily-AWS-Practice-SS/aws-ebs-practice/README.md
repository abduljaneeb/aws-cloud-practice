
# AWS EBS Practice

## Tasks Completed
- Connected to an EC2 instance using SSH
- Attached an EBS volume
- Created an XFS filesystem
- Created /data mount point
- Mounted the volume temporarily
- Configured permanent mounting using /etc/fstab

## Commands Used
```bash
lsblk
sudo mkfs.xfs /dev/nvme1n1
sudo mkdir /data
sudo mount /dev/nvme1n1 /data
df -Th
