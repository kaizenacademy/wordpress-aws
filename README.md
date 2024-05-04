# Host

sudo yum install python-pip -y
sudo yum install python -y
pip install ansible
ansible --version

# Remote

sudo yum install python -y
sudo yum install python-pip -y
sudo pip3 install pymysql

# mysql
sudo mysql -u root

CREATE USER 'ansible'@'localhost' IDENTIFIED BY 'new_password';

GRANT ALL PRIVILEGES ON *.* TO 'ansible'@'localhost' WITH GRANT OPTION;

FLUSH PRIVILEGES;