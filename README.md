	<System Infomation>

	CPU : Intel Core 2 Quad Q9550 (@3.4GHz)
 	M/B : Gigabyte EP45-UD3R (rev. 1.1)
	GPU : Radeon RX560 OC 4G (rev. 2.0)
 	RAM : hynix 2GB DDR2 800Mhz x 4
	PCIe : Fresco FL1100 4x USB 3.0 PCI Express Card
 	Model identifier : iMacPro 1,1 (2017)
	OS : macOS Sonoma 14.7.4
 	OpenCore : 1.0.4
	Opencore Legacy Patcher : 2.2.0  
  
	<config.plist>
 
 	boot-args alcid=1 -nehalem_error_disable spin_wait_for_gpu=1 batman-nosmc=1 -no_compat_check -crypt_force_avx swd_panic=1
