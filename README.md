# 🔍 Nmap Reconnaissance Toolkit

A curated collection of **Nmap** commands, usage guides, and examples for beginners and cybersecurity enthusiasts. This repository will serve as a reference and practice base for exploring the capabilities of **Nmap** on **Kali Linux**.

---

## 📘 What is Nmap?

**Nmap (Network Mapper)** is a free and open-source tool for network discovery and security auditing. It is widely used by network administrators and ethical hackers to:

- Scan hosts and services on a network
- Identify open ports
- Detect OS and software versions
- Perform vulnerability assessments

> Nmap comes pre-installed on Kali Linux, making it easily accessible for penetration testing and reconnaissance tasks.

---

## 🛠️ How to Use Nmap on Kali Linux

### 🔹 Basic Syntax

```bash
nmap [options] <target>
```

- `<target>` can be an IP, hostname, or IP range.
- `[options]` define the type and depth of the scan.

---

## 🧪 Common Nmap Commands

### 1. **Ping Scan** – Check if host is up
```bash
nmap -sn 192.168.1.1
```

### 2. **Port Scan** – Scan most common 1000 ports
```bash
nmap 192.168.1.1
```

### 3. **Scan Multiple Targets**
```bash
nmap 192.168.1.1 192.168.1.2 192.168.1.3
```

### 4. **Scan an Entire Subnet**
```bash
nmap 192.168.1.0/24
```

### 5. **Service and Version Detection**
```bash
nmap -sV 192.168.1.1
```

### 6. **Operating System Detection**
```bash
nmap -O 192.168.1.1
```

### 7. **Aggressive Scan**
```bash
nmap -A 192.168.1.1
```

### 8. **Scan Specific Ports**
```bash
nmap -p 22,80,443 192.168.1.1
```

### 9. **Save Results to File**
```bash
nmap -oN output.txt 192.168.1.1
```

---

## 💡 Pro Tips

- Use `sudo` for advanced scanning options.
- Combine flags like `-sS -sV -O -A` for deeper analysis.
- Be ethical — never scan unauthorized networks.

---

## 🖼️ Screenshots

> 📷 Screenshots showing output and real scans will be added soon.

---

## 👩‍💻 Author

**Joyce**  
Cybersecurity Enthusiast | Penetration Tester in Training  
Initial Commit: ✅

---

## 📁 Coming Soon

- 📸 Practical scan examples with screenshots
- 🧪 Sample reports and scan results
- 📝 Shell script wrappers for automated scans

---

## 📜 License

This repo is open for learning and personal use. Please credit when using parts of it in your work.

---

Feel free to star ⭐ the repo if you find it helpful!

