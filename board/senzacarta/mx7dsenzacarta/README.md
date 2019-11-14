# senzacarta_uboot_v2019_07
mx7d/dl/s/spl senzacarta u-boot v2019.07

# Download Repository
	git clone https://github.com/en-vikrant/senzacarta-uboot-v2019.07.git
	cd senzacarta-uboot-v2019.07

# Install cross compiler
	apt-get install gcc-arm-linux-gnueabihf

# Setup cross compiler
	export CROSS_COMPILE=arm-linux-gnueabihf-
	export ARCH=arm

# Build
	make distclean
	make mx7dsenzacarta_config
	make
	