# konvoy-cluster.yaml-foo - gpu-nodepools
Some konvoy cluster.yaml config examples

Note that for centos nodes use konvoy provision option initially, then ssh to each node in the gpu nodepool and perform a yum update and reboot, before completing the install using konvoy deploy option.

Ubuntu AMI already has the Nvidia drivers loaded in the kernel so install can be completed in one go using the konvoy up option.

