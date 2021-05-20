# Chia Coin Optimization Experiment
Comparing performance of different chia blockchain environments to determine most efficient mining setup
## Analysis between Setups
* [Chia Github Link](https://github.com/Chia-Network/chia-blockchain)
* [Chia Explorer](https://www.chiaexplorer.com/)
### No more plotting run smallest connect to Cold HDD(Case 3)
### Windows Server 2019 (Case 2)
* Ec2 instance size: t2x.2large 
* Volume 1: 500gb general purpose hdd (gp2)
* Volume 2: 1TB Cold HDD
* CPU at 1 plot : 8 (26%)
* CPU at 2 plot parrel : (81%)
* Memory: 5.4gib 32gib (16%)
* Up Speed: 800mbps and down 388mbps
* Time to Create Plot: 6hr (single plot) 2plots in 8hr (barely had enough space by 1gb gap)
* Time to Farm and output: 10 plots = 
* Cloud Cost / Month: $278
* Coin Return / Month:NA
* Net Profit: NA
* [Install Link](https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide)
* [EBS Volume Available for Use Windows Tutorial](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ebs-using-volumes.html)
### Windows Server 2019  (Case 1)
* [Install Link](https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide)
* Ec2 instance size: t3a.large
* Volume 1: 500gb general purpose hdd (gp2)
* CPU: 2
* Memory: 3.5 of 8gib (42%)
* Up Speed: 800mbps and down 388mbps
* Time to Create Plot: 16hrs
* Time to Farm and output: NA
* Cloud Cost / Month: $150
* Coin Return / Month:NA
* Net Profit: NA
### Windows Surface Pro (Case 0) 
* [Install Link](https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide)
* CPU: 87% across four cores
* Memory: 5gb/8gb (70%)
* Up Speed: 40mbs
* Time to Create Plot: 8hr ?? **RAN out space 100gb need 235 for one plot**
* Time to Farm and output:
### Rasberry Pi4 (Case TBD)
* [Link How To](https://www.tomshardware.com/how-to/raspberry-pi-chia-coin)
    * What you need?
        - Raspberry Pi 4 4GB
        - Raspberry pi case, perhaps one of the best Raspberry Pi cases, with cooling
        - An external USB storage drive or SSD / HDD with USB 3.0 caddy.
        - 16GB Micro SD card or larger
        - Raspberry Pi Imager tool
        - Accessories to use your Raspberry Pi 4
