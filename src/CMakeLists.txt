add_library(${PROJECT_NAME} SHARED
        frame.cc
        mappoint.cc
        map.cc
        camera.cc
        config.cc
        )

target_link_libraries(${PROJECT_NAME}
        ${THIRD_PARTY_LIBS}
        )