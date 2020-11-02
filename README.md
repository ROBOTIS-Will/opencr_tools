opencr_ld
=======

OpenCR DownLoader for arduino and normal firmware


=======
Compile - Mac/Linux

make

=======
Compile - Windows

1. Install Atollic TrueStudio.
2. File > New > C Project
  - Project Name : opencr_ld
  - Project type : PC C Project
  - Toolchaines : Atollic PC Tools
3. Delete src folder from the project
4. Copy & Paste opencr_tools file
5. Refresh the project files
6. Build the project


=======
Execute 

opencr_ld /dev/tty 115200 main.bin 1 




