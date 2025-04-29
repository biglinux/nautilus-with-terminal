# Nautilus Patch & PKGBUILD

Welcome!  
This repository provides a custom patch and a PKGBUILD for the Nautilus file manager.

![image](https://github.com/user-attachments/assets/862fde02-b0a7-44c1-9462-a4ab026a67c0)


## About

Feel free to use this patch, fork the repository, and make improvements.  
If future versions of Nautilus require updates to the patch, please submit a pull request with your changes.  
**Please do not ask me to implement new features or maintain long-term compatibility.**

I created this patch as a personal challenge to see if I could do it—Nautilus is not my daily file manager.

## Repository Contents

- `0001-*.patch` – The patch file to be applied to Nautilus.
- `PKGBUILD` – The build script to generate the package for Arch Linux or compatible distributions.

The full source code can be found at:  
https://gitlab.gnome.org/bigbruno/nautilus

This repository only contains the patch and the PKGBUILD necessary for building the package.

## How to Use

1. **Clone this repository:**
   ```sh
   git clone https://github.com/YOUR-USERNAME/nautilus-patch.git
   cd nautilus-patch
   ```

2. **Build the package:**
   - Make sure you have the necessary build tools for your distribution.
   - Run:
     ```sh
     makepkg -si
     ```

3. **Contributing**
   - Improvements are welcome! Please submit a pull request if you have enhancements or fixes for future Nautilus versions.

---

Thank you for your interest!
