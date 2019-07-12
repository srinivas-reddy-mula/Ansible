
##  softwares need to be installed on your system

    1.Chocolety Package Manager
        Install with cmd.exe:
            @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
        

        Install with PowerShell.exe:
            Set-ExecutionPolicy Bypass -Scope Process -Force; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
    2.Visual Studio
        '''
        choco install vscode
        '''


    3.Git bash
        '''
        choco install git.install
        '''