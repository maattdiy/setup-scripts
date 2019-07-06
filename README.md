My general setup scripts.  
See also: [autohotkey-scripts](https://maattdiy.github.io/autohotkey-scripts/), [gists](https://gist.github.com/maattdiy)

### Prerequisites (Chocolatey and Boxstarter)
`@"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin" && choco feature enable -n allowGlobalConfirmation && choco install boxstarter`

### Windows Setup (Basic) [Gist](https://gist.github.com/maattdiy/190776c957780d7148f471dc22f074a2)
`Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/maattdiy/47a07f9c3a012f54b7671bc24aedbff4/raw/b1a010cc4f24d158dd2baa0c1df1d2b0a96303b6/win-dev.txt`

### Windows Setup (Developer) [Gist](https://gist.github.com/maattdiy/47a07f9c3a012f54b7671bc24aedbff4)
`Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/maattdiy/47a07f9c3a012f54b7671bc24aedbff4/raw/b1a010cc4f24d158dd2baa0c1df1d2b0a96303b6/win-dev.txt`

### AutoHotKey [Gist](https://gist.github.com/maattdiy/18302277ba4df3bb97b7b62fdac7324a)
`Install-BoxstarterPackage -PackageName https://gist.githubusercontent.com/maattdiy/18302277ba4df3bb97b7b62fdac7324a/raw/6913f576736f0cbe0457a68151814e83f62f86eb/ahk.txt -DisableReboots`
