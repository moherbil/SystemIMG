# SystemIMG
Unpack Repack System.img

Perintah unpack :
Buka di linux
1.Rename system.img to system.img.ext4
2.perintah di linux : simg2img system.img.ext4 system.img
=======================================
untuk extract pakai perintah cmd
=======================================
Lihat ukuran size sebelum repack 
1. Perintah di linux : tune2fs -l system.img | grep "Block size\|Block count
2. hasil block size di kalikan dengan count
=======================================
Perintah repack System.img : 
1. perintah lewat cmd : make_ext4fs -s -l 3170938880 -a system system_new.img system/

