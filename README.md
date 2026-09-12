<p align="center">
  <img
    src="https://github.com/user-attachments/assets/bad8c514-14c1-47a7-8187-df2ef0600384"
    alt="Yug"
    width="300"
  />
</p>





<p align="center">      </p>

<h1 align="center">Microsoft  Activation  Scripts (MAS)</h1>

<p align="center">Open-source Windows and Office activator featuring HWID, Ohook, TSforge, and Online KMS activation methods, along with advanced troubleshooting.</p>

<hr>
  
## How to Activate Windows / Office / Extended Security Updates (ESU)?

### Method 1 - PowerShell 🎀

1. Click the **Start Menu**, type `PowerShell`, and open it.

2. Copy and paste the code below and press **Enter.**  
   - For **Windows 8.1, 10 and 11**:
     ```
     irm https://get.activated.win | iex
     ```
	 If the above is blocked (by ISP/DNS), try this (needs updated Windows 10 or 11):  
	 ```
	 iex (curl.exe -s --doh-url https://1.1.1.1/dns-query https://get.activated.win | Out-String)
	 ```
	- **Script not launching? Use the below-listed Method 2.**

3. In the menu that appears, type the number corresponding to one of the **Green** options.

---

### Method 2 - Traditional (Windows Vista and later)

1.   Download the script:
      *   [**MAS_AIO.cmd**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?path=/MAS/All-In-One-Version-KL/MAS_AIO.cmd&download=true) (Direct script)
      *   [**MAS_AIO.zip**](https://dev.azure.com/massgrave/Microsoft-Activation-Scripts/_apis/git/repositories/Microsoft-Activation-Scripts/items?$format=zip) (If the direct script is blocked by your browser)
2.   Run the `MAS_AIO.cmd` file.
3.   In the menu that appears, type the number corresponding to one of the **Green** options.

---

> [!TIP]
> - Some ISPs/DNS providers block access to our domains. You can bypass this by enabling [DNS-over-HTTPS (DoH)](https://developers.cloudflare.com/1.1.1.1/encryption/dns-over-https/encrypted-dns-browsers/) in your browser. 
> - **Having trouble**? Visit our [troubleshooting page](https://massgrave.dev/troubleshoot) or raise an issue on [GitHub](https://github.com/massgravel/Microsoft-Activation-Scripts/issues).

> [!NOTE]
>
> - The `irm` command in PowerShell downloads a script from a specified URL, and the `iex` command executes it.
> - Always double-check the URL before executing the command and verify the source is trustworthy when manually downloading files.
> - Be cautious of third parties spreading malware disguised as MAS by altering the URL in the PowerShell command.

---

<div align="center">

---

Latest Version: 3.12  
Release date: 04-Jul-2026
