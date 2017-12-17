# viperos
##Feel the venom in your vein


Viper Device tree for the Qualcomm Xiaomi Redmi Note 4G Single SIM
- by kelvin virani




--------------------------------------##these files needed if u r making dot os##---------------------------------------------

 
 
##device tree-
git clone https://github.com/kelvinvirani/dot_android_device_xiaomi_dior.git -b viperos-n device/xiaomi/dior


##kernel tree (ashish kotnala)-
git clone https://github.com/ashishkotnala29/android_kernel_xiaomi_dior.git -b cm-14.1 kernel/xiaomi/dior


##vendor tree (ashish kotnala)-
git clone https://github.com/ashishkotnala29/proprietary_vendor_xiaomi.git -b cm-14.1 vendor/xiaomi

##proprietary_vendor_qcom_binaries (ashish kotnala)-
git clone https://github.com/ashishkotnala29/proprietary_vendor_qcom_binaries.git -b cm-14.1 vendor/qcom/binaries


##android_packages_resources_devicesettings  (lineage os)-
git clone https://github.com/LineageOS/android_packages_resources_devicesettings.git -b cm-14.1 packages/resources/devicesettings


##device_qcom_common  -  
git clone https://github.com/LineageOS/android_device_qcom_common.git -b cm-14.1 device/qcom/common

-----------------------------------------------------other things - personal - not fot you --------------------------------


repo  -  repo init -u https://github.com/Viper-Project/viper_manifest -b nougat

sync  -  repo sync -c -f -j8 --force-sync --no-clone-bundle --no-tags

. build/envsetup.sh

lunch

make otapackage -j8

