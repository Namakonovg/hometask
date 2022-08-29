0 0 * * * mv /home/vagrant/Job/job.log job_$(date +%y%m%d).log && find /home/vagrant/Job/  -mtime  +7 \( -name "*.log" -o  -name "*.err" \)  -exec rm -rf {} \;
