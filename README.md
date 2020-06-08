# ODVariabletoHashTable
Convert a string variable in Octopus Deploy to a hash table in PowerShell

This will convert your Octopus deploy variable $ODVariable to a PowerShell hash table. An example of OD variable content that should be set as a multiline string:

@{Name                 = "ServiceName";     
	InstallLocation      = "C:\Services;
  ServiceExe           = "Process.exe";
	ServiceUserName      = "User"; 
  ServicePassword      = "Pass";
	ServiceInstallSource = "C:\Program Files\Services";
}
