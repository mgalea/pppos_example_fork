set(src "src/libGSM.c"
                        )

idf_component_register( SRCS "${src}"
                        INCLUDE_DIRS "include"
                        REQUIRES driver lwip 
                    )