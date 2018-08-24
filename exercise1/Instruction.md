# Exercise 1
Running Ansible on virtualenv

### Install Python Package Manager pip
You could skip this one if you already had pip.
```sh
python --version
[sudo] easy_install pip
pip --version
```

### Virtualenv Installation and Run python inside Python Virtaul Environment

```sh
[sudo] pip install virtualenv
virtualenv venv -p /usr/bin/python
source venv/bin/activate
```

```sh
which python
```
You should see your python is running in Virtaul environment, which seperate from /usr/bin/python



### Install Ansible
```sh
pip install ansible
ansible --version
```
