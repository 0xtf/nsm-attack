# Mappings

| Rules     |    SID    | Signature 		                                                      	    |  Verified |
| --------- | --------- | --------------------------------------------------------------------------------- | --------- |
| ET Open   | 2025725   | ET POLICY RunDll Request Over SMB - Likely Lateral Movement			    |    Yes    |

# Notes

* Rundll32 - [T1085](https://attack.mitre.org/techniques/T1085/)

Coverage of this technique is limited to the software/user agent/identifiers mapped above and when done over the network. 

# Packet capture example

**2025725**

```
..^..!.PV.N...E...8{@............#."....m@.Z..P...\...(.\.d.{.1.,.2.}.\...\.d.{.1.,.2.}.\...\.d.{.1.,.4.}.\...\.d.{.1.,.4.}.\.\.*.).?.....\...D.i.s.p.l.a.y.L.i.n.k. .C.o.r.e. .S.o.f.t.w.a.r.e.\.....@@AAAAAAAAAAAAAAAAAAAAAOI9kB9bTDzsuPUImOKJyecMhHPCH7DRHyOz7G4lgcYW45ZU100QKxr0Wsh1Hmtatg==@@....@@AAAAAAAAAAAAAAAAAAAAAERBTlifQmf1fz1vxjiciD8vRlxlEgpXPezQY83v72BU6SGNQ7VDUVvS7Rrgsg8RTA==@@....dl::tk::installer::updateProductsUninstallString....R.u.n.D.l.l.3.2...e.x.e. .".....@@AAAAAAAAAAAAAAAAAAAAAIOcja9jf6b/gJx97HR2oqM=@@....H.K.L.M.\.S.o.f.t.w.a.r.e.\.M.i.c.r.o.s.o.f.t.\.W.i.n.d.o.w.s.\.C.u.r.r.e.n.t.V.e.r.s.i.o.n.\.U.n.i.n.s.t.a.l.l.......O.@@AAAAAAAAAAAAAAAAAAAAAHAsyHoA8y5s8AaQ+7Q9drNdgXbs/96rcTUVfoJcA/1z@@....@@AAAAAAAAAAAAAAAAAAAAAERBTlifQmf1fz1vxjiciD8vRlxlEgpXPezQY83v72BU6SGNQ7VDUVvS7Rrgsg8RTA==@@....I.n.s.t.a.l.l.e.r.A.p.i...d.l.l.".,.d.l.R.e.m.o.v.e.P.r.o.d.u.c.t. .....I.n.s.t.a.l.l.e.r.A.p.i...d.l.l.".,.d.l.R.e.m.o.v.e.P.r.o.d.u.c.t. .....R.u.n.D.l.l.3.2...e.x.e. .".....@@AAAAAAAAAAAAAAAAAAAAAERBTlifQmf1fz1vxjiciD8vRlxlEgpXPezQY83v72BU6SGNQ7VDUVvS7Rrgsg8RTA==@@....@@AAAAAAAAAAAAAAAAAAAAAE+1gMTpfleKlBCJyzpIKZ5j3fxUO/pJYL5293oBLMQzq9Qdjx+wye3TD1UHGpIb1jbZDZBotgn4KlmC17n+Lpg=@@....D.e.f.a.u.l.t.P.r.o.d.u.c.t.........@@AAAAAAAAAAAAAAAAAAAAAERBTlifQmf1fz1vxjiciD8vRlxlEgpXPezQY83v72BU6SGNQ7VDUVvS7Rrgsg8RTA==@@....L.o.c.a.l.\.D.i.s.p.l.a.y.L.i.n.k.S.e.t.u.p.P.r.e.v.I.n.s.t.a.n.c.e.D.e.t.e.c.t.o.r.....C.u.s.t.o.m.A.c.t.i.o.n.D.a.t.a.........V.e.r.s.i.o.n.S.t.r.i.n.g...V.e.r.s.i.o.n.S.t.r.i.n.
```
