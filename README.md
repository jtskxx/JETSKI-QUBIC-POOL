# 🌊JETSKI QUBIC POOL🌊

<div align="center">
<h3> <picture> <img src = "https://discords.com/_next/image?url=https%3A%2F%2Fcdn.discordapp.com%2Femojis%2F983705077590130719.gif%3Fv%3D1&w=64&q=75" width = 25px>  </picture> Join us to achieve true AI power powered by useful miners! <img src = "https://discords.com/_next/image?url=https%3A%2F%2Fcdn.discordapp.com%2Femojis%2F983705077590130719.gif%3Fv%3D1&w=64&q=75" width = 25px
	<!--horizontal divider(gradiant)-->
	
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">
	<img align="right" width=200px height=200px alt="side_sticker" src="https://media.giphy.com/media/TEnXkcsHrP4YedChhA/giphy.gif" />
</div>

### Mining Dashboard <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZW1ramN2N3lnZXFrajNod2VzcGhmcWM3ZG56YmVhbGx0NDc0ZGFpZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/clOgAGJ5iR1RVx5GUl/giphy.gif" width="18px"> https://qubic.jetskipool.ai

### Payout Dashboard <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZW1ramN2N3lnZXFrajNod2VzcGhmcWM3ZG56YmVhbGx0NDc0ZGFpZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/clOgAGJ5iR1RVx5GUl/giphy.gif" width="18px"> https://qubic.jetskipool.ai/payout

### Discord Server <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZW1ramN2N3lnZXFrajNod2VzcGhmcWM3ZG56YmVhbGx0NDc0ZGFpZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/clOgAGJ5iR1RVx5GUl/giphy.gif" width="18px"> https://discord.jetskipool.ai/




<br/>

## <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYjh0bW1nb3lpYzMwY2h1bWs2MWt0NWZsdzdiNWRrN3NzNm85MGR3MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/sUEkwdECIoepv2Caib/giphy.gif" width = 60px> Summary <img src = "https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExYjh0bW1nb3lpYzMwY2h1bWs2MWt0NWZsdzdiNWRrN3NzNm85MGR3MiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/sUEkwdECIoepv2Caib/giphy.gif" width = 60px>

