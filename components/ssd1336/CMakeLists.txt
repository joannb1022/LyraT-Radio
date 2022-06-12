# idf_component_register(SRCS "ssd1336.c"
#                     INCLUDE_DIRS "include")


set(component_srcs "ssd1336.c")

idf_component_register(SRCS "${component_srcs}"
                       PRIV_REQUIRES driver
                       INCLUDE_DIRS ".")
