# Mappings

| Rules     |    SID    | Signature 		                                                                 |  Verified |
| --------- | --------- | ------------------------------------------------------------------------------ | --------- |
| ET Pro    |  2027190  | ET NETBIOS DCERPC DCOM ShellExecute - Likely Lateral Movement                  |    Yes    |
| ET Pro    |  2027189  | ET NETBIOS DCERPC DCOM ExecuteShellCommand Call - Likely Lateral Movement      |    Yes    |
| ET Open   |  2021616  | ET TROJAN PSEmpire Checkin via POST                                            |    Yes    |

# Notes

* Distributed Component Object Model - [T1175](https://attack.mitre.org/techniques/T1175/)

# Packet capture

**2027190**

```
..^.."...S....E...j.@.@......y........l\.n{NU.....H.........fo....x...........`...........H...........0...........N...!...&...{FFB8655F-81B9-4fce-B89C-9A6BA76D13E7}......vk..J...................S.h.e.l.l. .E.x.e.c.u.t.e. .H.a.r.d.w.a.r.e. .E.v.e.n.t. .H.a.n.d.l.e.r.............X...........vk..N...x...........AppID.......{.F.F.B.8.6.5.5.F.-.8.1.B.9.-.4.f.c.e.-.B.8.9.C.-.9.A.6.B.A.7.6.D.1.3.E.7.}.............nk .E..Oe.......h.......................X...................................LocalServer32.......vk......H...............%.S.y.s.t.e.m.R.o.o.t.%.\.S.y.s.t.e.m.3.2.\.r.u.n.d.l.l.3.2...e.x.e. .%.S.y.s.t.e.m.R.o.o.t.%.\.S.y.s.t.e.m.3.2.\.s.h.e.l.l.3.2...d.l.l.,.S.H.C.r.e.a.t.e.L.o.c.a.l.S.e.r.v.e.r.R.u.n.D.l.l. .{.F.F.B.8.6.5.5.F.-.8.1.B.9.-.4.f.c.e.-.B.8.9.C.-.9.A.6.B.A.7.6.D.1.3.E.7.}.......0.......lh..............u..TH....s.Q....nk .E..Oe.......h.......................@.......................F...........ProgID......vk..F...................S.h.e.l.l...H.W.E.v.e.n.t.H.a.n.d.l.e.r.S.h.e.l.l.E.x.e.c.u.t.e...1.....................nk .E..Oe.......h...............................................B...........VersionIndependentProgID....vk..B..............T....S.h.e.l.l...H.W.E.v.e.n.t.H.a.n.d.l.e.r.S.h.e.l.l.E.x.e.c.u.t.e.................nk .E..Oe.......x...........X.......................,...........:...!...&...{FFC9F9AE-E87A-3252-8E25-B22423A40065}......vk..:...................S.y.s.t.e.m...T.h.r.e.a.d.S.t.a.t.i.c.A.t.t.r.i.b.u.t.e.................nk .E..Oe.......................................
```
