# cmake_examples_for_cortex_from_github_projects
Good cmake examples to build cortex firmware, from other github projects.


  - candleLight:
      -  https://github.com/candle-usb/candleLight_fw/blob/master/CMakeLists.txt
      -  https://github.com/candle-usb/candleLight_fw/blob/master/cmake/gcc-arm-none-eabi-8-2019-q3-update.cmake  
      -  cmake -B output_candlelight -G "Eclipse CDT4 - Ninja" candleLight_fw -DCMAKE_C_COMPILER=arm-none-eabi-gcc -DCMAKE_C_COMPILER_WORKS=TRUE -DCMAKE_CXX_COMPILER_WORKS=TRUE -DCMAKE_SYSTEM_NAME=Generic
  - StateOS: https://github.com/stateos/StateOS/blob/main/CMakeLists.txt  
