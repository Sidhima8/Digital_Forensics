**Aim**
Create a forensics disk image using FTK Imager or guymager and verify its integrity using SHA-256 hashing.

Learn to acquire a forensically sound image of a storage device using imaging tools. Verify image integrity by generating and comparing SHA-256 hash values of original and copied data.

**Objective**
- To perform digital forensic disk imaging using Guymager & create an Expert witness format image.
- To generate and verify hash values (MD5, SHA-1, SHA-256) to ensure the integrity of the acquired
  image.

**Methodology**
**Step1:** Launching Guymager
**Step2:** Selecting the Target Device
- The device /dev/sda (size: 256GB) was selected for acquisition.
**Step3:** Configuring image acquisition & hash calculation
**Step4:** Start image acquisition process
- Guymager started creating the forensic image of the device.
**Step5:** Generated image files and verified the data integrity.

After completing, the forensic image file is created in a folder and hashes were verified successfully, confirming data integrity.

**Conclusion**
It can be concluded that guymager can successfully create a forensic image of a storage device while maintaining data integrity. The generated hash values confirm that the acquired image is an exact and reliable copy of the original device, making it suitable for further digital forensic analysis and investigation.
