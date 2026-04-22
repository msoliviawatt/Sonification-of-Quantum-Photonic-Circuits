# Instructions

These commands will need to be run in Windows Powershell because the modules don't work too well on WSL or Linux.

```
python.exe -m pip install --upgrade pip
```

```
Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope CurrentUser
```

```
python -m venv windows-env
```

```
.\windows-env\Scripts\Activate.ps1
```

```
pip install numpy matplotlib sounddevice
```