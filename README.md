# CmdLineRaw
AutoItSetOption ("WinTitleMatchMode", 2) If Not ProcessExists ( "SciTE.exe" ) Then     Run(@ProgramFilesDir &amp; "\AutoIt3\SciTE\SciTE.exe",@ProgramFilesDir &amp; "\AutoIt3\SciTE")     WinWaitActive("SciTE","",3)     SystemMetrics_WaitTillProcessIdleEX2('SciTE.exe',1234) EndIf ;ShellExecute($CmdLineRaw) Run(@ProgramFilesDir &amp; "\AutoIt3\SciTE\SciTE.exe " &amp; $CmdLineRaw
