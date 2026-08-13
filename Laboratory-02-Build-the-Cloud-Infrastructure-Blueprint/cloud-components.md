# Cloud Infrastructure Components

## 1. Compute Resources

### Example
The CPU and RAM available in the KillerCoda Linux server represent compute resources.

### Purpose
Compute resources provide the processing power and memory required to execute applications, services, and workloads.

### Importance in Cloud Computing
Compute resources are essential because cloud applications require processing capacity to run. Cloud providers allow organizations to obtain compute resources without purchasing and maintaining physical servers.

### KillerCoda Environment
The CPU cores and RAM identified through commands such as `lscpu`, `nproc`, and `free -h` demonstrate the compute resources allocated to the Linux environment.

---

## 2. Storage Resources

### Example
The disk attached to the KillerCoda Linux environment represents a storage resource.

### Purpose
Storage resources are used to save operating system files, applications, configuration files, and user data.

### Importance in Cloud Computing
Cloud storage allows data to be stored persistently and accessed when needed. It also supports applications that require reliable data storage.

### KillerCoda Environment
The disk capacity and mounted filesystems were identified using `df -h` and `mount`.

---

## 3. Networking Resources

### Example
The IP address and network interfaces of the KillerCoda server represent networking resources.

### Purpose
Networking resources allow systems and applications to communicate with other devices and services.

### Importance in Cloud Computing
Networking connects cloud resources and enables users and applications to communicate with cloud-hosted services.

### KillerCoda Environment
The hostname, IP address, and network interfaces were identified using `hostname`, `hostname -I`, and `ip addr`.

---

## 4. Operating System

### Example
The Linux operating system running in the KillerCoda environment is an operating system resource.

### Purpose
The operating system manages hardware resources and provides an environment where applications and services can run.

### Importance in Cloud Computing
Linux is widely used in cloud environments because it supports server applications, networking tools, automation, and many cloud-native technologies.

### KillerCoda Environment
The Linux distribution was identified using `cat /etc/os-release`, while the kernel version was identified using `uname -r`.
