# Mappings

| Rules     |    SID    | Signature                                                                                          |  Verified |
| --------- | --------- | -------------------------------------------------------------------------------------------------- | --------- |
| ET Open   |  2027267  | ET ATTACK\_RESPONSE Possible Lateral Movement - File Creation Request in Remote System32 Directory |    Yes    |

# Notes

As the signature name entails, this rule will only trigger when RunDll runs over SMB. Due to the nature of our sources in NSM, detection of [T1085](https://attack.mitre.org/techniques/T1085/) is therefor limited to RunDll between hosts.

Packet capture example:

```
..)!~a..^.."..E.....@...^.............I30.....P....s.......SMB@...............................-..................Hm<...R.l9.......................................@...x.:.........W.i.n.d.o.w.s.\.S.y.s.t.e.m.3.2.\.s.q.l.s.r.v.3.2...d.l.l.
```
