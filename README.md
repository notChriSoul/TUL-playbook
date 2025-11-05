Ansible source code OS family dictionary
https://github.com/ansible/ansible/blob/37ae2435878b7dd76b812328878be620a93a30c9/lib/ansible/module_utils/facts.py#L267


        OS_FAMILY = dict(
            RedHat = 'RedHat', Fedora = 'RedHat', CentOS = 'RedHat', Scientific = 'RedHat',
            SLC = 'RedHat', Ascendos = 'RedHat', CloudLinux = 'RedHat', PSBM = 'RedHat',
            OracleLinux = 'RedHat', OVS = 'RedHat', OEL = 'RedHat', Amazon = 'RedHat',
            XenServer = 'RedHat', Ubuntu = 'Debian', Debian = 'Debian', Raspbian = 'Debian', Slackware = 'Slackware', SLES = 'Suse',
            SLED = 'Suse', openSUSE = 'Suse', SuSE = 'Suse', SLES_SAP = 'Suse', Gentoo = 'Gentoo', Funtoo = 'Gentoo',
            Archlinux = 'Archlinux', Manjaro = 'Archlinux', Mandriva = 'Mandrake', Mandrake = 'Mandrake',
            Solaris = 'Solaris', Nexenta = 'Solaris', OmniOS = 'Solaris', OpenIndiana = 'Solaris',
            SmartOS = 'Solaris', AIX = 'AIX', Alpine = 'Alpine', MacOSX = 'Darwin',
            FreeBSD = 'FreeBSD', HPUX = 'HP-UX'
        )


To run the playbook locally use (administrator privileges needed)
```ansible-playbook -i "localhost," -c local playbook.yml```
