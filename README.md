# Apt World

**Apt World** is a lightweight command-line tool written in Python that parses the `/var/lib/dpkg/status` file on Debian-based systems to display a clean list of packages explicitly installed by the user.

This repository includes a **Debian package** that installs the script to `/usr/local/bin/apt-world`, making it easy to run from anywhere on your system.

---

## 📦 Installation

### Option 1: Download and Install the `.deb` Package

1. [Download the latest `.deb` release](https://github.com/Vukodlok/apt-world/releases) from the [Releases](https://github.com/Vukodlok/apt-world/releases) tab.
2. Install it using `dpkg`:
   ```bash
   sudo dpkg -i apt-world.deb

### Option 2: Clone and Build Locally

```bash
git clone https://github.com/Vukodlok/apt-world.git
cd apt-world
dpkg-deb --build debian
sudo dpkg -i apt-world.deb
```

## Usage

Once installed, run:

`apt-world`

### Example Output

bash  
build-essential  
curl  
git  
python3

### Run Locally

`python3 apt-world.py`

## License

MIT License. See LICENSE for details.

## Author

Mark Robuck  
[GitHub](https://github.com/Vukodlok)  
[LinkedIn](https://www.linkedin.com/in/mark-robuck-b4756620/)  
[Portfolio Website](https://mrmarkrobuck.wordpress.com)
