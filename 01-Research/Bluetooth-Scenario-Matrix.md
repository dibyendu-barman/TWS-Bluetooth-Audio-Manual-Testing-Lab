# Bluetooth Scenario Matrix

| ID | Scenario | Initial State | Trigger | Expected Area to Observe | Actual Observation |
|---|---|---|---|---|---|
| TS-BT-001 | Device Discovery | Bluetooth ON | Open case | Device visibility | |
| TS-BT-002 | First Pairing | Unpaired | Select device | Pairing | |
| TS-BT-003 | Normal Connection | Paired | Connect | Connection | |
| TS-BT-004 | Bluetooth OFF | Connected | Bluetooth OFF | Disconnection | |
| TS-BT-005 | Bluetooth ON | Disconnected | Bluetooth ON | Reconnection | |
| TS-BT-006 | Out of Range | Connected | Move away | Connection stability | |
| TS-BT-007 | Return to Range | Disconnected/unstable | Return | Recovery | |
| TS-BT-008 | Phone Restart | Connected | Restart phone | Recovery | |
| TS-BT-009 | Re-Pairing | Forgotten | Pair again | Pairing | |
| TS-BT-010 | Audio Recovery | Audio playing | Reconnect | Audio recovery | |

## Notes

These are test scenarios, not final test cases.

Expected behavior should be confirmed through requirements or established product behavior before a scenario is classified as Pass or Fail.
