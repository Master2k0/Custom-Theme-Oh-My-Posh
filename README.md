# Custom-Theme-Oh-My-Posh


oh-my-posh init pwsh --config C:\Users\sontran2x\Documents\PowerShell\custom.omp.json | Invoke-Expression
 
Import-Module -Name Terminal-Icons
Import-Module -Name PSReadLine
 
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
Set-PSReadLineOption -EditMode Windows
