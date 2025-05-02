# CMakeFiles.txt inside "SparkFun_u-blox_GNSS" folder
cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "src/u-blox_GNSS.cpp" "src/sfe_bus.cpp"
                    INCLUDE_DIRS "src/."
                    REQUIRES "arduino" # Library requires Arduino
                    )

project(SparkFun_u-blox_GNSS_v3)