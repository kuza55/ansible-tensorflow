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
This role depends on these two roles, but they're automatically installed if you install this from galaxy:

jpnewman.java Installs java 8, for Bazel
kuza55.cudnn Installs CUDA & cuDNN

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
       - role: kuza55.tensorflow

License
-------

Apache 2.0

Author Information
------------------

N/A