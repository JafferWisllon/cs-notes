# CS50 – Understanding Technology  
## Lecture: Hardware (Detailed Summary)

---

## 1. Computers and the Binary System

### 1.1 Why do computers use only 0s and 1s?
- Computers operate using **two physical states**:
  - **0** → off
  - **1** → on
- These states are easy to represent electrically using **transistors**, which act like microscopic switches.
- Billions of transistors inside a computer allow it to store data and perform computations.

---

## 2. Decimal vs Binary Number Systems

### 2.1 Decimal System (Base 10)
- Used by humans.
- Each digit position represents a power of 10:
  - 1, 10, 100, 1000…
- Example:
    123 = (1 × 100) + (2 × 10) + (3 × 1)

### 2.2 Binary System (Base 2)
- Used by computers.
- Each digit position represents a power of 2:
- 1, 2, 4, 8, 16, 32…
- Only two digits are available: **0 and 1**

#### Binary Examples
| Binary | Decimal |
|------|--------|
| 000 | 0 |
| 001 | 1 |
| 010 | 2 |
| 011 | 3 |
| 100 | 4 |
| 111 | 7 |
| 1000 | 8 |

👉 The idea is identical to the decimal system; only the base changes.

---

## 3. Bits and Bytes

- **Bit**: a single binary digit (0 or 1)
- **Byte**: 8 bits
- A byte can represent values from **0 to 255**

Bytes are commonly used to represent:
- Numbers
- Letters
- Symbols
- Instructions

---

## 4. Representing Text: ASCII and Unicode

### 4.1 ASCII (American Standard Code for Information Interchange)
- A standardized mapping from numbers to characters.
- Examples:
- 65 → `A`
- 66 → `B`
- 97 → `a`
- Originally used **7 bits** (128 characters), later extended to **8 bits** (256 characters).

### 4.2 Unicode
- A superset of ASCII.
- Supports:
- Multiple languages
- Accented characters
- Emojis 🙂
- Uses more bytes to represent a much larger set of symbols.

### 4.3 Context Matters
- Computers only store **bits**.
- Software decides how to interpret them:
- As numbers (calculator)
- As text (text editor)
- As images, audio, or video

---

## 5. Central Processing Unit (CPU)

### 5.1 What is the CPU?
- The **brain of the computer**
- Performs:
- Arithmetic operations
- Logic operations
- Data movement
- Executes billions of operations per second (GHz).

### 5.2 Cores and Hyperthreading
- **Core**: an independent processing unit inside a CPU.
- More cores → more tasks can run simultaneously.
- **Hyperthreading**:
- A single core appears as two logical processors.
- Improves efficiency and multitasking.

---

## 6. Memory Types

### 6.1 RAM (Random Access Memory)
- Volatile memory (data is lost when power is off).
- Stores:
- Running programs
- Open files
- Very fast compared to disk storage.
- Common sizes: 8GB, 16GB, 32GB.

---

## 7. Storage (Non-Volatile Memory)

### 7.1 Hard Disk Drives (HDD)
- Mechanical storage using spinning platters.
- Data stored using **magnetic particles**.
- Pros:
- Large capacity
- Lower cost
- Cons:
- Slower
- Moving parts (can fail)

### 7.2 Solid State Drives (SSD)
- No moving parts.
- Uses flash memory.
- Pros:
- Much faster
- More reliable
- Cons:
- More expensive
- Limited number of write cycles

### 7.3 Hybrid Drives
- Combine HDD + SSD.
- Frequently used data is kept on the SSD portion.

---

## 8. Memory Hierarchy (The Funnel Model)

From slowest & largest to fastest & smallest:

1. **Disk (HDD / SSD)** – terabytes, slowest
2. **RAM** – gigabytes
3. **Cache**
 - L3 Cache (MB)
 - L2 Cache (KB–MB)
 - L1 Cache (KB)
4. **Registers** – bytes, fastest

### Key Trade-offs
- Speed ↑ → Size ↓ → Cost ↑
- Purpose: keep data as close as possible to the CPU.

---

## 9. Registers
- Smallest and fastest memory.
- Located inside the CPU.
- Used for:
- Temporary values
- Arithmetic operations

---

## 10. Ports and Connectivity

### 10.1 Display Ports
- VGA (legacy)
- HDMI
- DisplayPort
- Mini DisplayPort

### 10.2 USB (Universal Serial Bus)
- Used for:
- Keyboard
- Mouse
- Printers
- External storage
- Variants:
- USB-A
- USB-B
- USB-C (reversible, faster)

### 10.3 Wireless Technologies
- **Wi-Fi**: internet connectivity
- **Bluetooth**: short-range device communication

---

## 11. Operating System (OS)

### 11.1 Role of the OS
- Software that manages hardware.
- Examples:
- Windows
- macOS
- Linux
- Responsibilities:
- Memory management
- File system
- Device communication
- User interface

### 11.2 Device Drivers
- Specialized software that allows the OS to communicate with hardware.
- Can be installed later to support new devices.

---

## 12. Inside a Computer (Physical Components)

- **Motherboard**: central communication hub
- **CPU + Heatsink + Fan**: processing and cooling
- **RAM sticks**: volatile memory
- **Power Supply (PSU)**: distributes power
- **Storage devices**: HDD, SSD
- **Expansion slots (PCI)**: graphics cards, sound cards

---

## 13. Key Takeaways

- Computers only understand **0s and 1s**, but clever abstraction makes them powerful.
- Hardware and software work together.
- Performance depends on:
- CPU speed and cores
- Amount of RAM
- Storage type (SSD vs HDD)
- Understanding hardware helps you make better technical and purchasing decisions.

---
