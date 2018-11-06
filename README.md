# oci-automation
starter kit for automating OCI infrastructure build &amp; config

# setup steps...
1. install git and docker if necessary
2. git clone https://github.com/rdewes/oci-automation.git
3. cd ./oci-automation
3. docker build -t oci-automation .
4. docker run --interactive --tty --rm --volume "$PWD":/data oci-automation:latest 

you now have a OL7 image that has the OCI Terraform provider and Ansible modules installed & configured, along with a set of samples
