if(${CONFIG_ADSUM_NETWORKS_SDK})
    zephyr_library()
    zephyr_library_sources(adsum_models/src/adsum_models.c)
    zephyr_include_directories(adsum_models/include )
    zephyr_include_directories(adsum_lib/include)
endif()

