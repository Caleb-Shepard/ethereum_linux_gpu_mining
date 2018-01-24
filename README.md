# ethereum_linux_gpu_mining
Setup scripts for Ethereum mining on the Ubuntu operating system

## Usage
`git clone https://github.com/Caleb-Shepard/ethereum_linux_gpu_mining`

`cd ethereum_linux_gpu_mining`

`chmod +x *.sh`

`#pick the script corresponding to your GPU type and`

`./script.sh`

Be sure to modify the script variables to fit your needs.
You may need to run as root and change the $(whoami) 
statements on 73 and 76 to assign the start job to the correct user.

In the rare case that you have both an AMD and Nvidia card in your computer,
I believe that it is possible to use these configurations to mine ETH on both
at the same time. I have not tried this personally but there isn't an
apparent reason for it not to work out. 

Linux Kernel versions > 4.13 reportedly have open source AMD drivers that perform
better than their proprietary counterparts. I do not know this is true but 
have managed to get slightly better performance on an AMD Radeon RX 560 
than I achieved on Windows 10 with a similar setup using proprietary drivers. 
(+ < 0.5 MH/s)
