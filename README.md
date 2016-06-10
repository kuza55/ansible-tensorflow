ansible-tensorflow
=========

Installs Bazel and TensorFlow on Ubuntu

Requirements
------------

None

Role Variables
--------------

None

Dependencies
------------

jpnewman.java Installs java 8, for Bazel
kuza55.cudnn Installs CUDA & cuDNN

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
       - role: jpnewman.java
       - role: kuza55.cudnn
       - role: kuza55.ansible-tensorflow

License
-------

Apache 2.0

Author Information
------------------

N/A