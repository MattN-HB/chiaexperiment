# Chia Coin Optimization Experiment
Comparing performance of different chia blockchain environments to determine most efficient mining setup
## Resources
* [Chia Github Link](https://github.com/Chia-Network/chia-blockchain)
* [Chia Explorer](https://www.chiaexplorer.com/)
* [Issues connecting to wallet](https://arstech.net/how-to-fix-chia-connecting-to-wallet-problem/)
* [Blaze Cloud Storage experiment](https://www.backblaze.com/blog/experimenting-cloud-storage-for-chia-mining/)
### Case 3: No more plotting run smallest connect to Cold HDD
* Ec2 instance size: t3a.small
* Volume 1: 30gb general purpose hdd (gp2) $3/month
* Volume 2: 8TB Cold HDD ($122/month)
* CPU at 1 plot : 2
* Memory: 2
* Up Speed: 800mbps and down 388mbps
* Time to Create Plot: NA
* Time to win: 1yr estimate
* Cloud Cost / Month: $150 ($22 instance size +$3 ebs base+ $8TB cold hdd 122)
* Coin Return / Month: TBD on time to win and present value of chia coin to dollar
* Net Profit: TBD
* When attach "existing with data" volume don't intiliaze/reformat you will wipe out your data stop at step 3>>! [EBS Volume Available for Use Windows Tutorial](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ebs-using-volumes.html)
    * If new drive for first time FORMAT IN GPT!!!!!
    * Important note about 2TB MTB drives for your cold HDD![image](https://user-images.githubusercontent.com/44328319/119240571-77e76b00-bb1e-11eb-9343-88b5ef94fcfe.png)
### Case 2: Windows Server 2019 
* Ec2 instance size: t2x.2large 
* Volume 1: 1TB general purpose hdd (gp2) ...4 plots parrell
* Volume 2: 5TB Cold HDD
* CPU at 1 plot : 8 (26%)
* CPU at 4 plot parrel : (95%)
* Memory: 5.4gib 32gib (50%)
* Up Speed: 800mbps and down 388mbps
* Time to Create Plot: 6hr (single plot) 2plots in 8hr, 4 plot 8hr ish,
* Estimated time to win: 10 plots = ;7 plots = 6 years; 12 plots = 4years; 35 plot = 2years
* Cloud Cost / Month: $360 
* Coin Return / Month:NA
* Net Profit: NA
* [Install Link](https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide)
* [EBS Volume Available for Use Windows Tutorial](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ebs-using-volumes.html)
* When attach "existing with data" volume don't intiliaze/reformat you will wipe out your data stop at step 3>>! [EBS Volume Available for Use Windows Tutorial](https://docs.aws.amazon.com/AWSEC2/latest/WindowsGuide/ebs-using-volumes.html)
    * If new drive for first time FORMAT IN GPT!!!!!
    * Important note about 2TB MTB drives for your cold HDD![image](https://user-images.githubusercontent.com/44328319/119240571-77e76b00-bb1e-11eb-
### Case 1: Windows Server 2019  
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
### Case 0: Windows Surface Pro  
* [Install Link](https://github.com/Chia-Network/chia-blockchain/wiki/Quick-Start-Guide)
* CPU: 87% across four cores
* Memory: 5gb/8gb (70%)
* Up Speed: 40mbs
* Time to Create Plot: 8hr ?? **RAN out space 100gb need 235 for one plot**
* Time to Farm and output:
### Case TBD: Rasberry Pi4 
* [Link How To](https://www.tomshardware.com/how-to/raspberry-pi-chia-coin)
    * What you need?
        - Raspberry Pi 4 4GB
        - Raspberry pi case, perhaps one of the best Raspberry Pi cases, with cooling
        - An external USB storage drive or SSD / HDD with USB 3.0 caddy.
        - 16GB Micro SD card or larger
        - Raspberry Pi Imager tool
        - Accessories to use your Raspberry Pi 4
