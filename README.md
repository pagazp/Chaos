# Chaos exploit for iOS 12.0 through 12.1.2 PoC & Writeup
- Read everything please.
This only works with 64-bit devices running 12.0 - 12.1.2
- Writeup by @haxoorr (me) I made a clean writeup because the original PoC was posted as an image.
- Original PoC by @s0rrymybad
- Patched in iOS 12.1.3 (16D39)

- If you're interested in bootstrapping iOS kernel security research (including the ability to forge PACs and call arbitrary kernel functions), keep an A7-A12 research device on iOS 12.1.2 or lower.

- Confirmed to work on...
- 12.0 (16A366)
- 12.0.1(16A404)
- 12.1(16B92)
- 12.1.1(16C50)
- 12.1.2(16C101)
- 12.1.2(16C104)

- iPhone 5s/SE
- iPhone 6/6+
- iPhone 7/7+
- iPhone 8/8+
- iPhone X
- iPhone XS/XS Max
- iPhone XR
- Some iPads (not tested)
- iPod 6th Gen (not tested)

- Downgrade from 12.1.3(16D39) to 12.1.2(16C104) or lower
- If you're on 11.4 - 11.4.1 stay there! tihmstar is working on something. #etason
