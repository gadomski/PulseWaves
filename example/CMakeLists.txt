set(src
    exampleLIB.cpp
    )

add_executable(pulsewaves-executable ${src})
target_link_libraries(pulsewaves-executable pulsewaves)
set_target_properties(pulsewaves-executable PROPERTIES
    OUTPUT_NAME pulsewaves
    )
