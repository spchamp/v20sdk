cmake_minimum_required(VERSION 3.20)
project(oanda_v20_rest_api_cpp VERSION 0.1.0 LANGUAGES CXX) # x-release-please-version

option(SCALAR_SDK_BUILD_TESTS "Build generated SDK smoke tests" OFF)

add_library(oanda_v20_rest_api_cpp)
add_library(oanda_v20_rest_api_cpp::oanda_v20_rest_api_cpp ALIAS oanda_v20_rest_api_cpp)

target_sources(oanda_v20_rest_api_cpp
  PRIVATE
    src/client.cpp
    src/resources/instruments.cpp
    src/resources/price.cpp
    src/resources/accounts.cpp
    src/resources/positions.cpp
    src/resources/trades.cpp
    src/resources/instruments.cpp
    src/resources/transactions.cpp
    src/resources/pricing.cpp
    src/resources/orders.cpp
    src/resources/users.cpp
    src/resources/pricing.cpp
)

target_include_directories(oanda_v20_rest_api_cpp
  PUBLIC
    $<BUILD_INTERFACE:${CMAKE_CURRENT_SOURCE_DIR}/include>
    $<INSTALL_INTERFACE:include>
)

target_compile_features(oanda_v20_rest_api_cpp PUBLIC cxx_std_20)

if(SCALAR_SDK_BUILD_TESTS)
  enable_testing()
  add_executable(scalar_sdk_smoke tests/smoke.cpp)
  target_link_libraries(scalar_sdk_smoke PRIVATE oanda_v20_rest_api_cpp)
  add_test(NAME scalar_sdk_smoke COMMAND scalar_sdk_smoke)
endif()
