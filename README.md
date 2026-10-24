<div align="center">

<img src="https://raw.githubusercontent.com/jtskxx/JETSKI-Miner/HEAD/assets/jetski-miner.svg" alt="JETSKI" width="800">

<h1>QUBJETSKI (QUBIC)</h1>


<p>
  <a href="https://github.com/jtskxx/Jetski-Qubic-Pool/releases"><img src="https://img.shields.io/github/downloads/jtskxx/Jetski-Qubic-Pool/total?style=flat-square&amp;color=0078D4" alt="Total GitHub release downloads"></a>
  <img src="https://img.shields.io/badge/mining-CPU%20%7C%20GPU-76B900?style=flat-square" alt="CPU and GPU mining">
  <img src="https://img.shields.io/badge/payout-SOLO%20%7C%20PPLNS-E53935?style=flat-square" alt="SOLO and PPLNS payouts">
  <img src="https://img.shields.io/badge/platform-Linux%20%7C%20Windows-0078D4?style=flat-square" alt="Linux and Windows">
  <a href="#hiveos"><img src="https://img.shields.io/badge/HiveOS-custom%20miner-F5A623?style=flat-square" alt="HiveOS custom miner"></a>
  <a href="https://discord.jetskipool.ai/"><img src="https://img.shields.io/badge/Discord-join-5865F2?style=flat-square" alt="Join the Discord server"></a>
</p>

<p>
  <a href="https://qubic.jetskipool.ai"><strong>Dashboard</strong></a> ·
  <a href="https://download.jetskipool.ai/">Download</a> ·
  <a href="#quick-start">Quick start</a> ·
  <a href="#mining-modes">Mining modes</a> ·
  <a href="#options">Options</a> ·
  <a href="#hiveos">HiveOS</a>
</p>

</div>

## Pool

| Page | Link |
| --- | --- |
| Mining dashboard | [qubic.jetskipool.ai](https://qubic.jetskipool.ai) |
| Payout dashboard | [qubic.jetskipool.ai/payout](https://qubic.jetskipool.ai/payout) |
| Discord server | [discord.jetskipool.ai](https://discord.jetskipool.ai/) |

> [!IMPORTANT]
> **Every worker needs a unique worker name. Duplicate worker names are not allowed**

## Quick start

Download the miner from **[download.jetskipool.ai](https://download.jetskipool.ai/)**:

| Platform | File |
| --- | --- |
| Linux | `qubjetski-Linux-v4.5.tar.gz` |
| Windows | `qubjetski-Windows-v4.5.zip` |

Then launch the setup wizard:

- **Windows:** Extract the .zip, double-click `qubjetski-Miner.exe` and fill in **Wallet Address** and **Worker Name**
- **Linux:** Extract the archive and run the client, the wizard guides you step by step

```bash
tar -xvzf qubjetski-Linux-v4.5.tar.gz
cd qubjetski-Linux-v4.5
./qubjetski-Client
```

For command-line setup, see [Options](#options); for HiveOS, see [HiveOS setup](#hiveos)

<details>
<summary><strong>Windows screenshot</strong></summary>

<br>

<img width="1520" height="923" alt="qubjetski-Miner on Windows" src="https://github.com/user-attachments/assets/a17f66d9-97f3-4fe9-906c-f8587e3abd1a" />

</details>

## Mining modes

CPU and GPU power is used for Qubic AI training. Mine with either one, or both at once

| Hardware | Windows | Linux |
| --- | --- | --- |
| CPU only | Enable **CPU Mining** | `-cpu` |
| GPU only | Enable **GPU Mining** | `-gpu` |
| CPU + GPU | Enable **CPU Mining** and **GPU Mining** | `-cpu -gpu` |

| Payout | Linux | HiveOS |
| --- | --- | --- |
| SOLO | Default | [SOLO installation URL](#hiveos) |
| PPLNS | `-pplns` | [PPLNS installation URL](#hiveos) |

## Options

**Linux command-line options**

```text
./qubjetski-Client -wallet <wallet> -workername <worker> -gpu -start
```

| Option | Purpose |
| --- | --- |
| `-wallet ADDRESS` | Payout wallet address |
| `-workername NAME` | Worker name/alias, must be unique |
| `-cpu` | Enable CPU mining |
| `-threads N` | CPU mining thread count, `0` = auto |
| `-gpu` | Enable GPU mining |
| `-pplns` | Use the PPLNS pool, default: SOLO |
| `-start` | Start the client |
| `-help` | Show available commands |

Running `./qubjetski-Client` without options starts the setup wizard. Command-line mode is handy for large deployments

## HiveOS

In your Flight Sheet, select **Custom** miner and enter:

| Setting | Value |
| --- | --- |
| Installation URL (SOLO) | `https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/latest/qubjetski-latest.tar.gz` |
| Installation URL (PPLNS) | `https://github.com/jtskxx/Jetski-Qubic-Pool/releases/download/latest/qubjetski.PPLNS-latest.tar.gz` |
| Wallet and worker template | `%WAL%-%WORKER_NAME%` |
| Extra config arguments | Depends on your hardware, see below |

- **`%WAL%`** uses the Qubic wallet address configured in your HiveOS account
- **`%WORKER_NAME%`** uses your HiveOS rig name automatically, no need to replace it manually

**Extra config arguments**

**GPU only:** No extra config arguments needed

**CPU only**

```text
"cpuOnly":"yes"
"hugePages":1000
```

**CPU + GPU (dual mining)**

```text
"amountOfThreads":0
"hugePages":1000
```

- `"amountOfThreads":0` uses all available threads
- Set `"hugePages"` to 100 × your thread count, e.g. `1000` for 10 threads

## Licence

Licensed under **Anti-Military License**
