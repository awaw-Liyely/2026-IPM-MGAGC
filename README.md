# 2026-IPM-MGAGC

# 2026-TKDE-GBDH-FS
**The code  will be open-sourced upon the acceptance of this paper to ensure reproducibility.**

This is the code for the accepted paper:

**Authors:** Ye Li, Lei Yang, Binbin Sang\*, Guoyin Wang\*, **Senior Member, IEEE**, Shuyin Xia, **Senior Member, IEEE**, Weihua Xu, and Jianhang Yu

**Title:**  *An Efficient Feature Selection Method using the Granular-ball Divergence-based Fuzzy Rough Hypergraph*

 **IEEE Transactions on Knowledge and Data Engineering (TKDE).**



GBDH-FS.py is the main function file

If you have any questions, please connect liyely@126.com



Example Output on the **IA** dataset:

```txt
IA dataset training and testing started
Data shape: (3279, 1559)
Features: 1558, Samples: 3279
============================================================
Testing parameters: thita=0.1, min_sample=20
Completed: 1/90 (1.1%)
  Feature selection time: 35.4688s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9610 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=18
Completed: 2/90 (2.2%)
  Feature selection time: 36.1789s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9619 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=16
Completed: 3/90 (3.3%)
  Feature selection time: 62.3608s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9597 (+/- 0.0225)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=14
Completed: 4/90 (4.4%)
  Feature selection time: 1365.3687s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9558 (+/- 0.0224)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=12
Completed: 5/90 (5.6%)
  Feature selection time: 101.3261s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9570 (+/- 0.0243)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=10
Completed: 6/90 (6.7%)
  Feature selection time: 80.4642s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9558 (+/- 0.0211)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=8
Completed: 7/90 (7.8%)
  Feature selection time: 688.6611s
  Total edges: 104416, Reduced attributes: 57
  Remaining edges per round: [np.int64(62865), np.int64(36218), np.int64(21868), np.int64(15199), np.int64(11367), np.int64(9527), np.int64(5998), np.int64(5521), np.int64(3916), np.int64(3415), np.int64(2914), np.int64(2767), np.int64(2410), np.int64(2245), np.int64(1973), np.int64(1682), np.int64(1474), np.int64(1401), np.int64(1306), np.int64(1054), np.int64(903), np.int64(758), np.int64(624), np.int64(521), np.int64(478), np.int64(415), np.int64(378), np.int64(332), np.int64(247), np.int64(246), np.int64(229), np.int64(209), np.int64(177), np.int64(171), np.int64(166), np.int64(137), np.int64(123), np.int64(109), np.int64(97), np.int64(94), np.int64(59), np.int64(39), np.int64(36), np.int64(32), np.int64(28), np.int64(25), np.int64(22), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7334 (+/- 0.0690)
  NB  Accuracy: 0.8588 (+/- 0.2002)
  CR  Accuracy: 0.9567 (+/- 0.0227)
  SVC Accuracy: 0.9600 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=6
Completed: 8/90 (8.9%)
  Feature selection time: 82.5811s
  Total edges: 49572, Reduced attributes: 55
  Remaining edges per round: [np.int64(29737), np.int64(21156), np.int64(13534), np.int64(9699), np.int64(8075), np.int64(6466), np.int64(4038), np.int64(3430), np.int64(2824), np.int64(2695), np.int64(2370), np.int64(2069), np.int64(1912), np.int64(1763), np.int64(1526), np.int64(1282), np.int64(1109), np.int64(1023), np.int64(903), np.int64(854), np.int64(729), np.int64(688), np.int64(569), np.int64(456), np.int64(394), np.int64(364), np.int64(322), np.int64(278), np.int64(237), np.int64(205), np.int64(168), np.int64(131), np.int64(130), np.int64(123), np.int64(118), np.int64(107), np.int64(95), np.int64(81), np.int64(71), np.int64(61), np.int64(39), np.int64(23), np.int64(21), np.int64(19), np.int64(17), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7493 (+/- 0.0679)
  NB  Accuracy: 0.8800 (+/- 0.1484)
  CR  Accuracy: 0.9494 (+/- 0.0211)
  SVC Accuracy: 0.9597 (+/- 0.0283)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=4
Completed: 9/90 (10.0%)
  Feature selection time: 103.5565s
  Total edges: 56640, Reduced attributes: 62
  Remaining edges per round: [np.int64(33646), np.int64(23351), np.int64(14376), np.int64(10169), np.int64(8492), np.int64(6853), np.int64(4531), np.int64(3597), np.int64(3135), np.int64(2829), np.int64(2703), np.int64(2391), np.int64(2248), np.int64(1943), np.int64(1691), np.int64(1504), np.int64(1254), np.int64(1162), np.int64(1093), np.int64(947), np.int64(820), np.int64(703), np.int64(621), np.int64(527), np.int64(441), np.int64(400), np.int64(359), np.int64(298), np.int64(257), np.int64(218), np.int64(217), np.int64(210), np.int64(205), np.int64(188), np.int64(169), np.int64(147), np.int64(131), np.int64(115), np.int64(89), np.int64(73), np.int64(69), np.int64(47), np.int64(43), np.int64(39), np.int64(36), np.int64(29), np.int64(26), np.int64(25), np.int64(24), np.int64(20), np.int64(18), np.int64(16), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7468 (+/- 0.0690)
  NB  Accuracy: 0.3230 (+/- 0.0146)
  CR  Accuracy: 0.9521 (+/- 0.0230)
  SVC Accuracy: 0.9588 (+/- 0.0267)
------------------------------------------------------------
Testing parameters: thita=0.1, min_sample=2
Completed: 10/90 (11.1%)
  Feature selection time: 126.5528s
  Total edges: 61088, Reduced attributes: 86
  Remaining edges per round: [np.int64(35710), np.int64(24707), np.int64(15110), np.int64(10545), np.int64(7419), np.int64(5950), np.int64(4535), np.int64(3886), np.int64(3549), np.int64(2934), np.int64(2808), np.int64(2484), np.int64(2340), np.int64(1983), np.int64(1739), np.int64(1491), np.int64(1401), np.int64(1345), np.int64(1170), np.int64(1048), np.int64(919), np.int64(793), np.int64(677), np.int64(599), np.int64(513), np.int64(469), np.int64(420), np.int64(360), np.int64(316), np.int64(280), np.int64(240), np.int64(239), np.int64(233), np.int64(226), np.int64(211), np.int64(195), np.int64(174), np.int64(158), np.int64(123), np.int64(107), np.int64(96), np.int64(92), np.int64(73), np.int64(70), np.int64(69), np.int64(68), np.int64(66), np.int64(64), np.int64(63), np.int64(59), np.int64(57), np.int64(50), np.int64(48), np.int64(45), np.int64(43), np.int64(42), np.int64(41), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(28), np.int64(25), np.int64(23), np.int64(21), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(9), np.int64(8), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7700 (+/- 0.0620)
  NB  Accuracy: 0.2910 (+/- 0.0321)
  CR  Accuracy: 0.9494 (+/- 0.0213)
  SVC Accuracy: 0.9588 (+/- 0.0280)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=20
Completed: 11/90 (12.2%)
  Feature selection time: 36.1138s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9607 (+/- 0.0266)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=18
Completed: 12/90 (13.3%)
  Feature selection time: 35.9676s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9616 (+/- 0.0247)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=16
Completed: 13/90 (14.4%)
  Feature selection time: 62.5258s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9588 (+/- 0.0224)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=14
Completed: 14/90 (15.6%)
  Feature selection time: 1371.1222s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9558 (+/- 0.0224)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=12
Completed: 15/90 (16.7%)
  Feature selection time: 101.3267s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9582 (+/- 0.0250)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=10
Completed: 16/90 (17.8%)
  Feature selection time: 80.9250s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9555 (+/- 0.0201)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=8
Completed: 17/90 (18.9%)
  Feature selection time: 687.9358s
  Total edges: 104416, Reduced attributes: 57
  Remaining edges per round: [np.int64(62865), np.int64(36218), np.int64(21868), np.int64(15199), np.int64(11367), np.int64(9527), np.int64(5998), np.int64(5521), np.int64(3916), np.int64(3415), np.int64(2914), np.int64(2767), np.int64(2410), np.int64(2245), np.int64(1973), np.int64(1682), np.int64(1474), np.int64(1401), np.int64(1306), np.int64(1054), np.int64(903), np.int64(758), np.int64(624), np.int64(521), np.int64(478), np.int64(415), np.int64(378), np.int64(332), np.int64(247), np.int64(246), np.int64(229), np.int64(209), np.int64(177), np.int64(171), np.int64(166), np.int64(137), np.int64(123), np.int64(109), np.int64(97), np.int64(94), np.int64(59), np.int64(39), np.int64(36), np.int64(32), np.int64(28), np.int64(25), np.int64(22), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7334 (+/- 0.0690)
  NB  Accuracy: 0.8588 (+/- 0.2002)
  CR  Accuracy: 0.9561 (+/- 0.0246)
  SVC Accuracy: 0.9600 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=6
Completed: 18/90 (20.0%)
  Feature selection time: 82.4910s
  Total edges: 49572, Reduced attributes: 55
  Remaining edges per round: [np.int64(29737), np.int64(21156), np.int64(13534), np.int64(9699), np.int64(8075), np.int64(6466), np.int64(4038), np.int64(3430), np.int64(2824), np.int64(2695), np.int64(2370), np.int64(2069), np.int64(1912), np.int64(1763), np.int64(1526), np.int64(1282), np.int64(1109), np.int64(1023), np.int64(903), np.int64(854), np.int64(729), np.int64(688), np.int64(569), np.int64(456), np.int64(394), np.int64(364), np.int64(322), np.int64(278), np.int64(237), np.int64(205), np.int64(168), np.int64(131), np.int64(130), np.int64(123), np.int64(118), np.int64(107), np.int64(95), np.int64(81), np.int64(71), np.int64(61), np.int64(39), np.int64(23), np.int64(21), np.int64(19), np.int64(17), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7493 (+/- 0.0679)
  NB  Accuracy: 0.8800 (+/- 0.1484)
  CR  Accuracy: 0.9485 (+/- 0.0232)
  SVC Accuracy: 0.9597 (+/- 0.0283)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=4
Completed: 19/90 (21.1%)
  Feature selection time: 104.0319s
  Total edges: 56640, Reduced attributes: 62
  Remaining edges per round: [np.int64(33646), np.int64(23351), np.int64(14376), np.int64(10169), np.int64(8492), np.int64(6853), np.int64(4531), np.int64(3597), np.int64(3135), np.int64(2829), np.int64(2703), np.int64(2391), np.int64(2248), np.int64(1943), np.int64(1691), np.int64(1504), np.int64(1254), np.int64(1162), np.int64(1093), np.int64(947), np.int64(820), np.int64(703), np.int64(621), np.int64(527), np.int64(441), np.int64(400), np.int64(359), np.int64(298), np.int64(257), np.int64(218), np.int64(217), np.int64(210), np.int64(205), np.int64(188), np.int64(169), np.int64(147), np.int64(131), np.int64(115), np.int64(89), np.int64(73), np.int64(69), np.int64(47), np.int64(43), np.int64(39), np.int64(36), np.int64(29), np.int64(26), np.int64(25), np.int64(24), np.int64(20), np.int64(18), np.int64(16), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7468 (+/- 0.0690)
  NB  Accuracy: 0.3230 (+/- 0.0146)
  CR  Accuracy: 0.9512 (+/- 0.0227)
  SVC Accuracy: 0.9588 (+/- 0.0267)
------------------------------------------------------------
Testing parameters: thita=0.2, min_sample=2
Completed: 20/90 (22.2%)
  Feature selection time: 126.8734s
  Total edges: 61088, Reduced attributes: 86
  Remaining edges per round: [np.int64(35710), np.int64(24707), np.int64(15110), np.int64(10545), np.int64(7419), np.int64(5950), np.int64(4535), np.int64(3886), np.int64(3549), np.int64(2934), np.int64(2808), np.int64(2484), np.int64(2340), np.int64(1983), np.int64(1739), np.int64(1491), np.int64(1401), np.int64(1345), np.int64(1170), np.int64(1048), np.int64(919), np.int64(793), np.int64(677), np.int64(599), np.int64(513), np.int64(469), np.int64(420), np.int64(360), np.int64(316), np.int64(280), np.int64(240), np.int64(239), np.int64(233), np.int64(226), np.int64(211), np.int64(195), np.int64(174), np.int64(158), np.int64(123), np.int64(107), np.int64(96), np.int64(92), np.int64(73), np.int64(70), np.int64(69), np.int64(68), np.int64(66), np.int64(64), np.int64(63), np.int64(59), np.int64(57), np.int64(50), np.int64(48), np.int64(45), np.int64(43), np.int64(42), np.int64(41), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(28), np.int64(25), np.int64(23), np.int64(21), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(9), np.int64(8), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7700 (+/- 0.0620)
  NB  Accuracy: 0.2910 (+/- 0.0321)
  CR  Accuracy: 0.9491 (+/- 0.0214)
  SVC Accuracy: 0.9588 (+/- 0.0280)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=20
Completed: 21/90 (23.3%)
  Feature selection time: 35.8065s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9607 (+/- 0.0248)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=18
Completed: 22/90 (24.4%)
  Feature selection time: 36.5600s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9619 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=16
Completed: 23/90 (25.6%)
  Feature selection time: 62.2405s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9591 (+/- 0.0234)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=14
Completed: 24/90 (26.7%)
  Feature selection time: 1359.4073s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9561 (+/- 0.0225)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=12
Completed: 25/90 (27.8%)
  Feature selection time: 100.5803s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9594 (+/- 0.0257)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=10
Completed: 26/90 (28.9%)
  Feature selection time: 80.2197s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9552 (+/- 0.0206)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=8
Completed: 27/90 (30.0%)
  Feature selection time: 693.4006s
  Total edges: 104416, Reduced attributes: 57
  Remaining edges per round: [np.int64(62865), np.int64(36218), np.int64(21868), np.int64(15199), np.int64(11367), np.int64(9527), np.int64(5998), np.int64(5521), np.int64(3916), np.int64(3415), np.int64(2914), np.int64(2767), np.int64(2410), np.int64(2245), np.int64(1973), np.int64(1682), np.int64(1474), np.int64(1401), np.int64(1306), np.int64(1054), np.int64(903), np.int64(758), np.int64(624), np.int64(521), np.int64(478), np.int64(415), np.int64(378), np.int64(332), np.int64(247), np.int64(246), np.int64(229), np.int64(209), np.int64(177), np.int64(171), np.int64(166), np.int64(137), np.int64(123), np.int64(109), np.int64(97), np.int64(94), np.int64(59), np.int64(39), np.int64(36), np.int64(32), np.int64(28), np.int64(25), np.int64(22), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7334 (+/- 0.0690)
  NB  Accuracy: 0.8588 (+/- 0.2002)
  CR  Accuracy: 0.9567 (+/- 0.0236)
  SVC Accuracy: 0.9600 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=6
Completed: 28/90 (31.1%)
  Feature selection time: 82.7782s
  Total edges: 49572, Reduced attributes: 55
  Remaining edges per round: [np.int64(29737), np.int64(21156), np.int64(13534), np.int64(9699), np.int64(8075), np.int64(6466), np.int64(4038), np.int64(3430), np.int64(2824), np.int64(2695), np.int64(2370), np.int64(2069), np.int64(1912), np.int64(1763), np.int64(1526), np.int64(1282), np.int64(1109), np.int64(1023), np.int64(903), np.int64(854), np.int64(729), np.int64(688), np.int64(569), np.int64(456), np.int64(394), np.int64(364), np.int64(322), np.int64(278), np.int64(237), np.int64(205), np.int64(168), np.int64(131), np.int64(130), np.int64(123), np.int64(118), np.int64(107), np.int64(95), np.int64(81), np.int64(71), np.int64(61), np.int64(39), np.int64(23), np.int64(21), np.int64(19), np.int64(17), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7493 (+/- 0.0679)
  NB  Accuracy: 0.8800 (+/- 0.1484)
  CR  Accuracy: 0.9494 (+/- 0.0211)
  SVC Accuracy: 0.9597 (+/- 0.0283)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=4
Completed: 29/90 (32.2%)
  Feature selection time: 104.5469s
  Total edges: 56640, Reduced attributes: 62
  Remaining edges per round: [np.int64(33646), np.int64(23351), np.int64(14376), np.int64(10169), np.int64(8492), np.int64(6853), np.int64(4531), np.int64(3597), np.int64(3135), np.int64(2829), np.int64(2703), np.int64(2391), np.int64(2248), np.int64(1943), np.int64(1691), np.int64(1504), np.int64(1254), np.int64(1162), np.int64(1093), np.int64(947), np.int64(820), np.int64(703), np.int64(621), np.int64(527), np.int64(441), np.int64(400), np.int64(359), np.int64(298), np.int64(257), np.int64(218), np.int64(217), np.int64(210), np.int64(205), np.int64(188), np.int64(169), np.int64(147), np.int64(131), np.int64(115), np.int64(89), np.int64(73), np.int64(69), np.int64(47), np.int64(43), np.int64(39), np.int64(36), np.int64(29), np.int64(26), np.int64(25), np.int64(24), np.int64(20), np.int64(18), np.int64(16), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7468 (+/- 0.0690)
  NB  Accuracy: 0.3230 (+/- 0.0146)
  CR  Accuracy: 0.9515 (+/- 0.0224)
  SVC Accuracy: 0.9588 (+/- 0.0267)
------------------------------------------------------------
Testing parameters: thita=0.3, min_sample=2
Completed: 30/90 (33.3%)
  Feature selection time: 127.6125s
  Total edges: 61088, Reduced attributes: 87
  Remaining edges per round: [np.int64(35764), np.int64(24738), np.int64(15136), np.int64(10564), np.int64(7436), np.int64(5963), np.int64(4543), np.int64(3894), np.int64(3556), np.int64(2939), np.int64(2812), np.int64(2488), np.int64(2343), np.int64(1986), np.int64(1742), np.int64(1494), np.int64(1404), np.int64(1348), np.int64(1173), np.int64(1051), np.int64(922), np.int64(796), np.int64(680), np.int64(602), np.int64(515), np.int64(471), np.int64(421), np.int64(361), np.int64(317), np.int64(281), np.int64(241), np.int64(240), np.int64(234), np.int64(227), np.int64(212), np.int64(196), np.int64(175), np.int64(159), np.int64(124), np.int64(108), np.int64(97), np.int64(93), np.int64(74), np.int64(71), np.int64(70), np.int64(69), np.int64(67), np.int64(65), np.int64(64), np.int64(60), np.int64(58), np.int64(51), np.int64(49), np.int64(46), np.int64(44), np.int64(43), np.int64(42), np.int64(41), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(28), np.int64(25), np.int64(23), np.int64(21), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(9), np.int64(8), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9552 (+/- 0.0231)
  NB  Accuracy: 0.2913 (+/- 0.0326)
  CR  Accuracy: 0.9561 (+/- 0.0230)
  SVC Accuracy: 0.9588 (+/- 0.0280)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=20
Completed: 31/90 (34.4%)
  Feature selection time: 36.1658s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9610 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=18
Completed: 32/90 (35.6%)
  Feature selection time: 35.7762s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9619 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=16
Completed: 33/90 (36.7%)
  Feature selection time: 61.4127s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9585 (+/- 0.0232)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=14
Completed: 34/90 (37.8%)
  Feature selection time: 1365.8578s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9558 (+/- 0.0224)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=12
Completed: 35/90 (38.9%)
  Feature selection time: 100.9536s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9567 (+/- 0.0253)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=10
Completed: 36/90 (40.0%)
  Feature selection time: 80.6110s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9567 (+/- 0.0207)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=8
Completed: 37/90 (41.1%)
  Feature selection time: 688.2709s
  Total edges: 104416, Reduced attributes: 57
  Remaining edges per round: [np.int64(62865), np.int64(36218), np.int64(21868), np.int64(15199), np.int64(11367), np.int64(9527), np.int64(5998), np.int64(5521), np.int64(3916), np.int64(3415), np.int64(2914), np.int64(2767), np.int64(2410), np.int64(2245), np.int64(1973), np.int64(1682), np.int64(1474), np.int64(1401), np.int64(1306), np.int64(1054), np.int64(903), np.int64(758), np.int64(624), np.int64(521), np.int64(478), np.int64(415), np.int64(378), np.int64(332), np.int64(247), np.int64(246), np.int64(229), np.int64(209), np.int64(177), np.int64(171), np.int64(166), np.int64(137), np.int64(123), np.int64(109), np.int64(97), np.int64(94), np.int64(59), np.int64(39), np.int64(36), np.int64(32), np.int64(28), np.int64(25), np.int64(22), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7334 (+/- 0.0690)
  NB  Accuracy: 0.8588 (+/- 0.2002)
  CR  Accuracy: 0.9561 (+/- 0.0232)
  SVC Accuracy: 0.9600 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=6
Completed: 38/90 (42.2%)
  Feature selection time: 82.9240s
  Total edges: 49572, Reduced attributes: 55
  Remaining edges per round: [np.int64(29737), np.int64(21156), np.int64(13534), np.int64(9699), np.int64(8075), np.int64(6466), np.int64(4038), np.int64(3430), np.int64(2824), np.int64(2695), np.int64(2370), np.int64(2069), np.int64(1912), np.int64(1763), np.int64(1526), np.int64(1282), np.int64(1109), np.int64(1023), np.int64(903), np.int64(854), np.int64(729), np.int64(688), np.int64(569), np.int64(456), np.int64(394), np.int64(364), np.int64(322), np.int64(278), np.int64(237), np.int64(205), np.int64(168), np.int64(131), np.int64(130), np.int64(123), np.int64(118), np.int64(107), np.int64(95), np.int64(81), np.int64(71), np.int64(61), np.int64(39), np.int64(23), np.int64(21), np.int64(19), np.int64(17), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7493 (+/- 0.0679)
  NB  Accuracy: 0.8800 (+/- 0.1484)
  CR  Accuracy: 0.9494 (+/- 0.0220)
  SVC Accuracy: 0.9597 (+/- 0.0283)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=4
Completed: 39/90 (43.3%)
  Feature selection time: 104.7305s
  Total edges: 56640, Reduced attributes: 62
  Remaining edges per round: [np.int64(33646), np.int64(23351), np.int64(14376), np.int64(10169), np.int64(8492), np.int64(6853), np.int64(4531), np.int64(3597), np.int64(3135), np.int64(2829), np.int64(2703), np.int64(2391), np.int64(2248), np.int64(1943), np.int64(1691), np.int64(1504), np.int64(1254), np.int64(1162), np.int64(1093), np.int64(947), np.int64(820), np.int64(703), np.int64(621), np.int64(527), np.int64(441), np.int64(400), np.int64(359), np.int64(298), np.int64(257), np.int64(218), np.int64(217), np.int64(210), np.int64(205), np.int64(188), np.int64(169), np.int64(147), np.int64(131), np.int64(115), np.int64(89), np.int64(73), np.int64(69), np.int64(47), np.int64(43), np.int64(39), np.int64(36), np.int64(29), np.int64(26), np.int64(25), np.int64(24), np.int64(20), np.int64(18), np.int64(16), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.7468 (+/- 0.0690)
  NB  Accuracy: 0.3230 (+/- 0.0146)
  CR  Accuracy: 0.9521 (+/- 0.0237)
  SVC Accuracy: 0.9588 (+/- 0.0267)
------------------------------------------------------------
Testing parameters: thita=0.4, min_sample=2
Completed: 40/90 (44.4%)
  Feature selection time: 127.5956s
  Total edges: 61088, Reduced attributes: 87
  Remaining edges per round: [np.int64(35764), np.int64(24738), np.int64(15136), np.int64(10564), np.int64(7436), np.int64(5963), np.int64(4543), np.int64(3894), np.int64(3556), np.int64(2939), np.int64(2812), np.int64(2488), np.int64(2343), np.int64(1986), np.int64(1742), np.int64(1494), np.int64(1404), np.int64(1348), np.int64(1173), np.int64(1051), np.int64(922), np.int64(796), np.int64(680), np.int64(602), np.int64(515), np.int64(471), np.int64(421), np.int64(361), np.int64(317), np.int64(281), np.int64(241), np.int64(240), np.int64(234), np.int64(227), np.int64(212), np.int64(196), np.int64(175), np.int64(159), np.int64(124), np.int64(108), np.int64(97), np.int64(93), np.int64(74), np.int64(71), np.int64(70), np.int64(69), np.int64(67), np.int64(65), np.int64(64), np.int64(60), np.int64(58), np.int64(51), np.int64(49), np.int64(46), np.int64(44), np.int64(43), np.int64(42), np.int64(41), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(28), np.int64(25), np.int64(23), np.int64(21), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(9), np.int64(8), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9552 (+/- 0.0231)
  NB  Accuracy: 0.2913 (+/- 0.0326)
  CR  Accuracy: 0.9570 (+/- 0.0242)
  SVC Accuracy: 0.9588 (+/- 0.0280)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=20
Completed: 41/90 (45.6%)
  Feature selection time: 36.0523s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9613 (+/- 0.0252)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=18
Completed: 42/90 (46.7%)
  Feature selection time: 36.1363s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9616 (+/- 0.0247)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=16
Completed: 43/90 (47.8%)
  Feature selection time: 61.0523s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9600 (+/- 0.0216)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=14
Completed: 44/90 (48.9%)
  Feature selection time: 1364.6403s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9555 (+/- 0.0221)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=12
Completed: 45/90 (50.0%)
  Feature selection time: 100.6916s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9576 (+/- 0.0247)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=10
Completed: 46/90 (51.1%)
  Feature selection time: 79.8787s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9552 (+/- 0.0208)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=8
Completed: 47/90 (52.2%)
  Feature selection time: 689.1923s
  Total edges: 104416, Reduced attributes: 58
  Remaining edges per round: [np.int64(63224), np.int64(36430), np.int64(22064), np.int64(15383), np.int64(11536), np.int64(9694), np.int64(6135), np.int64(5656), np.int64(4048), np.int64(3538), np.int64(3035), np.int64(2887), np.int64(2525), np.int64(2357), np.int64(2085), np.int64(1792), np.int64(1642), np.int64(1436), np.int64(1364), np.int64(1272), np.int64(1020), np.int64(871), np.int64(728), np.int64(595), np.int64(493), np.int64(451), np.int64(389), np.int64(353), np.int64(308), np.int64(225), np.int64(224), np.int64(207), np.int64(187), np.int64(155), np.int64(149), np.int64(145), np.int64(118), np.int64(104), np.int64(90), np.int64(78), np.int64(75), np.int64(40), np.int64(37), np.int64(33), np.int64(29), np.int64(26), np.int64(23), np.int64(16), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8902 (+/- 0.0327)
  NB  Accuracy: 0.8619 (+/- 0.2037)
  CR  Accuracy: 0.9527 (+/- 0.0173)
  SVC Accuracy: 0.9600 (+/- 0.0269)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=6
Completed: 48/90 (53.3%)
  Feature selection time: 82.5817s
  Total edges: 49572, Reduced attributes: 56
  Remaining edges per round: [np.int64(30181), np.int64(18890), np.int64(13814), np.int64(9959), np.int64(8322), np.int64(6703), np.int64(4238), np.int64(3785), np.int64(3192), np.int64(2602), np.int64(2472), np.int64(2156), np.int64(1995), np.int64(1843), np.int64(1593), np.int64(1411), np.int64(1160), np.int64(1035), np.int64(949), np.int64(821), np.int64(771), np.int64(729), np.int64(636), np.int64(519), np.int64(408), np.int64(347), np.int64(317), np.int64(272), np.int64(231), np.int64(199), np.int64(161), np.int64(123), np.int64(122), np.int64(115), np.int64(111), np.int64(95), np.int64(83), np.int64(69), np.int64(58), np.int64(47), np.int64(43), np.int64(27), np.int64(25), np.int64(23), np.int64(21), np.int64(12), np.int64(11), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8932 (+/- 0.0302)
  NB  Accuracy: 0.8791 (+/- 0.1520)
  CR  Accuracy: 0.9518 (+/- 0.0215)
  SVC Accuracy: 0.9600 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=4
Completed: 49/90 (54.4%)
  Feature selection time: 103.9721s
  Total edges: 56640, Reduced attributes: 62
  Remaining edges per round: [np.int64(34103), np.int64(23762), np.int64(14655), np.int64(10428), np.int64(8741), np.int64(7085), np.int64(4726), np.int64(3784), np.int64(3364), np.int64(2915), np.int64(2611), np.int64(2484), np.int64(2181), np.int64(2038), np.int64(1889), np.int64(1654), np.int64(1469), np.int64(1221), np.int64(1132), np.int64(1064), np.int64(918), np.int64(796), np.int64(678), np.int64(595), np.int64(500), np.int64(412), np.int64(370), np.int64(329), np.int64(267), np.int64(226), np.int64(187), np.int64(186), np.int64(179), np.int64(175), np.int64(158), np.int64(139), np.int64(117), np.int64(102), np.int64(86), np.int64(70), np.int64(50), np.int64(46), np.int64(42), np.int64(38), np.int64(36), np.int64(33), np.int64(26), np.int64(25), np.int64(24), np.int64(20), np.int64(18), np.int64(16), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8945 (+/- 0.0294)
  NB  Accuracy: 0.3245 (+/- 0.0169)
  CR  Accuracy: 0.9536 (+/- 0.0227)
  SVC Accuracy: 0.9597 (+/- 0.0267)
------------------------------------------------------------
Testing parameters: thita=0.5, min_sample=2
Completed: 50/90 (55.6%)
  Feature selection time: 126.2018s
  Total edges: 61088, Reduced attributes: 86
  Remaining edges per round: [np.int64(36275), np.int64(25176), np.int64(15429), np.int64(10833), np.int64(7666), np.int64(6180), np.int64(4745), np.int64(4084), np.int64(3742), np.int64(3314), np.int64(2713), np.int64(2585), np.int64(2271), np.int64(2126), np.int64(1974), np.int64(1729), np.int64(1540), np.int64(1286), np.int64(1196), np.int64(1139), np.int64(993), np.int64(863), np.int64(743), np.int64(659), np.int64(565), np.int64(475), np.int64(438), np.int64(396), np.int64(345), np.int64(287), np.int64(249), np.int64(248), np.int64(240), np.int64(235), np.int64(215), np.int64(195), np.int64(172), np.int64(153), np.int64(121), np.int64(108), np.int64(92), np.int64(83), np.int64(79), np.int64(77), np.int64(74), np.int64(70), np.int64(69), np.int64(68), np.int64(64), np.int64(63), np.int64(59), np.int64(55), np.int64(53), np.int64(47), np.int64(45), np.int64(42), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(30), np.int64(29), np.int64(28), np.int64(24), np.int64(23), np.int64(21), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(8), np.int64(7), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9530 (+/- 0.0244)
  NB  Accuracy: 0.2907 (+/- 0.0319)
  CR  Accuracy: 0.9597 (+/- 0.0231)
  SVC Accuracy: 0.9603 (+/- 0.0261)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=20
Completed: 51/90 (56.7%)
  Feature selection time: 36.1613s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9607 (+/- 0.0248)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=18
Completed: 52/90 (57.8%)
  Feature selection time: 36.2868s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9619 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=16
Completed: 53/90 (58.9%)
  Feature selection time: 62.5463s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9607 (+/- 0.0219)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=14
Completed: 54/90 (60.0%)
  Feature selection time: 1365.5940s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9558 (+/- 0.0228)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=12
Completed: 55/90 (61.1%)
  Feature selection time: 99.8452s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9582 (+/- 0.0243)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=10
Completed: 56/90 (62.2%)
  Feature selection time: 80.6302s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9552 (+/- 0.0201)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=8
Completed: 57/90 (63.3%)
  Feature selection time: 691.1763s
  Total edges: 104416, Reduced attributes: 58
  Remaining edges per round: [np.int64(63224), np.int64(36430), np.int64(22064), np.int64(15383), np.int64(11536), np.int64(9694), np.int64(6135), np.int64(5656), np.int64(4048), np.int64(3538), np.int64(3035), np.int64(2887), np.int64(2525), np.int64(2357), np.int64(2085), np.int64(1792), np.int64(1642), np.int64(1436), np.int64(1364), np.int64(1272), np.int64(1020), np.int64(871), np.int64(728), np.int64(595), np.int64(493), np.int64(451), np.int64(389), np.int64(353), np.int64(308), np.int64(225), np.int64(224), np.int64(207), np.int64(187), np.int64(155), np.int64(149), np.int64(145), np.int64(118), np.int64(104), np.int64(90), np.int64(78), np.int64(75), np.int64(40), np.int64(37), np.int64(33), np.int64(29), np.int64(26), np.int64(23), np.int64(16), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8902 (+/- 0.0327)
  NB  Accuracy: 0.8619 (+/- 0.2037)
  CR  Accuracy: 0.9536 (+/- 0.0181)
  SVC Accuracy: 0.9600 (+/- 0.0269)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=6
Completed: 58/90 (64.4%)
  Feature selection time: 83.4725s
  Total edges: 49572, Reduced attributes: 56
  Remaining edges per round: [np.int64(30181), np.int64(18890), np.int64(13814), np.int64(9959), np.int64(8322), np.int64(6703), np.int64(4238), np.int64(3785), np.int64(3192), np.int64(2602), np.int64(2472), np.int64(2156), np.int64(1995), np.int64(1843), np.int64(1593), np.int64(1411), np.int64(1160), np.int64(1035), np.int64(949), np.int64(821), np.int64(771), np.int64(729), np.int64(636), np.int64(519), np.int64(408), np.int64(347), np.int64(317), np.int64(272), np.int64(231), np.int64(199), np.int64(161), np.int64(123), np.int64(122), np.int64(115), np.int64(111), np.int64(95), np.int64(83), np.int64(69), np.int64(58), np.int64(47), np.int64(43), np.int64(27), np.int64(25), np.int64(23), np.int64(21), np.int64(12), np.int64(11), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8932 (+/- 0.0302)
  NB  Accuracy: 0.8791 (+/- 0.1520)
  CR  Accuracy: 0.9512 (+/- 0.0219)
  SVC Accuracy: 0.9600 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=4
Completed: 59/90 (65.6%)
  Feature selection time: 104.6039s
  Total edges: 56640, Reduced attributes: 62
  Remaining edges per round: [np.int64(34103), np.int64(23762), np.int64(14655), np.int64(10428), np.int64(8741), np.int64(7085), np.int64(4726), np.int64(3784), np.int64(3364), np.int64(2915), np.int64(2611), np.int64(2484), np.int64(2181), np.int64(2038), np.int64(1889), np.int64(1654), np.int64(1469), np.int64(1221), np.int64(1132), np.int64(1064), np.int64(918), np.int64(796), np.int64(678), np.int64(595), np.int64(500), np.int64(412), np.int64(370), np.int64(329), np.int64(267), np.int64(226), np.int64(187), np.int64(186), np.int64(179), np.int64(175), np.int64(158), np.int64(139), np.int64(117), np.int64(102), np.int64(86), np.int64(70), np.int64(50), np.int64(46), np.int64(42), np.int64(38), np.int64(36), np.int64(33), np.int64(26), np.int64(25), np.int64(24), np.int64(20), np.int64(18), np.int64(16), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8945 (+/- 0.0294)
  NB  Accuracy: 0.3245 (+/- 0.0169)
  CR  Accuracy: 0.9518 (+/- 0.0202)
  SVC Accuracy: 0.9597 (+/- 0.0267)
------------------------------------------------------------
Testing parameters: thita=0.6, min_sample=2
Completed: 60/90 (66.7%)
  Feature selection time: 128.0946s
  Total edges: 61088, Reduced attributes: 86
  Remaining edges per round: [np.int64(36303), np.int64(25189), np.int64(15441), np.int64(10842), np.int64(7674), np.int64(6185), np.int64(4747), np.int64(4086), np.int64(3743), np.int64(3112), np.int64(2713), np.int64(2585), np.int64(2271), np.int64(2126), np.int64(1974), np.int64(1729), np.int64(1540), np.int64(1286), np.int64(1196), np.int64(1139), np.int64(993), np.int64(863), np.int64(743), np.int64(659), np.int64(565), np.int64(475), np.int64(438), np.int64(396), np.int64(345), np.int64(287), np.int64(249), np.int64(248), np.int64(240), np.int64(235), np.int64(215), np.int64(195), np.int64(172), np.int64(153), np.int64(121), np.int64(108), np.int64(92), np.int64(83), np.int64(79), np.int64(77), np.int64(74), np.int64(70), np.int64(69), np.int64(68), np.int64(64), np.int64(63), np.int64(59), np.int64(55), np.int64(53), np.int64(47), np.int64(45), np.int64(42), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(30), np.int64(29), np.int64(28), np.int64(24), np.int64(23), np.int64(21), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(8), np.int64(7), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9530 (+/- 0.0244)
  NB  Accuracy: 0.2907 (+/- 0.0319)
  CR  Accuracy: 0.9585 (+/- 0.0232)
  SVC Accuracy: 0.9603 (+/- 0.0261)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=20
Completed: 61/90 (67.8%)
  Feature selection time: 36.2287s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9610 (+/- 0.0249)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=18
Completed: 62/90 (68.9%)
  Feature selection time: 36.6137s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9619 (+/- 0.0250)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=16
Completed: 63/90 (70.0%)
  Feature selection time: 62.5045s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9591 (+/- 0.0221)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=14
Completed: 64/90 (71.1%)
  Feature selection time: 1359.7672s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9558 (+/- 0.0226)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=12
Completed: 65/90 (72.2%)
  Feature selection time: 100.4630s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9573 (+/- 0.0246)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=10
Completed: 66/90 (73.3%)
  Feature selection time: 80.4747s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9567 (+/- 0.0216)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=8
Completed: 67/90 (74.4%)
  Feature selection time: 691.0988s
  Total edges: 104416, Reduced attributes: 58
  Remaining edges per round: [np.int64(63224), np.int64(36430), np.int64(22064), np.int64(15383), np.int64(11536), np.int64(9694), np.int64(6135), np.int64(5656), np.int64(4048), np.int64(3538), np.int64(3035), np.int64(2887), np.int64(2525), np.int64(2357), np.int64(2085), np.int64(1792), np.int64(1642), np.int64(1436), np.int64(1364), np.int64(1272), np.int64(1020), np.int64(871), np.int64(728), np.int64(595), np.int64(493), np.int64(451), np.int64(389), np.int64(353), np.int64(308), np.int64(225), np.int64(224), np.int64(207), np.int64(187), np.int64(155), np.int64(149), np.int64(145), np.int64(118), np.int64(104), np.int64(90), np.int64(78), np.int64(75), np.int64(40), np.int64(37), np.int64(33), np.int64(29), np.int64(26), np.int64(23), np.int64(16), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8902 (+/- 0.0327)
  NB  Accuracy: 0.8619 (+/- 0.2037)
  CR  Accuracy: 0.9524 (+/- 0.0186)
  SVC Accuracy: 0.9600 (+/- 0.0269)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=6
Completed: 68/90 (75.6%)
  Feature selection time: 82.7861s
  Total edges: 49572, Reduced attributes: 57
  Remaining edges per round: [np.int64(30395), np.int64(19042), np.int64(13950), np.int64(10087), np.int64(7854), np.int64(6517), np.int64(4286), np.int64(3469), np.int64(3045), np.int64(2607), np.int64(2477), np.int64(2161), np.int64(2000), np.int64(1848), np.int64(1598), np.int64(1416), np.int64(1165), np.int64(1040), np.int64(954), np.int64(826), np.int64(776), np.int64(734), np.int64(641), np.int64(524), np.int64(413), np.int64(352), np.int64(322), np.int64(277), np.int64(236), np.int64(204), np.int64(166), np.int64(128), np.int64(127), np.int64(120), np.int64(116), np.int64(100), np.int64(88), np.int64(74), np.int64(63), np.int64(52), np.int64(44), np.int64(28), np.int64(24), np.int64(22), np.int64(20), np.int64(18), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9536 (+/- 0.0252)
  NB  Accuracy: 0.8822 (+/- 0.1419)
  CR  Accuracy: 0.9570 (+/- 0.0213)
  SVC Accuracy: 0.9600 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=4
Completed: 69/90 (76.7%)
  Feature selection time: 104.3911s
  Total edges: 56640, Reduced attributes: 65
  Remaining edges per round: [np.int64(34517), np.int64(24134), np.int64(14905), np.int64(10664), np.int64(8573), np.int64(7194), np.int64(4819), np.int64(3874), np.int64(3454), np.int64(2817), np.int64(2538), np.int64(2413), np.int64(2101), np.int64(1822), np.int64(1689), np.int64(1552), np.int64(1381), np.int64(1147), np.int64(1065), np.int64(999), np.int64(898), np.int64(784), np.int64(693), np.int64(583), np.int64(486), np.int64(424), np.int64(382), np.int64(341), np.int64(278), np.int64(271), np.int64(230), np.int64(191), np.int64(190), np.int64(183), np.int64(179), np.int64(162), np.int64(143), np.int64(121), np.int64(106), np.int64(90), np.int64(80), np.int64(66), np.int64(46), np.int64(41), np.int64(37), np.int64(36), np.int64(33), np.int64(26), np.int64(25), np.int64(24), np.int64(23), np.int64(21), np.int64(20), np.int64(17), np.int64(16), np.int64(14), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9555 (+/- 0.0234)
  NB  Accuracy: 0.3303 (+/- 0.0198)
  CR  Accuracy: 0.9558 (+/- 0.0227)
  SVC Accuracy: 0.9594 (+/- 0.0272)
------------------------------------------------------------
Testing parameters: thita=0.7, min_sample=2
Completed: 70/90 (77.8%)
  Feature selection time: 127.0427s
  Total edges: 61088, Reduced attributes: 89
  Remaining edges per round: [np.int64(36822), np.int64(25620), np.int64(15719), np.int64(11099), np.int64(7896), np.int64(6395), np.int64(4943), np.int64(4020), np.int64(3513), np.int64(3197), np.int64(2797), np.int64(2311), np.int64(2191), np.int64(1902), np.int64(1766), np.int64(1626), np.int64(1446), np.int64(1206), np.int64(1124), np.int64(1069), np.int64(966), np.int64(848), np.int64(757), np.int64(645), np.int64(576), np.int64(486), np.int64(449), np.int64(407), np.int64(400), np.int64(349), np.int64(290), np.int64(252), np.int64(251), np.int64(243), np.int64(238), np.int64(218), np.int64(198), np.int64(175), np.int64(156), np.int64(143), np.int64(111), np.int64(99), np.int64(85), np.int64(81), np.int64(80), np.int64(78), np.int64(75), np.int64(71), np.int64(70), np.int64(69), np.int64(65), np.int64(64), np.int64(61), np.int64(57), np.int64(53), np.int64(47), np.int64(45), np.int64(42), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(30), np.int64(29), np.int64(28), np.int64(24), np.int64(23), np.int64(22), np.int64(16), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(8), np.int64(7), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9518 (+/- 0.0234)
  NB  Accuracy: 0.2925 (+/- 0.0315)
  CR  Accuracy: 0.9585 (+/- 0.0214)
  SVC Accuracy: 0.9600 (+/- 0.0273)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=20
Completed: 71/90 (78.9%)
  Feature selection time: 35.9535s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9613 (+/- 0.0252)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=18
Completed: 72/90 (80.0%)
  Feature selection time: 36.4411s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9613 (+/- 0.0264)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=16
Completed: 73/90 (81.1%)
  Feature selection time: 62.5532s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9588 (+/- 0.0224)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=14
Completed: 74/90 (82.2%)
  Feature selection time: 1357.5643s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9561 (+/- 0.0225)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=12
Completed: 75/90 (83.3%)
  Feature selection time: 101.5403s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9570 (+/- 0.0247)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=10
Completed: 76/90 (84.4%)
  Feature selection time: 80.1451s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9555 (+/- 0.0199)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=8
Completed: 77/90 (85.6%)
  Feature selection time: 693.2471s
  Total edges: 104416, Reduced attributes: 58
  Remaining edges per round: [np.int64(63224), np.int64(36430), np.int64(22064), np.int64(15383), np.int64(11536), np.int64(9694), np.int64(6135), np.int64(5656), np.int64(4048), np.int64(3538), np.int64(3035), np.int64(2887), np.int64(2525), np.int64(2357), np.int64(2085), np.int64(1792), np.int64(1642), np.int64(1436), np.int64(1364), np.int64(1272), np.int64(1020), np.int64(871), np.int64(728), np.int64(595), np.int64(493), np.int64(451), np.int64(389), np.int64(353), np.int64(308), np.int64(225), np.int64(224), np.int64(207), np.int64(187), np.int64(155), np.int64(149), np.int64(145), np.int64(118), np.int64(104), np.int64(90), np.int64(78), np.int64(75), np.int64(40), np.int64(37), np.int64(33), np.int64(29), np.int64(26), np.int64(23), np.int64(16), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8902 (+/- 0.0327)
  NB  Accuracy: 0.8619 (+/- 0.2037)
  CR  Accuracy: 0.9533 (+/- 0.0172)
  SVC Accuracy: 0.9600 (+/- 0.0269)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=6
Completed: 78/90 (86.7%)
  Feature selection time: 82.7051s
  Total edges: 49572, Reduced attributes: 57
  Remaining edges per round: [np.int64(30395), np.int64(19042), np.int64(13950), np.int64(10087), np.int64(7854), np.int64(6517), np.int64(4286), np.int64(3469), np.int64(3045), np.int64(2607), np.int64(2477), np.int64(2161), np.int64(2000), np.int64(1848), np.int64(1598), np.int64(1416), np.int64(1165), np.int64(1040), np.int64(954), np.int64(826), np.int64(776), np.int64(734), np.int64(641), np.int64(524), np.int64(413), np.int64(352), np.int64(322), np.int64(277), np.int64(236), np.int64(204), np.int64(166), np.int64(128), np.int64(127), np.int64(120), np.int64(116), np.int64(100), np.int64(88), np.int64(74), np.int64(63), np.int64(52), np.int64(44), np.int64(28), np.int64(24), np.int64(22), np.int64(20), np.int64(18), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9536 (+/- 0.0252)
  NB  Accuracy: 0.8822 (+/- 0.1419)
  CR  Accuracy: 0.9555 (+/- 0.0213)
  SVC Accuracy: 0.9600 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=4
Completed: 79/90 (87.8%)
  Feature selection time: 104.1063s
  Total edges: 56640, Reduced attributes: 65
  Remaining edges per round: [np.int64(34517), np.int64(24134), np.int64(14905), np.int64(10664), np.int64(8573), np.int64(7194), np.int64(4819), np.int64(3874), np.int64(3454), np.int64(2817), np.int64(2538), np.int64(2413), np.int64(2101), np.int64(1822), np.int64(1689), np.int64(1552), np.int64(1381), np.int64(1147), np.int64(1065), np.int64(999), np.int64(898), np.int64(784), np.int64(693), np.int64(583), np.int64(486), np.int64(424), np.int64(382), np.int64(341), np.int64(278), np.int64(271), np.int64(230), np.int64(191), np.int64(190), np.int64(183), np.int64(179), np.int64(162), np.int64(143), np.int64(121), np.int64(106), np.int64(90), np.int64(80), np.int64(66), np.int64(46), np.int64(41), np.int64(37), np.int64(36), np.int64(33), np.int64(26), np.int64(25), np.int64(24), np.int64(23), np.int64(21), np.int64(20), np.int64(17), np.int64(16), np.int64(14), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9555 (+/- 0.0234)
  NB  Accuracy: 0.3303 (+/- 0.0198)
  CR  Accuracy: 0.9567 (+/- 0.0227)
  SVC Accuracy: 0.9594 (+/- 0.0272)
------------------------------------------------------------
Testing parameters: thita=0.8, min_sample=2
Completed: 80/90 (88.9%)
  Feature selection time: 126.2152s
  Total edges: 61088, Reduced attributes: 89
  Remaining edges per round: [np.int64(36822), np.int64(25620), np.int64(15719), np.int64(11099), np.int64(7896), np.int64(6395), np.int64(4943), np.int64(4020), np.int64(3513), np.int64(3197), np.int64(2797), np.int64(2311), np.int64(2191), np.int64(1902), np.int64(1766), np.int64(1626), np.int64(1446), np.int64(1206), np.int64(1124), np.int64(1069), np.int64(966), np.int64(848), np.int64(757), np.int64(645), np.int64(576), np.int64(486), np.int64(449), np.int64(407), np.int64(400), np.int64(349), np.int64(290), np.int64(252), np.int64(251), np.int64(243), np.int64(238), np.int64(218), np.int64(198), np.int64(175), np.int64(156), np.int64(143), np.int64(111), np.int64(99), np.int64(85), np.int64(81), np.int64(80), np.int64(78), np.int64(75), np.int64(71), np.int64(70), np.int64(69), np.int64(65), np.int64(64), np.int64(61), np.int64(57), np.int64(53), np.int64(47), np.int64(45), np.int64(42), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(30), np.int64(29), np.int64(28), np.int64(24), np.int64(23), np.int64(22), np.int64(16), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(8), np.int64(7), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9518 (+/- 0.0234)
  NB  Accuracy: 0.2925 (+/- 0.0315)
  CR  Accuracy: 0.9582 (+/- 0.0229)
  SVC Accuracy: 0.9600 (+/- 0.0273)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=20
Completed: 81/90 (90.0%)
  Feature selection time: 36.0403s
  Total edges: 23004, Reduced attributes: 36
  Remaining edges per round: [np.int64(14985), np.int64(9644), np.int64(6681), np.int64(4608), np.int64(3610), np.int64(2717), np.int64(2353), np.int64(1821), np.int64(1401), np.int64(1241), np.int64(1140), np.int64(1014), np.int64(807), np.int64(785), np.int64(664), np.int64(456), np.int64(402), np.int64(305), np.int64(209), np.int64(159), np.int64(138), np.int64(113), np.int64(84), np.int64(60), np.int64(51), np.int64(44), np.int64(43), np.int64(39), np.int64(30), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5697 (+/- 0.0391)
  NB  Accuracy: 0.9567 (+/- 0.0261)
  CR  Accuracy: 0.9613 (+/- 0.0252)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=18
Completed: 82/90 (91.1%)
  Feature selection time: 36.3290s
  Total edges: 23544, Reduced attributes: 37
  Remaining edges per round: [np.int64(15457), np.int64(10023), np.int64(6806), np.int64(4686), np.int64(3673), np.int64(2782), np.int64(2418), np.int64(1861), np.int64(1440), np.int64(1252), np.int64(1151), np.int64(1025), np.int64(817), np.int64(795), np.int64(673), np.int64(465), np.int64(411), np.int64(385), np.int64(288), np.int64(193), np.int64(180), np.int64(129), np.int64(104), np.int64(73), np.int64(49), np.int64(44), np.int64(36), np.int64(35), np.int64(31), np.int64(26), np.int64(21), np.int64(19), np.int64(16), np.int64(9), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.5690 (+/- 0.0397)
  NB  Accuracy: 0.9573 (+/- 0.0250)
  CR  Accuracy: 0.9616 (+/- 0.0247)
  SVC Accuracy: 0.9607 (+/- 0.0232)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=16
Completed: 83/90 (92.2%)
  Feature selection time: 62.3426s
  Total edges: 30444, Reduced attributes: 44
  Remaining edges per round: [np.int64(19310), np.int64(13082), np.int64(8780), np.int64(6261), np.int64(4814), np.int64(3684), np.int64(2756), np.int64(2389), np.int64(2257), np.int64(1718), np.int64(1508), np.int64(1378), np.int64(1141), np.int64(1093), np.int64(952), np.int64(878), np.int64(641), np.int64(605), np.int64(490), np.int64(383), np.int64(311), np.int64(294), np.int64(261), np.int64(151), np.int64(112), np.int64(105), np.int64(75), np.int64(69), np.int64(68), np.int64(61), np.int64(55), np.int64(49), np.int64(46), np.int64(41), np.int64(26), np.int64(25), np.int64(19), np.int64(15), np.int64(8), np.int64(5), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.4852 (+/- 0.0419)
  NB  Accuracy: 0.9448 (+/- 0.0248)
  CR  Accuracy: 0.9588 (+/- 0.0221)
  SVC Accuracy: 0.9591 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=14
Completed: 84/90 (93.3%)
  Feature selection time: 1364.9679s
  Total edges: 88263, Reduced attributes: 51
  Remaining edges per round: [np.int64(53589), np.int64(31597), np.int64(18993), np.int64(13030), np.int64(9704), np.int64(7941), np.int64(5906), np.int64(5365), np.int64(3209), np.int64(2815), np.int64(2335), np.int64(2188), np.int64(1847), np.int64(1574), np.int64(1162), np.int64(1102), np.int64(1017), np.int64(861), np.int64(726), np.int64(598), np.int64(475), np.int64(377), np.int64(338), np.int64(254), np.int64(212), np.int64(184), np.int64(183), np.int64(169), np.int64(148), np.int64(129), np.int64(123), np.int64(114), np.int64(110), np.int64(97), np.int64(93), np.int64(81), np.int64(80), np.int64(77), np.int64(35), np.int64(30), np.int64(23), np.int64(16), np.int64(11), np.int64(10), np.int64(9), np.int64(7), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6188 (+/- 0.0322)
  NB  Accuracy: 0.9369 (+/- 0.0247)
  CR  Accuracy: 0.9552 (+/- 0.0225)
  SVC Accuracy: 0.9591 (+/- 0.0270)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=12
Completed: 85/90 (94.4%)
  Feature selection time: 100.9550s
  Total edges: 41072, Reduced attributes: 47
  Remaining edges per round: [np.int64(24876), np.int64(17016), np.int64(11413), np.int64(7917), np.int64(6295), np.int64(5037), np.int64(3783), np.int64(3386), np.int64(2633), np.int64(2253), np.int64(1968), np.int64(1836), np.int64(1544), np.int64(1407), np.int64(1231), np.int64(993), np.int64(933), np.int64(842), np.int64(778), np.int64(604), np.int64(566), np.int64(447), np.int64(338), np.int64(281), np.int64(241), np.int64(229), np.int64(201), np.int64(160), np.int64(119), np.int64(105), np.int64(104), np.int64(88), np.int64(74), np.int64(68), np.int64(64), np.int64(52), np.int64(47), np.int64(37), np.int64(23), np.int64(15), np.int64(12), np.int64(7), np.int64(6), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6517 (+/- 0.0888)
  NB  Accuracy: 0.9488 (+/- 0.0227)
  CR  Accuracy: 0.9585 (+/- 0.0253)
  SVC Accuracy: 0.9597 (+/- 0.0282)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=10
Completed: 86/90 (95.6%)
  Feature selection time: 80.7341s
  Total edges: 41538, Reduced attributes: 52
  Remaining edges per round: [np.int64(25488), np.int64(17814), np.int64(11708), np.int64(8365), np.int64(6530), np.int64(5272), np.int64(3831), np.int64(3434), np.int64(2665), np.int64(2278), np.int64(2152), np.int64(1844), np.int64(1698), np.int64(1551), np.int64(1372), np.int64(1128), np.int64(810), np.int64(727), np.int64(685), np.int64(632), np.int64(594), np.int64(485), np.int64(385), np.int64(307), np.int64(250), np.int64(213), np.int64(204), np.int64(176), np.int64(156), np.int64(117), np.int64(116), np.int64(101), np.int64(87), np.int64(81), np.int64(77), np.int64(71), np.int64(59), np.int64(47), np.int64(45), np.int64(27), np.int64(26), np.int64(23), np.int64(19), np.int64(12), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(4), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.6468 (+/- 0.0795)
  NB  Accuracy: 0.8488 (+/- 0.2059)
  CR  Accuracy: 0.9552 (+/- 0.0198)
  SVC Accuracy: 0.9585 (+/- 0.0274)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=8
Completed: 87/90 (96.7%)
  Feature selection time: 686.9373s
  Total edges: 104416, Reduced attributes: 58
  Remaining edges per round: [np.int64(63224), np.int64(36430), np.int64(22064), np.int64(15383), np.int64(11536), np.int64(9694), np.int64(6135), np.int64(5656), np.int64(4048), np.int64(3538), np.int64(3035), np.int64(2887), np.int64(2525), np.int64(2357), np.int64(2085), np.int64(1792), np.int64(1642), np.int64(1436), np.int64(1364), np.int64(1272), np.int64(1020), np.int64(871), np.int64(728), np.int64(595), np.int64(493), np.int64(451), np.int64(389), np.int64(353), np.int64(308), np.int64(225), np.int64(224), np.int64(207), np.int64(187), np.int64(155), np.int64(149), np.int64(145), np.int64(118), np.int64(104), np.int64(90), np.int64(78), np.int64(75), np.int64(40), np.int64(37), np.int64(33), np.int64(29), np.int64(26), np.int64(23), np.int64(16), np.int64(15), np.int64(12), np.int64(11), np.int64(9), np.int64(6), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.8902 (+/- 0.0327)
  NB  Accuracy: 0.8619 (+/- 0.2037)
  CR  Accuracy: 0.9533 (+/- 0.0179)
  SVC Accuracy: 0.9600 (+/- 0.0269)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=6
Completed: 88/90 (97.8%)
  Feature selection time: 81.9544s
  Total edges: 49572, Reduced attributes: 57
  Remaining edges per round: [np.int64(30395), np.int64(19042), np.int64(13950), np.int64(10087), np.int64(7854), np.int64(6517), np.int64(4286), np.int64(3469), np.int64(3045), np.int64(2607), np.int64(2477), np.int64(2161), np.int64(2000), np.int64(1848), np.int64(1598), np.int64(1416), np.int64(1165), np.int64(1040), np.int64(954), np.int64(826), np.int64(776), np.int64(734), np.int64(641), np.int64(524), np.int64(413), np.int64(352), np.int64(322), np.int64(277), np.int64(236), np.int64(204), np.int64(166), np.int64(128), np.int64(127), np.int64(120), np.int64(116), np.int64(100), np.int64(88), np.int64(74), np.int64(63), np.int64(52), np.int64(44), np.int64(28), np.int64(24), np.int64(22), np.int64(20), np.int64(18), np.int64(10), np.int64(9), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9536 (+/- 0.0252)
  NB  Accuracy: 0.8822 (+/- 0.1419)
  CR  Accuracy: 0.9573 (+/- 0.0214)
  SVC Accuracy: 0.9600 (+/- 0.0279)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=4
Completed: 89/90 (98.9%)
  Feature selection time: 103.7405s
  Total edges: 56640, Reduced attributes: 65
  Remaining edges per round: [np.int64(34517), np.int64(24134), np.int64(14905), np.int64(10664), np.int64(8573), np.int64(7194), np.int64(4819), np.int64(3874), np.int64(3454), np.int64(2817), np.int64(2538), np.int64(2413), np.int64(2101), np.int64(1822), np.int64(1689), np.int64(1552), np.int64(1381), np.int64(1147), np.int64(1065), np.int64(999), np.int64(898), np.int64(784), np.int64(693), np.int64(583), np.int64(486), np.int64(424), np.int64(382), np.int64(341), np.int64(278), np.int64(271), np.int64(230), np.int64(191), np.int64(190), np.int64(183), np.int64(179), np.int64(162), np.int64(143), np.int64(121), np.int64(106), np.int64(90), np.int64(80), np.int64(66), np.int64(46), np.int64(41), np.int64(37), np.int64(36), np.int64(33), np.int64(26), np.int64(25), np.int64(24), np.int64(23), np.int64(21), np.int64(20), np.int64(17), np.int64(16), np.int64(14), np.int64(8), np.int64(7), np.int64(6), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9555 (+/- 0.0234)
  NB  Accuracy: 0.3303 (+/- 0.0198)
  CR  Accuracy: 0.9570 (+/- 0.0216)
  SVC Accuracy: 0.9594 (+/- 0.0272)
------------------------------------------------------------
Testing parameters: thita=0.9, min_sample=2
Completed: 90/90 (100.0%)
  Feature selection time: 127.2857s
  Total edges: 61088, Reduced attributes: 89
  Remaining edges per round: [np.int64(36822), np.int64(25620), np.int64(15719), np.int64(11099), np.int64(7896), np.int64(6395), np.int64(4943), np.int64(4020), np.int64(3513), np.int64(3197), np.int64(2797), np.int64(2311), np.int64(2191), np.int64(1902), np.int64(1766), np.int64(1626), np.int64(1446), np.int64(1206), np.int64(1124), np.int64(1069), np.int64(966), np.int64(848), np.int64(757), np.int64(645), np.int64(576), np.int64(486), np.int64(449), np.int64(407), np.int64(400), np.int64(349), np.int64(290), np.int64(252), np.int64(251), np.int64(243), np.int64(238), np.int64(218), np.int64(198), np.int64(175), np.int64(156), np.int64(143), np.int64(111), np.int64(99), np.int64(85), np.int64(81), np.int64(80), np.int64(78), np.int64(75), np.int64(71), np.int64(70), np.int64(69), np.int64(65), np.int64(64), np.int64(61), np.int64(57), np.int64(53), np.int64(47), np.int64(45), np.int64(42), np.int64(40), np.int64(39), np.int64(38), np.int64(37), np.int64(36), np.int64(35), np.int64(34), np.int64(33), np.int64(32), np.int64(31), np.int64(30), np.int64(29), np.int64(28), np.int64(24), np.int64(23), np.int64(22), np.int64(16), np.int64(15), np.int64(14), np.int64(13), np.int64(12), np.int64(11), np.int64(10), np.int64(8), np.int64(7), np.int64(5), np.int64(4), np.int64(3), np.int64(2), np.int64(1), np.int64(0)]
  KNN Accuracy: 0.9518 (+/- 0.0234)
  NB  Accuracy: 0.2925 (+/- 0.0315)
  CR  Accuracy: 0.9585 (+/- 0.0210)
  SVC Accuracy: 0.9600 (+/- 0.0273)
------------------------------------------------------------
IA experimental results saved, progress: 100.0%
```

