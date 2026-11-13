# Scenario 05: Computer Connected to Wi-Fi but No Internet Access

**Category:** Networking / Windows Troubleshooting  
**Status:** Completed (Simulated Training Scenario)  
**Author:** kuronoi

## 1. Problem Description

A user reported that their Windows laptop was connected to a Wi-Fi network but could not access the internet. Other devices connected to the same Wi-Fi network had internet access.

## 2. Possible Causes

- Incorrect IP configuration.
- DHCP server communication failure.
- Missing default gateway.
- DNS configuration problems.
- Wireless adapter or driver problems.

## 3. Investigation and Diagnosis

The following checks were performed:

1. Confirmed that other devices could access the internet.
2. Verified that the laptop was connected to the correct Wi-Fi network.
3. Checked the connection status, which displayed Connected, No Internet.
4. Ran the Windows Network Troubleshooter.
5. Received a report indicating that the DNS server was not responding.
6. Used `ipconfig /all` to inspect network configuration.
7. Identified an APIPA address (`169.254.12.45`) and a missing default gateway.

## 4. Troubleshooting Procedure

1. Compared connectivity across multiple devices.
2. Verified the laptop's Wi-Fi connection.
3. Ran the Windows Network Troubleshooter.
4. Inspected IP configuration using `ipconfig /all`.
5. Identified the APIPA address and missing default gateway.
6. Used `ipconfig /release` and `ipconfig /renew` to request fresh network configuration.
7. Received a valid IPv4 address and default gateway.
8. Tested communication with the router using `ping`.
9. Tested internet access and website loading.

## 5. Solution Implemented

The laptop initially failed to obtain a valid IP address through DHCP. The network configuration was renewed successfully, and the laptop received a valid IP address, default gateway and DNS server.

Internet access was restored in the simulated scenario.

## 6. Results and Verification

- The laptop received a valid IPv4 address.
- A default gateway was assigned.
- Communication with the router was successful.
- Websites loaded successfully.
- The user was asked to confirm that the issue was resolved.

**Note:** These results are from a simulated training exercise, not an actual network repair.

## 7. Lessons Learned

- Compare connectivity across multiple devices.
- Understand the purpose of DHCP, DNS and Default Gateway.
- Recognise APIPA addresses.
- Use Command Prompt to diagnose network configuration.
- Understand the purpose of `ipconfig` and `ping`.
- Verify internet connectivity after troubleshooting.
- Document solutions for future reference.

## 8. Tools Used

- Windows Network Troubleshooter
- Command Prompt
- `ipconfig /all`
- `ipconfig /release`
- `ipconfig /renew`
- `ping`

## 9. Conclusion

This exercise improved my understanding of network troubleshooting, IP addressing and connectivity testing. It also strengthened my ability to diagnose network problems systematically, apply appropriate solutions and document technical findings.

---

**Author:** kuronoi  
**Project:** IT Troubleshooting Handbook
