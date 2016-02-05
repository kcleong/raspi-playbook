

http://docs.ansible.com/ansible/intro_installation.html

cat /etc/ansible/hosts
raspberrypi.lan
raspberrypi2.lan

virtualenv --python=`which python3` .
pip install -r requirements.txt

ansible all -m ping


based on: https://github.com/dstinebaugh/server_pi
