# Forensic Version Checker
Script that checks for available updates for the most commonly used Digital Forensics tools.

![FVC screenshot](https://github.com/jankais3r/Forensic-Version-Checker/blob/master/screen.png)


![CLI interface](https://github.com/jankais3r/Forensic-Version-Checker/blob/master/cli.png)
FVC v1.5+ also comes with a command line interface. In this mode, the tools you don't use are not being reported.

## Supported tools
- EnCase
- BlackLight
- MacQuisition
- AXIOM
- UFED 4PC
- Physical Analyzer
- OSForensics
- ForensicExplorer
- USB Detective
- FTK
- FTK Imager
- XAMN
- X-Ways
- CyberChef
- NSRL hash list
- Arsenal Image Mounter
- Passware
- hashcat
- ExifTool
- Belkasoft Evidence Center
- CAINE
- DEFT
- Forensic Falcon Neo
- Atola TaskForce
- Forensic Email Collector
- VeraCrypt

If your favorite tool is missing, feel free to open an Issue and provide me with a link to that tool's website.

## Dependencies
```
pip3 install grequests
pip3 install beautifulsoup4
```

## Tested with Python 3.7 under
- Windows 10
- Ubuntu WSL (requires X server, e.g. Xming)
