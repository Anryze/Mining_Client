Ubuntu/Debian
-----------------------------------
  **Download** [.tar.gz](https://anryze.com/miner/linux/miner-1.0.tar.gz)
  ### Dependencies
*  `sudo add-apt-repository ppa:linuxuprising/java`
*  `sudo apt-get update`
*  `sudo apt-get install oracle-java10-installer`
*  `sudo apt-get install oracle-java10-set-default`

 ### Basic Usage
 * Start: `sudo java -jar miner.jar --address <your ryz address>`
 * Stop: enter `e` to stop mining (ctrl+z will lead to an incorrect shutdown)

Requirements for the hardware:
-----------------------------------

- graphics core Nvidia, AMD or Intel 

### Nvidia 
- install the latest version of the graphics driver from the official website of the manufacturer of the laptop or the manufacturer of the GPU.
- it's important to test the driver with a simple test: run high-resolution video or another graphical task and look at the loading of the graphics core on the resource monitor (if there is always 0%, then something is wrong).
- in some cases, you need to install the latest version of CUDA Tolkit from the official site (https://developer.nvidia.com/cuda-toolkit).
### AMD 
- install the latest version of the graphics driver from the official website of the manufacturer of the laptop or the manufacturer of the GPU.
- it's important to test the driver with a simple test: run high-resolution video or another graphical task and look at the loading of the graphics core on the resource monitor (if there is always 0%, then something is wrong).
### Intel
- install the latest version of the graphics driver from the official website of the manufacturer of the laptop or the manufacturer of the GPU.
- it's important to test the driver with a simple test: run high-resolution video or another graphical task and look at the loading of the graphics core on the resource monitor (if there is always 0%, then something is wrong).
- the only the graphics processors which is suitable - the generation Skylake.
- computing on Intel cores is not efficient enough, weak kernels often do not have enough processing power to perform the task received from the server, and because of this, a critical stop of the script occurs with an error.
### Intel + AMD/Nvidia
- Sometimes there is a problem where, in the presence of two graphics processors, computing is performed on Intel. Unfortunately, this problem can be solved only by manually disconnecting the Intel video adapter in the Windows Device Manager.

If you followed the instructions above, but you still do not have the mining work, please fill in a short form so that our developers know about the problem and can solve it. (https://goo.gl/forms/yEfOm3gMMzRJ1y502).
