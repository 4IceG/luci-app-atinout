# luci-app-atinout

![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/luci-app-atinout?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/luci-app-atinout?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/luci-app-atinout?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/4IceG/luci-app-atinout/total)

#### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> LuCI interface for the atinout. The user interface supports AT commands. (LuCI JS)

#### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Interfejs LuCI dla programu atinout. Interfejs do wysyłania poleceń AT. (LuCI JS)

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Useful AT commands (My list of at commands for Quectel modems) / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Przydatne polecenia AT (Moja lista poleceń at dla modemów Quectel'a)
<details>
   <summary>Pokaż | Show me</summary>
   
``` bash
4x4/2x2 MIMO ON/OFF ➜ AT+QCFG="lte4x4mimo/disable",0;AT+QCFG="lte4x4mimo/disable",0
4x4/2x2 MIMO OFF/ON ➜ AT+QCFG="lte4x4mimo/disable",1;AT+QCFG="lte4x4mimo/disable",1
Disable Cell Lock ➜ AT+QNWLOCK="COMMON/4G",0;AT+QNWLOCK="COMMON/4G",0
Query ➜ AT+QNWLOCK="COMMON/4G";AT+QNWLOCK="COMMON/4G"
CellLock ➜ AT+QNWLOCK="COMMON/4G",NUM OF CELLS,FREQ,PCI;AT+QNWLOCK="COMMON/4G",1,
Check the signal info on each antenna port ➜ AT+QRSRP;AT+QRSRP
Query and Report Signal Strength ➜ AT+QCSQ;AT+QCSQ
Get the temperature of MT ➜ AT+QTEMP;AT+QTEMP
Check the firmware version ➜ AT+GMR;AT+GMR
Band Preferred ➜ AT+QNWPREFCFG="lte_band"?;AT+QNWPREFCFG="lte_band"?
Carrier Agregation Info ➜ AT+QCAINFO;AT+QCAINFO
Query the serving cell information ➜ AT+QENG="servingcell";AT+QENG="servingcell"
Query the information of neighbour cells ➜ AT+QENG="neighbourcell";AT+QENG="neighbourcell"
Query network information ➜ AT+QNWINFO;AT+QNWINFO
Band 1/3/7/8/20/38 ➜ AT+QNWPREFCFG="lte_band",1:3:7:8:20:38;AT+QNWPREFCFG="lte_band",1:3:7:8:20:38
SIM Preferred Message Storage ➜ AT+CPMS="SM","SM","SM";AT+CPMS="SM","SM","SM"
Modem memory preferred Message Storage ➜ AT+CPMS="ME","ME","ME";AT+CPMS="ME","ME","ME"
Save SMS Settings ➜ AT+CSAS;AT+CSAS
Reboot the modem ➜ AT+CFUN=1,1;AT+CFUN=1,1
Reset the modem ➜ AT+CFUN=1;AT+CFUN=1
Reset modem to factory default ➜ AT+QPRTPARA=3;AT+QPRTPARA=3
Save NVM items through reset/reboot ➜ AT+QPRTPARA=1;AT+QPRTPARA=1
QMI/PPP/Default ➜ AT+QCFG="usbnet",0;AT+QCFG="usbnet",0
ECM ➜ AT+QCFG="usbnet",1;AT+QCFG="usbnet",1
MBIM ➜ AT+QCFG="usbnet",2;AT+QCFG="usbnet",2
Set RAT to 4G-LTE only ➜ AT+QNWPREFCFG="mode_pref",LTE;AT+QNWPREFCFG="mode_pref",LTE
Set RAT to LTE & 5G NR ➜ AT+QNWPREFCFG= "mode_pref",LTE:NR5G;AT+QNWPREFCFG= "mode_pref",LTE:NR5G
WCDMA only ➜ AT+QCFG="nwscanmode",2,1;AT+QCFG="nwscanmode",2,1
GSM only ➜ AT+QCFG="nwscanmode",1,1;AT+QCFG="nwscanmode",1,1
Scan all modes ➜ AT+QNWPREFCFG="mode_pref",AUTO;AT+QNWPREFCFG="mode_pref",AUTO
```

</details>

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> Preview / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Podgląd

![]()
![]()
