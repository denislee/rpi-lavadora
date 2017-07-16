
cp daemon.py /etc/init.d/
cp lavadora /etc/init.d/
ln -s /etc/init.d/lavadora S95lavadora
sudo systemctl enable rc.local.service

apt-get remove insserv


