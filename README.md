# 🌊JETSKI QUBIC POOL🌊

<div align="center">
<h3> <picture> <img src = "https://discords.com/_next/image?url=https%3A%2F%2Fcdn.discordapp.com%2Femojis%2F983705077590130719.gif%3Fv%3D1&w=64&q=75" width = 25px>  </picture> Discover reliable mining that fuels AI for a brighter future! <img src = "https://discords.com/_next/image?url=https%3A%2F%2Fcdn.discordapp.com%2Femojis%2F983705077590130719.gif%3Fv%3D1&w=64&q=75" width = 25px
	<!--horizontal divider(gradiant)-->
	
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
	<img align="right" width=200px height=200px alt="side_sticker" src="https://media.giphy.com/media/TEnXkcsHrP4YedChhA/giphy.gif" />
</div>


### <picture> <img src = "https://github.com/7oSkaaa/7oSkaaa/blob/main/Images/Statistics.gif?raw=true" width = 30px>  </picture> Pool Dashboard:

### ➡️ https://qubic.jetskipool.ai/

### <a target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/discord.svg" height="30" width="40" /></a> Discord Server:

### ➡️ https://discord.jetskipool.ai/


> [!NOTE]
> Miners are preconfigured to connect with the pool. You just need to update your alias with your Wallet Address and Worker Name, separated by a dash (-).

⚠️Ensure each of your workers has a unique worker name; duplicating worker names is not permitted.⚠️


# 🌴HIVE OS FS:🌴

### **💥Installation URL:**

### ➡️ https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/latest/qubjetski-latest.tar.gz

![image](https://github.com/user-attachments/assets/ca0c3dfa-57d1-4df0-b38f-3f1ecbb0a454)


> [!IMPORTANT]
> **For instance: "%WAL%-%WORKER_NAME%"**
>
> %WAL%- will use the Qubic wallet address that you configured in your HiveOS account.
>
> -%WORKER_NAME% will automatically use your HiveOS rig name without requiring you to replace it manually.









##  <img src="https://media.giphy.com/media/W5eoZHPpUx9sapR0eu/giphy.gif" width="30px" alt="Git"/>&nbsp;<b>Extra Config Arguments:</b></p>

### ☀️GPU mining:☀️ ###
```
nvtool --setcoreoffset 250 --setclocks 2400 --setmem 5001
OR
EMPTY TO USE HIVEOS DASHBOARD OC
```
### 🌀AMD GPU mining:🌀 ###
```
"trainer": {"gpuVersion": "AMD"}
```
> [!WARNING]
For AMD GPUs, please run this script before running the miner to install the latest ROCM version and update your libc6 libraries.
```
amd-ocl-install 5.7 5.7 && cd /opt/rocm/lib && apt install unzip && wget https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/1.9.7-JETSKI-POOL/libamdhip64.so.zip && unzip libamdhip64.so.zip && chmod +rwx /opt/rocm/lib/* && rm libamdhip64.so.zip && cd / && ldconfig &&
echo "deb http://archive.ubuntu.com/ubuntu jammy main" >> /etc/apt/sources.list && apt update && apt upgrade -y && apt install g++-11 -y && apt install libc6 -y
```
### 🏖️CPU mining:🏖️ ### 
(For Huge Pages: Numbers of threads x 138)
```
"cpuOnly":"yes" 
"amountOfThreads":32
"hugePages":4416
```
### ⚡GPU+CPU (Dual mining:)⚡ ###
(For Huge Pages: Numbers of threads x 138)
```
nvtool --setcoreoffset 250 --setclocks 2400 --setmem 5001 OR EMPTY FOR HIVEOS DASHBOARD OC
"amountOfThreads":32
"hugePages":4416
```


## Recommended GPU overclocks:

### 🪢Medium:
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

***3000 Series:***

	nvtool --setcoreoffset 250 --setclocks 1500 --setmem 5001
***4000 Series:***

	nvtool --setcoreoffset 250 --setclocks 2400 --setmem 5001

### 🪢High:
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

***3000 Series:***

	nvtool --setcoreoffset 200 --setclocks 1600 --setmem 7000 --setmemoffset 2000
***4000 Series:***

	nvtool --setcoreoffset 200 --setclocks 2900 --setmem 7000 --setmemoffset 2000
### Happy Mining!❤️‍🔥
