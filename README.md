# PowerShellTestModuleManifestBrokenSinceV3
Repro for Powershell/Powershell developers

1. New-ModuleManifest -Path .\Example.psd1 -CompanyName "MyCompany" -RootModule "Eample.psm1" -FunctionsToExport @("Get-ScriptDirectory")
