# Mappings

| Rules     |    SID    | Signature                                                                     |  Verified |
| --------- | --------- | ----------------------------------------------------------------------------- | --------- |
| ET Open   |  2026879  | ET POLICY Possible winexe over SMB - Possible Lateral Movement                |    YES    |
| ET Open   |  2010781  | ET POLICY PsExec service created                                              |    YES    |

# Notes

* Service Execution - [T1035](https://attack.mitre.org/techniques/T1035/)

Coverage of this technique is limited to the software/user agent/identifiers mapped above and when done over the network. 

# Packet capture example:

**2026879**

```
1.0...0...2...6.....W.O.R.K.G.R.O.U.P.A.d.m.i.n.i.s.t.r.a.t.o.r.K.A.L.I...._1B..tM.BcrV.........&.$..:.......U.n.i.x...S.a.m.b.a. .4...9...4.-.D.e.b.i.a.n.....
```
**2010781**

```
P.s.E.x.e.c. .S.e.r.v.i.c.e.....(.....F.i.l.e.V.e.r.s.i.o.n.....2...2...H.....I.n.t.e.r.n.a.l.N.a.m.e...P.s.E.x.e.c. .S.e.r.v.i.c.e. .H.o.s.t...v.)...L.e.g.a.l.C.o.p.y.r.i.g.h.t...C.o.p.y.r.i.g.h.t. .(.C.). .2.0.0.1.-.2.0.1.6. .M.a.r.k. .R.u.s.s.i.n.o.v.i.c.h.....B.
```
