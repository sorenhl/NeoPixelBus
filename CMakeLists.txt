set(COMPONENT_SRCDIRS
    "src"
    "src/internal"
    "src/internal/animations"
    "src/internal/buffers"
    "src/internal/colors"
    "src/internal/features"
    "src/internal/methods"
    "src/internal/topologies"
)

set(COMPONENT_ADD_INCLUDEDIRS
    "src"
)

set(COMPONENT_REQUIRES
    "arduino-esp32"
)

register_component()
