<<<<<<< HEAD
Cloud
-----

Work in progress Ansible Roles to create the initial installation of my private cloud

using :
	- CouchPotato
	- Headphones
	- Plex
	- Sonarr
	- Sabnzbd
	- Deluge ( WIP )
	- Transmission ( WIP )
	- Handlebar ( TBC )
	- BitTorrent Sync ( TBC )


Nginx
-----

Nginx is configured to use https and redirect all http requests to https.
Afaik, https is configured using the current best security practices,
that is, TLS 1.2 and 1.1 only with AES-GCM used as the most preferable cipher.


Sabnzbd
-------

You'll find sabnzbd at https://your_server/sabnzbd
Sabnzbd doesn't allow for configuration of a url-base/web-root, so on initial setup,
it won't redirect to the wizard properly. To fix this, just manually append the wizard path.
In other words, go here: https://your_server/sabnzbd/wizard.


Couchpotato
-----------

Couchpotato should also *just work*, find it at https://your_server/couchpotato


Headphones
-----------

Headphones should also *just work*, find it at https://your_server/headphones/home

 
Sonarr
------------

Sonarr manages all your TV shows and is located at https://your_server/sonarr


Plex
----

Downloads latest version - accessibly by going directly to https://your_server/web/index.html


Transmission ( WIP )
------------

Transmission is at https://your_server/transmission

=======
# ansible-cloud
Ansible Roles to create a private cloud - includes Nginx as a frontend, Plex, CouchPotato, Headphones, Sabnzbd, Sonarr. 
>>>>>>> 4601d92... Initial commit
