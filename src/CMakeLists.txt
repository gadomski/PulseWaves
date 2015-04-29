set(src
    arithmeticdecoder.cpp
    arithmeticencoder.cpp
    arithmeticmodel.cpp
    integercompressor.cpp
    pulsedescriptor.cpp
    pulsefilter.cpp
    pulseheader.cpp
    pulsepulse.cpp
    pulsereader.cpp
    pulsereader_csd.cpp
    pulsereader_gcw.cpp
    pulsereader_lgw.cpp
    pulsereader_pls.cpp
    pulsereadermerged.cpp
    pulsereaditemcompressed_v1.cpp
    pulsereadpulse.cpp
    pulsereadwaves_compressed.cpp
    pulsereadwaves_raw.cpp
    pulsetransform.cpp
    pulseutility.cpp
    pulsevlrs.cpp
    pulsewriteitemcompressed_v1.cpp
    pulsewritepulse.cpp
    pulsewriter.cpp
    pulsewriter_pls.cpp
    pulsewriter_txt.cpp
    pulsewritewaves_compressed.cpp
    pulsewritewaves_raw.cpp
    pulsezip.cpp
    waveswaves.cpp
    )

add_library(pulsewaves ${src})
target_include_directories(pulsewaves
    PUBLIC ${PROJECT_SOURCE_DIR}/inc
    PRIVATE ${PROJECT_SOURCE_DIR}/src
    )
