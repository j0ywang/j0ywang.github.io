---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


### <span style="color:#52ADC8">InsectACIDE: Debugger-Based Holistic Asynchronous CFI for Embedded System</span>
<b>Yujie Wang</b>, Cailani Lemieux Mack, Xi Tan, Ning Zhang, Ziming Zhao, Sanjoy Baruah, and Bryan C. Ward.\
In *IEEE Real-Time and Embedded Technology and Applications Symposium (RTAS)*, 2024.\
[[PDF](https://ieeexplore.ieee.org/abstract/document/10568062)] [[Code](https://github.com/InsectACIDE/insectACIDE)]

- We designed a novel module in the Arm Cortex-M TrustZone that detects control flow hijacking attacks targeting both userspace and kernelspace code in real-time embedded systems. This module utilizes hardware debugging features to provide protection without requiring modifications to the normal-world binary.

### <span style="color:#52ADC8">Opportunistic Data Flow Integrity for Real-time Cyber-physical Systems Using Worst Case Execution Time Reservation</span>
<b>Yujie Wang</b>, Ao Li, Jinwen Wang, Sanjoy Baruah, and Ning Zhang.\
In *USENIX Security Symposium (Security)*, 2024.\
[[PDF](https://www.usenix.org/conference/usenixsecurity24/presentation/wang-yujie)] [[Code](https://github.com/WUSTL-CSPL/OP-DFI/)]

- By leveraging a feature of real-time systems known as "worst-case execution time reservation'', we  designed a novel method that incorporates Data-Flow Integrity—a system defense technique providing strong  protection—into real-time cyber-physical systems (e.g., ROS-based robots and autonomous vehicles) with less than 5% system overhead. In contrast, the state-of-the-art approaches can incur overheads of up to 200%.

### <span style="color:#52ADC8">Partial Context-Sensitive Pointer Integrity for Real-time Embedded Systems</span>
<b>Yujie Wang</b>, Kailani Lemieux Mack, Thidapat Chantem, Sanjoy Baruah, Ning Zhang, and Bryan C. Ward.\
In *IEEE Real-Time Systems Symposium (RTSS)*, 2024.\
[[PDF](https://github.com/parcspi/ParCSPI)] [[Code](https://github.com/parcspi/ParCSPI)]

-   This work formulates the security level provided by partial context-sensitivity in relation to its performance impact on real-time schedulability. As a result, optimal policy-guided security protection can be achieved with theoretical real-time schedulability guarantees. Our approach can provide 60% pointer integrity protection with only 10% runtime overhead. In contrast, existing approaches can incur over 150% overhead without offering any real-time schedulability guarantees.


### <span style="color:#52ADC8">Your Firmware Has Arrived: A Study of Firmware Update Vulnerabilities</span>
Yuhao Wu, Jinwen Wang, <b>Yujie Wang</b>, Shixuan Zhai, Zihan Li, Yi He, Kun Sun, Qi Li and Ning Zhang.\
In *USENIX Security Symposium (Security)*, 2024.\
[[PDF](https://www.usenix.org/conference/usenixsecurity24/presentation/wu-yuhao)] [[Code](https://github.com/WUSTL-CSPL/ChkUp)]

- We developped a novel static binary analyzer that can automatically identify firmware update vulnerabilities for IoT devices. We have reported over 30 vulnerabilities.

### <span style="color:#52ADC8">Secure and Timely GPU Execution in Cyber-physical Systems</span>
Jinwen Wang, <b>Yujie Wang</b> and Ning Zhang.\
In *ACM Conference on Computer and Communications Security (CCS)*, 2023.\
[[PDF](https://dl.acm.org/doi/pdf/10.1145/3576915.3623197)] 

- We designed a trusted module using TEE to ensure the timely execution of GPU workloads.

### <span style="color:#52ADC8">ARI: Attestation of Real-time Mission Execution Integrity</span>
Jinwen Wang, <b>Yujie Wang</b>, Ao Li, Yang Xiao, Ruide Zhang, Wenjing Lou, Y. Thomas Hou and Ning Zhang.\
In *USENIX Security Symposium (Security)*, 2023.\
[[PDF](https://www.usenix.org/system/files/sec23fall-prepub-482-wang-jinwen.pdf)] [[Code](https://github.com/WUSTL-CSPL/ARI)]

- We designed a software-only attestation module to efficiently attest the mission execution integrity of cyber-physical systems.

