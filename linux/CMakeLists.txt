add_library(hidapi-hidraw hid.c)
target_link_libraries(hidapi-hidraw udev)
