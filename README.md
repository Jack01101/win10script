# Win10 Setup script
This is a fork of ChrisTitusTech's script. It was close to what I liked so no need to waste time making my own.

## My changes
- Removed Adobe
- Added all my chocolatey programs
- Kept Windows Defender

## Running the script

To run the script that also installs my applications via Chocolatey
```powershell
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JUbtQ')"
```
---

To run the script that does not install any Chocolatey applications:
```powershell
powershell -nop -c "iex(New-Object Net.WebClient).DownloadString('https://git.io/JT9YQ')"
```
