# dot_android_device_xiaomi_dior
Device tree for the Qualcomm Xiaomi Redmi Note 4G Single SIM
- by kelvin virani =+




--------------------------------------these files needed if u r making dot os---------------------------------------------

 
 
device tree-
git clone https://github.com/kelvinvirani/dot_android_device_xiaomi_dior.git -b cm-14.1 device/xiaomi/dior


kernel tree (ashish kotnala)-
git clone https://github.com/ashishkotnala29/android_kernel_xiaomi_dior.git -b cm-14.1 kernel/xiaomi/dior


vendor tree (ashish kotnala)-
git clone https://github.com/ashishkotnala29/proprietary_vendor_xiaomi.git -b cm-14.1 vendor/xiaomi

proprietary_vendor_qcom_binaries (ashish kotnala)-
git clone https://github.com/ashishkotnala29/proprietary_vendor_qcom_binaries.git -b cm-14.1 vendor/qcom/binaries


android_packages_resources_devicesettings  (lineage os)-
git clone https://github.com/LineageOS/android_packages_resources_devicesettings.git -b cm-14.1 packages/resources/devicesettings


device_qcom_common
git clone https://github.com/LineageOS/android_device_qcom_common.git -b cm-14.1 device/qcom/commmon

-----------------------------------------------------other things - personal - not fot you --------------------------------

{}{dot.mk}{} ===  DOT_OFFICIAL := true   


sourceforge
sftp kelvinvirani@frs.sourceforge.net
cd /home/frs/project/dotos-ota/dior
Put DOT*.zip

. build/envsetup.sh  ,  breakfast dior or lunch dot_dior-userdebug  ,  brunch dior
 
Dot OTA-
https://github.com/DotOS/services_apps_ota


