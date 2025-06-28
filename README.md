# 🚀 Advanced Task Manager Pro open source



## ✨ Features

### 🎯 **Advanced Process Management**
- **Right-click context menus** - No buttons needed!
- **Kill, Suspend, Resume** processes instantly
- **Locate process files** in explorer
- **Set process priorities** (Realtime, High, Normal, Low)
- **Detailed process information** with real-time stats
- **Search and filter** processes in real-time
- **Copy process info** to clipboard
- **Online process lookup** for security analysis

### 📊 **Real-time Performance Monitoring**
- **Live performance graphs** - CPU, Memory, Network, Disk
- **Color-coded metrics** for easy identification
- **Performance statistics** with averages and peaks
- **50-point history** for trend analysis
- **Ultra-fast updates** every 500ms

### 👁️ **Enhanced Process Visibility**
- **Show hidden/system processes** that Windows hides
- **Kernel-level process detection**
- **Extended process information** (PID, Threads, Handles, Path)
- **Process tree relationships**
- **Real-time CPU and memory usage**

### 🎨 **Modern Interface**
- **Dark theme** with professional appearance
- **Colorful accents** - Blue, Green, Orange, Purple, Red
- **Tabbed interface** for organized data
- **Enhanced status bar** with system info
- **Keyboard shortcuts** for power users

### ⚡ **Performance Optimized**
- **Multi-threaded monitoring** for responsiveness
- **Queue-based data processing** prevents GUI blocking
- **Optimized process listing** with smart filtering
- **Memory efficient** data structures
- **Cross-platform compatibility**

### 🔧 **Professional Features**
- **Export process lists** to JSON
- **Performance report generation**
- **Settings import/export**
- **Network connection monitoring**
- **System information display**
- **Alert system** for monitoring thresholds

---


## 🚀 Installation

### Method 1: Run from Source
```bash
# Clone the repository
git clone https://github.com/yourusername/advanced-task-manager.git
cd advanced-task-manager

# Install dependencies
pip install -r requirements.txt

# Run the application
python task.py
```

### Method 2: Download Executable
1. Go to [Releases](https://github.com/yourusername/advanced-task-manager/releases)
2. Download `TaskManagerPro_v3.0.exe`
3. Run directly - no installation needed!

### Dependencies
```
psutil>=5.9.0
matplotlib>=3.5.0
tkinter (included with Python)
```

---

## 💻 Usage

### Basic Operations
- **Launch**: Double-click `task.py` or the executable
- **Kill Process**: Right-click any process → "Kill Process"
- **Locate File**: Right-click process → "Locate Process File"
- **Search**: Type in the search box to filter processes
- **Refresh**: Press `F5` or `Ctrl+R` for manual refresh

### Keyboard Shortcuts
- `Ctrl+R` - Refresh all data
- `F5` - Force refresh
- `Ctrl+F` - Focus search box
- `Delete` - Kill selected process
- `Ctrl+D` - Show process details
- `Esc` - Clear selection

### Context Menu Options
Right-click any process for:
- 🗡️ **Kill Process** - Terminate immediately
- ⏸️ **Suspend Process** - Pause execution
- ▶️ **Resume Process** - Resume execution
- 📍 **Locate Process File** - Open in file explorer
- 🔍 **Process Details** - Detailed information window
- ⚡ **Set Priority** - Change process priority
- 📋 **Copy Process Info** - Copy to clipboard
- 🔗 **Search Online** - Google process information

---

## 🏗️ Building Executable

### Using PyInstaller (Recommended)

```bash
# Install PyInstaller
pip install pyinstaller

# Build executable
pyinstaller --onefile --windowed --name "TaskManagerPro" task.py

# Find executable in dist/ folder
```

### Using the Build Script
```bash
# Windows users can use the automated build script
.\build_exe.bat
```

### Build Options
- `--onefile` - Single executable file
- `--windowed` - No console window
- `--icon=icon.ico` - Custom icon
- `--name` - Custom executable name

---

## 📋 Requirements

### System Requirements
- **OS**: Windows 7+, macOS 10.12+, Linux (most distributions)
- **Python**: 3.7 or higher
- **RAM**: 50MB minimum
- **Disk**: 100MB for source, 80MB for executable

### Python Dependencies
```txt
psutil>=5.9.0
matplotlib>=3.5.0
```

### Optional Dependencies
```txt
pyinstaller>=5.0.0  # For building executable
```

---

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Development Setup
```bash
git clone https://github.com/yourusername/advanced-task-manager.git
cd advanced-task-manager
pip install -r requirements.txt
# Start developing!
```

---

## 👨‍💻 Author

**Dr. Mohammed Tawfik**
- 📧 Email: [kmkhol01@gmail.com](mailto:kmkhol01@gmail.com)
- 🐙 GitHub: [@yourusername](https://github.com/yourusername)
- 💼 LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/yourprofile)

---

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

```
MIT License

Copyright (c) 2024 Dr. Mohammed Tawfik

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---


---

## 🙏 Acknowledgments

- **psutil** - Cross-platform system and process utilities
- **matplotlib** - Plotting library for performance graphs
- **tkinter** - GUI framework
- **PyInstaller** - For creating standalone executables

---

<div align="center">

### 🌟 If you found this project helpful, please give it a star! 🌟

**Made with ❤️ by Dr. Mohammed Tawfik** kmkhol01@gmail.com

