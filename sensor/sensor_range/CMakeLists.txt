add_library(sensor_range
  rangereading.cpp
  rangesensor.cpp
)
target_link_libraries(sensor_range
  sensor_base
)
