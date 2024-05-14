My Plex


sur source
sudo service plexmediaserver stop
sudo tar --exclude='./Cache' -cvf /home/myadmin/plex.tar /var/lib/plexmediaserver/Library/Application\ Support/Plex\ Media\ Server

transfert sur destination
sudo service plexmediaserver stop

sudo tar -xvf plex.tar -C /var/lib/plexmediaserver/Library/Application\ Support/Plex\ Media\ Server
