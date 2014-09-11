webrtc
======

team15-android-codec
====================

Webrtc environment setup and compilation.

Environment setup for linux 64-bit.

1. Download and install JDK: http://www.oracle.com/technetwork/java/javasebusiness/downloads/java-archive-downloads-javase6-419409.html#jdk-6u45-oth-JPR
2. git, svn
3. Download and install depoot-tools: http://www.chromium.org/developers/how-tos/install-depot-tools

Prerequirements for compilation:

1. checkout source code from github repository: https://github.com/samsungaccelerator/team15-android-codec

Compilation:
Run build.sh from the root of the repository with one of the follwoing arguments:

      clean      
          Build clean
          
      debug      
          Build in debug mode
          
      release    
          Build in release mode

If the build is successful, the compiled library will be located in out/`<Selected mode>` directory. 