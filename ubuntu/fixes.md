# Ubuntu Fixes & Troubleshooting

## Bluetooth audio popping / micro pauses

**Device:** Bluetooth headset  
**OS:** Ubuntu  
**Issue:** Small popping sounds and very short pauses during audio playback.

### What I tried
- Reconnected the Bluetooth device
- Restarted Bluetooth service
- Checked audio codec (SBC / SBC-XQ)

### Temporary fix
- Disconnect and reconnect the headset
- Use A2DP profile instead of HSP/HFP

### Notes
Issue seems related to Bluetooth codec stability on Linux.
Further testing needed.
