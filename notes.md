# Confidential Computing

---

## Intel-SGX

- Title: Intel Software Guard Extensions
- Source: [link](https://software.intel.com/content/www/us/en/develop/topics/software-guard-extensions.html)
- Description: an instruction set introduced in the new Intel CPUs to protect application code and data in a secure enclave
- Keywords: SGX, SDK, Enclave, CPU

## Graphene-SGX

- Title: Graphene SGX libOS
- Based-on: Intel-SGX
- Source: [link](https://www.usenix.org/conference/atc17/technical-sessions/presentation/tsai)
- Description: run an application inside an SGX enclave without modifications
- Keywords: SGX, tools, open-source, linux, libOS

## SGX-LKL

- Title: SGX-LKL LibOS
- Based-on: Intel-SGX
- Source: [link](https://github.com/lsds/sgx-lkl)
- Description: run unmodified Linux applications inside Intel SGX enclaves
- Keywords: SGX, [LKL](https://github.com/lkl/linux), open-source, libOS, linux, tools

## Panoply

- Title: Low-TCB linux applications with SGX enclaves
- Based-on: Intel-SGX
- Source: [link](https://www.ndss-symposium.org/ndss2017/ndss-2017-programme/panoply-low-tcb-linux-applications-sgx-enclaves/)
- Description: run unmodified Linux applications inside Intel SGX enclaves
- Keywords: SGX, open-source, library wrapper, linux

## Scone

- Title: Scone Confidential Computing
- Based-on: Intel-SGX
- Source: [link](https://sconedocs.github.io/)
- Description: run unmodified applications inside Intel SGX enclaves
- Keywords: SGX, instruction wrapper

## Haven

- Title: Haven for Windows
- Based-on: Intel-SGX
- Source: [link](https://www.usenix.org/system/files/conference/osdi14/osdi14-paper-baumann.pdf)
- Description: run unmodified Windows applications inside Intel SGX enclaves
- Keywords: SGX, windows, SQL server, apache, Drawbridge libOS

## Glamdring

- Title: Automatic application partitioning for Intel SGX
- Source: [link](https://www.researchgate.net/publication/317933820_Glamdring_Automatic_Application_Partitioning_for_Intel_SGX)
- Description: framework for automatic partitioning of applications written in C after annotation, to protect only sensitive data and functions with Intel SGX
- Keywords: SGX, framework, C

## Seng

- Title: SGX-Enforcing Network Gateway
- Based-on: Graphene-SGX / Intel-SGX
- Source: [link](https://www.usenix.org/conference/usenixsecurity20/presentation/schwarz)
- Description: a network gateway service that enables firewalls to assign network traffic to an application
- Keywords: SGX, network, DTLS, firewall, open-source, linux

## TaLoS

- Title: Secure and transparent TLS termination inside SGX Enclaves
- Based-on: Intel-SGX
- Source: [link](https://www.researchgate.net/publication/315715902_TaLoS_Secure_and_Transparent_TLS_Termination_inside_SGX_Enclaves)
- Description: a TLS library that allows existing applications to securely terminate their TLS connection
- Keywords: SGX, TLS-library, open-source, network

## LibSEAL

- Title: Auditing Internet Services with Intel SGX
- Based-on: Intel-SGX
- Source: [link](https://www.researchgate.net/publication/322897219_LibSEAL_Revealing_Service_Integrity_Violations_Using_Trusted_Execution)
- Description: a secure audit library for detecting Internet service integrity violations without the need to trust the service operator. Uses TaLos and SQLite to create and check logs
- Keywords: SGX, audit, open-source, TaLoS, SQLite

## EnclaveDB

- Title: Secure Database using SGX
- Based-on: Intel SGX
- Source: [link](https://ieeexplore.ieee.org/document/8418608)
- Description: a secure database based on the SQL Server Hekaton in-memory engine that uses Intel SGX to protect the confidentiality, integrity, and freshness of data
- Keywords: SGX, Database, SQL Server, hekaton, small TCB

## EnclaveOS

- Title: 
- Source: [link]()
- Description:
- Keywords: 

## Open Enclave

- Title: Open Enclave SDK
- Source: [link](https://openenclave.io/sdk/)
- Description: open source library for developing applications that use Hardware-based Trusted Execution Environments
- Keywords: SDK, open-source, C, C++, linux, windows, SGX, ARM TrustZone

## Asylo

## Fortanix EDP

## Fortanix SKDMS

## Fortanix CCM

## AWS Nitro Enclave

## AWS Nitro System
