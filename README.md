# Useful-Script-for-Registry-Run-Box-Task-Manager
Created by SMN666

Registry Editor Enable Script:

@echo off
REG DELETE HKCU\SOFTWARE\MICROSOFT\WINDOWS\CURRENTVERSION\POLICIES\EXPLORER/V DisableRegistry Tools /f


Run Box Enable Script:

@echo off
REG DELETE HKCU\SOFTWARE\MICROSOFT\WINDOWS\CURRENTVERSION\POLICIES\EXPLORER /V NoRun /f


Task Manager Enable:

@echo off
REG DELETE HKCU\SOFTWARE\MICROSOFT\WINDOWS\CURRENTVERSION\POLICIES\SYSTEM /V DisableTaskMgr /f
