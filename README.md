# Drive-Firmware-Qual
Firmware Update Qualification is the process of testing and validating a new drive  firmware version before it’s deployed to production

**Project Scope**
Firmware qualification involves thoroughly testing and validating the firmware update to ensure that it functions correctly and complies with applicable industry standards and requirements. The process verifies that the drive continues to operate reliably after the update and that no data is lost, corrupted, or adversely affected during or after the firmware upgrade.

**Why**
- Firmware upgrades systematically address known defects and significantly improve operational stability
- Ensures new or updated firmware functions correctly and safely.
- Quality benchmarks
- Prevents failures, data loss, and performance issues in production.

**Process of Drive firmware upgrade**

<img width="1166" height="649" alt="image" src="https://github.com/user-attachments/assets/c1531940-e671-41fb-9d88-b9ad23a1d38b" />

- Once we have the storage server run load tests qualification before and after the firmware upgrade.
- Comparing the performance results will help us understand the impact of the upgrade.

**Baseline**
- We are running the load against the old build, which is currently running in production, and the current build, which is under qualification

**Data**
- We have to capture Performance KPIs such as TTFBs, Latencies, CPU & Drive utilization for comparison

<img width="708" height="410" alt="image" src="https://github.com/user-attachments/assets/7177e010-1258-4ce5-b3e1-1c15c4b8fd11" />

**Scopes** 

- **Compatibility Testing:**
Confirm the updated firmware is fully compatible with existing hardware, operating systems, and applications.

- **Functional Testing:**
  Ensure all drive features and commands work as expected (read/write operations, TRIM, SMART reporting, etc.)


