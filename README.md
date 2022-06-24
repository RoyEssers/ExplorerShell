# ExplorerShell
With this script you can add or remove a link to/from the left pane of the Windows file Explorer (like OneDrive or GoogleDrive), which will opens that particular folder.

New-ExplorerShellFolder -Name 'Github' -Path "$($env:USERPROFILE)\Documents\GitHub" -Force

Remove-ExplorerShellFolder -Name 'Github'
