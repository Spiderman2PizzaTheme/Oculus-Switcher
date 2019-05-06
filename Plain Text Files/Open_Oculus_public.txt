@echo off
net start OVRService
timeout 4
cd "C:\Program Files\Oculus\Support\oculus-client"
start OculusClient.exe
exit