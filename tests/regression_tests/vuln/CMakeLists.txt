add_test(
    NAME vuln
    WORKING_DIRECTORY "${CMAKE_CURRENT_SOURCE_DIR}"
    COMMAND ${PYTHON_EXECUTABLE} vuln.py
)
