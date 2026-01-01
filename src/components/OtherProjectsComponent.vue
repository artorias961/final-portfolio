<template>
  <section
    class="isolate overflow-hidden bg-[#030303] pt-16 pb-0 mb-0 relative"
    id="other-projects"
  >
    <div class="relative mx-auto max-w-7xl pt-0 px-6 lg:px-8">
      <!-- Heading -->
      <div class="relative px-4 md:px-14" ref="imageContainer">
        <div class="flex items-center mb-8">
          <p
            class="font-inter text-[25px] md:text-[45px] font-semibold text-[#EBEBEA] text-center md:text-left"
          >
            all my other projects
          </p>
        </div>
      </div>

      <!-- Bento Grid Layout -->
      <div class="relative px-4 md:px-14">



        <!-- First Row -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-4">
          <!-- Left box - double height -->
          <div
            class="col-span-1 md:col-span-2 md:row-span-2 relative rounded-md overflow-hidden group"
          >
            <img src="/mips32.png" class="w-full h-full object-cover" alt="Multi Cycle MIPS32" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-2xl font-bold mb-2">Multi Cycle MIPS32</h3>
                <p class="mb-4">
                  This repository implements a complete multi-cycle MIPS32 processor in Verilog, designed for FPGA synthesis with Intel Quartus and verified through simulation as an educational computer architecture project
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/Multi-Cycle-MIPS32"
                    class="px-4 py-2 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors"
                    >GitHub</a
                  >
                  
                </div>
              </div>
            </div>
          </div>

          <!-- Right top box -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img
              src="/Websocket-REST-API-using-Python.png"
              class="w-full h-full object-cover"
              alt="Websocket REST API using Python"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">Websocket REST API using Python</h3>
                <p class="mb-4">
                  My Websocket project! The code you can explore here combines real-time WebSocket communication with classic REST API patterns in Python 🐍
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/Websocket-REST-API-using-Python"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                </div>
              </div>
            </div>
          </div>

          <!-- Right bottom box -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/dqn_snake_model.png" class="w-full h-full object-cover" alt="Deep Neural Network SnakeIO Game" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">Deep Neural Network SnakeIO Game</h3>
                <p class="mb-4">
                My DQN Snake agent! A Neural Networks course final where I trained a model to play Snake using Python                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/deep-learning-neural-network-SnakeIO-Game"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>






        <!-- Second Row -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mb-4">
          <!-- Left top box -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/mechanical_keyboard.png" class="w-full h-full object-cover" alt="Mechanical Keyboards" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">Mechanical Keyboards</h3>
                <p class="mb-4">
                      This repository contains the design and development of custom mechanical keyboard PCBs using ESP32 and ATMEGA32A-P
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/Mechanical-Keyboards"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                </div>
              </div>
            </div>
          </div>

          <!-- Left bottom box -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img
              src="/opencv_retro_filter.png"
              class="w-full h-full object-cover"
              alt="OpenCV Retro Filter"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">OpenCV Retro Filter</h3>
                <p class="mb-4">A C++ and Python computer vision project that recreates a Game Boy Advance–style visual aesthetic from modern images.</p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/OpenCV-Retro-Filter"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                </div>
              </div>
            </div>
          </div>

          <!-- Right box - double height -->
          <div
            class="col-span-1 md:col-span-1 md:row-span-2 relative rounded-md overflow-hidden group"
          >
            <img
              src="/3D_Medical_Reconstruction_project.png"
              class="w-full h-full object-cover"
              alt="3D Geometry Recontruction"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-2xl font-bold mb-2">3D Geometry Recontruction</h3>
                <p class="mb-4">
                  My senior design project used numerical and computer vision tools to analyze pelvic MRI scans and 
                  construct 3D models of the bladder, vagina, and rectum. 
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/3D-Geometry-Recontruction-of-Medical-Image.git"
                    class="px-4 py-2 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors"
                    >GitHub</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>






        <!-- Third Row -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-4 mt-4">
          <!-- Project One -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/network-visualizer.png" class="w-full h-full object-cover" alt="Network Visualizer" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6">
                <h3 class="text-xl font-bold mb-2">Network Visualizer</h3>
                <p class="mb-4">
                  Network Visualizer is a system that passively captures local network traffic using Scapy, exposes processed connection data through a FastAPI backend, and presents device-to-device interactions.
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/Network-Visualizer"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                  
                </div>
              </div>
            </div>
          </div>

          <!-- Project Two -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/smart_program_VR_AR_XR_tech.png" class="w-full h-full object-cover" alt="VR/AR/XR for Learning Space" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6">
                <h3 class="text-xl font-bold mb-2">VR/AR/XR for Learning Space</h3>
                <p class="mb-4">
                  A Unity-based VR/AR/XR virtual learning space developed during Summer 2024 that explores immersive education through interactive environments.
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/Smart-Program-VR-AR-XR-Tech-for-Virtual-Learning-Space-Summer-2024"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                  
                </div>
              </div>
            </div>
          </div>

          <!-- Project Three -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/Heated_Sonicator.png" class="w-full h-full object-cover" alt="Heated-Sonicator" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6">
                <h3 class="text-xl font-bold mb-2">Heated-Sonicator </h3>
                <p class="mb-4">
                  This repository documents the retrofit of a heated ultrasonic sonicator by replacing its failed controller CCA with an ESP32-based control system.
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/Heated-Sonicator"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                  
                </div>
              </div>
            </div>
          </div>
        </div>




        





        

          <!-- Fourth Row -->
          <div class="grid grid-cols-1 md:grid-cols-3 gap-4">


          <!-- Portfolio One -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/portfolio_one.png" class="w-full h-full object-cover" alt="First Portfolio" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">My First Portfolio</h3>
                <p class="mb-4">
                  This is my first portfolio, built using HTML, CSS, JavaScript, and SCSS. I’m proud of 
                  this projectit took approximately 1.6 years to complete and marked the beginning of my 
                  web development journey. 
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/artorias961.github.io"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                  <a
                    href="https://artorias961.github.io"
                    class="px-3 py-1 bg-gray-600 rounded-md hover:bg-gray-700 transition-colors text-sm"
                    >Website</a
                  >
                </div>
              </div>
            </div>
          </div>


          <!-- Portfolio Two -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img
              src="/portfolio_two.png"
              class="w-full h-full object-cover"
              alt="Second Portfolio"
            />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">My Second Portfolio</h3>
                <p class="mb-4">
                  This is my second portfolio using React and Vercel!
                </p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/portfolio"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                  <a
                    href="https://christopher-morales.vercel.app/"
                    class="px-3 py-1 bg-gray-600 rounded-md hover:bg-gray-700 transition-colors text-sm"
                    >Website</a
                  >
                </div>
              </div>
            </div>
          </div>
          

          <!-- Portfolio Finale -->
          <div class="col-span-1 relative rounded-md overflow-hidden group">
            <img src="/portfolio_finale.png" class="w-full h-full object-cover" alt="Third Portfolio" />
            <div
              class="absolute inset-0 bg-black bg-opacity-0 group-hover:bg-opacity-70 transition-all duration-300 flex items-center justify-center"
            >
              <div
                class="opacity-0 group-hover:opacity-100 transition-opacity duration-300 text-white p-6"
              >
                <h3 class="text-xl font-bold mb-2">Christopher's Portfolio</h3>
                <p class="mb-4">My portfolio website! The page you are currently on :)</p>
                <div class="flex space-x-3">
                  <a
                    href="https://github.com/artorias961/main-portfolio"
                    class="px-3 py-1 bg-blue-600 rounded-md hover:bg-blue-700 transition-colors text-sm"
                    >GitHub</a
                  >
                  <a
                    href="https://main--jyotsnav.netlify.app/"
                    class="px-3 py-1 bg-gray-600 rounded-md hover:bg-gray-700 transition-colors text-sm"
                    >Website</a
                  >
                </div>
              </div>
            </div>
          </div>
        </div>








        <!-- END OF BENTO BOX-->
      </div>
    </div>














       


    <!-- Second wave image at bottom of section -->
    <div class="wave-bottom">
      <img
        src="/third wave.png"
        alt="Wave Background"
        class="w-full h-auto object-bottom object-cover"
        style="display: block; margin-bottom: -2px; vertical-align: bottom;"
      />
    </div>
  </section>
</template>

<script setup>
// Component logic can be added here if needed
</script>
