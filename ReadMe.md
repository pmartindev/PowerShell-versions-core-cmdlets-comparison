Cmdlet | Description | v5 | v4 | v3 | v2
--- | --- | --- | --- | --- | --- | 
Add-History | Appends entries to the session history. | ✓ | ✓ | ✓ | ✓
Add-PSSnapin | Adds one or more Windows PowerShell snap-ins to the current session. | ✓ | ✓ | ✓ | ✓
Clear-History | Deletes entries from the command history. | ✓ | ✓ | ✓ | ✓
Connect-PSSession | Reconnects to disconnected sessions. | ✓ | ✓ | ✓ | -
Debug-Job | Debugs a running background, remote, or Windows PowerShell Workflow job. | ✓ | - | - | -
Disable-PSRemoting | Prevents remote users from running commands on the local computer. | ✓ | ✓ | ✓ | -
Disable-PSSessionConfiguration | Disables session configurations on the local computer. | ✓ | ✓ | ✓ | ✓
Disconnect-PSSession | Disconnects from a session. | ✓ | ✓ | ✓ | -
Enable-PSRemoting | Configures the computer to receive remote commands. | ✓ | ✓ | ✓ | ✓
Enable-PSSessionConfiguration | Enables the session configurations on the local computer. | ✓ | ✓ | ✓ | ✓
Enter-PSHostProcess | Connects to and enters into an interactive session with a local process. | ✓ | - | - | -
Enter-PSSession | Starts an interactive session with a remote computer. | ✓ | ✓ | ✓ | ✓
Exit-PSHostProcess | Closes an interactive session with a local process. | ✓ | - | - | -
Exit-PSSession | Ends an interactive session with a remote computer. | ✓ | ✓ | ✓ | ✓
Export-Console | Exports the names of snap-ins in the current session to a console file. | ✓ | ✓ | ✓ | ✓
Export-ModuleMember | Specifies the module members that are exported. | ✓ | ✓ | ✓ | ✓
ForEach-Object | Performs an operation against each item in a collection of input objects. | ✓ | ✓ | ✓ | ✓
Get-Command | Gets all commands. | ✓ | ✓ | ✓ | ✓
Get-Help | Displays information about Windows PowerShell commands and concepts. | ✓ | ✓ | ✓ | ✓
Get-History | Gets a list of the commands entered during the current session. | ✓ | ✓ | ✓ | ✓
Get-Job | Gets Windows PowerShell background jobs that are running in the current session. | ✓ | ✓ | ✓ | ✓
Get-Module | Gets the modules that have been imported or that can be imported into the current session. | ✓ | ✓ | ✓ | ✓
Get-PSSession | Gets the Windows PowerShell sessions on local and remote computers. | ✓ | ✓ | ✓ | ✓
Get-PSSessionCapability | Gets the capabilities of a specific user on a constrained session configuration. | ✓ | - | - | -
Get-PSSessionConfiguration | Gets the registered session configurations on the computer. | ✓ | ✓ | ✓ | ✓
Get-PSSnapin | Gets the Windows PowerShell snap-ins on the computer. | ✓ | ✓ | ✓ | ✓
Get-Verb | Gets approved Windows PowerShell verbs. | ✓ | ✓ | ✓ | -
Import-Module | Adds modules to the current session. | ✓ | ✓ | ✓ | ✓
Invoke-Command | Runs commands on local and remote computers. | ✓ | ✓ | ✓ | ✓
Invoke-History | Runs commands from the session history. | ✓ | ✓ | ✓ | ✓
New-Module | Creates a new dynamic module that exists only in memory. | ✓ | ✓ | ✓ | ✓
New-ModuleManifest | Creates a new module manifest. | ✓ | ✓ | ✓ | ✓
New-PSRoleCapabilityFile | Creates a file that defines a set of capabilities to be exposed through a session configuration. | ✓ | - | - | -
New-PSSession | Creates a persistent connection to a local or remote computer. | ✓ | ✓ | ✓ | ✓
New-PSSessionConfigurationFile | Creates a file that defines a session configuration. | ✓ | ✓ | ✓ | -
New-PSSessionOption | Creates an object that contains advanced options for a PSSession. | ✓ | ✓ | ✓ | ✓
New-PSTransportOption | Creates an object that contains advanced options for a session configuration. | ✓ | ✓ | ✓ | ✓
Out-Default | Sends the output to the default formatter and to the default output cmdlet. | ✓ | ✓ | ✓ | -
Out-Host | Sends output to the command line. | ✓ | ✓ | ✓ | -
Out-Null | Deletes output instead of sending it down the pipeline. | ✓ | ✓ | ✓ | -
Receive-Job | Gets the results of the Windows PowerShell background jobs in the current session. | ✓ | ✓ | ✓ | ✓
Receive-PSSession | Gets results of commands in disconnected sessions. | ✓ | ✓ | - | -
Register-PSSessionConfiguration | Creates and registers a new session configuration. | ✓ | ✓ | ✓ | ✓
Remove-Job | Deletes a Windows PowerShell background job. | ✓ | ✓ | ✓ | ✓
Remove-Module | Removes modules from the current session. | ✓ |   | ✓ | ✓
Remove-PSSession | Closes one or more Windows PowerShell sessions (PSSessions). | ✓ | ✓ | ✓ | ✓
Remove-PSSnapin | Removes Windows PowerShell snap-ins from the current session. | ✓ | ✓ | ✓ | ✓
Resume-Job | Restarts a suspended job. | ✓ | ✓ | ✓ | -
Save-Help | Downloads and saves the newest help files to a file system directory. | ✓ | ✓ | ✓ | -
Set-PSDebug | Turns script debugging features on and off, sets the trace level, and toggles strict mode. | ✓ | ✓ | ✓ | ✓
Set-PSSessionConfiguration | Changes the properties of a registered session configuration. | ✓ | ✓ | ✓ | ✓
Set-StrictMode | Establishes and enforces coding rules in expressions, scripts, and script blocks. | ✓ | ✓ | ✓ | ✓
Start-Job | Starts a Windows PowerShell background job. | ✓ | ✓ | ✓ | ✓
Stop-Job | Stops a Windows PowerShell background job. | ✓ | ✓ | ✓ | ✓
Suspend-Job | Temporarily stops workflow jobs. | ✓ | ✓ | ✓ | -
Test-ModuleManifest | Verifies that a module manifest file accurately describes the contents of a module. | ✓ | ✓ | ✓ | ✓
Test-PSSessionConfigurationFile | Verifies the keys and values in a session configuration file. | ✓ | ✓ | ✓ | -
Unregister-PSSessionConfiguration | Deletes registered session configurations from the computer. | ✓ | ✓ | ✓ | ✓
Update-Help | Downloads and installs the newest help files on your computer. | ✓ | ✓ | ✓ | -
Wait-Job | Suppresses the command prompt until one or all of the Windows PowerShell background jobs running in the session are completed. | ✓ | ✓ | ✓ | ✓
Where-Object | Selects objects from a collection based on their property values. | ✓ | ✓ | ✓ | ✓
