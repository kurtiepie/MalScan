# MalScan
A Docker-integrated YARA-based malware scanning tool for container security, leveraging diverse open-source and commercial threat intelligence feeds to detect malicious indicators in Docker images.

## Run
chmod +x malware_scan.sh
./malware_scan.sh -r rules/rules/public/eicar.yara kvad/eicar-test:0.1