1. **🌴 [HiveOS Setup](#%EF%B8%8F-flight-sheet-configuration)** 
2. **🥥 [Linux Setup](#-linux-setup-)**
3. **<img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGtnMHhjZzh3dTMwM3psZ2ZxNDFwbjB2b25zdWdvdzg0bW9nMWd2OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/PhYTgixTZOrdFNrxHk/giphy.gif" width="18px"> [Windows Setup](#-windows-setup-)**
5. **🌊 [Docker Setup](#-docker-setup-)**

<br/>

> [!IMPORTANT]
> **Ensure each of your workers has a unique worker name; duplicate worker names is not allowed!**

<br/>

## ✈️ Flight Sheet Configuration

### Solo Mining <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZW1ramN2N3lnZXFrajNod2VzcGhmcWM3ZG56YmVhbGx0NDc0ZGFpZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/clOgAGJ5iR1RVx5GUl/giphy.gif" width="18px"> https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/latest/qubjetski-latest.tar.gz
### PPLNS Mining <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExZW1ramN2N3lnZXFrajNod2VzcGhmcWM3ZG56YmVhbGx0NDc0ZGFpZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/clOgAGJ5iR1RVx5GUl/giphy.gif" width="18px"> https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/latest/qubjetski.PPLNS-latest.tar.gz

<br/>

> [!IMPORTANT]
> **For instance: `%WAL%-%WORKER_NAME%`**
>
> **`%WAL%-` will use the Qubic wallet address that you configured in your HiveOS account**
>
> **`-%WORKER_NAME%` will automatically use your HiveOS rig name without requiring you to replace it manually**

<br>

##  <img src="https://media.giphy.com/media/W5eoZHPpUx9sapR0eu/giphy.gif" width="30px" alt="Git"/>&nbsp;<b>Extra Config Arguments</b></p>

### ☀️GPU mining☀️ ###
```

```

### 🏖️CPU mining🏖️ ###
> [!NOTE]
> **`"amountOfThreads":0` = All available Threads**
>

`Huge Pages: (100 x Numbers of threads)`
```
"cpuOnly":"yes"
"hugePages":1000
```
### ⚡GPU+CPU (Dual mining)⚡ ###
```
"amountOfThreads":0
"hugePages":1000
```

<br>

# <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2tsdHBlcnl4Z21leWc1aHNyejFmbXJkcjZ5YXJoM2RsMzQ2Z2JvdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/WFZvB7VIXBgiz3oDXE/giphy.gif" width="30px"> Linux Setup <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExd2tsdHBlcnl4Z21leWc1aHNyejFmbXJkcjZ5YXJoM2RsMzQ2Z2JvdiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/WFZvB7VIXBgiz3oDXE/giphy.gif" width="30px">

### **1️⃣ Download the Miner**
**Go to https://download.jetskipool.ai/ to download `qubjetski-Linux-v3.0.tar.gz`**

<br>

### **2️⃣ Extract the Miner**
```
tar -xvzf qubjetski-Linux-v3.0.tar.gz
cd qubjetski-Linux-v3.0
```
<br>

### **3️⃣ Launch the Miner**

Once extracted, you can start the miner in two simple ways:

### - **Quick Start (Wizard Mode)**
Just run the miner directly and the setup wizard will guide you step-by-step

### - **Advanced (Command Line Mode)**
For large deployments, you can launch with custom flags

### `./qubjetski-Client`

|  Setting 		|  Description 	|
|---	|---	|
|   `-wallet` |  **Your wallet address**  	|
|  `-workername` |  **Set worker name/alias**	|
|    `-cpu` |  **Enable CPU mining**	|
|    `-threads`  	|  **Set number of CPU threads (0 = auto)**  	|
|    `-gpu` | **Enable GPU mining** 	|
|   `-pplns`  |  **Use PPLNS pool (default = SOLO)**	|
|   `-start`   |  **Start the client**	|
|   `-help ` |  **Show available commands**	|

<br>

# <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGtnMHhjZzh3dTMwM3psZ2ZxNDFwbjB2b25zdWdvdzg0bW9nMWd2OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/PhYTgixTZOrdFNrxHk/giphy.gif" width="30px"> Windows Setup <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExaGtnMHhjZzh3dTMwM3psZ2ZxNDFwbjB2b25zdWdvdzg0bW9nMWd2OSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/PhYTgixTZOrdFNrxHk/giphy.gif" width="30px">

### **1️⃣ Download the Miner**
**Go to https://download.jetskipool.ai/ to download `qubjetski-Windows-v3.0.zip`**

<br>

### **2️⃣ Extract the Miner**
**Extract the .zip file**

- **The default Windows unzipper or WinRAR can be used to decompress the file**
- **Once extracted, navigate to the folder where the miner is located**

<br>

### **3️⃣ Launch the Miner**

Once extracted, double-click on `qubjetski-Miner.exe` and fill in the **Wallet Address** and **Worker Name** fields

### Mining Options

**CPU-only mining**
`Enable CPU Mining`

- CPU → used for AI Training

**GPU-only mining**
`Enable GPU Mining`

- GPU → used for AI Training

**CPU + GPU mining**
`Enable` all options: `CPU Mining, GPU Mining`

- CPU + GPU → both used for AI Training

<img width="1520" height="923" alt="win" src="https://github.com/user-attachments/assets/a17f66d9-97f3-4fe9-906c-f8587e3abd1a" />


<br>

# <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXVtcGNwZDd1Z2tldjE5NXNyOTc0M2R0bmhnazg0ZDl4aGQxZmZieSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/ViCcQEvD4yYHUZKguG/giphy.gif" width="30px"> Docker Setup <img src="https://media0.giphy.com/media/v1.Y2lkPTc5MGI3NjExbXVtcGNwZDd1Z2tldjE5NXNyOTc0M2R0bmhnazg0ZDl4aGQxZmZieSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/ViCcQEvD4yYHUZKguG/giphy.gif" width="30px">

### **Docker Deployment:**
Docker images are available for large-scale deployments, these images are ideal for use with rental platforms such as Vast.ai, Salad, and Clore.AI

**Below are the available Docker images and their corresponding run options:**

### <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHF6YnhpMDV3ajFiZzh6aHgwbng0YzBseHdieHY2MTA5OHdudjM2ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/HrRvnN7NuJy4InG4MV/giphy.gif" width="30px"> Quick Start Command: <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMHF6YnhpMDV3ajFiZzh6aHgwbng0YzBseHdieHY2MTA5OHdudjM2ayZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9cw/HrRvnN7NuJy4InG4MV/giphy.gif" width="30px">

- **CPU Mining :** `docker run --rm jetskipool/miner:qubjetski --pplns -w WALLET --cpu`
- **GPU Mining :** `docker run --rm --gpus all jetskipool/miner:qubjetski --pplns -w WALLET --gpu`
- **CPU+GPU Mining :** `docker run --rm --gpus all jetskipool/miner:qubjetski --pplns -w WALLET --cpu --gpu`

|  Setting 		|  Description 	|
|---	|---	|
|   `-wallet` |  **Your wallet address**  	|
|  `-workername` |  **Set worker name/alias**	|
|    `-cpu` |  **Enable CPU mining**	|
|    `-threads`  	|  **Set number of CPU threads (0 = auto)**  	|
|    `-gpu` | **Enable GPU mining** 	|
|   `-pplns`  |  **Use PPLNS pool (default = SOLO)**	|

---
<p align="center"><sub> LICENSED UNDER ANTI-MILITARY LICENSE</sub></p>
