set(DATA_FILES 
    "CentOS_7_(MySQL_Package).xml"
    "Fedora_Linux_(MySQL_Package).xml"
    "Fedora_Linux_(Vendor_Package).xml"
    "Fedora_Linux_24_(Vendor_Package).xml"
    "Fedora_Linux_25_(Vendor_Package).xml"
    "FreeBSD_(MySQL_Package).xml"
    "Generic_Linux_(MySQL_tar_package).xml"
    "Linux_(Custom).xml"
    "MacOS_X_(MySQL_Package).xml"
    "OpenSolaris_(MySQL_Package).xml"
    "RHEL_(MySQL_Package).xml"
    "RHEL_7_(MySQL_Package).xml"
    "Oracle_Linux_6_(MySQL_Package).xml"
    "Oracle_Linux_7_(MySQL_Package).xml"
    "SLES_(MySQL_Package).xml"
    "Ubuntu_Linux_(MySQL_Package).xml"
    "Ubuntu_Linux_(Vendor_Package).xml"
    "Ubuntu_Linux_(sysvinit,_MySQL_Package).xml"
    "Ubuntu_Linux_(sysvinit,_Vendor_Package).xml"
    "Windows_(MySQL_5.5_Installer_Package).xml"
    "Windows_(MySQL_5.6_Installer_Package).xml"
    "Windows_(MySQL_5.7_Installer_Package).xml"
    "Windows_(MySQL_8.0_Installer_Package).xml"
    "Windows_x64_(MySQL_x86_zip_Package).xml"
    "MySQL_Sandbox_Linux(MySQL_tar_package).xml"
    "MySQL_Sandbox_MacOS(MySQL_tar_package).xml"
)

install(FILES ${DATA_FILES} DESTINATION ${WB_PACKAGE_SHARED_DIR}/mysql.profiles)
