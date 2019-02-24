# ZabbixTemplates/MikroTic

For small wireless router,Products: RB911G-5HPnD

mtxrWireless	GROUP	1.3.6.1.4.1.14988.1.1.1
iso(1). org(3). dod(6). internet(1). private(4). enterprises(1). mikrotik(14988). mikrotikExperimentalModule(1). mtXRouterOs(1). mtxrWireless(1)
  	mtxrWlStatTable	TABLE	not-accessible	SEQUENCE OF	1.3.6.1.4.1.14988.1.1.1.1
  	  	mtxrWlStatEntry	ENTRY	not-accessible	MtxrWlStatEntry	1.3.6.1.4.1.14988.1.1.1.1.1
  	  	  	mtxrWlStatIndex	TABULAR	not-accessible	ObjectIndex	1.3.6.1.4.1.14988.1.1.1.1.1.1
  	  	  	mtxrWlStatTxRate	TABULAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.1.1.2
  	  	  	mtxrWlStatRxRate	TABULAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.1.1.3
  	  	  	mtxrWlStatStrength	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.1.1.4
  	  	  	mtxrWlStatSsid	TABULAR	read-only	DisplayString	1.3.6.1.4.1.14988.1.1.1.1.1.5
  	  	  	mtxrWlStatBssid	TABULAR	read-only	MacAddress	1.3.6.1.4.1.14988.1.1.1.1.1.6
  	  	  	mtxrWlStatFreq	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.1.1.7
  	  	  	mtxrWlStatBand	TABULAR	read-only	DisplayString	1.3.6.1.4.1.14988.1.1.1.1.1.8
  	mtxrWlRtabTable	TABLE	not-accessible	SEQUENCE OF	1.3.6.1.4.1.14988.1.1.1.2
  	  	mtxrWlRtabEntry	ENTRY	not-accessible	MtxrWlRtabEntry	1.3.6.1.4.1.14988.1.1.1.2.1
  	  	  	mtxrWlRtabAddr	TABULAR	not-accessible	MacAddress	1.3.6.1.4.1.14988.1.1.1.2.1.1
  	  	  	mtxrWlRtabIface	TABULAR	not-accessible	ObjectIndex	1.3.6.1.4.1.14988.1.1.1.2.1.2
  	  	  	mtxrWlRtabStrength	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.3
  	  	  	mtxrWlRtabTxBytes	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.2.1.4
  	  	  	mtxrWlRtabRxBytes	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.2.1.5
  	  	  	mtxrWlRtabTxPackets	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.2.1.6
  	  	  	mtxrWlRtabRxPackets	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.2.1.7
  	  	  	mtxrWlRtabTxRate	TABULAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.2.1.8
  	  	  	mtxrWlRtabRxRate	TABULAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.2.1.9
  	  	  	mtxrWlRtabRouterOSVersion	TABULAR	read-only	DisplayString	1.3.6.1.4.1.14988.1.1.1.2.1.10
  	  	  	mtxrWlRtabUptime	TABULAR	read-only	TimeTicks	1.3.6.1.4.1.14988.1.1.1.2.1.11
  	  	  	mtxrWlRtabSignalToNoise	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.12
  	  	  	mtxrWlRtabTxStrengthCh0	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.13
  	  	  	mtxrWlRtabRxStrengthCh0	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.14
  	  	  	mtxrWlRtabTxStrengthCh1	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.15
  	  	  	mtxrWlRtabRxStrengthCh1	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.16
  	  	  	mtxrWlRtabTxStrengthCh2	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.17
  	  	  	mtxrWlRtabRxStrengthCh2	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.2.1.18
  	mtxrWlRtabEntryCount	SCALAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.4.0
  	mtxrWlApTable	TABLE	not-accessible	SEQUENCE OF	1.3.6.1.4.1.14988.1.1.1.3
  	  	mtxrWlApEntry	ENTRY	not-accessible	MtxrWlApEntry	1.3.6.1.4.1.14988.1.1.1.3.1
  	  	  	mtxrWlApIndex	TABULAR	not-accessible	ObjectIndex	1.3.6.1.4.1.14988.1.1.1.3.1.1
  	  	  	mtxrWlApTxRate	TABULAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.3.1.2
  	  	  	mtxrWlApRxRate	TABULAR	read-only	Gauge32	1.3.6.1.4.1.14988.1.1.1.3.1.3
  	  	  	mtxrWlApSsid	TABULAR	read-only	DisplayString	1.3.6.1.4.1.14988.1.1.1.3.1.4
  	  	  	mtxrWlApBssid	TABULAR	read-only	MacAddress	1.3.6.1.4.1.14988.1.1.1.3.1.5
  	  	  	mtxrWlApClientCount	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.3.1.6
  	  	  	mtxrWlApFreq	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.3.1.7
  	  	  	mtxrWlApBand	TABULAR	read-only	DisplayString	1.3.6.1.4.1.14988.1.1.1.3.1.8
  	  	  	mtxrWlApNoiseFloor	TABULAR	read-only	Integer32	1.3.6.1.4.1.14988.1.1.1.3.1.9
  	  	  	mtxrWlApOverallTxCCQ	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.3.1.10
  	  	  	mtxrWlApAuthClientCount	TABULAR	read-only	Counter32	1.3.6.1.4.1.14988.1.1.1.3.1.11
