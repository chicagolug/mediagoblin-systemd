# mediagoblin-systemd
GNU Mediagoblin systemd service files for use on Fedora, CentOS, Scientific Linux, and/or RHEL systems.

# Instructions

1. Place these files in the appropriate directory: `/etc/systemd/system`
2. Mark them as executable: `# chmod +x mediagoblin-celeryd.service mediagoblin-paster.service`.
3. Enable the services to start on boot: `# systemctl enable mediagoblin-celeryd.service mediagoblin-paster.service`
4. Start the services: `# systemctl start mediagoblin-celeryd.service mediagoblin-paster.service`


# Credit

Credit for these service files goes to Aleyph, whose original git repository is [here](https://github.com/ayleph/mediagoblin-systemd). Our files contain slight modifications to allow for proper creation of PID files when running a variant of "the prominent North American Enterprise Linux vendor."
