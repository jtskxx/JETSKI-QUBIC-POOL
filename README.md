# 🌊Jetski-Qubic-Pool🌊

<div align="center">
<h3> <picture> <img src = "https://discords.com/_next/image?url=https%3A%2F%2Fcdn.discordapp.com%2Femojis%2F983705077590130719.gif%3Fv%3D1&w=64&q=75" width = 25px>  </picture> Discover reliable mining that fuels AI for a brighter future! <img src = "https://discords.com/_next/image?url=https%3A%2F%2Fcdn.discordapp.com%2Femojis%2F983705077590130719.gif%3Fv%3D1&w=64&q=75" width = 25px
	<!--horizontal divider(gradiant)-->
	
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
	<img align="right" width=200px height=200px alt="side_sticker" src="https://media.giphy.com/media/TEnXkcsHrP4YedChhA/giphy.gif" />
</div>


### <picture> <img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/Statistics.gif?raw=true" width = 30px>  </picture> Pool Dashboard:

### ➡️ https://qubic.jetskipool.xyz/

### <a target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" height="30" width="40" /></a> Discord Server:

### ➡️ https://discord.jetskipool.ai/


> [!NOTE]
> Miners are available preconfigured to link up with the pool. You just need to update your alias with your Worker Name and your Wallet Address.


> [!IMPORTANT]
> **For instance: "%WAL%.%WORKER_NAME%"**

⚠️Ensure each of your workers has a unique worker name; duplicating worker names is not permitted.⚠️


# 🌴HIVE OS FS:🌴

### **💥Installation URL:**

### ➡️ https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/latest/qubjetski-latest.tar.gz


![image](https://github.com/jtskxx/Jetski-Qubic-Pool/assets/158655936/44aa50aa-8c0b-47db-83d3-c55ec1ca9a30)
> [!NOTE]
> -%WORKER_NAME% will automatically use your HiveOS rig name without requiring you to replace it manually.









##  <img src="https://media.giphy.com/media/W5eoZHPpUx9sapR0eu/giphy.gif" width="30px" alt="Git"/>&nbsp;<i><b>Extra Config Arguments:</b></i></p>

### ☀️GPU mining:☀️ ###
```
nvtool --setcoreoffset 200 --setclocks 1600 --setmem 7000 --setmemoffset 2000
OR
EMPTY TO USE HIVEOS DASHBOARD OC
```
### 🌀AMD GPU mining:🌀 ###
> [!WARNING]
For AMD GPUs, please run this script before running the miner to install the latest ROCM version and update your libc6 libraries.
```
amd-ocl-install 5.7 5.7 && cd /opt/rocm/lib && apt install unzip && wget https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/1.9.7-JETSKI-POOL/libamdhip64.so.zip && unzip libamdhip64.so.zip && chmod +rwx /opt/rocm/lib/* && rm libamdhip64.so.zip && cd / && ldconfig &&
echo "deb http://archive.ubuntu.com/ubuntu jammy main" >> /etc/apt/sources.list && apt update && apt upgrade -y && apt install g++-11 -y && apt install libc6 -y
```
```
"trainer": {"gpuVersion": "AMD"}
```
### 🏖️CPU mining:🏖️ ### 
(For Huge Pages: Numbers of threads x 241)
```
"cpuOnly":"yes" 
"amountOfThreads":32
"hugePages":7712
```
### ⚡GPU+CPU (Dual mining:)⚡ ###
(For Huge Pages: Numbers of threads x 241)
```
nvtool --setcoreoffset 200 --setclocks 1600 --setmem 7000 --setmemoffset 2000 OR EMPTY FOR HIVEOS DASHBOARD OC
"amountOfThreads":32
"hugePages":7712
```


## Recommended GPU overclocks:

### Medium:
---
➡️***3000 Series:***

	nvtool --setcoreoffset 250 --setclocks 1500 --setmem 5001
➡️***4000 Series:***

	nvtool --setcoreoffset 250 --setclocks 2400 --setmem 5001

### High:
---

➡️***3000 Series:***

	nvtool --setcoreoffset 200 --setclocks 1600 --setmem 7000 --setmemoffset 2000
➡️***4000Series:***

	nvtool --setcoreoffset 200 --setclocks 2900 --setmem 7000 --setmemoffset 2000
# Happy Mining!
![image](https://github.com/jtskxx/Jetski-Qubic-Pool/assets/158655936/dd2e712c-50b4-4b5a-a5a9-5b05e9d7c64f)


🫶 A big thank you to Joetom for his work! Below is the original repository from Qubic.li. 🫶

https://github.com/qubic-li


