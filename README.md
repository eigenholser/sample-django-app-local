# Sample Django App with Vagrantfile
Sample Django app with Vagrantfile for local development.

## Environment Variables

``VAGRANT_BOX_URL`` is the partial URL path to the Vagrant box location. The
Vagrantfile will set the filename of the Vagrant box. For example, if the
Vagrant box is available at the URL ``https://some.domain.com/vagrant/mybox.box``,
then ``VAGRANT_BOX_URL`` would be set like this:

    export VAGRANT_BOX_URL=https://some.domain.com/vagrant/

Your box name will be set literally in the Vagrantfile. I arranged it this way
to avoid publishing the details of my Vagrant box cache on Github.
