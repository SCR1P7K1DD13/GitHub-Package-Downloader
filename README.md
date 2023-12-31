# GPD: GitHub Package Downloader
![Python Version](https://img.shields.io/badge/python-3.x-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## Overview
GPD (GitHub Package Downloader) is a Python script that streamlines the process of downloading and installing packages directly from GitHub repositories. It leverages the GitHub API to search for repositories based on the specified package name, identifies the repository with the highest number of stars, and clones it to a local directory. GPD also offers the flexibility to proceed with a repo URL that the user have, or they could choose the default download method (auto-download based on github repo star ⭐).

## Features
- **GitHub Repository Search:** Utilizes the GitHub API to search for repositories based on the specified package name, sorting them by the number of stars.
- **Efficient Package Download:** Clones the selected repository to a local directory, checking for existing downloads to avoid unnecessary duplication.
- **Requirements Installation:** Installs package requirements from the `requirements.txt` file, if available.

## Usage
1. Run the script.
2. Enter the name of the package you want to download.
3. GPD will search GitHub, identify the top repository, and download it to the 'GPD' directory.

## Getting Started
```bash
git clone https://github.com/SCR1P7K1DD13/GitHub-Package-Downloader.git
cd GitHub-Package-Downloader
pip install -r requirements.txt
python gpd.py
```

## Dependencies
- GitPython: [GitPython](https://github.com/gitpython-developers/GitPython)
- Requests: [Requests](https://docs.python-requests.org/en/latest/)
- Colorama: [Colorama](https://github.com/tartley/colorama)
- PyFiglet: [PyFiglet](https://github.com/pwaller/pyfiglet)

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
