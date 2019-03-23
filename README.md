My general setup scripts.  
See also: [autohotkey-scripts](https://maattdiy.github.io/autohotkey-scripts/), [gists](https://gist.github.com/maattdiy)

### Prerequisites
`@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin" && choco feature enable -n allowGlobalConfirmation && choco install boxstarter`

### AutoHotKey
`Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/maattdiy/18302277ba4df3bb97b7b62fdac7324a/raw/6913f576736f0cbe0457a68151814e83f62f86eb/ahk.txt -DisableReboots`

### Windows Setup (Developer)
`Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/maattdiy/47a07f9c3a012f54b7671bc24aedbff4/raw/b1a010cc4f24d158dd2baa0c1df1d2b0a96303b6/win-dev.txt`
