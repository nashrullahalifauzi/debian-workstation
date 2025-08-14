# Boot Messages

```bash
[    0.000000] Linux version 6.12.38+deb13-amd64 (debian-kernel@lists.debian.org) (x86_64-linux-gnu-gcc-14 (Debian 14.2.0-19) 14.2.0, GNU ld (GNU Binutils for Debian) 2.44) #1 SMP PREEMPT_DYNAMIC Debian 6.12.38-1 (2025-07-16)
[    0.000000] Command line: BOOT_IMAGE=/vmlinuz-6.12.38+deb13-amd64 root=/dev/mapper/syenasweta-root ro nvidia-drm.modeset=1 nvidia-drm.fbdev=1 quiet
[    0.000000] Disabled fast string operations
[    0.000000] reserving inaccessible SNB gfx pages
[    0.000000] BIOS-provided physical RAM map:
[    0.000000] BIOS-e820: [mem 0x0000000000000000-0x0000000000057fff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000058000-0x0000000000058fff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x0000000000059000-0x000000000009ffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000000100000-0x000000001fffffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000020000000-0x00000000201fffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000020200000-0x000000003fffffff] usable
[    0.000000] BIOS-e820: [mem 0x0000000040000000-0x00000000401fffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000040200000-0x00000000ba59efff] usable
[    0.000000] BIOS-e820: [mem 0x00000000ba59f000-0x00000000baa9efff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000baa9f000-0x00000000bab9efff] ACPI NVS
[    0.000000] BIOS-e820: [mem 0x00000000bab9f000-0x00000000babfefff] ACPI data
[    0.000000] BIOS-e820: [mem 0x00000000babff000-0x00000000babfffff] usable
[    0.000000] BIOS-e820: [mem 0x00000000f80f8000-0x00000000f80f8fff] reserved
[    0.000000] BIOS-e820: [mem 0x00000000fed1c000-0x00000000fed1ffff] reserved
[    0.000000] BIOS-e820: [mem 0x0000000100000000-0x000000083e5fffff] usable
[    0.000000] NX (Execute Disable) protection: active
[    0.000000] APIC: Static calls initialized
[    0.000000] e820: update [mem 0xb66f2018-0xb6702057] usable ==> usable
[    0.000000] e820: update [mem 0xb66e2018-0xb66f1e57] usable ==> usable
[    0.000000] e820: update [mem 0xb66d2018-0xb66e1657] usable ==> usable
[    0.000000] extended physical RAM map:
[    0.000000] reserve setup_data: [mem 0x0000000000000000-0x0000000000057fff] usable
[    0.000000] reserve setup_data: [mem 0x0000000000058000-0x0000000000058fff] ACPI NVS
[    0.000000] reserve setup_data: [mem 0x0000000000059000-0x000000000009ffff] usable
[    0.000000] reserve setup_data: [mem 0x0000000000100000-0x000000001fffffff] usable
[    0.000000] reserve setup_data: [mem 0x0000000020000000-0x00000000201fffff] reserved
[    0.000000] reserve setup_data: [mem 0x0000000020200000-0x000000003fffffff] usable
[    0.000000] reserve setup_data: [mem 0x0000000040000000-0x00000000401fffff] reserved
[    0.000000] reserve setup_data: [mem 0x0000000040200000-0x00000000b66d2017] usable
[    0.000000] reserve setup_data: [mem 0x00000000b66d2018-0x00000000b66e1657] usable
[    0.000000] reserve setup_data: [mem 0x00000000b66e1658-0x00000000b66e2017] usable
[    0.000000] reserve setup_data: [mem 0x00000000b66e2018-0x00000000b66f1e57] usable
[    0.000000] reserve setup_data: [mem 0x00000000b66f1e58-0x00000000b66f2017] usable
[    0.000000] reserve setup_data: [mem 0x00000000b66f2018-0x00000000b6702057] usable
[    0.000000] reserve setup_data: [mem 0x00000000b6702058-0x00000000ba59efff] usable
[    0.000000] reserve setup_data: [mem 0x00000000ba59f000-0x00000000baa9efff] reserved
[    0.000000] reserve setup_data: [mem 0x00000000baa9f000-0x00000000bab9efff] ACPI NVS
[    0.000000] reserve setup_data: [mem 0x00000000bab9f000-0x00000000babfefff] ACPI data
[    0.000000] reserve setup_data: [mem 0x00000000babff000-0x00000000babfffff] usable
[    0.000000] reserve setup_data: [mem 0x00000000f80f8000-0x00000000f80f8fff] reserved
[    0.000000] reserve setup_data: [mem 0x00000000fed1c000-0x00000000fed1ffff] reserved
[    0.000000] reserve setup_data: [mem 0x0000000100000000-0x000000083e5fffff] usable
[    0.000000] efi: EFI v2.0 by Lenovo
[    0.000000] efi: ACPI=0xbabfe000 ACPI 2.0=0xbabfe014 SMBIOS=0xbaa9e000 MOKvar=0xba89f000 INITRD=0xb699e398 
[    0.000000] efi: Not removing mem64: MMIO range=[0xf80f8000-0xf80f8fff] (4KB) from e820 map
[    0.000000] efi: Not removing mem65: MMIO range=[0xfed1c000-0xfed1ffff] (16KB) from e820 map
[    0.000000] secureboot: Secure boot disabled
[    0.000000] SMBIOS 2.6 present.
[    0.000000] DMI: LENOVO 42763KU/42763KU, BIOS 8BET66WW (1.46 ) 06/14/2018
[    0.000000] DMI: Memory slots populated: 4/4
[    0.000000] tsc: Fast TSC calibration using PIT
[    0.000000] tsc: Detected 2392.314 MHz processor
[    0.001220] e820: update [mem 0x00000000-0x00000fff] usable ==> reserved
[    0.001223] e820: remove [mem 0x000a0000-0x000fffff] usable
[    0.001235] last_pfn = 0x83e600 max_arch_pfn = 0x400000000
[    0.001242] MTRR map: 7 entries (3 fixed + 4 variable; max 23), built from 10 variable MTRRs
[    0.001245] x86/PAT: Configuration [0-7]: WB  WC  UC- UC  WB  WP  UC- WT  
[    0.002088] last_pfn = 0xbac00 max_arch_pfn = 0x400000000
[    0.015320] RAMDISK: [mem 0xa7d24000-0xac5c1fff]
[    0.015879] ACPI: Early table checksum verification disabled
[    0.015884] ACPI: RSDP 0x00000000BABFE014 000024 (v02 LENOVO)
[    0.015890] ACPI: XSDT 0x00000000BABFE120 0000AC (v01 LENOVO TP-8B    00001460 PTEC 00000002)
[    0.015897] ACPI: FACP 0x00000000BABE8000 0000F4 (v04 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015903] ACPI: DSDT 0x00000000BABEB000 00EA91 (v01 LENOVO TP-8B    00001460 INTL 20061109)
[    0.015907] ACPI: FACS 0x00000000BAB2D000 000040
[    0.015911] ACPI: FACS 0x00000000BAB2D000 000040
[    0.015914] ACPI: SLIC 0x00000000BABFD000 000176 (v01 LENOVO TP-8B    00001460 PTEC 00000001)
[    0.015917] ACPI: SSDT 0x00000000BABFC000 000249 (v01 LENOVO TP-SSDT2 00000200 INTL 20061109)
[    0.015921] ACPI: SSDT 0x00000000BABFB000 000033 (v01 LENOVO TP-SSDT1 00000100 INTL 20061109)
[    0.015925] ACPI: SSDT 0x00000000BABFA000 000797 (v01 LENOVO SataAhci 00001000 INTL 20061109)
[    0.015929] ACPI: HPET 0x00000000BABE7000 000038 (v01 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015932] ACPI: APIC 0x00000000BABE6000 000098 (v01 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015936] ACPI: MCFG 0x00000000BABE5000 00003C (v01 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015939] ACPI: ECDT 0x00000000BABE4000 000052 (v01 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015943] ACPI: ASF! 0x00000000BABEA000 0000A5 (v32 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015947] ACPI: TCPA 0x00000000BABE3000 000032 (v02 PTL    LENOVO   06040000 LNVO 00000001)
[    0.015951] ACPI: SSDT 0x00000000BABE2000 000AD7 (v01 PmRef  Cpu0Ist  00003000 INTL 20061109)
[    0.015954] ACPI: SSDT 0x00000000BABE1000 000996 (v01 PmRef  CpuPm    00003000 INTL 20061109)
[    0.015958] ACPI: DMAR 0x00000000BABE0000 0000E8 (v01 INTEL  SNB      00000001 INTL 00000001)
[    0.015962] ACPI: UEFI 0x00000000BABDF000 00003E (v01 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015965] ACPI: UEFI 0x00000000BABDE000 000042 (v01 PTL    COMBUF   00000001 PTL  00000001)
[    0.015969] ACPI: UEFI 0x00000000BABDD000 000292 (v01 LENOVO TP-8B    00001460 PTL  00000002)
[    0.015972] ACPI: Reserving FACP table memory at [mem 0xbabe8000-0xbabe80f3]
[    0.015974] ACPI: Reserving DSDT table memory at [mem 0xbabeb000-0xbabf9a90]
[    0.015975] ACPI: Reserving FACS table memory at [mem 0xbab2d000-0xbab2d03f]
[    0.015976] ACPI: Reserving FACS table memory at [mem 0xbab2d000-0xbab2d03f]
[    0.015977] ACPI: Reserving SLIC table memory at [mem 0xbabfd000-0xbabfd175]
[    0.015978] ACPI: Reserving SSDT table memory at [mem 0xbabfc000-0xbabfc248]
[    0.015979] ACPI: Reserving SSDT table memory at [mem 0xbabfb000-0xbabfb032]
[    0.015980] ACPI: Reserving SSDT table memory at [mem 0xbabfa000-0xbabfa796]
[    0.015981] ACPI: Reserving HPET table memory at [mem 0xbabe7000-0xbabe7037]
[    0.015983] ACPI: Reserving APIC table memory at [mem 0xbabe6000-0xbabe6097]
[    0.015984] ACPI: Reserving MCFG table memory at [mem 0xbabe5000-0xbabe503b]
[    0.015985] ACPI: Reserving ECDT table memory at [mem 0xbabe4000-0xbabe4051]
[    0.015986] ACPI: Reserving ASF! table memory at [mem 0xbabea000-0xbabea0a4]
[    0.015987] ACPI: Reserving TCPA table memory at [mem 0xbabe3000-0xbabe3031]
[    0.015988] ACPI: Reserving SSDT table memory at [mem 0xbabe2000-0xbabe2ad6]
[    0.015989] ACPI: Reserving SSDT table memory at [mem 0xbabe1000-0xbabe1995]
[    0.015990] ACPI: Reserving DMAR table memory at [mem 0xbabe0000-0xbabe00e7]
[    0.015991] ACPI: Reserving UEFI table memory at [mem 0xbabdf000-0xbabdf03d]
[    0.015992] ACPI: Reserving UEFI table memory at [mem 0xbabde000-0xbabde041]
[    0.015993] ACPI: Reserving UEFI table memory at [mem 0xbabdd000-0xbabdd291]
[    0.016148] No NUMA configuration found
[    0.016149] Faking a node at [mem 0x0000000000000000-0x000000083e5fffff]
[    0.016161] NODE_DATA(0) allocated [mem 0x83e5b9680-0x83e5e3fff]
[    0.016559] Zone ranges:
[    0.016560]   DMA      [mem 0x0000000000001000-0x0000000000ffffff]
[    0.016562]   DMA32    [mem 0x0000000001000000-0x00000000ffffffff]
[    0.016564]   Normal   [mem 0x0000000100000000-0x000000083e5fffff]
[    0.016566]   Device   empty
[    0.016567] Movable zone start for each node
[    0.016570] Early memory node ranges
[    0.016571]   node   0: [mem 0x0000000000001000-0x0000000000057fff]
[    0.016573]   node   0: [mem 0x0000000000059000-0x000000000009ffff]
[    0.016574]   node   0: [mem 0x0000000000100000-0x000000001fffffff]
[    0.016575]   node   0: [mem 0x0000000020200000-0x000000003fffffff]
[    0.016576]   node   0: [mem 0x0000000040200000-0x00000000ba59efff]
[    0.016578]   node   0: [mem 0x00000000babff000-0x00000000babfffff]
[    0.016579]   node   0: [mem 0x0000000100000000-0x000000083e5fffff]
[    0.016584] Initmem setup node 0 [mem 0x0000000000001000-0x000000083e5fffff]
[    0.016592] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.016594] On node 0, zone DMA: 1 pages in unavailable ranges
[    0.016625] On node 0, zone DMA: 96 pages in unavailable ranges
[    0.018602] On node 0, zone DMA32: 512 pages in unavailable ranges
[    0.022351] On node 0, zone DMA32: 512 pages in unavailable ranges
[    0.022382] On node 0, zone DMA32: 1632 pages in unavailable ranges
[    0.023045] On node 0, zone Normal: 21504 pages in unavailable ranges
[    0.023148] On node 0, zone Normal: 6656 pages in unavailable ranges
[    0.023170] Reserving Intel graphics memory at [mem 0xbba00000-0xbf9fffff]
[    0.023348] ACPI: PM-Timer IO Port: 0x408
[    0.023360] ACPI: LAPIC_NMI (acpi_id[0x00] high edge lint[0x1])
[    0.023362] ACPI: LAPIC_NMI (acpi_id[0x01] high edge lint[0x1])
[    0.023374] IOAPIC[0]: apic_id 2, version 32, address 0xfec00000, GSI 0-23
[    0.023377] ACPI: INT_SRC_OVR (bus 0 bus_irq 0 global_irq 2 dfl dfl)
[    0.023380] ACPI: INT_SRC_OVR (bus 0 bus_irq 9 global_irq 9 high level)
[    0.023385] ACPI: Using ACPI (MADT) for SMP configuration information
[    0.023387] ACPI: HPET id: 0x8086a301 base: 0xfed00000
[    0.023393] TSC deadline timer available
[    0.023400] CPU topo: Max. logical packages:   1
[    0.023401] CPU topo: Max. logical dies:       1
[    0.023401] CPU topo: Max. dies per package:   1
[    0.023408] CPU topo: Max. threads per core:   2
[    0.023409] CPU topo: Num. cores per package:     4
[    0.023410] CPU topo: Num. threads per package:   8
[    0.023410] CPU topo: Allowing 8 present CPUs plus 0 hotplug CPUs
[    0.023430] PM: hibernation: Registered nosave memory: [mem 0x00000000-0x00000fff]
[    0.023433] PM: hibernation: Registered nosave memory: [mem 0x00058000-0x00058fff]
[    0.023435] PM: hibernation: Registered nosave memory: [mem 0x000a0000-0x000fffff]
[    0.023437] PM: hibernation: Registered nosave memory: [mem 0x20000000-0x201fffff]
[    0.023439] PM: hibernation: Registered nosave memory: [mem 0x40000000-0x401fffff]
[    0.023441] PM: hibernation: Registered nosave memory: [mem 0xba59f000-0xbabfefff]
[    0.023443] PM: hibernation: Registered nosave memory: [mem 0xbac00000-0xffffffff]
[    0.023445] [mem 0xbfa00000-0xf80f7fff] available for PCI devices
[    0.023447] Booting paravirtualized kernel on bare hardware
[    0.023450] clocksource: refined-jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645519600211568 ns
[    0.030805] setup_percpu: NR_CPUS:8192 nr_cpumask_bits:8 nr_cpu_ids:8 nr_node_ids:1
[    0.032242] percpu: Embedded 66 pages/cpu s233472 r8192 d28672 u524288
[    0.032253] pcpu-alloc: s233472 r8192 d28672 u524288 alloc=1*2097152
[    0.032257] pcpu-alloc: [0] 0 1 2 3 [0] 4 5 6 7 
[    0.032281] Kernel command line: BOOT_IMAGE=/vmlinuz-6.12.38+deb13-amd64 root=/dev/mapper/syenasweta-root ro nvidia-drm.modeset=1 nvidia-drm.fbdev=1 quiet
[    0.032389] Unknown kernel command line parameters "BOOT_IMAGE=/vmlinuz-6.12.38+deb13-amd64", will be passed to user space.
[    0.036177] Dentry cache hash table entries: 4194304 (order: 13, 33554432 bytes, linear)
[    0.038098] Inode-cache hash table entries: 2097152 (order: 12, 16777216 bytes, linear)
[    0.038272] Fallback order for Node 0: 0 
[    0.038276] Built 1 zonelists, mobility grouping on.  Total pages: 8357694
[    0.038277] Policy zone: Normal
[    0.038289] mem auto-init: stack:all(zero), heap alloc:on, heap free:off
[    0.038299] software IO TLB: area num 8.
[    0.080851] SLUB: HWalign=64, Order=0-3, MinObjects=0, CPUs=8, Nodes=1
[    0.081010] Kernel/User page tables isolation: enabled
[    0.081109] ftrace: allocating 45713 entries in 179 pages
[    0.090243] ftrace: allocated 179 pages with 5 groups
[    0.091127] Dynamic Preempt: voluntary
[    0.091398] rcu: Preemptible hierarchical RCU implementation.
[    0.091399] rcu: 	RCU restricting CPUs from NR_CPUS=8192 to nr_cpu_ids=8.
[    0.091401] 	Trampoline variant of Tasks RCU enabled.
[    0.091402] 	Rude variant of Tasks RCU enabled.
[    0.091402] 	Tracing variant of Tasks RCU enabled.
[    0.091403] rcu: RCU calculated value of scheduler-enlistment delay is 25 jiffies.
[    0.091404] rcu: Adjusting geometry for rcu_fanout_leaf=16, nr_cpu_ids=8
[    0.091419] RCU Tasks: Setting shift to 3 and lim to 1 rcu_task_cb_adjust=1 rcu_task_cpu_ids=8.
[    0.091422] RCU Tasks Rude: Setting shift to 3 and lim to 1 rcu_task_cb_adjust=1 rcu_task_cpu_ids=8.
[    0.091424] RCU Tasks Trace: Setting shift to 3 and lim to 1 rcu_task_cb_adjust=1 rcu_task_cpu_ids=8.
[    0.098779] NR_IRQS: 524544, nr_irqs: 488, preallocated irqs: 16
[    0.099003] rcu: srcu_init: Setting srcu_struct sizes based on contention.
[    0.099132] Console: colour dummy device 80x25
[    0.099135] printk: legacy console [tty0] enabled
[    0.099438] ACPI: Core revision 20240827
[    0.099679] clocksource: hpet: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 133484882848 ns
[    0.099698] APIC: Switch to symmetric I/O mode setup
[    0.099700] DMAR: Host address width 36
[    0.099702] DMAR: DRHD base: 0x000000fed90000 flags: 0x0
[    0.099708] DMAR: dmar0: reg_base_addr fed90000 ver 1:0 cap c0000020e60262 ecap f0101a
[    0.099712] DMAR: DRHD base: 0x000000fed91000 flags: 0x1
[    0.099716] DMAR: dmar1: reg_base_addr fed91000 ver 1:0 cap c9008020660262 ecap f0105a
[    0.099719] DMAR: RMRR base: 0x000000ba8d5000 end: 0x000000ba8ebfff
[    0.099721] DMAR: RMRR base: 0x000000bb800000 end: 0x000000bf9fffff
[    0.099722] DMAR: [Firmware Bug]: No firmware reserved region can cover this RMRR [0x00000000bb800000-0x00000000bf9fffff], contact BIOS vendor for fixes
[    0.099729] DMAR: [Firmware Bug]: Your BIOS is broken; bad RMRR [0x00000000bb800000-0x00000000bf9fffff]
               BIOS vendor: LENOVO; Ver: 8BET66WW (1.46 ); Product Version: ThinkPad W520
[    0.099734] DMAR-IR: IOAPIC id 2 under DRHD base  0xfed91000 IOMMU 1
[    0.099736] DMAR-IR: HPET id 0 under DRHD base 0xfed91000
[    0.099737] DMAR-IR: Queued invalidation will be enabled to support x2apic and Intr-remapping.
[    0.100271] DMAR-IR: Enabled IRQ remapping in x2apic mode
[    0.100275] x2apic enabled
[    0.100348] APIC: Switched APIC routing to: cluster x2apic
[    0.100805] ..TIMER: vector=0x30 apic1=0 pin1=2 apic2=-1 pin2=-1
[    0.119697] clocksource: tsc-early: mask: 0xffffffffffffffff max_cycles: 0x227bdaa57aa, max_idle_ns: 440795235210 ns
[    0.119706] Calibrating delay loop (skipped), value calculated using timer frequency.. 4784.62 BogoMIPS (lpj=9569256)
[    0.119723] Disabled fast string operations
[    0.119739] CPU0: Thermal monitoring enabled (TM1)
[    0.119772] Last level iTLB entries: 4KB 512, 2MB 8, 4MB 8
[    0.119775] Last level dTLB entries: 4KB 512, 2MB 32, 4MB 32, 1GB 0
[    0.119779] process: using mwait in idle threads
[    0.119781] Spectre V1 : Mitigation: usercopy/swapgs barriers and __user pointer sanitization
[    0.119784] Spectre V2 : Mitigation: Retpolines
[    0.119785] Spectre V2 : Spectre v2 / SpectreRSB: Filling RSB on context switch and VMEXIT
[    0.119787] Spectre V2 : Enabling Restricted Speculation for firmware calls
[    0.119789] Spectre V2 : mitigation: Enabling conditional Indirect Branch Prediction Barrier
[    0.119790] Spectre V2 : User space: Mitigation: STIBP via prctl
[    0.119792] Speculative Store Bypass: Mitigation: Speculative Store Bypass disabled via prctl
[    0.119794] MDS: Mitigation: Clear CPU buffers
[    0.119796] MMIO Stale Data: Unknown: No mitigations
[    0.119802] x86/fpu: Supporting XSAVE feature 0x001: 'x87 floating point registers'
[    0.119803] x86/fpu: Supporting XSAVE feature 0x002: 'SSE registers'
[    0.119805] x86/fpu: Supporting XSAVE feature 0x004: 'AVX registers'
[    0.119806] x86/fpu: xstate_offset[2]:  576, xstate_sizes[2]:  256
[    0.119808] x86/fpu: Enabled xstate features 0x7, context size is 832 bytes, using 'standard' format.
[    0.144852] Freeing SMP alternatives memory: 40K
[    0.144862] pid_max: default: 32768 minimum: 301
[    0.148851] LSM: initializing lsm=lockdown,capability,landlock,yama,apparmor,tomoyo,bpf,ipe,ima,evm
[    0.149232] landlock: Up and running.
[    0.149233] Yama: disabled by default; enable with sysctl kernel.yama.*
[    0.149332] AppArmor: AppArmor initialized
[    0.149358] TOMOYO Linux initialized
[    0.149561] LSM support for eBPF active
[    0.149961] Mount-cache hash table entries: 65536 (order: 7, 524288 bytes, linear)
[    0.150021] Mountpoint-cache hash table entries: 65536 (order: 7, 524288 bytes, linear)
[    0.151816] smpboot: CPU0: Intel(R) Core(TM) i7-2760QM CPU @ 2.40GHz (family: 0x6, model: 0x2a, stepping: 0x7)
[    0.152235] Performance Events: PEBS fmt1+, SandyBridge events, 16-deep LBR, full-width counters, Intel PMU driver.
[    0.152256] ... version:                3
[    0.152257] ... bit width:              48
[    0.152258] ... generic registers:      4
[    0.152259] ... value mask:             0000ffffffffffff
[    0.152261] ... max period:             00007fffffffffff
[    0.152262] ... fixed-purpose events:   3
[    0.152263] ... event mask:             000000070000000f
[    0.152464] signal: max sigframe size: 1776
[    0.152486] Estimated ratio of average max frequency by base frequency (times 1024): 1365
[    0.155482] rcu: Hierarchical SRCU implementation.
[    0.155487] rcu: 	Max phase no-delay instances is 1000.
[    0.155557] Timer migration: 1 hierarchy levels; 8 children per group; 1 crossnode level
[    0.156275] NMI watchdog: Enabled. Permanently consumes one hw-PMU counter.
[    0.156411] smp: Bringing up secondary CPUs ...
[    0.156613] smpboot: x86: Booting SMP configuration:
[    0.156615] .... node  #0, CPUs:      #2 #4 #6
[    0.004666] Disabled fast string operations
[    0.004666] Disabled fast string operations
[    0.004666] Disabled fast string operations
[    0.163897]  #1 #3 #5 #7
[    0.004666] Disabled fast string operations
[    0.165705] Transient Scheduler Attacks: MDS CPU bug present and SMT on, data leak possible. See https://www.kernel.org/doc/html/latest/admin-guide/hw-vuln/mds.html for more details.
[    0.004666] Disabled fast string operations
[    0.004666] Disabled fast string operations
[    0.004666] Disabled fast string operations
[    0.171776] smp: Brought up 1 node, 8 CPUs
[    0.171776] smpboot: Total of 8 processors activated (38277.02 BogoMIPS)
[    0.229121] node 0 deferred pages initialised in 52ms
[    0.229121] Memory: 32654612K/33430776K available (16384K kernel code, 2486K rwdata, 11788K rodata, 4148K init, 4952K bss, 762556K reserved, 0K cma-reserved)
[    0.229125] devtmpfs: initialized
[    0.229125] x86/mm: Memory block size: 128MB
[    0.234548] ACPI: PM: Registering ACPI NVS region [mem 0x00058000-0x00058fff] (4096 bytes)
[    0.234548] ACPI: PM: Registering ACPI NVS region [mem 0xbaa9f000-0xbab9efff] (1048576 bytes)
[    0.234548] clocksource: jiffies: mask: 0xffffffff max_cycles: 0xffffffff, max_idle_ns: 7645041785100000 ns
[    0.234548] futex hash table entries: 2048 (order: 5, 131072 bytes, linear)
[    0.234548] pinctrl core: initialized pinctrl subsystem
[    0.236361] NET: Registered PF_NETLINK/PF_ROUTE protocol family
[    0.236990] DMA: preallocated 4096 KiB GFP_KERNEL pool for atomic allocations
[    0.237489] DMA: preallocated 4096 KiB GFP_KERNEL|GFP_DMA pool for atomic allocations
[    0.237985] DMA: preallocated 4096 KiB GFP_KERNEL|GFP_DMA32 pool for atomic allocations
[    0.238008] audit: initializing netlink subsys (disabled)
[    0.238035] audit: type=2000 audit(1755194362.136:1): state=initialized audit_enabled=0 res=1
[    0.238035] thermal_sys: Registered thermal governor 'fair_share'
[    0.238035] thermal_sys: Registered thermal governor 'bang_bang'
[    0.238035] thermal_sys: Registered thermal governor 'step_wise'
[    0.238035] thermal_sys: Registered thermal governor 'user_space'
[    0.238035] thermal_sys: Registered thermal governor 'power_allocator'
[    0.238035] cpuidle: using governor ladder
[    0.238035] cpuidle: using governor menu
[    0.238035] ACPI FADT declares the system doesn't support PCIe ASPM, so disable it
[    0.238035] acpiphp: ACPI Hot Plug PCI Controller Driver version: 0.5
[    0.238035] PCI: ECAM [mem 0xf8000000-0xfbffffff] (base 0xf8000000) for domain 0000 [bus 00-3f]
[    0.238035] PCI: Using configuration type 1 for base access
[    0.238035] core: PMU erratum BJ122, BV98, HSD29 worked around, HT is on
[    0.238035] kprobes: kprobe jump-optimization is enabled. All kprobes are optimized if possible.
[    0.242377] HugeTLB: registered 2.00 MiB page size, pre-allocated 0 pages
[    0.242377] HugeTLB: 28 KiB vmemmap can be freed for a 2.00 MiB page
[    0.245798] ACPI: Added _OSI(Module Device)
[    0.245798] ACPI: Added _OSI(Processor Device)
[    0.245798] ACPI: Added _OSI(Processor Aggregator Device)
[    0.258543] ACPI: 6 ACPI AML tables successfully acquired and loaded
[    0.259197] ACPI: EC: EC started
[    0.259199] ACPI: EC: interrupt blocked
[    0.259577] ACPI: EC: EC_CMD/EC_SC=0x66, EC_DATA=0x62
[    0.259580] ACPI: EC: Boot ECDT EC used to handle transactions
[    0.259875] ACPI: [Firmware Bug]: BIOS _OSI(Linux) query ignored
[    0.268795] ACPI: Dynamic OEM Table Load:
[    0.268795] ACPI: SSDT 0xFFFF8E4080F5E000 0008C0 (v01 PmRef  Cpu0Cst  00003001 INTL 20061109)
[    0.268795] ACPI: Dynamic OEM Table Load:
[    0.268795] ACPI: SSDT 0xFFFF8E43E653D000 000303 (v01 PmRef  ApIst    00003000 INTL 20061109)
[    0.269034] ACPI: Dynamic OEM Table Load:
[    0.269040] ACPI: SSDT 0xFFFF8E43E6534200 000119 (v01 PmRef  ApCst    00003000 INTL 20061109)
[    0.270278] ACPI: Interpreter enabled
[    0.270296] ACPI: PM: (supports S0 S3 S4 S5)
[    0.270298] ACPI: Using IOAPIC for interrupt routing
[    0.270325] PCI: Using host bridge windows from ACPI; if necessary, use "pci=nocrs" and report a bug
[    0.270327] PCI: Using E820 reservations for host bridge windows
[    0.271748] ACPI: Enabled 6 GPEs in block 00 to 3F
[    0.276465] ACPI: \_SB_.PCI0.LPC_.EC__.PUBS: New power resource
[    0.277582] acpi PNP0C0A:01: ACPI dock station (docks/bays count: 1)
[    0.278464] acpi LNXIOBAY:00: ACPI dock station (docks/bays count: 2)
[    0.280669] ACPI: PCI: Interrupt link LNKA configured for IRQ 11
[    0.280730] ACPI: PCI: Interrupt link LNKB configured for IRQ 0
[    0.280732] ACPI: PCI: Interrupt link LNKB disabled
[    0.280788] ACPI: PCI: Interrupt link LNKC configured for IRQ 0
[    0.280789] ACPI: PCI: Interrupt link LNKC disabled
[    0.280844] ACPI: PCI: Interrupt link LNKD configured for IRQ 0
[    0.280846] ACPI: PCI: Interrupt link LNKD disabled
[    0.280900] ACPI: PCI: Interrupt link LNKE configured for IRQ 0
[    0.280902] ACPI: PCI: Interrupt link LNKE disabled
[    0.280956] ACPI: PCI: Interrupt link LNKF configured for IRQ 0
[    0.280958] ACPI: PCI: Interrupt link LNKF disabled
[    0.281012] ACPI: PCI: Interrupt link LNKG configured for IRQ 0
[    0.281013] ACPI: PCI: Interrupt link LNKG disabled
[    0.281067] ACPI: PCI: Interrupt link LNKH configured for IRQ 0
[    0.281069] ACPI: PCI: Interrupt link LNKH disabled
[    0.281187] ACPI: PCI Root Bridge [PCI0] (domain 0000 [bus 00-fe])
[    0.281194] acpi PNP0A08:00: _OSC: OS supports [ExtendedConfig ASPM ClockPM Segments MSI HPX-Type3]
[    0.281275] acpi PNP0A08:00: _OSC: platform does not support [SHPCHotplug PCIeCapability LTR]
[    0.281344] acpi PNP0A08:00: _OSC: not requesting control; platform does not support [PCIeCapability]
[    0.281347] acpi PNP0A08:00: _OSC: OS requested [PCIeHotplug SHPCHotplug PME AER PCIeCapability LTR]
[    0.281349] acpi PNP0A08:00: _OSC: platform willing to grant [PCIeHotplug PME AER]
[    0.281350] acpi PNP0A08:00: _OSC: platform retains control of PCIe features (AE_SUPPORT)
[    0.281362] acpi PNP0A08:00: [Firmware Info]: ECAM [mem 0xf8000000-0xfbffffff] for domain 0000 [bus 00-3f] only partially covers this bridge
[    0.281582] PCI host bridge to bus 0000:00
[    0.281587] pci_bus 0000:00: root bus resource [io  0x0000-0x0cf7 window]
[    0.281590] pci_bus 0000:00: root bus resource [io  0x0d00-0xffff window]
[    0.281592] pci_bus 0000:00: root bus resource [mem 0x000a0000-0x000bffff window]
[    0.281594] pci_bus 0000:00: root bus resource [mem 0xbfa00000-0xfebfffff window]
[    0.281596] pci_bus 0000:00: root bus resource [mem 0xfed40000-0xfed4bfff window]
[    0.281598] pci_bus 0000:00: root bus resource [bus 00-fe]
[    0.281613] pci 0000:00:00.0: [8086:0104] type 00 class 0x060000 conventional PCI endpoint
[    0.281699] pci 0000:00:01.0: [8086:0101] type 01 class 0x060400 PCIe Root Port
[    0.281713] pci 0000:00:01.0: PCI bridge to [bus 01]
[    0.281717] pci 0000:00:01.0:   bridge window [io  0x5000-0x5fff]
[    0.281720] pci 0000:00:01.0:   bridge window [mem 0xf0000000-0xf10fffff]
[    0.281725] pci 0000:00:01.0:   bridge window [mem 0xc0000000-0xd1ffffff 64bit pref]
[    0.281753] pci 0000:00:01.0: PME# supported from D0 D3hot D3cold
[    0.281849] pci 0000:00:02.0: [8086:0126] type 00 class 0x030000 conventional PCI endpoint
[    0.281859] pci 0000:00:02.0: BAR 0 [mem 0xf1400000-0xf17fffff 64bit]
[    0.281865] pci 0000:00:02.0: BAR 2 [mem 0xe0000000-0xefffffff 64bit pref]
[    0.281870] pci 0000:00:02.0: BAR 4 [io  0x6000-0x603f]
[    0.281883] pci 0000:00:02.0: Video device with shadowed ROM at [mem 0x000c0000-0x000dffff]
[    0.282003] pci 0000:00:16.0: [8086:1c3a] type 00 class 0x078000 conventional PCI endpoint
[    0.282025] pci 0000:00:16.0: BAR 0 [mem 0xf3a25000-0xf3a2500f 64bit]
[    0.282102] pci 0000:00:16.0: PME# supported from D0 D3hot D3cold
[    0.282170] pci 0000:00:16.3: [8086:1c3d] type 00 class 0x070002 conventional PCI endpoint
[    0.282188] pci 0000:00:16.3: BAR 0 [io  0x60b0-0x60b7]
[    0.282198] pci 0000:00:16.3: BAR 1 [mem 0xf3a2c000-0xf3a2cfff]
[    0.282332] pci 0000:00:19.0: [8086:1502] type 00 class 0x020000 conventional PCI endpoint
[    0.282348] pci 0000:00:19.0: BAR 0 [mem 0xf3a00000-0xf3a1ffff]
[    0.282357] pci 0000:00:19.0: BAR 1 [mem 0xf3a2b000-0xf3a2bfff]
[    0.282366] pci 0000:00:19.0: BAR 2 [io  0x6080-0x609f]
[    0.282428] pci 0000:00:19.0: PME# supported from D0 D3hot D3cold
[    0.282517] pci 0000:00:1a.0: [8086:1c2d] type 00 class 0x0c0320 conventional PCI endpoint
[    0.282534] pci 0000:00:1a.0: BAR 0 [mem 0xf3a2a000-0xf3a2a3ff]
[    0.282621] pci 0000:00:1a.0: PME# supported from D0 D3hot D3cold
[    0.282724] pci 0000:00:1b.0: [8086:1c20] type 00 class 0x040300 PCIe Root Complex Integrated Endpoint
[    0.282743] pci 0000:00:1b.0: BAR 0 [mem 0xf3a20000-0xf3a23fff 64bit]
[    0.282825] pci 0000:00:1b.0: PME# supported from D0 D3hot D3cold
[    0.282945] pci 0000:00:1c.0: [8086:1c10] type 01 class 0x060400 PCIe Root Port
[    0.282986] pci 0000:00:1c.0: PCI bridge to [bus 02]
[    0.283112] pci 0000:00:1c.0: PME# supported from D0 D3hot D3cold
[    0.283150] pci 0000:00:1c.0: Enabling MPC IRBNCE
[    0.283153] pci 0000:00:1c.0: Intel PCH root port ACS workaround enabled
[    0.283270] pci 0000:00:1c.1: [8086:1c12] type 01 class 0x060400 PCIe Root Port
[    0.283320] pci 0000:00:1c.1: PCI bridge to [bus 03]
[    0.283330] pci 0000:00:1c.1:   bridge window [mem 0xf3900000-0xf39fffff]
[    0.283447] pci 0000:00:1c.1: PME# supported from D0 D3hot D3cold
[    0.283483] pci 0000:00:1c.1: Enabling MPC IRBNCE
[    0.283486] pci 0000:00:1c.1: Intel PCH root port ACS workaround enabled
[    0.283601] pci 0000:00:1c.3: [8086:1c16] type 01 class 0x060400 PCIe Root Port
[    0.283650] pci 0000:00:1c.3: PCI bridge to [bus 05-0c]
[    0.283658] pci 0000:00:1c.3:   bridge window [io  0x4000-0x4fff]
[    0.283663] pci 0000:00:1c.3:   bridge window [mem 0xf3100000-0xf38fffff]
[    0.283680] pci 0000:00:1c.3:   bridge window [mem 0xf1800000-0xf1ffffff 64bit pref]
[    0.283785] pci 0000:00:1c.3: PME# supported from D0 D3hot D3cold
[    0.283819] pci 0000:00:1c.3: Enabling MPC IRBNCE
[    0.283822] pci 0000:00:1c.3: Intel PCH root port ACS workaround enabled
[    0.283947] pci 0000:00:1c.4: [8086:1c18] type 01 class 0x060400 PCIe Root Port
[    0.283998] pci 0000:00:1c.4: PCI bridge to [bus 0d]
[    0.284005] pci 0000:00:1c.4:   bridge window [io  0x3000-0x3fff]
[    0.284010] pci 0000:00:1c.4:   bridge window [mem 0xf2900000-0xf30fffff]
[    0.284027] pci 0000:00:1c.4:   bridge window [mem 0xf2000000-0xf27fffff 64bit pref]
[    0.284129] pci 0000:00:1c.4: PME# supported from D0 D3hot D3cold
[    0.284164] pci 0000:00:1c.4: Enabling MPC IRBNCE
[    0.284167] pci 0000:00:1c.4: Intel PCH root port ACS workaround enabled
[    0.284283] pci 0000:00:1c.6: [8086:1c1c] type 01 class 0x060400 PCIe Root Port
[    0.284334] pci 0000:00:1c.6: PCI bridge to [bus 0e]
[    0.284345] pci 0000:00:1c.6:   bridge window [mem 0xf2800000-0xf28fffff]
[    0.284460] pci 0000:00:1c.6: PME# supported from D0 D3hot D3cold
[    0.284494] pci 0000:00:1c.6: Enabling MPC IRBNCE
[    0.284497] pci 0000:00:1c.6: Intel PCH root port ACS workaround enabled
[    0.284622] pci 0000:00:1d.0: [8086:1c26] type 00 class 0x0c0320 conventional PCI endpoint
[    0.284639] pci 0000:00:1d.0: BAR 0 [mem 0xf3a29000-0xf3a293ff]
[    0.284727] pci 0000:00:1d.0: PME# supported from D0 D3hot D3cold
[    0.284837] pci 0000:00:1f.0: [8086:1c4f] type 00 class 0x060100 conventional PCI endpoint
[    0.285036] pci 0000:00:1f.2: [8086:1c03] type 00 class 0x010601 conventional PCI endpoint
[    0.285050] pci 0000:00:1f.2: BAR 0 [io  0x60a8-0x60af]
[    0.285059] pci 0000:00:1f.2: BAR 1 [io  0x60bc-0x60bf]
[    0.285067] pci 0000:00:1f.2: BAR 2 [io  0x60a0-0x60a7]
[    0.285076] pci 0000:00:1f.2: BAR 3 [io  0x60b8-0x60bb]
[    0.285084] pci 0000:00:1f.2: BAR 4 [io  0x6060-0x607f]
[    0.285092] pci 0000:00:1f.2: BAR 5 [mem 0xf3a28000-0xf3a287ff]
[    0.285135] pci 0000:00:1f.2: PME# supported from D3hot
[    0.285219] pci 0000:00:1f.3: [8086:1c22] type 00 class 0x0c0500 conventional PCI endpoint
[    0.285238] pci 0000:00:1f.3: BAR 0 [mem 0xf3a24000-0xf3a240ff 64bit]
[    0.285260] pci 0000:00:1f.3: BAR 4 [io  0xefa0-0xefbf]
[    0.285390] pci 0000:01:00.0: [10de:0dfa] type 00 class 0x030000 PCIe Endpoint
[    0.285405] pci 0000:01:00.0: BAR 0 [mem 0xf0000000-0xf0ffffff]
[    0.285416] pci 0000:01:00.0: BAR 1 [mem 0xc0000000-0xcfffffff 64bit pref]
[    0.285427] pci 0000:01:00.0: BAR 3 [mem 0xd0000000-0xd1ffffff 64bit pref]
[    0.285434] pci 0000:01:00.0: BAR 5 [io  0x5000-0x507f]
[    0.285441] pci 0000:01:00.0: ROM [mem 0xfff80000-0xffffffff pref]
[    0.285449] pci 0000:01:00.0: enabling Extended Tags
[    0.285463] pci 0000:01:00.0: Enabling HDA controller
[    0.285776] pci 0000:01:00.1: [10de:0bea] type 00 class 0x040300 PCIe Endpoint
[    0.285793] pci 0000:01:00.1: BAR 0 [mem 0xf1000000-0xf1003fff]
[    0.285843] pci 0000:01:00.1: enabling Extended Tags
[    0.285968] pci 0000:00:01.0: PCI bridge to [bus 01]
[    0.286035] pci 0000:00:1c.0: PCI bridge to [bus 02]
[    0.286285] pci 0000:03:00.0: [8086:0085] type 00 class 0x028000 PCIe Endpoint
[    0.286462] pci 0000:03:00.0: BAR 0 [mem 0xf3900000-0xf3901fff 64bit]
[    0.287219] pci 0000:03:00.0: PME# supported from D0 D3hot D3cold
[    0.287769] pci 0000:00:1c.1: PCI bridge to [bus 03]
[    0.287869] acpiphp: Slot [1] registered
[    0.287876] pci 0000:00:1c.3: PCI bridge to [bus 05-0c]
[    0.288051] pci 0000:0d:00.0: MMC controller base frequency changed to 50Mhz.
[    0.288055] pci 0000:0d:00.0: [1180:e823] type 00 class 0x088001 PCIe Endpoint
[    0.288090] pci 0000:0d:00.0: BAR 0 [mem 0xf2901000-0xf29010ff]
[    0.288314] pci 0000:0d:00.0: supports D1 D2
[    0.288316] pci 0000:0d:00.0: PME# supported from D0 D1 D2 D3hot D3cold
[    0.288613] pci 0000:0d:00.3: [1180:e832] type 00 class 0x0c0010 PCIe Endpoint
[    0.288648] pci 0000:0d:00.3: BAR 0 [mem 0xf2900000-0xf29007ff]
[    0.288777] pci 0000:0d:00.3: Enabling fixed DMA alias to 00.0
[    0.288894] pci 0000:0d:00.3: supports D1 D2
[    0.288895] pci 0000:0d:00.3: PME# supported from D0 D1 D2 D3hot D3cold
[    0.289137] pci 0000:00:1c.4: PCI bridge to [bus 0d]
[    0.289289] pci 0000:0e:00.0: [1033:0194] type 00 class 0x0c0330 PCIe Endpoint
[    0.289321] pci 0000:0e:00.0: BAR 0 [mem 0xf2800000-0xf2801fff 64bit]
[    0.289488] pci 0000:0e:00.0: PME# supported from D0 D3hot D3cold
[    0.289672] pci 0000:00:1c.6: PCI bridge to [bus 0e]
[    0.291966] ACPI: EC: interrupt unblocked
[    0.291968] ACPI: EC: event unblocked
[    0.291973] ACPI: EC: EC_CMD/EC_SC=0x66, EC_DATA=0x62
[    0.291975] ACPI: EC: GPE=0x11
[    0.291977] ACPI: \_SB_.PCI0.LPC_.EC__: Boot ECDT EC initialization complete
[    0.291979] ACPI: \_SB_.PCI0.LPC_.EC__: EC: Used to handle transactions and events
[    0.292110] iommu: Default domain type: Translated
[    0.292110] iommu: DMA domain TLB invalidation policy: lazy mode
[    0.292110] pps_core: LinuxPPS API ver. 1 registered
[    0.292110] pps_core: Software ver. 5.3.6 - Copyright 2005-2007 Rodolfo Giometti <giometti@linux.it>
[    0.292110] PTP clock support registered
[    0.292119] EDAC MC: Ver: 3.0.0
[    0.292348] efivars: Registered efivars operations
[    0.292348] NetLabel: Initializing
[    0.292348] NetLabel:  domain hash size = 128
[    0.292348] NetLabel:  protocols = UNLABELED CIPSOv4 CALIPSO
[    0.292348] NetLabel:  unlabeled traffic allowed by default
[    0.292348] PCI: Using ACPI for IRQ routing
[    0.293691] PCI: pci_cache_line_size set to 64 bytes
[    0.293937] e820: reserve RAM buffer [mem 0x00058000-0x0005ffff]
[    0.293939] e820: reserve RAM buffer [mem 0xb66d2018-0xb7ffffff]
[    0.293941] e820: reserve RAM buffer [mem 0xb66e2018-0xb7ffffff]
[    0.293943] e820: reserve RAM buffer [mem 0xb66f2018-0xb7ffffff]
[    0.293944] e820: reserve RAM buffer [mem 0xba59f000-0xbbffffff]
[    0.293946] e820: reserve RAM buffer [mem 0xbac00000-0xbbffffff]
[    0.293947] e820: reserve RAM buffer [mem 0x83e600000-0x83fffffff]
[    0.293988] pci 0000:00:02.0: vgaarb: setting as boot VGA device
[    0.293988] pci 0000:00:02.0: vgaarb: bridge control possible
[    0.293988] pci 0000:00:02.0: vgaarb: VGA device added: decodes=io+mem,owns=io+mem,locks=none
[    0.293988] pci 0000:01:00.0: vgaarb: bridge control possible
[    0.293988] pci 0000:01:00.0: vgaarb: VGA device added: decodes=io+mem,owns=none,locks=none
[    0.293988] vgaarb: loaded
[    0.293988] hpet0: at MMIO 0xfed00000, IRQs 2, 8, 0, 0, 0, 0, 0, 0
[    0.293988] hpet0: 8 comparators, 64-bit 14.318180 MHz counter
[    0.296736] clocksource: Switched to clocksource tsc-early
[    0.297386] VFS: Disk quotas dquot_6.6.0
[    0.297452] VFS: Dquot-cache hash table entries: 512 (order 0, 4096 bytes)
[    0.297654] AppArmor: AppArmor Filesystem Enabled
[    0.297677] pnp: PnP ACPI init
[    0.298008] pnp 00:00: disabling [mem 0x000c0000-0x000c3fff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298013] pnp 00:00: disabling [mem 0x000c4000-0x000c7fff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298015] pnp 00:00: disabling [mem 0x000c8000-0x000cbfff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298018] pnp 00:00: disabling [mem 0x000cc000-0x000cffff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298020] pnp 00:00: disabling [mem 0x000d0000-0x000d3fff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298023] pnp 00:00: disabling [mem 0x000d4000-0x000d7fff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298025] pnp 00:00: disabling [mem 0x000d8000-0x000dbfff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298027] pnp 00:00: disabling [mem 0x000dc000-0x000dffff] because it overlaps 0000:00:02.0 BAR 6 [mem 0x000c0000-0x000dffff]
[    0.298071] system 00:00: [mem 0x00000000-0x0009ffff] could not be reserved
[    0.298076] system 00:00: [mem 0x000e0000-0x000e3fff] has been reserved
[    0.298082] system 00:00: [mem 0x000e4000-0x000e7fff] has been reserved
[    0.298084] system 00:00: [mem 0x000e8000-0x000ebfff] has been reserved
[    0.298087] system 00:00: [mem 0x000ec000-0x000effff] has been reserved
[    0.298089] system 00:00: [mem 0x000f0000-0x000fffff] could not be reserved
[    0.298091] system 00:00: [mem 0x00100000-0xbf9fffff] could not be reserved
[    0.298093] system 00:00: [mem 0xfec00000-0xfed3ffff] could not be reserved
[    0.298095] system 00:00: [mem 0xfed4c000-0xffffffff] could not be reserved
[    0.298206] system 00:01: [io  0x0400-0x047f] has been reserved
[    0.298209] system 00:01: [io  0x0500-0x057f] has been reserved
[    0.298211] system 00:01: [io  0x0800-0x080f] has been reserved
[    0.298213] system 00:01: [io  0x15e0-0x15ef] has been reserved
[    0.298215] system 00:01: [io  0x1600-0x167f] has been reserved
[    0.298217] system 00:01: [mem 0xf8000000-0xfbffffff] could not be reserved
[    0.298219] system 00:01: [mem 0x00000000-0x00000fff] could not be reserved
[    0.298222] system 00:01: [mem 0xfed1c000-0xfed1ffff] has been reserved
[    0.298225] system 00:01: [mem 0xfed10000-0xfed13fff] has been reserved
[    0.298227] system 00:01: [mem 0xfed18000-0xfed18fff] has been reserved
[    0.298229] system 00:01: [mem 0xfed19000-0xfed19fff] has been reserved
[    0.298232] system 00:01: [mem 0xfed45000-0xfed4bfff] has been reserved
[    0.368610] pnp: PnP ACPI: found 6 devices
[    0.375116] clocksource: acpi_pm: mask: 0xffffff max_cycles: 0xffffff, max_idle_ns: 2085701024 ns
[    0.375378] NET: Registered PF_INET protocol family
[    0.375634] IP idents hash table entries: 262144 (order: 9, 2097152 bytes, linear)
[    0.394853] tcp_listen_portaddr_hash hash table entries: 16384 (order: 6, 262144 bytes, linear)
[    0.394914] Table-perturb hash table entries: 65536 (order: 6, 262144 bytes, linear)
[    0.395127] TCP established hash table entries: 262144 (order: 9, 2097152 bytes, linear)
[    0.395735] TCP bind hash table entries: 65536 (order: 9, 2097152 bytes, linear)
[    0.396092] TCP: Hash tables configured (established 262144 bind 65536)
[    0.396395] MPTCP token hash table entries: 32768 (order: 7, 786432 bytes, linear)
[    0.396613] UDP hash table entries: 16384 (order: 7, 524288 bytes, linear)
[    0.396763] UDP-Lite hash table entries: 16384 (order: 7, 524288 bytes, linear)
[    0.396926] NET: Registered PF_UNIX/PF_LOCAL protocol family
[    0.396935] NET: Registered PF_XDP protocol family
[    0.396940] pci 0000:01:00.0: ROM [mem 0xfff80000-0xffffffff pref]: can't claim; no compatible bridge window
[    0.396951] pci 0000:00:1c.0: bridge window [io  0x1000-0x0fff] to [bus 02] add_size 1000
[    0.396954] pci 0000:00:1c.0: bridge window [mem 0x00100000-0x000fffff 64bit pref] to [bus 02] add_size 200000 add_align 100000
[    0.396958] pci 0000:00:1c.0: bridge window [mem 0x00100000-0x000fffff] to [bus 02] add_size 200000 add_align 100000
[    0.396970] pci 0000:00:1c.0: bridge window [mem 0xbfa00000-0xbfbfffff]: assigned
[    0.396974] pci 0000:00:1c.0: bridge window [mem 0xbfc00000-0xbfdfffff 64bit pref]: assigned
[    0.396978] pci 0000:00:1c.0: bridge window [io  0x2000-0x2fff]: assigned
[    0.396982] pci 0000:01:00.0: ROM [mem 0xf1080000-0xf10fffff pref]: assigned
[    0.396984] pci 0000:00:01.0: PCI bridge to [bus 01]
[    0.396987] pci 0000:00:01.0:   bridge window [io  0x5000-0x5fff]
[    0.396991] pci 0000:00:01.0:   bridge window [mem 0xf0000000-0xf10fffff]
[    0.396994] pci 0000:00:01.0:   bridge window [mem 0xc0000000-0xd1ffffff 64bit pref]
[    0.396998] pci 0000:00:1c.0: PCI bridge to [bus 02]
[    0.397002] pci 0000:00:1c.0:   bridge window [io  0x2000-0x2fff]
[    0.397009] pci 0000:00:1c.0:   bridge window [mem 0xbfa00000-0xbfbfffff]
[    0.397014] pci 0000:00:1c.0:   bridge window [mem 0xbfc00000-0xbfdfffff 64bit pref]
[    0.397023] pci 0000:00:1c.1: PCI bridge to [bus 03]
[    0.397030] pci 0000:00:1c.1:   bridge window [mem 0xf3900000-0xf39fffff]
[    0.397043] pci 0000:00:1c.3: PCI bridge to [bus 05-0c]
[    0.397046] pci 0000:00:1c.3:   bridge window [io  0x4000-0x4fff]
[    0.397052] pci 0000:00:1c.3:   bridge window [mem 0xf3100000-0xf38fffff]
[    0.397058] pci 0000:00:1c.3:   bridge window [mem 0xf1800000-0xf1ffffff 64bit pref]
[    0.397067] pci 0000:00:1c.4: PCI bridge to [bus 0d]
[    0.397071] pci 0000:00:1c.4:   bridge window [io  0x3000-0x3fff]
[    0.397078] pci 0000:00:1c.4:   bridge window [mem 0xf2900000-0xf30fffff]
[    0.397083] pci 0000:00:1c.4:   bridge window [mem 0xf2000000-0xf27fffff 64bit pref]
[    0.397092] pci 0000:00:1c.6: PCI bridge to [bus 0e]
[    0.397098] pci 0000:00:1c.6:   bridge window [mem 0xf2800000-0xf28fffff]
[    0.397111] pci_bus 0000:00: resource 4 [io  0x0000-0x0cf7 window]
[    0.397113] pci_bus 0000:00: resource 5 [io  0x0d00-0xffff window]
[    0.397115] pci_bus 0000:00: resource 6 [mem 0x000a0000-0x000bffff window]
[    0.397117] pci_bus 0000:00: resource 7 [mem 0xbfa00000-0xfebfffff window]
[    0.397119] pci_bus 0000:00: resource 8 [mem 0xfed40000-0xfed4bfff window]
[    0.397121] pci_bus 0000:01: resource 0 [io  0x5000-0x5fff]
[    0.397123] pci_bus 0000:01: resource 1 [mem 0xf0000000-0xf10fffff]
[    0.397125] pci_bus 0000:01: resource 2 [mem 0xc0000000-0xd1ffffff 64bit pref]
[    0.397127] pci_bus 0000:02: resource 0 [io  0x2000-0x2fff]
[    0.397128] pci_bus 0000:02: resource 1 [mem 0xbfa00000-0xbfbfffff]
[    0.397130] pci_bus 0000:02: resource 2 [mem 0xbfc00000-0xbfdfffff 64bit pref]
[    0.397132] pci_bus 0000:03: resource 1 [mem 0xf3900000-0xf39fffff]
[    0.397134] pci_bus 0000:05: resource 0 [io  0x4000-0x4fff]
[    0.397136] pci_bus 0000:05: resource 1 [mem 0xf3100000-0xf38fffff]
[    0.397137] pci_bus 0000:05: resource 2 [mem 0xf1800000-0xf1ffffff 64bit pref]
[    0.397139] pci_bus 0000:0d: resource 0 [io  0x3000-0x3fff]
[    0.397141] pci_bus 0000:0d: resource 1 [mem 0xf2900000-0xf30fffff]
[    0.397143] pci_bus 0000:0d: resource 2 [mem 0xf2000000-0xf27fffff 64bit pref]
[    0.397145] pci_bus 0000:0e: resource 1 [mem 0xf2800000-0xf28fffff]
[    0.397552] pci 0000:01:00.1: extending delay after power-on from D3hot to 20 msec
[    0.397588] pci 0000:01:00.1: D0 power state depends on 0000:01:00.0
[    0.398987] PCI: CLS 64 bytes, default 64
[    0.399018] DMAR: No ATSR found
[    0.399019] DMAR: No SATC found
[    0.399021] DMAR: IOMMU feature pgsel_inv inconsistent
[    0.399023] DMAR: IOMMU feature pass_through inconsistent
[    0.399025] DMAR: dmar0: Using Queued invalidation
[    0.399032] DMAR: dmar1: Using Queued invalidation
[    0.399085] Trying to unpack rootfs image as initramfs...
[    0.399326] pci 0000:00:02.0: Adding to iommu group 0
[    0.400321] pci 0000:00:00.0: Adding to iommu group 1
[    0.400345] pci 0000:00:01.0: Adding to iommu group 2
[    0.400367] pci 0000:00:16.0: Adding to iommu group 3
[    0.400377] pci 0000:00:16.3: Adding to iommu group 3
[    0.400388] pci 0000:00:19.0: Adding to iommu group 4
[    0.400399] pci 0000:00:1a.0: Adding to iommu group 5
[    0.400414] pci 0000:00:1b.0: Adding to iommu group 6
[    0.400425] pci 0000:00:1c.0: Adding to iommu group 7
[    0.400437] pci 0000:00:1c.1: Adding to iommu group 8
[    0.400451] pci 0000:00:1c.3: Adding to iommu group 9
[    0.400463] pci 0000:00:1c.4: Adding to iommu group 10
[    0.400476] pci 0000:00:1c.6: Adding to iommu group 11
[    0.400487] pci 0000:00:1d.0: Adding to iommu group 12
[    0.400517] pci 0000:00:1f.0: Adding to iommu group 13
[    0.400530] pci 0000:00:1f.2: Adding to iommu group 13
[    0.400542] pci 0000:00:1f.3: Adding to iommu group 13
[    0.400547] pci 0000:01:00.0: Adding to iommu group 2
[    0.400552] pci 0000:01:00.1: Adding to iommu group 2
[    0.400564] pci 0000:03:00.0: Adding to iommu group 14
[    0.400596] pci 0000:0d:00.0: Adding to iommu group 15
[    0.400605] pci 0000:0d:00.3: Adding to iommu group 15
[    0.400616] pci 0000:0e:00.0: Adding to iommu group 16
[    0.402755] DMAR: Intel(R) Virtualization Technology for Directed I/O
[    0.402761] PCI-DMA: Using software bounce buffering for IO (SWIOTLB)
[    0.402762] software IO TLB: mapped [mem 0x00000000af660000-0x00000000b3660000] (64MB)
[    0.403423] Initialise system trusted keyrings
[    0.403440] Key type blacklist registered
[    0.403538] workingset: timestamp_bits=36 max_order=23 bucket_order=0
[    0.403548] zbud: loaded
[    0.403937] fuse: init (API version 7.41)
[    0.404262] integrity: Platform Keyring initialized
[    0.404271] integrity: Machine keyring initialized
[    0.428506] Key type asymmetric registered
[    0.428512] Asymmetric key parser 'x509' registered
[    0.662494] Freeing initrd memory: 74360K
[    0.669085] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 246)
[    0.669134] io scheduler mq-deadline registered
[    0.671241] ledtrig-cpu: registered to indicate activity on CPUs
[    0.671481] pcieport 0000:00:1c.0: enabling device (0000 -> 0003)
[    0.672021] shpchp: Standard Hot Plug PCI Controller Driver version: 0.4
[    0.674705] thermal LNXTHERM:00: registered as thermal_zone0
[    0.674708] ACPI: thermal: Thermal Zone [THM0] (63 C)
[    0.674862] Serial: 8250/16550 driver, 4 ports, IRQ sharing enabled
[    0.675699] 0000:00:16.3: ttyS0 at I/O 0x60b0 (irq = 19, base_baud = 115200) is a 16550A
[    0.675949] Linux agpgart interface v0.103
[    0.687745] tpm_tis 00:05: 1.2 TPM (device-id 0x0, rev-id 78)
[    0.733721] i8042: PNP: PS/2 Controller [PNP0303:KBD,PNP0f13:MOU] at 0x60,0x64 irq 1,12
[    0.739550] serio: i8042 KBD port at 0x60,0x64 irq 1
[    0.739558] serio: i8042 AUX port at 0x60,0x64 irq 12
[    0.739722] mousedev: PS/2 mouse device common for all mice
[    0.739752] rtc_cmos 00:02: RTC can wake from S4
[    0.739948] random: crng init done
[    0.740105] rtc_cmos 00:02: registered as rtc0
[    0.740141] rtc_cmos 00:02: setting system clock to 2025-08-14T17:59:23 UTC (1755194363)
[    0.740172] rtc_cmos 00:02: alarms up to one month, y3k, 114 bytes nvram
[    0.740398] intel_pstate: Intel P-state driver initializing
[    0.741385] efifb: probing for efifb
[    0.741418] efifb: framebuffer at 0xe0000000, using 1200k, total 1200k
[    0.741424] efifb: mode is 640x480x32, linelength=2560, pages=1
[    0.741430] efifb: scrolling: redraw
[    0.741433] efifb: Truecolor: size=8:8:8:8, shift=24:16:8:0
[    0.741766] Console: switching to colour frame buffer device 80x30
[    0.742472] fb0: EFI VGA frame buffer device
[    0.742823] NET: Registered PF_INET6 protocol family
[    0.743829] input: AT Translated Set 2 keyboard as /devices/platform/i8042/serio0/input/input0
[    0.756728] Segment Routing with IPv6
[    0.756773] In-situ OAM (IOAM) with IPv6
[    0.756807] mip6: Mobile IPv6
[    0.756814] NET: Registered PF_PACKET protocol family
[    0.757127] mpls_gso: MPLS GSO support
[    0.758749] ENERGY_PERF_BIAS: Set to 'normal', was 'performance'
[    0.759268] microcode: Current revision: 0x0000002f
[    0.759279] microcode: Updated early from: 0x0000002e
[    0.759904] IPI shorthand broadcast: enabled
[    0.762234] sched_clock: Marking stable (759175920, 666434)->(768986297, -9143943)
[    0.762547] registered taskstats version 1
[    0.762712] Loading compiled-in X.509 certificates
[    0.838102] Loaded X.509 cert 'Build time autogenerated kernel key: ba77a71e64c453bc15410391734927a088a45279'
[    0.840720] Demotion targets for Node 0: null
[    0.841129] Key type .fscrypt registered
[    0.841134] Key type fscrypt-provisioning registered
[    0.895139] Key type encrypted registered
[    0.895159] AppArmor: AppArmor sha256 policy hashing enabled
[    0.896403] ima: Allocated hash algorithm: sha256
[    0.971907] ima: No architecture policies found
[    0.971945] evm: Initialising EVM extended attributes:
[    0.971947] evm: security.selinux
[    0.971949] evm: security.SMACK64 (disabled)
[    0.971950] evm: security.SMACK64EXEC (disabled)
[    0.971951] evm: security.SMACK64TRANSMUTE (disabled)
[    0.971953] evm: security.SMACK64MMAP (disabled)
[    0.971954] evm: security.apparmor
[    0.971955] evm: security.ima
[    0.971956] evm: security.capability
[    0.971957] evm: HMAC attrs: 0x1
[    0.974057] RAS: Correctable Errors collector initialized.
[    0.981123] clk: Disabling unused clocks
[    0.981131] PM: genpd: Disabling unused power domains
[    0.982688] Freeing unused decrypted memory: 2028K
[    0.983316] Freeing unused kernel image (initmem) memory: 4148K
[    0.983398] Write protecting the kernel read-only data: 28672k
[    0.983678] Freeing unused kernel image (rodata/data gap) memory: 500K
[    1.026509] x86/mm: Checked W+X mappings: passed, no W+X pages found.
[    1.026511] x86/mm: Checking user space page tables
[    1.065941] x86/mm: Checked W+X mappings: passed, no W+X pages found.
[    1.065946] Run /init as init process
[    1.065947]   with arguments:
[    1.065948]     /init
[    1.065949]   with environment:
[    1.065950]     HOME=/
[    1.065951]     TERM=linux
[    1.065952]     BOOT_IMAGE=/vmlinuz-6.12.38+deb13-amd64
[    1.230093] input: Lid Switch as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0D:00/input/input2
[    1.244737] ACPI: button: Lid Switch [LID]
[    1.244814] input: Sleep Button as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0C0E:00/input/input3
[    1.244875] ACPI: button: Sleep Button [SLPB]
[    1.244955] input: Power Button as /devices/LNXSYSTM:00/LNXPWRBN:00/input/input4
[    1.245003] ACPI: button: Power Button [PWRF]
[    1.247063] ACPI Warning: SystemIO range 0x0000000000000428-0x000000000000042F conflicts with OpRegion 0x0000000000000400-0x000000000000047F (\_SB.PCI0.LPC.PMIO) (20240827/utaddress-204)
[    1.247074] ACPI: OSL: Resource conflict; ACPI support missing from driver?
[    1.247078] ACPI Warning: SystemIO range 0x0000000000000540-0x000000000000054F conflicts with OpRegion 0x0000000000000500-0x000000000000057F (\_SB.PCI0.LPC.LPIO) (20240827/utaddress-204)
[    1.247084] ACPI: OSL: Resource conflict; ACPI support missing from driver?
[    1.247086] ACPI Warning: SystemIO range 0x0000000000000530-0x000000000000053F conflicts with OpRegion 0x0000000000000500-0x000000000000057F (\_SB.PCI0.LPC.LPIO) (20240827/utaddress-204)
[    1.247091] ACPI: OSL: Resource conflict; ACPI support missing from driver?
[    1.247093] ACPI Warning: SystemIO range 0x0000000000000500-0x000000000000052F conflicts with OpRegion 0x0000000000000500-0x000000000000057F (\_SB.PCI0.LPC.LPIO) (20240827/utaddress-204)
[    1.247098] ACPI: OSL: Resource conflict; ACPI support missing from driver?
[    1.247099] lpc_ich: Resource conflict(s) found affecting gpio_ich
[    1.255520] ACPI: battery: Slot [BAT0] (battery present)
[    1.266891] i801_smbus 0000:00:1f.3: SMBus using PCI interrupt
[    1.272871] i2c i2c-0: Successfully instantiated SPD at 0x50
[    1.273338] i2c i2c-0: Successfully instantiated SPD at 0x51
[    1.273768] i2c i2c-0: Successfully instantiated SPD at 0x52
[    1.274240] i2c i2c-0: Successfully instantiated SPD at 0x53
[    1.282521] e1000e: Intel(R) PRO/1000 Network Driver
[    1.282527] e1000e: Copyright(c) 1999 - 2015 Intel Corporation.
[    1.282737] e1000e 0000:00:19.0: Interrupt Throttling Rate (ints/sec) set to dynamic conservative mode
[    1.294728] sdhci: Secure Digital Host Controller Interface driver
[    1.294733] sdhci: Copyright(c) Pierre Ossman
[    1.311609] SCSI subsystem initialized
[    1.341235] iTCO_vendor_support: vendor-support=0
[    1.341317] sdhci-pci 0000:0d:00.0: SDHCI controller found [1180:e823] (rev 5)
[    1.341319] ACPI: bus type drm_connector registered
[    1.341774] mmc0 bounce up to 128 segments into one, max segment size 65536 bytes
[    1.346705] ACPI: bus type USB registered
[    1.346754] usbcore: registered new interface driver usbfs
[    1.346767] usbcore: registered new interface driver hub
[    1.346784] usbcore: registered new device driver usb
[    1.358277] libata version 3.00 loaded.
[    1.364492] e1000e 0000:00:19.0 0000:00:19.0 (uninitialized): registered PHC clock
[    1.388723] mmc0: SDHCI controller on PCI [0000:0d:00.0] using DMA
[    1.392299] iTCO_wdt iTCO_wdt.1.auto: Found a Cougar Point TCO device (Version=2, TCOBASE=0x0460)
[    1.392446] iTCO_wdt iTCO_wdt.1.auto: initialized. heartbeat=30 sec (nowayout=0)
[    1.401670] ahci 0000:00:1f.2: version 3.0
[    1.401870] ahci 0000:00:1f.2: SSS flag set, parallel bus scan disabled
[    1.402334] ehci-pci 0000:00:1a.0: EHCI Host Controller
[    1.402347] ehci-pci 0000:00:1a.0: new USB bus registered, assigned bus number 1
[    1.402361] ehci-pci 0000:00:1a.0: debug port 2
[    1.406299] ehci-pci 0000:00:1a.0: irq 16, io mem 0xf3a2a000
[    1.411970] ahci 0000:00:1f.2: AHCI vers 0001.0300, 32 command slots, 6 Gbps, SATA mode
[    1.411974] ahci 0000:00:1f.2: 4/6 ports implemented (port mask 0x1b)
[    1.411976] ahci 0000:00:1f.2: flags: 64bit ncq sntf ilck stag pm led clo pio slum part ems sxs apst 
[    1.412685] tsc: Refined TSC clocksource calibration: 2392.229 MHz
[    1.412694] clocksource: tsc: mask: 0xffffffffffffffff max_cycles: 0x227b8a85aa5, max_idle_ns: 440795284834 ns
[    1.417426] clocksource: Switched to clocksource tsc
[    1.417443] ehci-pci 0000:00:1a.0: USB 2.0 started, EHCI 1.00
[    1.417480] firewire_ohci 0000:0d:00.3: added OHCI v1.10 device as card 0, 4 IR + 4 IT contexts, quirks 0x11
[    1.417524] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002, bcdDevice= 6.12
[    1.417529] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    1.417532] usb usb1: Product: EHCI Host Controller
[    1.417536] usb usb1: Manufacturer: Linux 6.12.38+deb13-amd64 ehci_hcd
[    1.417538] usb usb1: SerialNumber: 0000:00:1a.0
[    1.417707] hub 1-0:1.0: USB hub found
[    1.417715] hub 1-0:1.0: 3 ports detected
[    1.417853] ehci-pci 0000:00:1d.0: EHCI Host Controller
[    1.417862] ehci-pci 0000:00:1d.0: new USB bus registered, assigned bus number 2
[    1.417877] ehci-pci 0000:00:1d.0: debug port 2
[    1.422196] ehci-pci 0000:00:1d.0: irq 23, io mem 0xf3a29000
[    1.433166] scsi host0: ahci
[    1.433385] scsi host1: ahci
[    1.433577] scsi host2: ahci
[    1.433769] scsi host3: ahci
[    1.433878] scsi host4: ahci
[    1.434002] scsi host5: ahci
[    1.434044] ata1: SATA max UDMA/133 abar m2048@0xf3a28000 port 0xf3a28100 irq 28 lpm-pol 3
[    1.434047] ata2: SATA max UDMA/133 abar m2048@0xf3a28000 port 0xf3a28180 irq 28 lpm-pol 0
[    1.434049] ata3: DUMMY
[    1.434051] ata4: SATA max UDMA/133 abar m2048@0xf3a28000 port 0xf3a28280 irq 28 lpm-pol 0
[    1.434054] ata5: SATA max UDMA/133 abar m2048@0xf3a28000 port 0xf3a28300 irq 28 lpm-pol 0
[    1.434055] ata6: DUMMY
[    1.436679] ehci-pci 0000:00:1d.0: USB 2.0 started, EHCI 1.00
[    1.436728] usb usb2: New USB device found, idVendor=1d6b, idProduct=0002, bcdDevice= 6.12
[    1.436732] usb usb2: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    1.436733] usb usb2: Product: EHCI Host Controller
[    1.436735] usb usb2: Manufacturer: Linux 6.12.38+deb13-amd64 ehci_hcd
[    1.436736] usb usb2: SerialNumber: 0000:00:1d.0
[    1.436856] hub 2-0:1.0: USB hub found
[    1.436864] hub 2-0:1.0: 3 ports detected
[    1.447959] e1000e 0000:00:19.0 eth0: (PCI Express:2.5GT/s:Width x1) 3c:97:0e:05:81:41
[    1.447962] e1000e 0000:00:19.0 eth0: Intel(R) PRO/1000 Network Connection
[    1.448002] e1000e 0000:00:19.0 eth0: MAC: 10, PHY: 11, PBA No: 1000FF-0FF
[    1.668775] usb 1-1: new high-speed USB device number 2 using ehci-pci
[    1.684852] usb 2-1: new high-speed USB device number 2 using ehci-pci
[    1.744789] ata1: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    1.755911] ata1.00: Model 'INTEL SSDSC2BF180A4L', rev 'LSTi', applying quirks: zeroaftertrim
[    1.758065] ata1.00: ACPI cmd f5/00:00:00:00:00:a0(SECURITY FREEZE LOCK) filtered out
[    1.758090] ata1.00: ACPI cmd ef/10:03:00:00:00:a0(SET FEATURES) filtered out
[    1.765893] ata1.00: supports DRM functions and may not be fully accessible
[    1.765909] ata1.00: ATA-9: INTEL SSDSC2BF180A4L, LSTi, max UDMA/133
[    1.767964] ata1.00: 351651888 sectors, multi 16: LBA48 NCQ (depth 32), AA
[    1.813780] usb 1-1: New USB device found, idVendor=8087, idProduct=0024, bcdDevice= 0.00
[    1.813802] usb 1-1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    1.814791] hub 1-1:1.0: USB hub found
[    1.815146] hub 1-1:1.0: 6 ports detected
[    1.815908] ata1.00: Security Log not supported
[    1.815925] ata1.00: Features: Dev-Sleep
[    1.827995] ata1.00: ACPI cmd f5/00:00:00:00:00:a0(SECURITY FREEZE LOCK) filtered out
[    1.828020] ata1.00: ACPI cmd ef/10:03:00:00:00:a0(SET FEATURES) filtered out
[    1.829491] usb 2-1: New USB device found, idVendor=8087, idProduct=0024, bcdDevice= 0.00
[    1.829510] usb 2-1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    1.830299] hub 2-1:1.0: USB hub found
[    1.830563] hub 2-1:1.0: 8 ports detected
[    1.835794] ata1.00: supports DRM functions and may not be fully accessible
[    1.885936] ata1.00: Security Log not supported
[    1.885966] ata1.00: configured for UDMA/133
[    1.888523] scsi 0:0:0:0: Direct-Access     ATA      INTEL SSDSC2BF18 LSTi PQ: 0 ANSI: 5
[    1.929209] firewire_core 0000:0d:00.3: created device fw0: GUID 3c970eff058141ff, S400
[    2.096788] usb 1-1.3: new full-speed USB device number 3 using ehci-pci
[    2.108780] usb 2-1.2: new full-speed USB device number 3 using ehci-pci
[    2.195103] usb 1-1.3: New USB device found, idVendor=147e, idProduct=2016, bcdDevice= 0.02
[    2.195125] usb 1-1.3: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    2.195133] usb 1-1.3: Product: Biometric Coprocessor
[    2.195138] usb 1-1.3: Manufacturer: UPEK
[    2.200125] ata2: SATA link up 6.0 Gbps (SStatus 133 SControl 300)
[    2.201255] ata2.00: ACPI cmd f5/00:00:00:00:00:a0(SECURITY FREEZE LOCK) filtered out
[    2.201269] ata2.00: ACPI cmd ef/10:03:00:00:00:a0(SET FEATURES) filtered out
[    2.201790] ata2.00: ATA-9: WDC WDS120G2G0A-00JH30, UE500000, max UDMA/133
[    2.201799] ata2.00: 234455040 sectors, multi 1: LBA48 NCQ (depth 32)
[    2.202893] ata2.00: Features: Dev-Sleep
[    2.207907] ata2.00: ACPI cmd f5/00:00:00:00:00:a0(SECURITY FREEZE LOCK) filtered out
[    2.207923] ata2.00: ACPI cmd ef/10:03:00:00:00:a0(SET FEATURES) filtered out
[    2.208571] ata2.00: configured for UDMA/133
[    2.208987] usb 2-1.2: New USB device found, idVendor=046d, idProduct=c534, bcdDevice=29.01
[    2.208999] usb 2-1.2: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    2.209005] usb 2-1.2: Product: USB Receiver
[    2.209011] usb 2-1.2: Manufacturer: Logitech
[    2.209031] scsi 1:0:0:0: Direct-Access     ATA      WDC WDS120G2G0A- 0000 PQ: 0 ANSI: 5
[    2.264806] usb 1-1.4: new full-speed USB device number 4 using ehci-pci
[    2.281818] psmouse serio1: synaptics: queried max coordinates: x [..5470], y [..4498]
[    2.367153] usb 1-1.4: New USB device found, idVendor=0a5c, idProduct=217f, bcdDevice= 7.48
[    2.367176] usb 1-1.4: New USB device strings: Mfr=1, Product=2, SerialNumber=3
[    2.367183] usb 1-1.4: Product: Broadcom Bluetooth Device
[    2.367188] usb 1-1.4: Manufacturer: Broadcom Corp
[    2.367193] usb 1-1.4: SerialNumber: 7CE9D3DBD208
[    2.393773] psmouse serio1: synaptics: Touchpad model: 1, fw: 7.2, id: 0x1c0b1, caps: 0xd047b1/0xb40000/0xa0000/0x0, board id: 0, fw id: 920262
[    2.393810] psmouse serio1: synaptics: serio: Synaptics pass-through port at isa0060/serio1/input0
[    2.440807] usb 1-1.5: new high-speed USB device number 5 using ehci-pci
[    2.463744] input: SynPS/2 Synaptics TouchPad as /devices/platform/i8042/serio1/input/input5
[    2.520576] ata4: SATA link down (SStatus 0 SControl 300)
[    2.541654] usb 1-1.5: New USB device found, idVendor=17ef, idProduct=100a, bcdDevice= 0.00
[    2.541679] usb 1-1.5: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    2.542461] hub 1-1.5:1.0: USB hub found
[    2.542710] hub 1-1.5:1.0: 7 ports detected
[    2.616807] usb 1-1.6: new high-speed USB device number 6 using ehci-pci
[    2.720295] usb 1-1.6: New USB device found, idVendor=04f2, idProduct=b217, bcdDevice= 8.54
[    2.720317] usb 1-1.6: New USB device strings: Mfr=1, Product=2, SerialNumber=0
[    2.720324] usb 1-1.6: Product: Integrated Camera
[    2.720330] usb 1-1.6: Manufacturer: Chicony Electronics Co., Ltd.
[    2.832731] ata5: SATA link down (SStatus 0 SControl 300)
[    2.836040] e1000e 0000:00:19.0 enp0s25: renamed from eth0
[    2.838163] xhci_hcd 0000:0e:00.0: xHCI Host Controller
[    2.838175] xhci_hcd 0000:0e:00.0: new USB bus registered, assigned bus number 3
[    2.838335] xhci_hcd 0000:0e:00.0: hcc params 0x014042cb hci version 0x96 quirks 0x0000000000000004
[    2.838746] xhci_hcd 0000:0e:00.0: xHCI Host Controller
[    2.838752] xhci_hcd 0000:0e:00.0: new USB bus registered, assigned bus number 4
[    2.838757] xhci_hcd 0000:0e:00.0: Host supports USB 3.0 SuperSpeed
[    2.841825] usb usb3: New USB device found, idVendor=1d6b, idProduct=0002, bcdDevice= 6.12
[    2.841831] usb usb3: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    2.841835] usb usb3: Product: xHCI Host Controller
[    2.841837] usb usb3: Manufacturer: Linux 6.12.38+deb13-amd64 xhci-hcd
[    2.841840] usb usb3: SerialNumber: 0000:0e:00.0
[    2.842024] hub 3-0:1.0: USB hub found
[    2.842041] hub 3-0:1.0: 2 ports detected
[    2.842256] usb usb4: We don't know the algorithms for LPM for this host, disabling LPM.
[    2.842294] usb usb4: New USB device found, idVendor=1d6b, idProduct=0003, bcdDevice= 6.12
[    2.842299] usb usb4: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    2.842302] usb usb4: Product: xHCI Host Controller
[    2.842304] usb usb4: Manufacturer: Linux 6.12.38+deb13-amd64 xhci-hcd
[    2.842307] usb usb4: SerialNumber: 0000:0e:00.0
[    2.842469] hub 4-0:1.0: USB hub found
[    2.842485] hub 4-0:1.0: 2 ports detected
[    2.849390] sd 1:0:0:0: [sdb] 234455040 512-byte logical blocks: (120 GB/112 GiB)
[    2.849409] sd 1:0:0:0: [sdb] Write Protect is off
[    2.849412] sd 1:0:0:0: [sdb] Mode Sense: 00 3a 00 00
[    2.849428] sd 1:0:0:0: [sdb] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    2.849456] sd 1:0:0:0: [sdb] Preferred minimum I/O size 512 bytes
[    2.849582] sd 0:0:0:0: [sda] 351651888 512-byte logical blocks: (180 GB/168 GiB)
[    2.849587] sd 0:0:0:0: [sda] 4096-byte physical blocks
[    2.849602] sd 0:0:0:0: [sda] Write Protect is off
[    2.849605] sd 0:0:0:0: [sda] Mode Sense: 00 3a 00 00
[    2.849626] sd 0:0:0:0: [sda] Write cache: enabled, read cache: enabled, doesn't support DPO or FUA
[    2.849661] sd 0:0:0:0: [sda] Preferred minimum I/O size 4096 bytes
[    2.863310] hid: raw HID events driver (C) Jiri Kosina
[    2.886178]  sda: sda1 sda2 sda3
[    2.886451] sd 0:0:0:0: [sda] Attached SCSI disk
[    2.887664]  sdb: sdb1
[    2.887821] sd 1:0:0:0: [sdb] Attached SCSI disk
[    2.899011] usbcore: registered new interface driver usbhid
[    2.899015] usbhid: USB HID core driver
[    2.902347] input: Logitech USB Receiver as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.0/0003:046D:C534.0001/input/input7
[    3.029803] device-mapper: core: CONFIG_IMA_DISABLE_HTABLE is disabled. Duplicate IMA measurements will not be recorded in the IMA log.
[    3.029840] device-mapper: uevent: version 1.0.3
[    3.029959] device-mapper: ioctl: 4.48.0-ioctl (2023-03-01) initialised: dm-devel@lists.linux.dev
[    3.092825] hid-generic 0003:046D:C534.0001: input,hidraw0: USB HID v1.11 Keyboard [Logitech USB Receiver] on usb-0000:00:1d.0-1.2/input0
[    3.093131] input: Logitech USB Receiver Mouse as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.1/0003:046D:C534.0002/input/input8
[    3.093268] input: Logitech USB Receiver Consumer Control as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.1/0003:046D:C534.0002/input/input9
[    3.148751] input: Logitech USB Receiver System Control as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.1/0003:046D:C534.0002/input/input10
[    3.148990] hid-generic 0003:046D:C534.0002: input,hiddev0,hidraw1: USB HID v1.11 Mouse [Logitech USB Receiver] on usb-0000:00:1d.0-1.2/input1
[    3.354118] psmouse serio2: trackpoint: IBM TrackPoint firmware: 0x0e, buttons: 3/3
[    3.577999] i915 0000:00:02.0: [drm] Found SANDYBRIDGE (device ID 0126) display version 6.00 stepping N/A
[    3.578553] i915 0000:00:02.0: [drm] Disabling ppGTT for VT-d support
[    3.578825] i915 0000:00:02.0: [drm] VT-d active for gfx access
[    3.579226] Console: switching to colour dummy device 80x25
[    3.579310] i915 0000:00:02.0: vgaarb: deactivate vga console
[    3.579343] i915 0000:00:02.0: [drm] Using Transparent Hugepages
[    3.579346] i915 0000:00:02.0: [drm] DMAR active, disabling use of stolen memory
[    3.601322] logitech-djreceiver 0003:046D:C534.0001: hidraw0: USB HID v1.11 Keyboard [Logitech USB Receiver] on usb-0000:00:1d.0-1.2/input0
[    3.614498] [drm] Initialized i915 1.6.0 for 0000:00:02.0 on minor 0
[    3.614741] ACPI: video: Video Device [VID] (multi-head: yes  rom: no  post: no)
[    3.614813] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/LNXVIDEO:00/input/input13
[    3.614879] ACPI: video: Video Device [VID1] (multi-head: yes  rom: yes  post: no)
[    3.614950] input: Video Bus as /devices/LNXSYSTM:00/LNXSYBUS:00/PNP0A08:00/device:09/LNXVIDEO:01/input/input14
[    3.692880] input: TPPS/2 IBM TrackPoint as /devices/platform/i8042/serio1/serio2/input/input6
[    3.750871] logitech-djreceiver 0003:046D:C534.0002: hiddev0,hidraw1: USB HID v1.11 Mouse [Logitech USB Receiver] on usb-0000:00:1d.0-1.2/input1
[    3.805580] logitech-djreceiver 0003:046D:C534.0002: device of type eQUAD nano Lite (0x0a) connected on slot 2
[    3.806085] input: Logitech Wireless Mouse PID:4054 Mouse as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.1/0003:046D:C534.0002/0003:046D:4054.0003/input/input15
[    3.807553] input: Logitech Wireless Mouse PID:4054 Consumer Control as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.1/0003:046D:C534.0002/0003:046D:4054.0003/input/input16
[    3.808289] hid-generic 0003:046D:4054.0003: input,hidraw2: USB HID v1.11 Mouse [Logitech Wireless Mouse PID:4054] on usb-0000:00:1d.0-1.2/input1:2
[    3.850168] fbcon: i915drmfb (fb0) is primary device
[    3.894184] input: Logitech Wireless Mouse as /devices/pci0000:00/0000:00:1d.0/usb2/2-1/2-1.2/2-1.2:1.1/0003:046D:C534.0002/0003:046D:4054.0003/input/input20
[    3.894758] logitech-hidpp-device 0003:046D:4054.0003: input,hidraw2: USB HID v1.11 Mouse [Logitech Wireless Mouse] on usb-0000:00:1d.0-1.2/input1:2
[    4.790583] Console: switching to colour frame buffer device 200x56
[    4.811457] i915 0000:00:02.0: [drm] fb0: i915drmfb frame buffer device
[    5.340556] PM: Image not found (code -22)
[    5.563426] EXT4-fs (dm-1): orphan cleanup on readonly fs
[    5.563784] EXT4-fs (dm-1): mounted filesystem 8c0b1033-51e6-4582-9cb2-dba9f913df8a ro with ordered data mode. Quota mode: none.
[    5.648803] Not activating Mandatory Access Control as /sbin/tomoyo-init does not exist.
[    5.742974] systemd[1]: Inserted module 'autofs4'
[    5.840489] systemd[1]: systemd 257.7-1 running in system mode (+PAM +AUDIT +SELINUX +APPARMOR +IMA +IPE +SMACK +SECCOMP +GCRYPT -GNUTLS +OPENSSL +ACL +BLKID +CURL +ELFUTILS +FIDO2 +IDN2 -IDN +IPTC +KMOD +LIBCRYPTSETUP +LIBCRYPTSETUP_PLUGINS +LIBFDISK +PCRE2 +PWQUALITY +P11KIT +QRENCODE +TPM2 +BZIP2 +LZ4 +XZ +ZLIB +ZSTD +BPF_FRAMEWORK +BTF -XKBCOMMON -UTMP +SYSVINIT +LIBARCHIVE)
[    5.840498] systemd[1]: Detected architecture x86-64.
[    5.844835] systemd[1]: Hostname set to <syenasweta>.
[    6.033241] systemd[1]: bpf-restrict-fs: LSM BPF program attached
[    6.275073] systemd[1]: Queued start job for default target graphical.target.
[    6.335125] systemd[1]: Created slice system-getty.slice - Slice /system/getty.
[    6.335622] systemd[1]: Created slice system-modprobe.slice - Slice /system/modprobe.
[    6.336050] systemd[1]: Created slice system-systemd\x2dfsck.slice - Slice /system/systemd-fsck.
[    6.336336] systemd[1]: Created slice user.slice - User and Session Slice.
[    6.336419] systemd[1]: Started systemd-ask-password-wall.path - Forward Password Requests to Wall Directory Watch.
[    6.336650] systemd[1]: Set up automount proc-sys-fs-binfmt_misc.automount - Arbitrary Executable File Formats File System Automount Point.
[    6.336700] systemd[1]: Expecting device dev-disk-by\x2duuid-64c148d6\x2d7420\x2d4230\x2da9bf\x2dc82760ba8410.device - /dev/disk/by-uuid/64c148d6-7420-4230-a9bf-c82760ba8410...
[    6.336713] systemd[1]: Expecting device dev-disk-by\x2duuid-96FB\x2d4464.device - /dev/disk/by-uuid/96FB-4464...
[    6.336723] systemd[1]: Expecting device dev-mapper-syenasweta\x2dhome.device - /dev/mapper/syenasweta-home...
[    6.336734] systemd[1]: Expecting device dev-mapper-syenasweta\x2dsrv.device - /dev/mapper/syenasweta-srv...
[    6.336742] systemd[1]: Expecting device dev-mapper-syenasweta\x2dswap.device - /dev/mapper/syenasweta-swap...
[    6.336753] systemd[1]: Expecting device dev-mapper-syenasweta\x2dtmp.device - /dev/mapper/syenasweta-tmp...
[    6.336765] systemd[1]: Expecting device dev-mapper-syenasweta\x2dvar.device - /dev/mapper/syenasweta-var...
[    6.336812] systemd[1]: Reached target nss-user-lookup.target - User and Group Name Lookups.
[    6.336833] systemd[1]: Reached target remote-fs.target - Remote File Systems.
[    6.336850] systemd[1]: Reached target slices.target - Slice Units.
[    6.336987] systemd[1]: Listening on dm-event.socket - Device-mapper event daemon FIFOs.
[    6.337077] systemd[1]: Listening on lvm2-lvmpolld.socket - LVM2 poll daemon socket.
[    6.343673] systemd[1]: Listening on systemd-coredump.socket - Process Core Dump Socket.
[    6.344849] systemd[1]: Listening on systemd-creds.socket - Credential Encryption/Decryption.
[    6.344949] systemd[1]: Listening on systemd-initctl.socket - initctl Compatibility Named Pipe.
[    6.345066] systemd[1]: Listening on systemd-journald-dev-log.socket - Journal Socket (/dev/log).
[    6.345189] systemd[1]: Listening on systemd-journald.socket - Journal Sockets.
[    6.345266] systemd[1]: systemd-pcrextend.socket - TPM PCR Measurements was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    6.345288] systemd[1]: systemd-pcrlock.socket - Make TPM PCR Policy was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    6.345384] systemd[1]: Listening on systemd-udevd-control.socket - udev Control Socket.
[    6.345456] systemd[1]: Listening on systemd-udevd-kernel.socket - udev Kernel Socket.
[    6.346972] systemd[1]: Mounting dev-hugepages.mount - Huge Pages File System...
[    6.347861] systemd[1]: Mounting dev-mqueue.mount - POSIX Message Queue File System...
[    6.347936] systemd[1]: run-lock.mount: Directory /run/lock to mount over is not empty, mounting anyway.
[    6.348880] systemd[1]: Mounting run-lock.mount - Legacy Locks Directory /run/lock...
[    6.349845] systemd[1]: Mounting sys-kernel-debug.mount - Kernel Debug File System...
[    6.351168] systemd[1]: Mounting sys-kernel-tracing.mount - Kernel Trace File System...
[    6.352921] systemd[1]: Starting blk-availability.service - Availability of block devices...
[    6.355282] systemd[1]: Starting keyboard-setup.service - Set the console keyboard layout...
[    6.357220] systemd[1]: Starting kmod-static-nodes.service - Create List of Static Device Nodes...
[    6.358832] systemd[1]: Starting lvm2-monitor.service - Monitoring of LVM2 mirrors, snapshots etc. using dmeventd or progress polling...
[    6.360560] systemd[1]: Starting modprobe@configfs.service - Load Kernel Module configfs...
[    6.362161] systemd[1]: Starting modprobe@drm.service - Load Kernel Module drm...
[    6.363806] systemd[1]: Starting modprobe@efi_pstore.service - Load Kernel Module efi_pstore...
[    6.365495] systemd[1]: Starting modprobe@fuse.service - Load Kernel Module fuse...
[    6.365782] systemd[1]: systemd-fsck-root.service - File System Check on Root Device was skipped because of an unmet condition check (ConditionPathExists=!/run/initramfs/fsck-root).
[    6.366069] systemd[1]: systemd-hibernate-clear.service - Clear Stale Hibernate Storage Info was skipped because of an unmet condition check (ConditionPathExists=/sys/firmware/efi/efivars/HibernateLocation-8cf2644b-4b0b-428f-9387-6d876050dc67).
[    6.369660] systemd[1]: Starting systemd-journald.service - Journal Service...
[    6.372909] systemd[1]: Starting systemd-modules-load.service - Load Kernel Modules...
[    6.372950] systemd[1]: systemd-pcrmachine.service - TPM PCR Machine ID Measurement was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    6.374504] systemd[1]: Starting systemd-remount-fs.service - Remount Root and Kernel File Systems...
[    6.374601] systemd[1]: systemd-tpm2-setup-early.service - Early TPM SRK Setup was skipped because of an unmet condition check (ConditionSecurity=measured-uki).
[    6.376137] systemd[1]: Starting systemd-udev-load-credentials.service - Load udev Rules from Credentials...
[    6.377772] systemd[1]: Starting systemd-udev-trigger.service - Coldplug All udev Devices...
[    6.378945] pstore: Using crash dump compression: deflate
[    6.394615] systemd[1]: Mounted dev-hugepages.mount - Huge Pages File System.
[    6.399947] systemd[1]: Mounted dev-mqueue.mount - POSIX Message Queue File System.
[    6.406952] systemd[1]: Mounted run-lock.mount - Legacy Locks Directory /run/lock.
[    6.411830] systemd[1]: Mounted sys-kernel-debug.mount - Kernel Debug File System.
[    6.412641] pstore: Registered efi_pstore as persistent store backend
[    6.412911] systemd[1]: Mounted sys-kernel-tracing.mount - Kernel Trace File System.
[    6.413497] systemd[1]: Finished blk-availability.service - Availability of block devices.
[    6.414072] systemd[1]: Finished kmod-static-nodes.service - Create List of Static Device Nodes.
[    6.414518] systemd[1]: modprobe@configfs.service: Deactivated successfully.
[    6.414770] systemd[1]: Finished modprobe@configfs.service - Load Kernel Module configfs.
[    6.415223] systemd[1]: modprobe@drm.service: Deactivated successfully.
[    6.415527] systemd[1]: Finished modprobe@drm.service - Load Kernel Module drm.
[    6.415999] systemd[1]: modprobe@efi_pstore.service: Deactivated successfully.
[    6.416285] systemd[1]: Finished modprobe@efi_pstore.service - Load Kernel Module efi_pstore.
[    6.416777] systemd[1]: modprobe@fuse.service: Deactivated successfully.
[    6.417067] systemd[1]: Finished modprobe@fuse.service - Load Kernel Module fuse.
[    6.418978] systemd[1]: Mounting sys-fs-fuse-connections.mount - FUSE Control File System...
[    6.420776] systemd[1]: Mounting sys-kernel-config.mount - Kernel Configuration File System...
[    6.422565] systemd[1]: Starting systemd-tmpfiles-setup-dev-early.service - Create Static Device Nodes in /dev gracefully...
[    6.427032] systemd[1]: Finished systemd-udev-load-credentials.service - Load udev Rules from Credentials.
[    6.430365] systemd[1]: Mounted sys-fs-fuse-connections.mount - FUSE Control File System.
[    6.430770] systemd-journald[393]: Collecting audit messages is disabled.
[    6.433497] systemd[1]: Mounted sys-kernel-config.mount - Kernel Configuration File System.
[    6.436453] lp: driver loaded but no devices found
[    6.443362] ppdev: user-space parallel port driver
[    6.454643] systemd[1]: Finished systemd-tmpfiles-setup-dev-early.service - Create Static Device Nodes in /dev gracefully.
[    6.458263] EXT4-fs (dm-1): re-mounted 8c0b1033-51e6-4582-9cb2-dba9f913df8a r/w.
[    6.459303] systemd[1]: Finished systemd-remount-fs.service - Remount Root and Kernel File Systems.
[    6.460177] systemd[1]: systemd-hwdb-update.service - Rebuild Hardware Database was skipped because of an unmet condition check (ConditionNeedsUpdate=/etc).
[    6.460304] systemd[1]: systemd-sysusers.service - Create System Users was skipped because no trigger condition checks were met.
[    6.461895] systemd[1]: Starting systemd-tmpfiles-setup-dev.service - Create Static Device Nodes in /dev...
[    6.478133] systemd[1]: Finished systemd-tmpfiles-setup-dev.service - Create Static Device Nodes in /dev.
[    6.479579] systemd[1]: Starting systemd-udevd.service - Rule-based Manager for Device Events and Files...
[    6.487012] systemd[1]: Finished lvm2-monitor.service - Monitoring of LVM2 mirrors, snapshots etc. using dmeventd or progress polling.
[    6.499120] systemd[1]: Finished keyboard-setup.service - Set the console keyboard layout.
[    6.499292] systemd[1]: Reached target local-fs-pre.target - Preparation for Local File Systems.
[    6.510621] IPMI message handler: version 39.2
[    6.514671] ipmi device interface
[    6.532403] systemd[1]: Started systemd-journald.service - Journal Service.
[    6.687636] sd 0:0:0:0: Attached scsi generic sg0 type 0
[    6.688067] sd 1:0:0:0: Attached scsi generic sg1 type 0
[    6.728365] Adding 9863164k swap on /dev/mapper/syenasweta-swap.  Priority:-2 extents:1 across:9863164k SS
[    6.772808] ACPI: AC: AC Adapter [AC] (on-line)
[    6.823817] at24 0-0050: supply vcc not found, using dummy regulator
[    6.827675] at24 0-0050: 256 byte spd EEPROM, read-only
[    6.828935] at24 0-0051: supply vcc not found, using dummy regulator
[    6.831502] at24 0-0051: 256 byte spd EEPROM, read-only
[    6.831660] at24 0-0052: supply vcc not found, using dummy regulator
[    6.843490] input: PC Speaker as /devices/platform/pcspkr/input/input21
[    6.851667] at24 0-0052: 256 byte spd EEPROM, read-only
[    6.851831] at24 0-0053: supply vcc not found, using dummy regulator
[    6.858392] at24 0-0053: 256 byte spd EEPROM, read-only
[    6.872519] Non-volatile memory driver v1.3
[    6.874398] mc: Linux media interface: v0.10
[    6.943411] thinkpad_acpi: ThinkPad ACPI Extras v0.26
[    6.943417] thinkpad_acpi: http://ibm-acpi.sf.net/
[    6.943419] thinkpad_acpi: ThinkPad BIOS 8BET66WW (1.46 ), EC unknown
[    6.943420] thinkpad_acpi: Lenovo ThinkPad W520, model 42763KU
[    6.947246] thinkpad_acpi: radio switch found; radios are enabled
[    6.947258] thinkpad_acpi: This ThinkPad has standard ACPI backlight brightness control, supported by the ACPI video driver
[    6.947260] thinkpad_acpi: Disabling thinkpad-acpi brightness events by default...
[    6.957730] videodev: Linux video capture interface: v2.00
[    6.961597] thinkpad_acpi: rfkill switch tpacpi_bluetooth_sw: radio is unblocked
[    6.972290] thinkpad_acpi: Standard ACPI backlight interface available, not loading native one
[    6.987346] thinkpad_acpi: battery 1 registered (start 0, stop 100, behaviours: 0x7)
[    6.987372] ACPI: battery: new extension: ThinkPad Battery Extension
[    6.989253] input: ThinkPad Extra Buttons as /devices/platform/thinkpad_acpi/input/input22
[    7.036281] Bluetooth: Core ver 2.22
[    7.071531] RAPL PMU: API unit is 2^-32 Joules, 3 fixed counters, 163840 ms ovfl timer
[    7.071535] RAPL PMU: hw unit of domain pp0-core 2^-16 Joules
[    7.071537] RAPL PMU: hw unit of domain package 2^-16 Joules
[    7.071538] RAPL PMU: hw unit of domain pp1-gpu 2^-16 Joules
[    7.071851] cfg80211: Loading compiled-in X.509 certificates for regulatory database
[    7.072142] Loaded X.509 cert 'benh@debian.org: 577e021cb980e0e820821ba7b54b4961b8b4fadf'
[    7.072352] Loaded X.509 cert 'romain.perier@gmail.com: 3abbc6ec146e09d1b6016ab9d6cf71dd233f0328'
[    7.072579] Loaded X.509 cert 'sforshee: 00b28ddf47aef9cea7'
[    7.072861] Loaded X.509 cert 'wens: 61c038651aabdcf94bd0ac7ff06c7248db18c600'
[    7.075673] cryptd: max_cpu_qlen set to 1000
[    7.094871] AES CTR mode by8 optimization enabled
[    7.100734] usb 1-1.6: Found UVC 1.00 device Integrated Camera (04f2:b217)
[    7.121822] usbcore: registered new interface driver uvcvideo
[    7.129543] NET: Registered PF_BLUETOOTH protocol family
[    7.129548] Bluetooth: HCI device and connection manager initialized
[    7.129554] Bluetooth: HCI socket layer initialized
[    7.129557] Bluetooth: L2CAP socket layer initialized
[    7.129565] Bluetooth: SCO socket layer initialized
[    7.156630] snd_hda_intel 0000:00:1b.0: bound 0000:00:02.0 (ops i915_audio_component_bind_ops [i915])
[    7.157543] snd_hda_intel 0000:01:00.1: Disabling MSI
[    7.157556] snd_hda_intel 0000:01:00.1: Handle vga_switcheroo audio client
[    7.160023] Intel(R) Wireless WiFi driver for Linux
[    7.161143] iwlwifi 0000:03:00.0: can't disable ASPM; OS doesn't have ASPM control
[    7.164951] iwlwifi 0000:03:00.0: Detected crf-id 0xa5a5a5a1, cnv-id 0xa5a5a5a1 wfpm id 0xa5a5a5a1
[    7.164991] iwlwifi 0000:03:00.0: PCI dev 0085/1311, rev=0xb0, rfid=0xd55555d5
[    7.164997] iwlwifi 0000:03:00.0: Detected Intel(R) Centrino(R) Advanced-N 6205 AGN
[    7.174714] iwlwifi 0000:03:00.0: loaded firmware version 18.168.6.1 6000g2a-6.ucode op_mode iwldvm
[    7.194967] snd_hda_codec_conexant hdaudioC0D0: CX20590: BIOS auto-probing.
[    7.195546] snd_hda_codec_conexant hdaudioC0D0: autoconfig for CX20590: line_outs=1 (0x1f/0x0/0x0/0x0/0x0) type:speaker
[    7.195552] snd_hda_codec_conexant hdaudioC0D0:    speaker_outs=0 (0x0/0x0/0x0/0x0/0x0)
[    7.195556] snd_hda_codec_conexant hdaudioC0D0:    hp_outs=2 (0x1c/0x19/0x0/0x0/0x0)
[    7.195559] snd_hda_codec_conexant hdaudioC0D0:    mono: mono_out=0x0
[    7.195561] snd_hda_codec_conexant hdaudioC0D0:    inputs:
[    7.195564] snd_hda_codec_conexant hdaudioC0D0:      Internal Mic=0x23
[    7.195566] snd_hda_codec_conexant hdaudioC0D0:      Dock Mic=0x1a
[    7.195569] snd_hda_codec_conexant hdaudioC0D0:      Mic=0x1b
[    7.199888] usbcore: registered new interface driver btusb
[    7.212744] input: HDA NVidia HDMI/DP,pcm=3 as /devices/pci0000:00/0000:00:01.0/0000:01:00.1/sound/card1/input23
[    7.212832] input: HDA NVidia HDMI/DP,pcm=7 as /devices/pci0000:00/0000:00:01.0/0000:01:00.1/sound/card1/input25
[    7.212899] input: HDA NVidia HDMI/DP,pcm=8 as /devices/pci0000:00/0000:00:01.0/0000:01:00.1/sound/card1/input30
[    7.212965] input: HDA NVidia HDMI/DP,pcm=9 as /devices/pci0000:00/0000:00:01.0/0000:01:00.1/sound/card1/input31
[    7.216817] input: HDA Digital PCBeep as /devices/pci0000:00/0000:00:1b.0/sound/card0/input24
[    7.216971] input: HDA Intel PCH Dock Mic as /devices/pci0000:00/0000:00:1b.0/sound/card0/input26
[    7.217051] input: HDA Intel PCH Mic as /devices/pci0000:00/0000:00:1b.0/sound/card0/input27
[    7.217125] input: HDA Intel PCH Dock Headphone as /devices/pci0000:00/0000:00:1b.0/sound/card0/input28
[    7.217198] input: HDA Intel PCH Headphone as /devices/pci0000:00/0000:00:1b.0/sound/card0/input29
[    7.404528] iwlwifi 0000:03:00.0: CONFIG_IWLWIFI_DEBUG disabled
[    7.404534] iwlwifi 0000:03:00.0: CONFIG_IWLWIFI_DEBUGFS disabled
[    7.404536] iwlwifi 0000:03:00.0: CONFIG_IWLWIFI_DEVICE_TRACING enabled
[    7.404538] iwlwifi 0000:03:00.0: Detected Intel(R) Centrino(R) Advanced-N 6205 AGN, REV=0xB0
[    7.407374] intel_rapl_common: Found RAPL domain package
[    7.407377] intel_rapl_common: Found RAPL domain core
[    7.407379] intel_rapl_common: Found RAPL domain uncore
[    7.407385] intel_rapl_common: package-0:package:long_term locked by BIOS
[    7.407387] intel_rapl_common: package-0:package:short_term locked by BIOS
[    7.460823] ieee80211 phy0: Selected rate control algorithm 'iwl-agn-rs'
[    7.469265] iwlwifi 0000:03:00.0 wlp3s0: renamed from wlan0
[    7.481456] EXT4-fs (sda2): mounted filesystem 64c148d6-7420-4230-a9bf-c82760ba8410 r/w with ordered data mode. Quota mode: none.
[    7.512547] EXT4-fs (dm-5): mounted filesystem 253ef33d-3bb6-43bb-8718-a7a1d18a9231 r/w with ordered data mode. Quota mode: none.
[    7.523588] EXT4-fs (dm-0): mounted filesystem 65d6a66f-a15c-41df-abfa-6c6363d31129 r/w with ordered data mode. Quota mode: none.
[    7.526360] EXT4-fs (dm-3): mounted filesystem 3f6fdb62-86c9-49ed-8b37-b1def5c13e8a r/w with ordered data mode. Quota mode: none.
[    7.526545] EXT4-fs (dm-4): mounted filesystem 339410ff-efa3-43b6-99a4-72d60166ba1c r/w with ordered data mode. Quota mode: none.
[    7.692149] systemd-journald[393]: Received client request to flush runtime journal.
[    7.838561] audit: type=1400 audit(1755194370.589:2): apparmor="STATUS" operation="profile_load" profile="unconfined" name="buildah" pid=775 comm="apparmor_parser"
[    7.838573] audit: type=1400 audit(1755194370.589:3): apparmor="STATUS" operation="profile_load" profile="unconfined" name=4D6F6E676F444220436F6D70617373 pid=770 comm="apparmor_parser"
[    7.838577] audit: type=1400 audit(1755194370.589:4): apparmor="STATUS" operation="profile_load" profile="unconfined" name="1password" pid=768 comm="apparmor_parser"
[    7.838580] audit: type=1400 audit(1755194370.589:5): apparmor="STATUS" operation="profile_load" profile="unconfined" name="QtWebEngineProcess" pid=771 comm="apparmor_parser"
[    7.838582] audit: type=1400 audit(1755194370.589:6): apparmor="STATUS" operation="profile_load" profile="unconfined" name="brave" pid=774 comm="apparmor_parser"
[    7.838585] audit: type=1400 audit(1755194370.593:7): apparmor="STATUS" operation="profile_load" profile="unconfined" name="balena-etcher" pid=773 comm="apparmor_parser"
[    7.838587] audit: type=1400 audit(1755194370.593:8): apparmor="STATUS" operation="profile_load" profile="unconfined" name="Discord" pid=769 comm="apparmor_parser"
[    7.840154] audit: type=1400 audit(1755194370.593:9): apparmor="STATUS" operation="profile_load" profile="unconfined" name="busybox" pid=777 comm="apparmor_parser"
[    7.840167] audit: type=1400 audit(1755194370.593:10): apparmor="STATUS" operation="profile_load" profile="unconfined" name="ch-checkns" pid=779 comm="apparmor_parser"
[    7.840564] audit: type=1400 audit(1755194370.593:11): apparmor="STATUS" operation="profile_load" profile="unconfined" name="chromium" pid=782 comm="apparmor_parser"
[    7.841331] nvidia: loading out-of-tree module taints kernel.
[    7.841344] nvidia: module license 'NVIDIA' taints kernel.
[    7.841346] Disabling lock debugging due to kernel taint
[    7.841350] nvidia: module verification failed: signature and/or required key missing - tainting kernel
[    7.841352] nvidia: module license taints kernel.
[    8.116030] nvidia: unknown parameter 'NVreg_PreserveVideoMemoryAllocations' ignored
[    8.116744] nvidia-nvlink: Nvlink Core is being initialized, major device number 236
[    8.117041] nvidia 0000:01:00.0: enabling device (0000 -> 0003)
[    8.117108] nvidia 0000:01:00.0: vgaarb: VGA decodes changed: olddecodes=io+mem,decodes=none:owns=none
[    8.117216] NVRM: loading NVIDIA UNIX x86_64 Kernel Module  390.157  Wed Oct 12 09:19:07 UTC 2022 (using threaded interrupts)
[    9.141880] nvidia-modeset: Loading NVIDIA Kernel Mode Setting Driver for UNIX platforms  390.157  Wed Oct 12 09:15:25 UTC 2022
[   10.142055] nvidia_drm: unknown parameter 'fbdev' ignored
[   10.142570] [drm] [nvidia-drm] [GPU ID 0x00000100] Loading driver
[   10.628329] [drm] Initialized nvidia-drm 0.0.0 for 0000:01:00.0 on minor 1
[   11.090331] Bluetooth: BNEP (Ethernet Emulation) ver 1.3
[   11.090336] Bluetooth: BNEP filters: protocol multicast
[   11.090341] Bluetooth: BNEP socket layer initialized
[   11.092334] Bluetooth: MGMT ver 1.23
[   11.152379] Bluetooth: RFCOMM TTY layer initialized
[   11.152390] Bluetooth: RFCOMM socket layer initialized
[   11.152397] Bluetooth: RFCOMM ver 1.11
[   11.323238] NET: Registered PF_QIPCRTR protocol family
[   11.561082] iwlwifi 0000:03:00.0: Radio type=0x1-0x2-0x0
[   11.852303] iwlwifi 0000:03:00.0: Radio type=0x1-0x2-0x0
[   11.982714] iwlwifi 0000:03:00.0: Radio type=0x1-0x2-0x0
[   12.272962] iwlwifi 0000:03:00.0: Radio type=0x1-0x2-0x0
[   12.963991] kauditd_printk_skb: 137 callbacks suppressed
[   12.963996] audit: type=1400 audit(1755194375.717:149): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   12.964002] audit: type=1400 audit(1755194375.717:150): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidiactl" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   12.964123] audit: type=1400 audit(1755194375.717:151): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   12.964128] audit: type=1400 audit(1755194375.717:152): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidiactl" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   12.964491] audit: type=1400 audit(1755194375.717:153): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   12.964494] audit: type=1400 audit(1755194375.717:154): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidiactl" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   12.965316] audit: type=1400 audit(1755194375.721:155): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   12.965341] audit: type=1400 audit(1755194375.721:156): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia0" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   12.965459] audit: type=1400 audit(1755194375.721:157): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   12.965482] audit: type=1400 audit(1755194375.721:158): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidiactl" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   14.212902] WARNING: Flushing system-wide workqueues will be prohibited in near future.
[   14.212910] CPU: 7 UID: 0 PID: 1225 Comm: Xorg Tainted: P          IOE      6.12.38+deb13-amd64 #1  Debian 6.12.38-1
[   14.212916] Tainted: [P]=PROPRIETARY_MODULE, [I]=FIRMWARE_WORKAROUND, [O]=OOT_MODULE, [E]=UNSIGNED_MODULE
[   14.212918] Hardware name: LENOVO 42763KU/42763KU, BIOS 8BET66WW (1.46 ) 06/14/2018
[   14.212920] Call Trace:
[   14.212923]  <TASK>
[   14.212926]  dump_stack_lvl+0x5d/0x80
[   14.212937]  __nv_drm_gem_fence_context_free+0x5f/0xc0 [nvidia_drm]
[   14.212947]  drm_gem_handle_delete+0x90/0xd0 [drm]
[   14.213006]  ? __pfx_drm_gem_close_ioctl+0x10/0x10 [drm]
[   14.213052]  drm_ioctl_kernel+0xb0/0x100 [drm]
[   14.213099]  drm_ioctl+0x277/0x4f0 [drm]
[   14.213143]  ? __pfx_drm_gem_close_ioctl+0x10/0x10 [drm]
[   14.213188]  __x64_sys_ioctl+0x94/0xd0
[   14.213192]  do_syscall_64+0x82/0x190
[   14.213196]  ? do_syscall_64+0x8e/0x190
[   14.213199]  entry_SYSCALL_64_after_hwframe+0x76/0x7e
[   14.213205] RIP: 0033:0x7f1d1d0fc8db
[   14.213225] Code: 00 48 89 44 24 18 31 c0 48 8d 44 24 60 c7 04 24 10 00 00 00 48 89 44 24 08 48 8d 44 24 20 48 89 44 24 10 b8 10 00 00 00 0f 05 <89> c2 3d 00 f0 ff ff 77 1c 48 8b 44 24 18 64 48 2b 04 25 28 00 00
[   14.213227] RSP: 002b:00007ffd62d68f90 EFLAGS: 00000246 ORIG_RAX: 0000000000000010
[   14.213230] RAX: ffffffffffffffda RBX: 000055e8a8e90ec0 RCX: 00007f1d1d0fc8db
[   14.213232] RDX: 00007ffd62d69020 RSI: 0000000040086409 RDI: 0000000000000018
[   14.213233] RBP: 00007ffd62d69020 R08: 0000000000000130 R09: 00007f1d195c2564
[   14.213234] R10: 0000000001000001 R11: 0000000000000246 R12: 0000000040086409
[   14.213236] R13: 0000000000000018 R14: 00000000000001a7 R15: 0000000000000640
[   14.213239]  </TASK>
[   14.213320] WARNING: Flushing system-wide workqueues will be prohibited in near future.
[   14.213326] CPU: 7 UID: 0 PID: 1225 Comm: Xorg Tainted: P          IOE      6.12.38+deb13-amd64 #1  Debian 6.12.38-1
[   14.213330] Tainted: [P]=PROPRIETARY_MODULE, [I]=FIRMWARE_WORKAROUND, [O]=OOT_MODULE, [E]=UNSIGNED_MODULE
[   14.213331] Hardware name: LENOVO 42763KU/42763KU, BIOS 8BET66WW (1.46 ) 06/14/2018
[   14.213332] Call Trace:
[   14.213333]  <TASK>
[   14.213334]  dump_stack_lvl+0x5d/0x80
[   14.213338]  __nv_drm_gem_fence_context_free+0x5f/0xc0 [nvidia_drm]
[   14.213344]  drm_gem_handle_delete+0x90/0xd0 [drm]
[   14.213389]  ? __pfx_drm_gem_close_ioctl+0x10/0x10 [drm]
[   14.213431]  drm_ioctl_kernel+0xb0/0x100 [drm]
[   14.213474]  drm_ioctl+0x277/0x4f0 [drm]
[   14.213516]  ? __pfx_drm_gem_close_ioctl+0x10/0x10 [drm]
[   14.213560]  __x64_sys_ioctl+0x94/0xd0
[   14.213563]  do_syscall_64+0x82/0x190
[   14.213568]  ? syscall_exit_to_user_mode+0x164/0x210
[   14.213572]  ? do_syscall_64+0x8e/0x190
[   14.213576]  ? do_syscall_64+0x8e/0x190
[   14.213579]  entry_SYSCALL_64_after_hwframe+0x76/0x7e
[   14.213583] RIP: 0033:0x7f1d1d0fc8db
[   14.213588] Code: 00 48 89 44 24 18 31 c0 48 8d 44 24 60 c7 04 24 10 00 00 00 48 89 44 24 08 48 8d 44 24 20 48 89 44 24 10 b8 10 00 00 00 0f 05 <89> c2 3d 00 f0 ff ff 77 1c 48 8b 44 24 18 64 48 2b 04 25 28 00 00
[   14.213590] RSP: 002b:00007ffd62d68f90 EFLAGS: 00000246 ORIG_RAX: 0000000000000010
[   14.213592] RAX: ffffffffffffffda RBX: 000055e8a8e90ec0 RCX: 00007f1d1d0fc8db
[   14.213593] RDX: 00007ffd62d69020 RSI: 0000000040086409 RDI: 0000000000000018
[   14.213595] RBP: 00007ffd62d69020 R08: 0000000000000130 R09: 00007f1d195c2564
[   14.213596] R10: 0000000001000001 R11: 0000000000000246 R12: 0000000040086409
[   14.213597] R13: 0000000000000018 R14: 00000000000001a7 R15: 0000000000000640
[   14.213600]  </TASK>
[   15.689211] iwlwifi 0000:03:00.0: Radio type=0x1-0x2-0x0
[   15.984467] iwlwifi 0000:03:00.0: Radio type=0x1-0x2-0x0
[   16.089005] wlp3s0: authenticate with 6c:eb:b6:df:69:04 (local address=8c:70:5a:bf:eb:30)
[   16.089013] wlp3s0: send auth to 6c:eb:b6:df:69:04 (try 1/3)
[   16.095423] wlp3s0: authenticated
[   16.096696] wlp3s0: associate with 6c:eb:b6:df:69:04 (try 1/3)
[   16.100753] wlp3s0: RX AssocResp from 6c:eb:b6:df:69:04 (capab=0x1431 status=0 aid=49)
[   16.120017] wlp3s0: associated
[   16.217387] wlp3s0: Limiting TX power to 19 (19 - 0) dBm as advertised by 6c:eb:b6:df:69:04
[   36.087600] logitech-hidpp-device 0003:046D:4054.0003: HID++ 4.5 device connected.
[   55.085864] show_signal_msg: 78 callbacks suppressed
[   55.085869] ibus-x11[1526]: segfault at 0 ip 0000000000000000 sp 00007fff2e1401b8 error 14 likely on CPU 5 (core 2, socket 0)
[   55.085877] Code: Unable to access opcode bytes at 0xffffffffffffffd6.
[   55.189969] ibus-extension-[1523]: segfault at 0 ip 0000000000000000 sp 00007fff79fc0d28 error 14 likely on CPU 4 (core 2, socket 0)
[   55.189980] Code: Unable to access opcode bytes at 0xffffffffffffffd6.
[   55.190900] ibus-ui-gtk3[1522]: segfault at 0 ip 0000000000000000 sp 00007fffc0432bf8 error 14 likely on CPU 3 (core 1, socket 0)
[   55.190911] Code: Unable to access opcode bytes at 0xffffffffffffffd6.
[   55.473142] audit: type=1400 audit(1755194417.880:237): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   55.473243] audit: type=1400 audit(1755194417.880:238): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   55.473269] audit: type=1400 audit(1755194417.880:239): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   55.473578] audit: type=1400 audit(1755194417.884:240): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   55.473698] audit: type=1400 audit(1755194417.884:241): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   55.473784] audit: type=1400 audit(1755194417.884:242): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[   55.486492] audit: type=1400 audit(1755194417.896:243): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   58.757027] warning: `kdeconnectd' uses wireless extensions which will stop working for Wi-Fi 7 hardware; use nl80211
[   61.950517] kauditd_printk_skb: 134 callbacks suppressed
[   61.950530] audit: type=1400 audit(1755194424.334:378): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   61.950552] audit: type=1400 audit(1755194424.334:379): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[   61.950578] audit: type=1400 audit(1755194424.334:380): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  138.517536] audit: type=1400 audit(1755194500.889:381): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  138.517545] audit: type=1400 audit(1755194500.889:382): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  138.517600] audit: type=1400 audit(1755194500.889:383): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  141.655705] audit: type=1400 audit(1755194504.024:384): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  141.655740] audit: type=1400 audit(1755194504.024:385): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  141.655765] audit: type=1400 audit(1755194504.024:386): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  141.656021] audit: type=1400 audit(1755194504.024:387): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  141.656049] audit: type=1400 audit(1755194504.024:388): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  141.656071] audit: type=1400 audit(1755194504.024:389): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  141.748846] audit: type=1400 audit(1755194504.116:390): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.460399] kauditd_printk_skb: 17 callbacks suppressed
[  165.460405] audit: type=1400 audit(1755194527.828:408): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.460456] audit: type=1400 audit(1755194527.828:409): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.460501] audit: type=1400 audit(1755194527.828:410): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  165.460815] audit: type=1400 audit(1755194527.828:411): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.460936] audit: type=1400 audit(1755194527.828:412): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.461046] audit: type=1400 audit(1755194527.828:413): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  165.545947] audit: type=1400 audit(1755194527.916:414): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.545956] audit: type=1400 audit(1755194527.916:415): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  165.546009] audit: type=1400 audit(1755194527.916:416): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  171.618728] audit: type=1400 audit(1755194533.992:417): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  171.618857] audit: type=1400 audit(1755194533.992:418): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  171.618956] audit: type=1400 audit(1755194533.992:419): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  171.619358] audit: type=1400 audit(1755194533.992:420): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  171.619476] audit: type=1400 audit(1755194533.992:421): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  171.619560] audit: type=1400 audit(1755194533.992:422): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  171.636059] audit: type=1400 audit(1755194534.008:423): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  171.636193] audit: type=1400 audit(1755194534.008:424): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  171.636290] audit: type=1400 audit(1755194534.008:425): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  185.327321] audit: type=1400 audit(1755194547.700:426): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  185.327388] audit: type=1400 audit(1755194547.700:427): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  185.327436] audit: type=1400 audit(1755194547.700:428): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  185.327669] audit: type=1400 audit(1755194547.700:429): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  185.327724] audit: type=1400 audit(1755194547.700:430): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  185.327767] audit: type=1400 audit(1755194547.700:431): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  185.348613] audit: type=1400 audit(1755194547.720:432): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  185.348690] audit: type=1400 audit(1755194547.720:433): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  185.348748] audit: type=1400 audit(1755194547.720:434): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  223.312786] audit: type=1400 audit(1755194585.684:435): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  223.312849] audit: type=1400 audit(1755194585.684:436): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  223.312956] audit: type=1400 audit(1755194585.684:437): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  223.313477] audit: type=1400 audit(1755194585.684:438): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  223.313488] audit: type=1400 audit(1755194585.684:439): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  223.313524] audit: type=1400 audit(1755194585.684:440): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  223.329152] audit: type=1400 audit(1755194585.700:441): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  223.329232] audit: type=1400 audit(1755194585.700:442): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  223.329322] audit: type=1400 audit(1755194585.700:443): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  223.594935] audit: type=1400 audit(1755194585.968:444): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.388564] kauditd_printk_skb: 9 callbacks suppressed
[  231.388576] audit: type=1400 audit(1755194593.760:454): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.388693] audit: type=1400 audit(1755194593.760:455): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.388796] audit: type=1400 audit(1755194593.760:456): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  231.389160] audit: type=1400 audit(1755194593.760:457): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.389264] audit: type=1400 audit(1755194593.760:458): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.389354] audit: type=1400 audit(1755194593.760:459): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  231.404754] audit: type=1400 audit(1755194593.776:460): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.404779] audit: type=1400 audit(1755194593.776:461): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  231.404967] audit: type=1400 audit(1755194593.776:462): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  231.993307] audit: type=1400 audit(1755194594.364:463): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  387.372388] [drm:drm_new_set_master [drm]] *ERROR* [nvidia-drm] [GPU ID 0x00000100] Failed to grab modeset ownership
[  433.386046] kauditd_printk_skb: 17 callbacks suppressed
[  433.386052] audit: type=1400 audit(1755194795.756:481): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  433.386193] audit: type=1400 audit(1755194795.756:482): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  433.386199] audit: type=1400 audit(1755194795.756:483): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  480.324295] audit: type=1400 audit(1755194842.692:484): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  480.324328] audit: type=1400 audit(1755194842.692:485): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  480.324354] audit: type=1400 audit(1755194842.692:486): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  480.324574] audit: type=1400 audit(1755194842.692:487): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  480.324602] audit: type=1400 audit(1755194842.692:488): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  480.324623] audit: type=1400 audit(1755194842.692:489): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  480.393102] audit: type=1400 audit(1755194842.760:490): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  480.393178] audit: type=1400 audit(1755194842.760:491): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  480.393234] audit: type=1400 audit(1755194842.760:492): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  611.081390] audit: type=1400 audit(1755194973.453:493): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  611.081521] audit: type=1400 audit(1755194973.453:494): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  611.081621] audit: type=1400 audit(1755194973.453:495): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  611.081962] audit: type=1400 audit(1755194973.453:496): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  611.082034] audit: type=1400 audit(1755194973.453:497): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  611.082121] audit: type=1400 audit(1755194973.453:498): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  611.097462] audit: type=1400 audit(1755194973.469:499): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  611.097511] audit: type=1400 audit(1755194973.469:500): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  611.097718] audit: type=1400 audit(1755194973.469:501): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  611.701676] audit: type=1400 audit(1755194974.073:502): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  721.935279] kauditd_printk_skb: 2 callbacks suppressed
[  721.935283] audit: type=1400 audit(1755195084.305:505): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  721.935311] audit: type=1400 audit(1755195084.305:506): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  721.935338] audit: type=1400 audit(1755195084.305:507): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  721.935584] audit: type=1400 audit(1755195084.305:508): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  721.935613] audit: type=1400 audit(1755195084.305:509): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  721.935636] audit: type=1400 audit(1755195084.305:510): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  722.002853] audit: type=1400 audit(1755195084.373:511): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  722.002911] audit: type=1400 audit(1755195084.373:512): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/driver/nvidia/params" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
[  722.003021] audit: type=1400 audit(1755195084.373:513): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/dev/nvidia-modeset" pid=1225 comm="Xorg" requested_mask="wr" denied_mask="wr" fsuid=0 ouid=0
[  724.525140] audit: type=1400 audit(1755195086.897:514): apparmor="ALLOWED" operation="open" class="file" profile="Xorg" name="/proc/modules" pid=1225 comm="Xorg" requested_mask="r" denied_mask="r" fsuid=0 ouid=0
```