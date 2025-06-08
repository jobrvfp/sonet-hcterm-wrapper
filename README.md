Copy your hcterm.dll into it.
Run build-and-register.bat as administrator.

In VFP use:
oTerm = CREATEOBJECT("HcTermWrapper.HcTermCom")
? oTerm.Init()
? oTerm.OpenTcp("192.168.0.100", 5555)
