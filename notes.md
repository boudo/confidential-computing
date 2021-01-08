# Confidential Computing

---

## Intel-SGX

- Title: Intel Software Guard Extensions
- Source: [link](https://software.intel.com/content/www/us/en/develop/topics/software-guard-extensions.html)
- Description: an instruction set introduced in the new Intel CPUs to protect application code and data in a secure enclave
- Keywords: Intel® SGX, SDK, Enclave, CPU

## Graphene-SGX

- Title: Graphene SGX libOS
- Based-on: Intel-SGX
- Source: [link](https://www.usenix.org/conference/atc17/technical-sessions/presentation/tsai)
- Description: run an application inside an SGX enclave without modifications
- Keywords: Intel® SGX, tools, open-source, linux, libOS

## SGX-LKL

- Title: SGX linux kernel kibrary OS
- Based-on: Intel-SGX
- Source: [link](https://github.com/lsds/sgx-lkl)
- Description: run unmodified Linux applications inside Intel SGX enclaves
- Keywords: Intel® SGX, [LKL](https://github.com/lkl/linux), open-source, libOS, linux, tools

## Panoply

- Title: Low-TCB linux applications with SGX enclaves
- Based-on: Intel-SGX
- Source: [link](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/panoply-low-tcb-linux-applications-sgx-enclaves/)
- Description: run unmodified Linux applications inside Intel SGX enclaves
- Keywords: Intel® SGX, open-source, library wrapper, linux

## Scone

- Title: Scone Confidential Computing
- Based-on: Intel-SGX
- Source: [link](https://sconedocs.github.io/)
- Description: run unmodified applications inside Intel SGX enclaves
- Keywords: Intel® SGX, instruction wrapper

## Haven

- Title: Haven for Windows
- Based-on: Intel-SGX
- Source: [link](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-baumann.pdf)
- Description: run unmodified Windows applications inside Intel SGX enclaves
- Keywords: Intel® SGX, windows, SQL server, apache, Drawbridge libOS

## Glamdring

- Title: Automatic application partitioning for Intel SGX
- Source: [link](https://www.researchgate.net/publication/317933820_Glamdring_Automatic_Application_Partitioning_for_Intel_SGX)
- Description: framework for automatic partitioning of applications written in C after annotation, to protect only sensitive data and functions with Intel SGX
- Keywords: Intel® SGX, framework, C, tools

## Seng

- Title: SGX-Enforcing Network Gateway
- Based-on: Graphene-SGX or Intel-SGX
- Source: [link](https://www.usenix.org/conference/usenixsecurity20/presentation/schwarz)
- Description: a network gateway service that enables firewalls to assign network traffic to an application
- Keywords: Intel® SGX, network, DTLS, firewall, open-source, linux

## TaLoS

- Title: Secure and transparent TLS termination inside SGX Enclaves
- Based-on: Intel-SGX
- Source: [link](https://www.researchgate.net/publication/315715902_TaLoS_Secure_and_Transparent_TLS_Termination_inside_SGX_Enclaves)
- Description: a TLS library that allows existing applications to securely terminate their TLS connection
- Keywords: Intel® SGX, TLS-library, open-source, network

## LibSEAL

- Title: Auditing Internet Services with Intel SGX
- Based-on: Intel-SGX
- Source: [link](https://www.researchgate.net/publication/322897219_LibSEAL_Revealing_Service_Integrity_Violations_Using_Trusted_Execution)
- Description: a secure audit library for detecting Internet service integrity violations without the need to trust the service operator. Uses TaLos and SQLite to create and check logs
- Keywords: Intel® SGX, audit, open-source, TaLoS, SQLite

## EnclaveDB

- Title: Secure Database using SGX
- Based-on: Intel-SGX
- Source: [link](https://ieeexplore.ieee.org/document/8418608)
- Description: a secure database based on the SQL Server Hekaton in-memory engine that uses Intel SGX to protect the confidentiality, integrity, and freshness of data
- Keywords: Intel® SGX, Database, SQL Server, hekaton, small TCB

## EnclaveOS

- Title: Fortanix enclaveOS
- Based-on: Intel-SGX
- Source: [link](https://www.fortanix.com/products/runtime-encryption/)
- Description: secure runtime environment for applications that allows them to run inside SGX enclaves without any modification
- Keywords: Intel® SGX, runtime environmen, linux

## Open-Enclave

- Title: Open Enclave SDK
- Source: [link](https://openenclave.io/sdk/)
- Description: open source library for developing applications that use Hardware-based Trusted Execution Environments
- Editor: Microsoft
- Keywords: SDK, open-source, C, C++, linux, windows, Intel® SGX, ARM TrustZone

## Runtime-Encryption

- Title: Runtime Encryption®
- Based-on: EnclaveOS
- Source: [link](https://www.fortanix.com/products/runtime-encryption/)
- Description: deterministic security platform with runtime memory encryption for applications, to protect data during processing
- Editor: Fortanix
- Keywords: Intel® SGX

## Asylo

- Title: Asylo framework for confidential computing
- Source: [link](https://asylo.dev/)
- Description: framework for developing enclave applications in trusted runtime environments, including software and hardware environments
- Editor: Google
- Keywords: Framework, open-source, SDK, tools, enclave, Intel® SGX, C++

## Rust-EDP

- Title: Enclave Development Platform
- Based-on: Runtime-Encryption
- Source: [link](https://fortanix.com/products/runtime-encryption/edp/)
- Description: writing Intel SGX applications from scratch with Rust
- Editor: Fortanix
- Keywords: Intel® SGX, tools, SDK, open-source, Rust

## Self-Defending-KMS

- Title: Self-Defending Key Management Service™
- Based-on: Runtime-Encryption
- Source: [link](https://fortanix.com/products/sdkms/)
- Description: Securely generate, store and use cryptographic keys and certificates, passwords, API keys, or others
- Editor: Fortanix
- Keywords: SaaS, KMS

## Confidential-Computing-Manager

- Title: Confidential Computing Manager™
- Based-on: Runtime-Encryption
- Source: [link](https://www.fortanix.com/products/confidential-computing-manager/)
- Description: SaaS, allows applications to run in confidential computer environments, allows to create enclaves from existing applications without any rewriting, modification or recompilation
- Editor: Fortanix
- Keywords: SaaS

## Nitro-Enclaves

- Title: Nitro Enclave for Amazon EC2 instances
- Source: [link](https://aws.amazon.com/fr/ec2/nitro/nitro-enclaves/)
- Description: an Amazon EC2 functionality for creating enclaves from Amazon EC2 instances. Enclaves are virtual machines that have no persistent storage, administrator or operator access
- Editor: AWS
- Keywords: EC2, enclave, Nitro hypervisor, KMS, VM

## Nitro-System

- Title: Nitro System for Amazon EC2 instances
- Source: [link](https://aws.amazon.com/fr/ec2/nitro/?nc1=h_ls)
- Description: a set of dedicated hardware and lightweight hypervisor that allows to prohibit and lock all Amazon employee accesses and all other root accesses
- Editor: AWS
- Keywords: EC2
