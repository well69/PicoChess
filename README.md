# PicoChess
looking to build a Physical chessboard with the following features:

  Bluetooth connection to laptop for use with arena/fritz/etc. (hm-10 connected to arduino to emulate keyboard)
  
  Email games in pgn after completion (picochess does this already via settings or even easier with mailgun)
  
  Leds to indicate move possibilities/moves of virtual opponents (also known as a 'training mode')
  
  Built in Clocks that can be adjusted via physical button or via the web server
  
  Battery Powered (with always on option if plugged in) 
  
  Easy to configure wifi (using turnkey wifi - working great)
  
  No computer necessary to play against engines/ record human v human games
  
  similar to this: https://www.hackster.io/lpalcu/foldable-electronic-chess-board-fbe264


# Make wifi hotspot for easy wifi settings configuration: https://github.com/schollz/raspberry-pi-turnkey

# Script to update Pi https://blog.robseder.com/2015/09/29/scripts-to-update-the-raspberry-pi-and-debian-based-linux-distros/
  wget https://gist.githubusercontent.com/RobSeder/24af1cd7c195a54fe8b0/raw/fd06d9241965de54a6ad44a833a93226eabfcd69/update.sh && chmod +x ./update.sh
  ./update.sh
 
 # Lipo Battery Config https://github.com/craic/pi_power
