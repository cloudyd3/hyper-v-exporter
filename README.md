# hyper-v-exporter

Prometheus exporter for various Hyper-V metrics.

## Installation

```bash
git clone https://github.com/cloudyd3/hyper-v-exporter.git
cd hyper-v-exporter
poetry install
```
## WMI classes coverage
### Priority: High
- [x] Win32_PerfFormattedData_VmmsVirtualMachineStats_HyperVVirtualMachineHealthSummary
- [x] Win32_PerfFormattedData_VidPerfProvider_HyperVVMVidPartition
- [x] Win32_PerfFormattedData_HvStats_HyperVHypervisor
- [x] Win32_PerfFormattedData_HvStats_HyperVHypervisorPartition
- [x] Win32_PerfFormattedData_HvStats_HyperVHypervisorRootPartition
- [x] Win32_PerfFormattedData_HvStats_HyperVHypervisorVirtualProcessor
- [x] Win32_PerfFormattedData_HvStats_HyperVHypervisorRootVirtualProcessor
- [x] Win32_PerfFormattedData_BalancerStats_HyperVDynamicMemoryVM
- [x] Win32_PerfFormattedData_BalancerStats_HyperVDynamicMemoryBalancer
- [x] Win32_PerfFormattedData_Counters_HyperVVirtualStorageDevice

### Priority: Medium 
- [x] Win32_PerfFormattedData_Counters_HyperVVirtualMachineBus
- [ ] Win32_PerfFormattedData_EthernetPerfProvider_HyperVLegacyNetworkAdapter
- [x] Win32_PerfFormattedData_NvspNicStats_HyperVVirtualNetworkAdapter
- [ ] Win32_PerfFormattedData_NvspPortStats_HyperVVirtualSwitchPort
- [ ] Win32_PerfFormattedData_NvspSwitchProcStats_HyperVVirtualSwitchProcessor
- [x] Win32_PerfFormattedData_NvspSwitchStats_HyperVVirtualSwitch

### Priority: Low
- [ ] Win32_PerfFormattedData_Counters_HyperVDynamicMemoryIntegrationService
- [ ] Win32_PerfFormattedData_GmoPerfProvider_HyperVVMSaveSnapshotandRestore
- [ ] Win32_PerfFormattedData_HvStats_HyperVHypervisorLogicalProcessor
- [ ] Win32_PerfFormattedData_HyperVReplicaStats_HyperVReplicaVM
- [ ] Win32_PerfFormattedData_IdePerfProvider_HyperVVirtualIDEControllerEmulated
- [ ] Win32_PerfFormattedData_LmPerfProvider_HyperVVMLiveMigration
- [ ] Win32_PerfFormattedData_RemotePerfProvider_HyperVVMRemoting
- [ ] Win32_PerfFormattedData_SvhdxFltPerfProvider_HyperVSharedVHDX
- [ ] Win32_PerfFormattedData_VidPerfProvider_HyperVVMVidNumaNode

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
