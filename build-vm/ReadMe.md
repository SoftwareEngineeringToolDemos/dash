#How to build your own Virtual Machine?

The following steps shows how you can spin up a Virtual Machine for tool <b>DASHboards</b> :

<ul>
<li>Install vagrant and virtualbox on your host machine.</li>
<li>Download the Vagrantfile from build-vm folder on your machine and save it in a folder where you want to install the VM.</li>
<li>From the host, navigate to that folder and execute the command : "vagrant up"</li>
</ul>

<h4>Note :</h4>

1. The Virtual Machine will boot up quickly and but the "vagrant up" command runs for nearly half an hour to complete as it provisions the VM for use when ran for the first time.
2. Deploys Base Vagrant Box : Ubuntu 14.04 Desktop
3. Default VM Login Credentials:
    user: vagrant
    password: vagrant

<h5>References :</h5>

A vagrant tutorial can be found [here](https://docs.vagrantup.com/v2/getting-started/index.html)<br/>
The binaries for vagrant can be found [here](https://www.vagrantup.com/downloads.html)<br/>
Vagrant tutotial by Dustin Barnes,Vagrant Tutorial


