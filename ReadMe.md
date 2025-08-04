# Mietzens Debian Repository

This repository automatically creates and maintains a Debian package repository hosted on GitHub Pages by pulling `.deb` packages from GitHub releases.

## Usage

### Adding the Repository to your System

```bash
echo "deb [trusted=yes] https://mietzen.github.io/debian-pkg-repo/ stable main" | sudo tee /etc/apt/sources.list.d/mietzens-deb-pkgs.list
sudo apt-get update
```

## License

This repository structure and scripts are provided under MIT License. Individual packages retain their original licenses.
