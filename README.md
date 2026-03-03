# The-Automation-Specialist
A real-time Python automation service that uses the Watchdog API to monitor directories and automatically sort downloads into categorized folders like Documents, Media, and Data.


# 🚀 Smart Sentinel: Automated File Organizer

**Smart Sentinel** is a Python-based background service that monitors your directories in real-time and automatically sorts incoming files into categorized folders based on their extensions.



## 🛠️ Features
- **Real-Time Monitoring:** Uses the `watchdog` API to observe file system events without wasting CPU cycles.
- **Data & Spreadsheet Support:** Automatically detects and organizes `.csv`, `.xlsx`, and `.json` files into a dedicated Data folder.
- **Collision Handling:** Smart renaming logic (e.g., `data_1.csv`) prevents accidental overwrites if a file with the same name already exists.
- **Modern Path Handling:** Built using `pathlib` for cross-platform compatibility (Windows, macOS, Linux).

## 📂 How It Organizes
| File Type | Destination Folder |
| :--- | :--- |
| `.pdf`, `.docx`, `.txt` | `Documents/` |
| `.csv`, `.xlsx`, `.json` | `Documents/Data/` |
| `.jpg`, `.png`, `.jpeg` | `Media/Images/` |
| `.zip`, `.tar` | `Archives/` |

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- pip (Python package manager)

### Installation
1. Clone the repository:
   ```bash
   git clone (https://github.com/Sanskruti5623/The-Automation-Specialist)
