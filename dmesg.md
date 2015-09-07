[    0.000000] Booting Linux on physical CPU 0x0
[    0.000000] Initializing cgroup subsys cpu
[    0.000000] Initializing cgroup subsys cpuacct
[    0.000000] Linux version 3.18.11+ (dc4@dc4-XPS13-9333) (gcc version 4.8.3 20140303 (prerelease) (crosstool-NG linaro-1.13.1+bzr2650 - Linaro GCC 2014.03) ) #781 PREEMPT Tue Apr 21 18:02:18 BST 2015
[    0.000000] CPU: ARMv6-compatible processor [410fb767] revision 7 (ARMv7), cr=00c5387d
[    0.000000] CPU: PIPT / VIPT nonaliasing data cache, VIPT nonaliasing instruction cache
[    0.000000] Machine model: Raspberry Pi Model B
[    0.000000] cma: Reserved 8 MiB at 0x1b800000
[    0.000000] Memory policy: Data cache writeback
[    0.000000] On node 0 totalpages: 114688
[    0.000000] free_area_init_node: node 0, pgdat c083d364, node_mem_map db474000
[    0.000000]   Normal zone: 896 pages used for memmap
[    0.000000]   Normal zone: 0 pages reserved
[    0.000000]   Normal zone: 114688 pages, LIFO batch:31
[    0.000000] pcpu-alloc: s0 r0 d32768 u32768 alloc=1*32768
[    0.000000] pcpu-alloc: [0] 0 
[    0.000000] Built 1 zonelists in Zone order, mobility grouping on.  Total pages: 113792
[    0.000000] Kernel command line: dma.dmachans=0x7f35 bcm2708_fb.fbwidth=592 bcm2708_fb.fbheight=448 bcm2708.boardrev=0xf bcm2708.serial=0x4666db9 smsc95xx.macaddr=B8:27:EB:66:6D:B9 bcm2708_fb.fbswap=1 sdhci-bcm2708.emmc_clock_freq=250000000 vc_mem.mem_base=0x1ec00000 vc_mem.mem_size=0x20000000  dwc_otg.lpm_enable=0 console=ttyAMA0,115200 console=tty1 root=/dev/mmcblk0p6 rootfstype=ext4 elevator=deadline rootwait
[    0.000000] PID hash table entries: 2048 (order: 1, 8192 bytes)
[    0.000000] Dentry cache hash table entries: 65536 (order: 6, 262144 bytes)
[    0.000000] Inode-cache hash table entries: 32768 (order: 5, 131072 bytes)
[    0.000000] Memory: 437276K/458752K available (5881K kernel code, 348K rwdata, 1868K rodata, 336K init, 733K bss, 21476K reserved)
[    0.000000] Virtual kernel memory layout:
[    0.000000]     vector  : 0xffff0000 - 0xffff1000   (   4 kB)
[    0.000000]     fixmap  : 0xffc00000 - 0xffe00000   (2048 kB)
[    0.000000]     vmalloc : 0xdc800000 - 0xff000000   ( 552 MB)
[    0.000000]     lowmem  : 0xc0000000 - 0xdc000000   ( 448 MB)
[    0.000000]     modules : 0xbf000000 - 0xc0000000   (  16 MB)
[    0.000000]       .text : 0xc0008000 - 0xc07997a0   (7750 kB)
[    0.000000]       .init : 0xc079a000 - 0xc07ee000   ( 336 kB)
[    0.000000]       .data : 0xc07ee000 - 0xc084513c   ( 349 kB)
[    0.000000]        .bss : 0xc084513c - 0xc08fc8a8   ( 734 kB)
[    0.000000] SLUB: HWalign=32, Order=0-3, MinObjects=0, CPUs=1, Nodes=1
[    0.000000] Preemptible hierarchical RCU implementation.
[    0.000000] NR_IRQS:522
[    0.000026] sched_clock: 32 bits at 1000kHz, resolution 1000ns, wraps every 2147483648000ns
[    0.000073] Switching to timer-based delay loop, resolution 1000ns
[    0.000355] Console: colour dummy device 80x30
[    0.001417] console [tty1] enabled
[    0.001462] Calibrating delay loop (skipped), value calculated using timer frequency.. 2.00 BogoMIPS (lpj=10000)
[    0.001536] pid_max: default: 32768 minimum: 301
[    0.001915] Mount-cache hash table entries: 1024 (order: 0, 4096 bytes)
[    0.001980] Mountpoint-cache hash table entries: 1024 (order: 0, 4096 bytes)
[    0.002986] Initializing cgroup subsys memory
[    0.003079] Initializing cgroup subsys devices
[    0.003138] Initializing cgroup subsys freezer
[    0.003192] Initializing cgroup subsys net_cls
[    0.003241] Initializing cgroup subsys blkio
[    0.003362] CPU: Testing write buffer coherency: ok
[    0.003474] ftrace: allocating 19232 entries in 57 pages
[    0.108262] Setting up static identity map for 0x553398 - 0x5533d0
[    0.111106] devtmpfs: initialized
[    0.128637] VFP support v0.3: implementor 41 architecture 1 part 20 variant b rev 5
[    0.131657] pinctrl core: initialized pinctrl subsystem
[    0.134270] NET: Registered protocol family 16
[    0.139762] DMA: preallocated 4096 KiB pool for atomic coherent allocations
[    0.141199] bcm2708.uart_clock = 3000000
[    0.144125] No ATAGs?
[    0.144190] hw-breakpoint: found 6 breakpoint and 1 watchpoint registers.
[    0.144253] hw-breakpoint: maximum watchpoint size is 4 bytes.
[    0.144317] mailbox: Broadcom VideoCore Mailbox driver
[    0.144479] bcm2708_vcio: mailbox at f200b880
[    0.144936] bcm_power: Broadcom power driver
[    0.144994] bcm_power_open() -> 0
[    0.145025] bcm_power_request(0, 8)
[    0.645733] bcm_mailbox_read -> 00000080, 0
[    0.645779] bcm_power_request -> 0
[    0.645981] Serial: AMBA PL011 UART driver
[    0.646218] dev:f1: ttyAMA0 at MMIO 0x20201000 (irq = 83, base_baud = 0) is a PL011 rev3
[    1.027639] console [ttyAMA0] enabled
[    1.090902] SCSI subsystem initialized
[    1.095033] usbcore: registered new interface driver usbfs
[    1.100824] usbcore: registered new interface driver hub
[    1.106331] usbcore: registered new device driver usb
[    1.113482] Switched to clocksource stc
[    1.145730] FS-Cache: Loaded
[    1.149048] CacheFiles: Loaded
[    1.168323] NET: Registered protocol family 2
[    1.174295] TCP established hash table entries: 4096 (order: 2, 16384 bytes)
[    1.181476] TCP bind hash table entries: 4096 (order: 2, 16384 bytes)
[    1.188251] TCP: Hash tables configured (established 4096 bind 4096)
[    1.194773] TCP: reno registered
[    1.198043] UDP hash table entries: 256 (order: 0, 4096 bytes)
[    1.203969] UDP-Lite hash table entries: 256 (order: 0, 4096 bytes)
[    1.210626] NET: Registered protocol family 1
[    1.215707] RPC: Registered named UNIX socket transport module.
[    1.221677] RPC: Registered udp transport module.
[    1.226513] RPC: Registered tcp transport module.
[    1.231245] RPC: Registered tcp NFSv4.1 backchannel transport module.
[    1.238855] hw perfevents: enabled with armv6_1176 PMU driver, 3 counters available
[    1.246990] bcm2708_dma: DMA manager at f2007000
[    1.251836] vc-mem: phys_addr:0x00000000 mem_base=0x1ec00000 mem_size:0x20000000(512 MiB)
[    1.261563] futex hash table entries: 256 (order: -1, 3072 bytes)
[    1.268059] audit: initializing netlink subsys (disabled)
[    1.273649] audit: type=2000 audit(1.040:1): initialized
[    1.294379] VFS: Disk quotas dquot_6.5.2
[    1.298712] Dquot-cache hash table entries: 1024 (order 0, 4096 bytes)
[    1.308178] FS-Cache: Netfs 'nfs' registered for caching
[    1.315364] NFS: Registering the id_resolver key type
[    1.320575] Key type id_resolver registered
[    1.324921] Key type id_legacy registered
[    1.330305] msgmni has been set to 870
[    1.336717] Block layer SCSI generic (bsg) driver version 0.4 loaded (major 252)
[    1.344733] io scheduler noop registered
[    1.348717] io scheduler deadline registered (default)
[    1.354460] io scheduler cfq registered
[    1.360830] BCM2708FB: allocated DMA memory 5bc00000
[    1.366137] BCM2708FB: allocated DMA channel 0 @ f2007000
[    1.376644] Console: switching to colour frame buffer device 74x28
[    1.388546] bcm2708-dmaengine bcm2708-dmaengine: Load BCM2835 DMA engine driver
[    1.399972] uart-pl011 dev:f1: no DMA platform data
[    1.407564] vc-cma: Videocore CMA driver
[    1.413300] vc-cma: vc_cma_base      = 0x00000000
[    1.419827] vc-cma: vc_cma_size      = 0x00000000 (0 MiB)
[    1.427003] vc-cma: vc_cma_initial   = 0x00000000 (0 MiB)
[    1.447132] brd: module loaded
[    1.458791] loop: module loaded
[    1.464172] vchiq: vchiq_init_state: slot_zero = 0xdb800000, is_master = 0
[    1.475159] Loading iSCSI transport class v2.0-870.
[    1.483368] usbcore: registered new interface driver smsc95xx
[    1.491143] dwc_otg: version 3.00a 10-AUG-2012 (platform bus)
[    1.698913] Core Release: 2.80a
[    1.703862] Setting default values for core params
[    1.710310] Finished setting default values for core params
[    1.917703] Using Buffer DMA mode
[    1.922683] Periodic Transfer Interrupt Enhancement - disabled
[    1.930237] Multiprocessor Interrupt Enhancement - disabled
[    1.937548] OTG VER PARAM: 0, OTG VER FLAG: 0
[    1.943660] Dedicated Tx FIFOs mode
[    1.949255] WARN::dwc_otg_hcd_init:1047: FIQ DMA bounce buffers: virt = 0xdbc14000 dma = 0x5bc14000 len=9024
[    1.962535] FIQ FSM acceleration enabled for :
[    1.962535] Non-periodic Split Transactions
[    1.962535] Periodic Split Transactions
[    1.962535] High-Speed Isochronous Endpoints
[    1.985847] dwc_otg: Microframe scheduler enabled
[    1.985961] WARN::hcd_init_fiq:412: FIQ on core 0 at 0xc03fad3c
[    1.993661] WARN::hcd_init_fiq:413: FIQ ASM at 0xc03fb014 length 36
[    2.001660] WARN::hcd_init_fiq:438: MPHI regs_base at 0xdc806000
[    2.009492] dwc_otg bcm2708_usb: DWC OTG Controller
[    2.016216] dwc_otg bcm2708_usb: new USB bus registered, assigned bus number 1
[    2.026883] dwc_otg bcm2708_usb: irq 32, io mem 0x00000000
[    2.034200] Init: Port Power? op_state=1
[    2.039841] Init: Power Port (0)
[    2.045175] usb usb1: New USB device found, idVendor=1d6b, idProduct=0002
[    2.055415] usb usb1: New USB device strings: Mfr=3, Product=2, SerialNumber=1
[    2.066157] usb usb1: Product: DWC OTG Controller
[    2.072648] usb usb1: Manufacturer: Linux 3.18.11+ dwc_otg_hcd
[    2.080309] usb usb1: SerialNumber: bcm2708_usb
[    2.087702] hub 1-0:1.0: USB hub found
[    2.093365] hub 1-0:1.0: 1 port detected
[    2.099711] dwc_otg: FIQ enabled
[    2.099735] dwc_otg: NAK holdoff enabled
[    2.099748] dwc_otg: FIQ split-transaction FSM enabled
[    2.099819] Module dwc_common_port init
[    2.100404] usbcore: registered new interface driver usb-storage
[    2.108875] mousedev: PS/2 mouse device common for all mice
[    2.117250] bcm2835-cpufreq: min=700000 max=700000
[    2.124401] sdhci: Secure Digital Host Controller Interface driver
[    2.132430] sdhci: Copyright(c) Pierre Ossman
[    2.138974] DMA channels allocated for the MMC driver
[    2.183650] Load BCM2835 MMC driver
[    2.191222] sdhci-pltfm: SDHCI platform and OF driver helper
[    2.204128] ledtrig-cpu: registered to indicate activity on CPUs
[    2.214450] hidraw: raw HID events driver (C) Jiri Kosina
[    2.223245] usbcore: registered new interface driver usbhid
[    2.232829] usbhid: USB HID core driver
[    2.242118] TCP: cubic registered
[    2.247459] Initializing XFRM netlink socket
[    2.254833] NET: Registered protocol family 17
[    2.263436] Key type dns_resolver registered
[    2.271432] registered taskstats version 1
[    2.277643] vc-sm: Videocore shared memory driver
[    2.284195] [vc_sm_connected_init]: start
[    2.291136] [vc_sm_connected_init]: end - returning 0
[    2.298304] Indeed it is in host mode hprt0 = 00021501
[    2.311668] mmc0: host does not support reading read-only switch, assuming write-enable
[    2.324246] Waiting for root device /dev/mmcblk0p6...
[    2.346676] mmc0: new high speed SDHC card at address e624
[    2.364240] mmcblk0: mmc0:e624 SU08G 7.40 GiB 
[    2.386366]  mmcblk0: p1 p2 < p5 p6 > p3
[    2.448996] EXT4-fs (mmcblk0p6): mounted filesystem with ordered data mode. Opts: (null)
[    2.460818] VFS: Mounted root (ext4 filesystem) readonly on device 179:6.
[    2.482666] devtmpfs: mounted
[    2.488647] Freeing unused kernel memory: 336K (c079a000 - c07ee000)
[    2.523792] usb 1-1: new high-speed USB device number 2 using dwc_otg
[    2.533777] Indeed it is in host mode hprt0 = 00001101
[    2.744070] usb 1-1: New USB device found, idVendor=0424, idProduct=9512
[    2.756139] usb 1-1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    2.768779] hub 1-1:1.0: USB hub found
[    2.777003] hub 1-1:1.0: 3 ports detected
[    3.063861] usb 1-1.1: new high-speed USB device number 3 using dwc_otg
[    3.174176] usb 1-1.1: New USB device found, idVendor=0424, idProduct=ec00
[    3.193394] usb 1-1.1: New USB device strings: Mfr=0, Product=0, SerialNumber=0
[    3.212037] smsc95xx v1.0.4
[    3.293223] smsc95xx 1-1.1:1.0 eth0: register 'smsc95xx' at usb-bcm2708_usb-1.1, smsc95xx USB 2.0 Ethernet, b8:27:eb:66:6d:b9
[    4.186060] udevd[156]: starting version 175
[   10.497261] EXT4-fs (mmcblk0p6): re-mounted. Opts: (null)
[   10.628047] random: nonblocking pool is initialized
[   10.954731] EXT4-fs (mmcblk0p6): re-mounted. Opts: (null)
[   21.704384] smsc95xx 1-1.1:1.0 eth0: hardware isn't capable of remote wakeup
[   23.100549] smsc95xx 1-1.1:1.0 eth0: link up, 100Mbps, full-duplex, lpa 0x4DE1
[   26.873342] cfg80211: Calling CRDA to update world regulatory domain
[   38.867129] Adding 102396k swap on /var/swap.  Priority:-1 extents:1 across:102396k SSFS
[127859.508084] nr_pdflush_threads exported in /proc is scheduled for removal
