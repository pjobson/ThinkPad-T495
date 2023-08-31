# lscpu info

lscpu gathers CPU architecture information from sysfs, /proc/cpuinfo and any applicable architecture-specific libraries (e.g. librtas on Powerpc). The command output can be optimized for parsing or for easy readability by humans. The information includes, for example, the number of CPUs, threads, cores, sockets, and Non-Uniform Memory Access (NUMA) nodes. There is also information about the CPU caches and cache sharing, family, model, bogoMIPS, byte order, and stepping.

`lscpu -e`

	CPU NODE SOCKET CORE L1d:L1i:L2:L3 ONLINE    MAXMHZ    MINMHZ      MHZ
	  0    0      0    0 0:0:0:0          yes 2100.0000 1400.0000 2159.539
	  1    0      0    0 0:0:0:0          yes 2100.0000 1400.0000 1400.000
	  2    0      0    1 1:1:1:0          yes 2100.0000 1400.0000 1400.000
	  3    0      0    1 1:1:1:0          yes 2100.0000 1400.0000 1400.000
	  4    0      0    2 2:2:2:0          yes 2100.0000 1400.0000 2755.230
	  5    0      0    2 2:2:2:0          yes 2100.0000 1400.0000 2100.000
	  6    0      0    3 3:3:3:0          yes 2100.0000 1400.0000 1400.000
	  7    0      0    3 3:3:3:0          yes 2100.0000 1400.0000 1400.000

`lscpu`

	Architecture:                    x86_64
	CPU op-mode(s):                  32-bit, 64-bit
	Address sizes:                   43 bits physical, 48 bits virtual
	Byte Order:                      Little Endian
	CPU(s):                          8
	On-line CPU(s) list:             0-7
	Vendor ID:                       AuthenticAMD
	Model name:                      AMD Ryzen 5 PRO 3500U w/ Radeon Vega Mobile Gfx
	CPU family:                      23
	Model:                           24
	Thread(s) per core:              2
	Core(s) per socket:              4
	Socket(s):                       1
	Stepping:                        1
	Frequency boost:                 enabled
	CPU max MHz:                     2100.0000
	CPU min MHz:                     1400.0000
	BogoMIPS:                        4192.19
	Flags:                           fpu vme de pse tsc msr pae mce cx8 apic sep mtrr pge mca cmov pat pse36 clflush mmx fxsr sse sse2 ht syscall nx mmxext fxsr_opt pdpe1gb rdtscp lm constant_tsc rep_good nopl nonstop_tsc cpuid extd_apicid aperfmperf rapl pni pclmulqdq monitor ssse3 fma cx16 sse4_1 sse4_2 movbe popcnt aes xsave avx f16c rdrand lahf_lm cmp_legacy svm extapic cr8_legacy abm sse4a misalignsse 3dnowprefetch osvw skinit wdt tce topoext perfctr_core perfctr_nb bpext perfctr_llc mwaitx cpb hw_pstate ssbd ibpb vmmcall fsgsbase bmi1 avx2 smep bmi2 rdseed adx smap clflushopt sha_ni xsaveopt xsavec xgetbv1 xsaves clzero irperf xsaveerptr arat npt lbrv svm_lock nrip_save tsc_scale vmcb_clean flushbyasid decodeassists pausefilter pfthreshold avic v_vmsave_vmload vgif overflow_recov succor smca sme sev sev_es
	Virtualization:                  AMD-V
	L1d cache:                       128 KiB (4 instances)
	L1i cache:                       256 KiB (4 instances)
	L2 cache:                        2 MiB (4 instances)
	L3 cache:                        4 MiB (1 instance)
	NUMA node(s):                    1
	NUMA node0 CPU(s):               0-7
	Vulnerability Itlb multihit:     Not affected
	Vulnerability L1tf:              Not affected
	Vulnerability Mds:               Not affected
	Vulnerability Meltdown:          Not affected
	Vulnerability Mmio stale data:   Not affected
	Vulnerability Retbleed:          Mitigation; untrained return thunk; SMT vulnerable
	Vulnerability Spec store bypass: Mitigation; Speculative Store Bypass disabled via prctl and seccomp
	Vulnerability Spectre v1:        Mitigation; usercopy/swapgs barriers and __user pointer sanitization
	Vulnerability Spectre v2:        Mitigation; Retpolines, IBPB conditional, STIBP disabled, RSB filling, PBRSB-eIBRS Not affected
	Vulnerability Srbds:             Not affected
	Vulnerability Tsx async abort:   Not affected

