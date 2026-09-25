```
lookingglass@linux:~/stuff/github$ cat skills.txt | awk -F'|' '{printf "%-15s | %s\n", $1, $2}'
```

```
LINUX           | Debian/Ubuntu-like, Fedora/AlmaLinux/CentOS (systemd, SSH, users and groups, security practices)
WINDOWS         | Active Directory fundamentals (Domain, GPO)
                | 
NETWORKING      | TCP/IP, DNS, DHCP, HTTP/HTTPS, VPN, MikroTik RouterOS fundamentals
DIAGNOSTICS     | ping, mtr, ss/netstat, tcpdump, curl, nc, iperf3
SERVERS         | NGINX fundamentals
                | 
VIRTUALIZATION  | Proxmox VE (KVM, LXC, snapshots, backups)
                | 
AUTOMATION      | Bash scripting (system audits, backup automation, network utilities)
PYTHON          | Python fundamentals, FastAPI
IaC             | Ansible (playbooks, roles), Terraform (bpg provider for Proxmox)
                | 
CONTAINERS      | Docker/Podman, Image optimization (multistage builds, distroless), container security practices
K8s             | Pods, Deployments, Services, ConfigMaps, Secrets, Ingess, diagnostics
                | 
CI/CD           | GitLab CI/CD fundamentals (Build, Test, Lint, Security (Trivy, Gitleaks), Deploy stages)
                | 
MONITORING      | Prometheus, Grafana fundamentals
                | 
SQL             | PostgreSQL, MySQL, MSSQL (JOIN queries, backup management)
NOSQL           | MongoDB fundamentals
```
