[Setup]
AppName=mushaf_ds
AppVersion=1.0
DefaultDirName={pf}\mushaf_ds
DefaultGroupName=mushaf_ds
OutputBaseFilename=mushaf_dsInstaller
Compression=lzma
SolidCompression=yes

[Files]
Source: "C:\mushaf_ds\*"; DestDir: "{app}"; Flags: ignoreversion recursesubdirs createallsubdirs

[Icons]
Name: "{group}\mushaf_ds"; Filename: "{app}\mushaf_ds.exe"
Name: "{commondesktop}\mushaf_ds"; Filename: "{app}\mushaf_ds.exe"
Name: "{group}\Uninstall mushaf_ds"; Filename: "{uninstallexe}"
