#########################################################

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3

Code to find and kill a process given either a numerical PID or an English name (like "python").

Reuben Brewer, Ph.D.

reuben.brewer@gmail.com

www.reubotics.com

Apache 2 License

Software Revision H, 02/02/2025

Verified working on:

Python 2.7, 3.12.

Windows 11 64-bit

Raspberry Pi Buster

GetPIDsByProcessEnglishName: Returns [PID_DictWithPIDasKey, PID_DictWithEXEenglishNameAsKey] for an input ProcessName string (in English, like "VLC", "python", or "notepad").

KillProcessByPIDlist: Kills/force-closes processes specified by their PID number.

Can kill programs based on their English name from the command line like this:

python GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3.py "EnglishNameOfProgramYouWishToKill" "kill"

#########################################################

######################################################### Python module installation instructions, all OS's

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies: ['future.builtins', 'pexpect']

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies_TestProgram: []

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies_NestedLayers: []

GetPIDsByProcessEnglishNameAndOptionallyKill_ReubenPython2and3, ListOfModuleDependencies_All:['future.builtins', 'pexpect']

#########################################################
