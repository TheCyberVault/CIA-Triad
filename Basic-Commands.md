# Basic Nmap Commands

1. **Scan a Single Target:**
   ```
   nmap [target]
   ```
   Scan a specific IP address or hostname.

2. **Scan Multiple Targets:**
   ```
   nmap [target1] [target2]
   ```
   Scan multiple targets at once.

3. **Scan Entire Subnet:**
   ```
   nmap [target/CIDR]
   ```
   Scan an entire subnet using CIDR notation (e.g., `192.168.1.0/24`).

4. **Scan Specific Ports:**
   ```
   nmap -p [port(s)] [target]
   ```
   Scan specific ports or port ranges (e.g., `-p 80,443` or `-p 1-100`).

5. **Scan All Ports:**
   ```
   nmap -p- [target]
   ```
   Scan all 65535 ports on the target.

6. **Scan Using Specific Scan Techniques:**
   - `nmap -sS [target]`: Perform a SYN scan (default).
   - `nmap -sT [target]`: Perform a full TCP connect scan.
   - `nmap -sU [target]`: Perform a UDP scan.
   - `nmap -sF [target]`: Perform a FIN scan.
   - `nmap -sN [target]`: Perform a NULL scan.
   - `nmap -sX [target]`: Perform an Xmas scan.

7. **Operating System Detection:**
   ```
   nmap -O [target]
   ```
   Detect the operating system of the target.

8. **Service Version Detection:**
   ```
   nmap -sV [target]
   ```
   Detect service versions running on open ports.

9. **Script Scanning:**
   - `nmap -sC [target]`: Run default NSE scripts against the target.
   - `nmap --script [script] [target]`: Run a specific NSE script.

10. **Output Options:**
    ```
    nmap -oN [output.txt] [target]
    ```
    Save results in normal format.

11. **Aggressive Scan:**
    ```
    nmap -A [target]
    ```
    Enable OS detection, version detection, script scanning, and traceroute.

12. **Verbose Output:**
    ```
    nmap -v [target]
    ```
    Increase verbosity for more detailed output.

13. **Ping Scan:**
    ```
    nmap -sn [target]
    ```
    Perform a ping scan (no port scan).

17. **Scan IPv6 Targets:**
    ```
    nmap -6 [target]
    ```
