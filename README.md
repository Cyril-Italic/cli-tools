# CLI-TOOLS

## Installation

**Automated install**

```
curl -sSL https://raw.githubusercontent.com/germain-italic/cli-tools/master/installer.sh | bash
```

**Or Manual install**

```
git clone https://github.com/germain-italic/cli-tools.git ~/cli-tools

echo -e "source ~/cli-tools/tools.sh" >> ~/.bashrc && source ~/.bashrc
```

# Uninstall

```
sed -i '/source ~/cli-tools\/tools.sh/d' ~/.bashrc && source ~/.bashrc
```
