# Mappings

| Rules     |    SID    | Signature 		                                                                 |  Verified |
| --------- | --------- | ------------------------------------------------------------------------------ | --------- |
| ET Pro    |  2027190  | ET NETBIOS DCERPC DCOM ShellExecute - Likely Lateral Movement                  |    Yes    |
| ET Pro    |  2027189  | ET NETBIOS DCERPC DCOM ExecuteShellCommand Call - Likely Lateral Movement      |    Yes    |

# Notes

* Distributed Component Object Model - [T1175](https://attack.mitre.org/techniques/T1175/)

# Packet capture

**2027190**

'''
LocalServer32.......vk......H...............%.S.y.s.t.e.m.R.o.o.t.%.\.S.y.s.t.e.m.3.2.\.r.u.n.d.l.l.3.2...e.x.e. .%.S.y.s.t.e.m.R.o.o.t.%.\.S.y.s.t.e.m.3.2.\.s.h.e.l.l.3.2...d.l.l.,.S.H.C.r.e.a.t.e.L.o.c.a.l.S.e.r.v.e.r.R.u.n.D.l.l. .
'''
