Moved to [redhat-openstack](https://github.com/redhat-openstack)

Please adjust local repos like:

    git remote rename fedora-openstack redhat-openstack
    sed -i 's/fedora-openstack/redhat-openstack/' .git/config
    git fetch --all # To verify
