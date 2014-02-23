chef-nginx-php55-mysql
======================

クックブック
CentOS 6.4でのみ確認済み

QuickStart!

$ git clone git@github.com:basicinc/Cookbook-nginx-apache-php-mysql.git

$ cd clone_dir

$ vagrant box add centos64 https://github.com/2creatives/vagrant-centos/releases/download/v0.1.0/centos64-x86_64-20131030.box

$ mv Vagrantfile_default ./Vagrantfile

$ vagrant ssh-config --host host_name >> ~/.ssh/config

$ knife solo prepare host_name

$ knife solo cook host_name
