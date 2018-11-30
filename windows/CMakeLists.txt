add_library(hidapi-hid hid.c)
target_link_libraries(hidapi-hid setupapi)
