# 🖥️ Metin2 Private Server on macOS (Apple Silicon) using Parallels Desktop

This guide explains how to set up **Windows 11 ARM** with **Parallels Desktop** on macOS (M1 / M2 / M3) to play Metin2 private servers that **do not work with Wine due to client-side anti-cheat**.

---

## 🇩🇪 Deutsche Anleitung

### Voraussetzungen

* Mac mit Apple Silicon (M1 / M2 / M3)
* Parallels Desktop
* Windows 11 ARM ISO
  👉 [https://www.microsoft.com/de-de/software-download/windows11arm64](https://www.microsoft.com/de-de/software-download/windows11arm64)

---

## Installation von Windows 11 (ARM)

### 1. Parallels Startbildschirm

Auswahl zwischen **„Get Windows 11“** und manueller Installation.

❌ **NICHT** „Get Windows 11“ auswählen
✅ **Install Windows, Linux or macOS from an image file**

![Step 1](screenshots/1.png)

---

### 2. ISO-Datei auswählen

Hier auf **„From an image file“ / „Datei auswählen“** klicken und die Windows-ISO auswählen.

![Step 2](screenshots/2.png)

---

### 3. ISO-Erkennung

Parallels erkennt automatisch die Windows-Version aus der ISO.

![Step 3](screenshots/3.png)

---

### 4. Windows Edition auswählen

* **Windows 11 Pro** auswählen (empfohlen)

![Step 4](screenshots/4.png)

---

### 5. Verwendungszweck auswählen

* In der **Trial-Version** ist nur die vorausgewählte Option verfügbar
* Auswahl unverändert lassen

![Step 5](screenshots/5.png)

---

### 6. Name & Speicherort festlegen

❗ **Sehr wichtig**
✅ **Haken setzen bei:**
**„Einstellungen vor dem Erstellen bearbeiten“**

> Ohne diesen Schritt wächst die virtuelle Festplatte später unkontrolliert weiter.

![Step 6](screenshots/6.png)

---

### 7. CPU & Arbeitsspeicher

* **CPU & Memory** auf **Empfohlen** lassen
  (sollte standardmäßig bereits so eingestellt sein)

![Step 7](screenshots/7.png)

---

### 8. Festplattenübersicht

* Reiter **Hard Disk**
* Aktuelle VM-Festplatte wird angezeigt
* Auf **Erweitert** klicken

![Step 8](screenshots/8.png)

---

### 9. Erweiterte Festplattenoptionen

* **Beide Haken setzen**
* Danach auf **Eigenschaften** klicken

![Step 9](screenshots/9.png)

---

### 10. Größe der VM-Festplatte festlegen

* **Mindestens 40 GB**
* Mehr empfohlen (z. B. 60–80 GB)

![Step 10](screenshots/10.png)

---

### 11. Grafikeinstellungen

* Reiter **Graphics**
* Modus auf **Scaled** setzen

⚠️ Verhindert automatisches Parallels-Scaling und Darstellungsprobleme

![Step 11](screenshots/11.png)

---

## 🔧 Windows 11 optimieren (SEHR EMPFOHLEN)

Nach erfolgreicher Installation solltest du Windows 11 **debloaten**, um:

* geringere CPU- & RAM-Auslastung
* weniger Hintergrunddienste
* bessere Gaming-Performance

### Win11Debloat

👉 [https://github.com/Raphire/Win11Debloat](https://github.com/Raphire/Win11Debloat)

* Open Source
* Detaillierte Anleitung im Repository
* Sicher für Gaming-VMs
* Besonders sinnvoll in Parallels-VMs

---

## ❗ Warum Parallels und nicht Wine?

* Metin2 Private Server nutzen **Client-side Anti-Cheat**
* Wine wird erkannt und blockiert ❌
* Parallels stellt ein **echtes Windows-System** bereit ✅

### 💡 Lizenz-Hinweis

* Parallels ist kostenpflichtig
* **14 Tage kostenlose Testversion**
* Accounts sind schnell erstellt
* Lizenz **nicht accountgebunden**
* Nach Ablauf kann ein neuer Account verwendet werden

---

## 🇬🇧 English Guide

### Requirements

* Mac with Apple Silicon (M1 / M2 / M3)
* Parallels Desktop
* Windows 11 ARM ISO
  👉 [https://www.microsoft.com/software-download/windows11arm64](https://www.microsoft.com/software-download/windows11arm64)

---

## Windows 11 (ARM) Installation

### 1. Parallels start screen

Choose between **“Get Windows 11”** and manual installation.

❌ Do **NOT** select “Get Windows 11”
✅ **Install Windows, Linux or macOS from an image file**

![Step 1](screenshots/1.png)

---

### 2. Select ISO file

Click **From an image file** and select the Windows ISO.

![Step 2](screenshots/2.png)

---

### 3. ISO detection

Parallels automatically detects the Windows version inside the ISO.

![Step 3](screenshots/3.png)

---

### 4. Select Windows edition

* Choose **Windows 11 Pro** (recommended)

![Step 4](screenshots/4.png)

---

### 5. Usage type

* Trial version allows only the preselected option
* Leave it unchanged or set to Games but I usually use Productivity

![Step 5](screenshots/5.png)

---

### 6. Name & location

❗ **Very important**
✅ Enable:
**Customize settings before installation**

> Without this step, the virtual disk may grow uncontrollably later.

![Step 6](screenshots/6.png)

---

### 7. CPU & Memory

* Leave **CPU & Memory** on **Recommended**

![Step 7](screenshots/7.png)

---

### 8. Hard disk overview

* Open **Hard Disk**
* Click **Advanced**

![Step 8](screenshots/8.png)

---

### 9. Advanced disk options

* Enable **both checkboxes**
* Click **Properties**

![Step 9](screenshots/9.png)

---

### 10. Set virtual disk size

* **Minimum 40 GB**
* More recommended (60–80 GB)

![Step 10](screenshots/10.png)

---

### 11. Graphics settings

* Open **Graphics**
* Set mode to **Scaled**

⚠️ Prevents Parallels auto-scaling issues

![Step 11](screenshots/11.png)

---

## 🔧 Optimize Windows 11 (Highly Recommended)

Use **Win11Debloat** to:

* reduce background services
* lower CPU & RAM usage
* improve gaming performance

👉 [https://github.com/Raphire/Win11Debloat](https://github.com/Raphire/Win11Debloat)

---

## ❗ Why Parallels instead of Wine?

* Metin2 private servers use **client-side anti-cheat**
* Wine is detected and blocked ❌
* Parallels runs a **real Windows environment** ✅
