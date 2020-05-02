set(COMPONENT_SRCS
    main.c
    recsrc.c
    speech_commands_action.c
    )

set(COMPONENT_ADD_INCLUDEDIRS 
    include
    )



set(COMPONENT_REQUIRES
    hardware_driver
    )

register_component()



