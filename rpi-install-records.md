1.	uninstalled alsa and its dependencies
2.	updated pulseaudio and ran pac-md set-default-sink (-source) to bluetooth speaker (USB jabra audio mic)
3.	Follow google assistant service
4.	Follow its 'Next Steps' to use custom actions/traits
5.	installed mps-youtube
6.	To fix dislike_count error in mpsyt,
pip uninstall -y pafy
pip install git+https://github.com/Cupcakus/pafy
7.	to get default player: sudo apt-get install mplayer2
8.	npm i -g @assistant/gactions and then chmod +x /usr/local/bin/gactions
to do this:
sudo chown -R pi:pi /usr/local/bin
sudo chown -R pi:pi /usr/local/lib
9.	



Mouting windows' shared folders on rpi:
1.	sudo apt-get  install smbclient
2.	smbclient -U <username> -L <ipADDR>
3.	sudo chown -R pi:pi /mnt
4.	sudo mkdir -p /mnt/sharan_pc
5.	sudo mount -t cifs //ipaddr/shared_folder /mnt/sharan_pc
6.	For access with login creds, user -o username= in above command after cifs
