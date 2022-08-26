0 0 * * * find /home/vagrant/Job/  -mtime  +7 \( -name "*.log" -o  -name "*.err" \)  -exec rm -rf {} \;
