# WindowsEnum

A Powershell Privilege Escalation Enumeration Script.

## Usage

To run the quick standard checks.

```powershell
.\WindowsEnum.ps1
```

Directly from CMD (you may need to change directory)

```
powershell -nologo -executionpolicy bypass -file WindowsEnum.ps1
```

Extended checks will search for config files, various interesting files, and passwords in files and the registry, etc. It will take some time so be patient.

```powershell
.\WindowsEnum.ps1 extended
```

```
powershell -nologo -executionpolicy bypass -file WindowsEnum.ps1 extended
```
