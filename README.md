# linux-image-5.6.0-1020-oem-update-config
linux-image-5.6.0-1020 , update , gcc-5 , gui perfomance gtk3 , wayland kernel perfomance gui , old perfomance xenial portage configuration

Install

tar xvpf config-5.6.0-1020-oem.tar.xz -C / && update-initramfs -u -v && update-grub

____________________________________________________________________________________________

My os https://github.com/Griggorii/Linux_OS20.04_V3_X64_By_Griggorii.iso_ubuntu_focal_fossa-linux-image-unsigned-5.6.0-1020-oem full + kernel headers

Kernel https://github.com/Griggorii/linux-image-oem-5.6.0-1020-kernel-ubuntu-x86_64-deb-package

____________________________________________________________________________________________

Данная технология не означает что у вас должен быть вайланд , а тестируется в этой среде по скольку успехи параллельны если это работает быстро в вайланд то это и работает ещё быстрее в X11. Так что моя рекомендация делать программы в ваиланд тогда они будут работать быстрее в иксах.
