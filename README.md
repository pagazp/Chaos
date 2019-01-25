# Chaos kernel bug for iOS 12.0 through 12.1.2 PoC & Writeup (CVE-2019-6225)
- Read everything please.
This only works with 64-bit devices running 12.0 - 12.1.2
- Writeup by @haxoorr (me) I made a clean writeup because the original PoC was posted as an image.

- Fixed in iOS 12.1.3 (16D39)

- If you're interested in bootstrapping iOS kernel security research (including the ability to forge PACs and call arbitrary kernel functions), keep an A7-A12 research device on iOS 12.1.2 or lower.

- These firmwares are vulnerable
- 11.x (N/A) (may be able to backport)
- 12.0 (16A366)
- 12.0.1(16A404)
- 12.1(16B92)
- 12.1.1(16C50)
- 12.1.2(16C101)
- 12.1.2(16C104)
- Should work on those devices.
- iPhone 5s/SE
- iPhone 6/6+
- iPhone 7/7+
- iPhone 8/8+
- iPhone X
- iPhone XS/XS Max
- iPhone XR
- iPad Air and higher (not tested)
- iPod 6th Gen (not tested)

- Downgrade from 12.1.3(16D39) to 12.1.2(16C104) or lower
- If you're on 11.4 - 11.4.1 stay there! tihmstar is working on something. #etason
- If you're on 11.0 - 11.4(b3) (jailbroken) just save shsh and stay where you are. You can update to 12.1.2 if you really want to.

- CVE Details

- Kernel
Available for: iPhone 5s and later, iPad Air and later, and iPod touch 6th generation

Impact: A malicious application may be able to elevate privileges

Description: A memory corruption issue was addressed with improved validation.

CVE-2019-6225: Brandon Azad of Google Project Zero, Qixun Zhao of Qihoo 360 Vulcan Team
