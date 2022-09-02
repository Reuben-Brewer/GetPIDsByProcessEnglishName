#########################################################

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3

Code to find and kill a process given either a numerical PID or an English name (like "python").

Reuben Brewer, Ph.D.

reuben.brewer@gmail.com

www.reubotics.com

Apache 2 License

Software Revision D, 08/29/2022

Verified working on:
Python 2.7, 3.8.
Windows 8.1, 10 64-bit
Raspberry Pi Buster 
(no Mac testing yet)

GetPIDsByProcessEnglishName: Returns [PID_DictWithPIDasKey, PID_DictWithEXEenglishNameAsKey] for an input ProcessName string (in English, like "VLC", "python", or "notepad").

KillProcessByPIDlist: Kills/force-closes processes specified by their PID number.

Can kill programs based on their English name from the command line like this:
python GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3.py "EnglishNameOfProgramYouWishToKill" "kill"

#########################################################

######################################################### Python module installation instructions, all OS's

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies: ['future.builtins', 'pexpect']
GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies_TestProgram: []
GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies_NestedLayers: []
GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies_All: ['future.builtins', 'pexpect']

#########################################################