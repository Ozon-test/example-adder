SET(${PROJECT_NAME}_HEADERS
  gepadd.hpp
  )

IF(NOT INSTALL_PYTHON_INTERFACE_ONLY)
  INSTALL(FILES
    ${${PROJECT_NAME}_HEADERS}
    DESTINATION include/${PROJECT_NAME}
    )
ENDIF(NOT INSTALL_PYTHON_INTERFACE_ONLY)
