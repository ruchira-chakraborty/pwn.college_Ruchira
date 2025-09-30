# Challenge Name
killing misbehaving processes

## My solve
**Flag:** `pwn.college{YA0wrBgs-39SIz5k-wQqodQiz7L.0FNzMDOxwyM3EzNzEzW}`

```bash
Connected!
hacker@processes~killing-misbehaving-processes:~$ ps -ef | grep /challenge/decoy
root         140       1  0 06:06 ?        00:00:00 su -c exec /challenge/decoy > /tmp/flag_fifo hacker
hacker       143     140  0 06:06 ?        00:00:00 /usr/bin/python /challenge/decoy
hacker       176     158  0 06:07 pts/1    00:00:00 grep --color=auto /challenge/decoy
hacker@processes~killing-misbehaving-processes:~$ kill 143
hacker@processes~killing-misbehaving-processes:~$ cat /tmp/flag_fifo & /challenge/run
[1] 177
pwn.college{ceSA73us.d9gKLl-glpCBI-Cf6SXVlio8kB2hi-Hu6VkElP}
pwn.college{GSyfjyoBOG47RAAl9pAySUqJG9NOP3RLJ4R6DOP4pUSVLy9}
pwn.college{Jvjd435GEWoL5S0zz7G1-5udswYBLwD5ntKdL3wZ2kgXorr}
pwn.college{drgHd4838I.ItuooR82sU3BZ0mVCLILbyrYkNLhCqhOHM-a}
pwn.college{Kf3MEkOF9aOms99knaGxsMry9fNQlNJYdCSQR81Sz9ZIgnc}
pwn.college{LDOQ1TW4fvZZQODIuGmMTIpC2EtjP.pl01crNnXsBgK7jUN}
pwn.college{gHYm5yn5aJVs4phjmrhVdmMBC0Q30SMDrFlcwMaMdu-FcnT}
pwn.college{q9Wlk4UQmI2b5fUrIhoFbxz1qn.3cZ8ynkhoA-rhdOS5YBa}
pwn.college{wgxKZ0B46ViWTOZbz3e0wQAf5yqmPu46PuWpe9dLdRCuFVf}
pwn.college{EvoFStwJVgMYsykfXWotjQhu7.uIMs2EaNY.pJY.jCH2AvT}
pwn.college{fJjmiqp4oTXQQ2EZGPhCl2IpQOZRkZT-hijpLArIF2ATX0S}
pwn.college{qhCoiRSuswZ8G6mREK89AcDBytsmtKaNDnonOGuVQ1jXd34}
pwn.college{Ei3GzyqHeBn0Dc0A8N3L8.Ho71fd8g3GttAvPYmwhRMMlnC}
pwn.college{kg9ZvM086IcTxBKBwb.idy0EydYKp6tBC5uHr0m3-MWdg8B}
pwn.college{XlVJFsbRiOa6zEzoYqZhqL4g2-X1HdqqLneh3YH6aj9Oszn}
pwn.college{ZgvehNJjdBTFt0xVWsr1W8gqBph7bhlBBnJSlR425MsO-Aw}
pwn.college{hHiBmkkcjtkSmo8NuBLyCcggbJRZIyiLXWnGNsqlLXCAnC6}
pwn.college{CNGPKmiQBvwFcS9W3AbfkcMU0.XBBI9kZeqmMRaGknudZXB}
pwn.college{u5xlbbK7IvNp8OYGGnA9gsx1sjLla94XLwP4ZzRmb3fTDIw}
pwn.college{P8dtyJO7EAuKBcJI-Oo6FK9lCtOyg9eVhwJO2ZQlaP2QtuC}
pwn.college{YvByzy9rmguyLcHtL71iu6XL5LXM4.37R9gBSXOHUbiAPZr}
pwn.college{rtyqneqxLYdSDJigQp4NHHcmolqXtpf8axvhHf9O2SctIwr}
pwn.college{YDLuk0WbJJVkdhDV2YQuX87pDql1tuGxgPiUNOAonB7XKBs}
pwn.college{uX6eJSaXlAjl5ThRLtbVcXT2hLacpq53tIl46fRoCM.72hB}
pwn.college{wmHKiJcPaZmvbT9J2yhNen9OtekrCnlFU09tbuPBUsqEKEL}
pwn.college{FKTVmDA.V670hojnT1ks59u4DvJXbui2glUZkJ9VzfVEJVe}
pwn.college{zJx1zhTNyi-SwHzuxo0lQ.EFWgwfDTNzA6ermanbjL8c7pn}
pwn.college{8zWKt4tJtfX71D9NGDb-2DbD.uNxVsz.IF8WdwSNT0GjGn.}
pwn.college{Ar31IdMYvibVjIghV5YZNyxl5rGn7L3hs.n02Qdoq9gAtbp}
pwn.college{YkvPAdKfR07zvvKqyYZnYpdbdLR-PrVdkCBI3wUk01ja4wp}
pwn.college{ezgewOFLfV2OYjE-jUczsETVT3u.BZvwnAIEiPPwxoo-6CB}
pwn.college{wiIkcX-nGrhXfzr2djLecFaET8kUH7nwihm3vCKZSse4Zb5}
pwn.college{zmvxRGg6c8EntjByPb0qtK9oQ21P2vs7ylNvQaJ63MvEezp}
pwn.college{9lP9Va.3J4zgyCnLIQRYgYgj0-lro2ie3b9m2pdJDdOlBo8}
pwn.college{T6yK9rgI2D4eUeRjj4xDWJOyxt6vPeC1gMiIhx-UtQ-wP8z}
pwn.college{XDH-tbcELEEVOUyO8ylrit6yyPOYW8clFimOodblkksy4gu}
pwn.college{DbZgImmQomP5jcm0tSmA79-2BAAk5X2wrmC4xycLew6.xcY}
pwn.college{cSGfQv9TbP4.Awf02AGmXTfMnqQ-qxJ2UuJtF46vSQWUhVP}
pwn.college{J8h6E7x91x0qMDQglbWbtM.AZqSB3wQssrw.L4tgxovXpl9}
pwn.college{wurfwUv1t48NupzibPHOEUHLHf7.XXo0-zCK6.tM.O.1oVA}
pwn.college{sTf9M4-0jSAUuE.pE-5qWGLn9Vx34Cf4gLIHKQhP2dt2FLx}
pwn.college{c2rjom6YMDJHNF2ZjIg-yC9a5ynP7.lt8sDcf1exifoOehF}
pwn.college{2X6rABnU0yQhU.Az4NS2LR08H4v4JdmXibmYe6ld.TGiouR}
pwn.college{-R7ofOVeFWEPI9lUT2bes3BgLxxTuRhHj4socBrEP0Gl7-W}
pwn.college{wYfxgxW.Q866-nzUtj.Ed4NpvF.ZUZeJJVHYkLeb7KQQqPN}
pwn.college{RK8Lw4ItLoGKlpk.QBxj4fRY3Zs7-ZIq7f4B1UaqOD1WRV5}
pwn.college{uN5RlTzG6K6MMEpyloRmOsdXU9.ctE2HvDGEXzBeOZsaNTA}
pwn.college{hyvfGhr59E173mVp4pywWneMc0emfHq2IpPsTovR54DMfa4}
pwn.college{CBD.Gj4mzPKypbUfvdC9ofKsAUt-rn81.OEC8fQ.MorfvUl}
pwn.college{rFSYj0e534MEl.asc2VY8sh6gKPiT9zztxhvJ3jDGo1pjqR}
pwn.college{cCO8kNNFMPremqxJZHjGs1VbSWfyzxP5nBa-HnvKdgtArOo}
pwn.college{HhRvXyL6d6SQlwsZlLYhIuNBhwb0ihg7-QXCSvdH9hreROD}
pwn.college{lbC4jbFZGLB6bs.IMA69OhMaPSAbh-KLcWrKF7OWZz6gBPs}
pwn.college{VvKetAWt7UWLmvBxWvxbq9-F9aIKEUN0IWDiBzXQn7caEwl}
pwn.college{eaAdFJAR8JxVO8xIo7-cWs.-aqgIWoFpU.S4CLlu75V0rPL}
pwn.college{-0Lli7sToBeBO.6dfLCPTvSW7QURQ.HeVymuWrWUKSehjO5}
pwn.college{rpcTUgBA2rjfgxYS4SR.4wccoOSrSct-RRcbSJEPOv7zBP5}
pwn.college{NdeDgt.Gr4VBOJwsOX9jAjajvURoPsI.-.DJdZBuZNlIWSn}
pwn.college{T5zuXKMzDZ4biFQa6qrMEmZMbrFT6sbj7.PoCyND3Af61pn}
pwn.college{IB2bf7hF3VCaeSynrIku-SJgQLirgzFupUyxF173vAJvO0g}
pwn.college{GBO6iVjdEpTeRSAXMB7giht3EsMOqcqq8lCzElWY9hDorvW}
pwn.college{0LKm1wxnZQstuuPUNVJPmCrY.KH0DxqzhvtNkSxGT52ZjNs}
pwn.college{kVCwyop984zAzV4xLtzbHCELzEaRZ8dFrHqK8ymT5Iyu3Lb}
pwn.college{cxSjmoWhtCG17D384E5RfvRnS5NW4WijMnOvyqDUV7UxD83}
pwn.college{Ue4fcBt5p.v.CdSeGMFXoQ49LtA.PUa5DpGxwAV2bPxAquA}
pwn.college{SykhEnLls035hroWlRfpiKrd.scn21HqiFubJA5kP5V750q}
pwn.college{45NCIuIgYsjmL5bErbC5h5reSuTHC.EoAv6We3w9QKXzTki}
pwn.college{YULtMRVOk4S93n6p2JVcKR95Zh3gnMQlx2O-VZlpwwNuPVB}
pwn.college{mZ-A2DUjNCu6XbIaY2Ji1pXf957.mqYzad9trPStACnA-vZ}
pwn.college{GY0P4Msc05Wico7WLSyg99TSbVlaoKS.-vhiHlYAdsS9Hah}
pwn.college{jZ3TWgtmjK8sj7L.4wkKK.O8LE5Kv.lDpVBRApotYolj4vC}
pwn.college{9iCV.o8fsazZjNY5AIlvd7KTdTNIyWbosbtWcUkrhbxUaSx}
pwn.college{BFgkX4ZvFfA4NX790nybmWEr7nE9DKErzPixhJ0fw18S04I}
pwn.college{ossTMjUe0VKBDo9RS-0Lt226Fy8bc2KYkyO5COgDrWAhLYX}
pwn.college{rdPCMSi1XygSv3Xzhkem.vyOzZ5YSx-BDgnrFS2iv9oIumm}
pwn.college{c9axysOCrO4.TTwqatXwtR4H8i-HLKcfrnra4BRDclEh1ES}
pwn.college{M3crZYd0r0fosqBtedsECAw7BLAJBp.vVg4L6bJtJiww0C5}
pwn.college{VZwuXZ2zq7TbtoeWOg.AvaMyt8erZ.Ti0DQq.igd4ibMafz}
pwn.college{u16k5-BSHT8m2O5ISaLaKrUhcEVx48a5.AjMCoNjZj6KRiH}
pwn.college{vmcrA-hDxLB4-M1enLuRJXGXJ8Ove.cKA4PAzyxYJbal9QF}
pwn.college{d6bSUPvKc-lFCw5wPHupHTAiaxhYhOm3sCSZ4xNvvGe6wdD}
pwn.college{QsF9beBnJtIDfHdAD1k8T.j1KswmtXADaCqzO5FNIaJYcOd}
pwn.college{42p8qmMLfYhHoFiRYdskZd8xc3LsbFaoLUUR2Sc8ul10OpE}
pwn.college{U8aZqFxAfKC-D2q7Y99qaM.agOJMNIbBRmT.geOGG9R0fu0}
pwn.college{W-zP41ognehhDooYOFEAlimKJoSNGn96vzZ7gk8bRFc.Vtq}
pwn.college{UIdhqLofgQhkEuWxiLcC2QdF-HCiT6qxCjw5r2SSR8HQvNz}
pwn.college{KiL.D.nIVsU8-dyuM0hbP5zIvnOuZ0jg4YfijWDRbut4ZAA}
pwn.college{wEGC.-A2nfXkFaAA91B.TBEX8JkZWbxRstWW2MNPLsi7zaQ}
pwn.college{FPbFOJf05GWVuLwzRODLgzCW3HOC5gI9b8fmg63MSRWiaEo}
pwn.college{.wNxFEfHPoxwBNnMMKrp9C9vDVml8WLIxH4tPN4tFhovju6}
pwn.college{i.rJm.QT.RUMjizPyIO7AGF4.RmDX2r1zninwJOcopDl-EU}
pwn.college{YjHl0mTAbweZ1rODNrM399Yd5DEUv37qGFFmVL0R3Su5ivJ}
pwn.college{WsLyAVQYCQkd1s4IV3tpPkespps9RRWUpv6kapZcU.TRzWp}
pwn.college{MJJf-7Ho16m3ca9R-ZDRwGdmFT8Mjxw0pcITGdiWJB1wN5G}
pwn.college{6qoskzyqLi6ECOtChIxygtmFvApRLSt6budqQUUhAfzYciL}
pwn.college{eNAGYx7GRO7aFTQLfO5MOFO7NleOSmo9qXVPPatBE.HBNW3}
pwn.college{EEKeAW1QrRztdy7wa0FOnzJcLc1dHrpQm1GdFm81zghNiAX}
pwn.college{vKvs1viAEHyj92XBq32PSvdDCxoAze7HA4U4AdW5DuGH-D4}
pwn.college{7eMfWTsn6ykgCpUSztKbT5rztSPyiC2cWKiYMrGlYkpg.tY}
pwn.college{vzNsDg5RkX-YdD2IrgwWdGXK8kGHq4m5eUU5dlcb1ic8Ow1}
pwn.college{xcpm4TA82kwKhXmC0kwKY8oMRNPIjf5cr7hbi62Y.TWxCio}
pwn.college{bVdyXQw5ra-VLIngIZb2dF2AJzOF53CCAVOjBdRmugb6qqy}
pwn.college{pG1Jr-66iQa9ioimzSQUDnmYneAzpPNTWK4JSv5KiS7Yct9}
pwn.college{MjOs35v3Z3N.qHThAUCSJWf4TIfZuEYF9LnfhAQgpT7LGIo}
pwn.college{E77llW2fKDWMjRr5t0o0voT2y-N5hP0w4Jqre9ckApKmXz-}
pwn.college{f132.YHSg4CGY8heSXlKx273ou5eZ9xz8P9LB2IMrT8sQif}
pwn.college{.B8VRPPEapzXYjjD-1yadFR7VVTlStCStJA9bjlJCliCQNp}
pwn.college{qNC5bki8OVZYzJgsAWa.VglsFKFcaLlG2L9U1p0qj7sF994}
pwn.college{iqYFZtpkxP-bpgNJaYl3sj6j2mARvzLehfkAVq3YIVnzH3y}
pwn.college{WmR73Bk4l8VaukSJye4jkGLPkrsv3njbIjPTsXvzhfB-ah3}
pwn.college{4AuOerblQtOYNn4wa2l693omaC3xZbjo6G.YVW4a25O0Dja}
pwn.college{AMYudSJRYppfgAqIJnsxD7Zdy4iq-CjpM71OpQ5sMGQ8HB-}
pwn.college{BK3tiAJwYdWGB-bOnvhnPlkbv8nzsl-qqNvw8n4jEiyXb6B}
pwn.college{.y3m2amq2lk1oGS0vXw5dfI7klAjzt2LCpuNx7-xOXnYOmF}
pwn.college{nfURcyFrRCwqh0G9xkEu0CSMwSaE2vr.YFeM84kNmaTODUb}
pwn.college{xra0gQLpwZnxlC082UOPf2bnCPwLOx-Cs0EAz1-N7Ek7c8m}
pwn.college{cCoVjn1s9zxfLEAvQ2oDJ3ZV3OSl9xE0IVyQy7UmPud1OBs}
pwn.college{hvn-A4fxUbYFs4LSOnBXcraQz6SBY5lIAKb6-DZ1-LdFkGF}
pwn.college{rVGLm2Sf65RX6VXxiFHJaZDgiX.UmJyUnDy6mQpW3ot4m4W}
pwn.college{eCQ0fhkRSAkC9OC8zMlYR-.CGnDHumcFT.SQ05IQE.3VkuD}
pwn.college{8gM5nNi1NyjUFAQUid7Rt-UAt37jvSQYmIJbH5CBSlNPacx}
pwn.college{rjiGIV-eOYbOXP4ZsjjBIOIigegAf9EjZwwzoowkunNa6Lv}
pwn.college{bMwlNZEuMHSgs.If6Gg4BzyJwxP0gSBtiRGHL5vVYcOXxmM}
pwn.college{B6s3Zx3A0jgqFlAWRpAOCPQmJMhjHcwDI4MSox8.nCT869x}
pwn.college{a66KtNy0KKZYtSm7fsldbknFmdOVECS3go1eKyhDsJdIRhl}
pwn.college{om8hK28aEDcNMuUNzJXOMSIGm-giQ5bdgoZ.k.QDJi4hSoW}
pwn.college{S8twvCh1rKPixD7BjnpAq9T-2d2q0LDMzG589LWX9FNfsfk}
pwn.college{p3zWaG.r4f8zOTbHnMTK4GqNJJGGv9YJx5X-2n8VSqHGtmu}
pwn.college{sWYqD6YZCL9da7dXWyzI8e0E39SlkR7BuErtRU8dvbc5VqC}
pwn.college{8.NpVnHh7xxoZLo8tZtlpsSeJPcagwuSqk4e3-hgx5YoRbO}
pwn.college{oz5s9.jPibgbxQTwZ6c8hod4XIvt-pr7CwwmuYJ2v9ZxExZ}
pwn.college{aGMoS2symgZD.LVtZ3JPH8o0nnMAAqpi7lGNdEXv-rRpW4t}
pwn.college{eJcbcYi6Taq3saDeJp5zEZpXsizvte.BuydVEFnBTSA-iii}
pwn.college{bjtmbaBAc-9OGldZh3hKeZxVZIuGe.PPfdX3t5h9D50uZ24}
Sending the flag to /tmp/flag_fifo!
pwn.college{YA0wrBgs-39SIz5k-wQqodQiz7L.0FNzMDOxwyM3EzNzEzW}
```
## Incorrect tangents I went on
after killing the process i tried running /challenge/run but it just kept showing:  "Sending the flag to /tmp/flag_fifo!" hence i opened another terminal and tried catting but for some reason it was not working hence i used the & opertor to combine both commands.

## What I learned
I learned how to kill processes that interfere with your work.

## References 
None
