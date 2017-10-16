set(file_name "")

set(cpp_src "${file_name}.cc")
set(cpp_exec "${file_name}.bin")
add_executable(${cpp_exec} ${cpp_src})
target_link_libraries(${cpp_exec} pthread)
