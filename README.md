# EBS-volume-mount-
EBS volume mount 

---
lsblk
sudo file -s /dev/xvdf
sudo mkfs -t xfs /dev/xvdf
sudo file -s /dev/xvdf
sudo mkdir /ebstest
sudo mount /dev/xvdf /ebstest
cd /ebstest
sudo nano amazingtestfile.txt
add a message
save and exit
ls -la
---
