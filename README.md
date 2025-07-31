[SoK: Root Cause of $1 Billion Loss in Smart Contract Real-World Attacks via a Systematic Literature Review of Vulnerabilities](https://arxiv.org/abs/2507.20175)

This repository accompanies our paper and includes the three main appendix sections for our paper including:
1. [List of Toy and Real-World Examples for Vulnerability Types Presented in the Paper](#1-list-of-toy-and-real-world-examples-for-vulnerability-types-presented-in-the-paper) 
2. [Attributes of Reviewed Incidents](#2-attributes-of-reviewed-incidents)
3. [Summary of 50 Real-World Smart Contract Incidents](#3-summary-of-50-real-world-smart-contract-incidents)

---
## 1. Toy and **Real-World** Examples for Vulnerability Types Presented in the Paper

To view the vulnerability descripition and its examples click on each vulnerability type.

| Vulnerability | Vulnerability | Vulnerability |
| :--- | :--- | :--- |
| [Dangerous Balance Inequality](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/Dangerous%2520Balance%2520Inequality.md) | [Bad Randomness](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/bad-randomness.md) | [Business Logic Error](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/business-logic-error.md) |
| [Call Stack Depth Limit](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/call-stack_deph-limit.md) | [Delegatecall](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/delegatecall.md) | [DoS Attack Via Owner Account](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/dos-attack-via-owner-account.md) |
| [Erroneous](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/erroneous.md) | [Ether Lost To Orphan Address](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/ether-lost-to-orphan-address.md) | [Event Ordering Bug](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/event-ordering-bug.md) |
| [Frozen Ether](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/forzen-ether.md) | [Front Running](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/front-running.md) | [Integer](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/integer.md) |
| [Ponzi](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/ponzi.md) | [Prodigal](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/prodigal.md) | [Reentrancy](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/reentrancy.md) |
| [Resource Exhaustion](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/resource-exhaustion.md) | [State Reverting](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/state%2520reverting.md) | [Suicidal](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/suicidal.md) |
| [Tx.origin](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/tx.origin.md) | [Type Casting](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/type-casting.md) | [Type Confusion](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/type-confusion.md) |
| [Unbounded Loop In Dynamic Arrays](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/unbounded-loop-in-dynamic-arrays.md) | [Unchecked Call](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/unchecked-call.md) | [Untrustworthy Data Feeds](https://github.com/mojtaba-eshghie/SoK-Root-Cause-of-Smart-Contract-Incidents/blob/main/vulnerabilities/untrustworthy-data-feeds.md) |
---

## 2. Attributes of Reviewed Incidents


**On-chain analysis of blockchain attacks: Detailed mapping of exploit transaction hashes, compromised victim contracts, and attacker addresses (smart contracts and EOAs) for comprehensive incident investigation**

---

| **ID** | **Transactions** | **Victim Contract** | **Attacker Smart Contract/EOA** |
|:---|:---|:---|:---|
| 1 | [0xc310](https://etherscan.io/tx/0xc310a0affe2169d1f6feec1c63dbc7f7c62a887fa48795d327d4d2da2d6b111d), [0x62bd](https://etherscan.io/tx/0x62bd3d31a7b75c098ccf28bc4d4af8c4a191b4b9e451fab4232258079e8b18c4), [0x3097](https://etherscan.io/tx/0x3097830e9921e4063d334acb82f6a79374f76f0b1a8f857e89b89bc58df1f311), [0x47ac](https://etherscan.io/tx/0x47ac3527d02e6b9631c77fad1cdee7bfa77a8a7bfd4880dccbda5146ace4088f) | [0xe025](https://etherscan.io/address/0xe025e3ca2be02316033184551d4d3aa22024d9dc) | [0xebc2](https://etherscan.io/address/0xeBC29199C817Dc47BA12E3F86102564D640CBf99), [0x036c](https://etherscan.io/address/0x036cec1a199234fc02f72d29e596a09440825f1c), [0xd3b7](https://etherscan.io/address/0xD3b7CEA28Feb5E537fcA4E657e3f60129456eaF3), [0x0b81](https://etherscan.io/address/0x0b812c74729b6aBc723F22986C61D95344ff7ABA) |
| 2 | [0xa5fe](https://etherscan.io/tx/0xa5fe9d044e4f3e5aa5bc4c0709333cd2190cba0f4e7f16bcf73f49f83e4a5460) | [0x88a6](https://etherscan.io/address/0x88a69b4e698a4b090df6cf5bd7b2d47325ad30a3) | [0xb5c5](https://etherscan.io/address/0xb5c55f76f90cc528b2609109ca14d8d84593590e) |
| 3 | [0x3195](https://polygonscan.com/tx/0x31957ecc43774d19f54d9968e95c69c882468b46860f921668f2c55fadd51b19) | [0x8f55](https://polygonscan.com/address/0x8f55d884cad66b79e1a131f6bcb0e66f4fd84d5b) | [0xcacf](https://polygonscan.com/address/0xcacf2d28b2a5309e099f0c6e8c60ec3ddf656642) |
| 4 | [0xe80a](https://arbiscan.io/tx/0xe80a16678b5008d5be1484ec6e9e77dc6307632030553405863ffb38c1f94266) | [0xeff2](https://arbiscan.io/address/0xeff23b4be1091b53205e35f3afcd9c7182bf3062) | [0x9961](https://arbiscan.io/address/0x9961190b258897bca7a12b8f37f415e689d281c4) |
| 5 | [0xd9ee](https://etherscan.io/tx/0xd9ee4fc5ee0b8815e6aae20e8bc5697ee49b8a1c76619a008bf534a4084197dc), [0xadbe](https://etherscan.io/tx/0xadbe5cf9269a001d50990d0c29075b402bcc3a0b0f3258821881621b787b35c6), [0x0f75](https://etherscan.io/tx/0x0f75349606610313cb666277eeda612e72be624cae061d017e503056bbf4d8e0), [0x0742](https://etherscan.io/tx/0x0742b138a78ad9bd5d0b55221d514637313bc64c40272ca98c8d0417a519e2e4), [0x2547](https://etherscan.io/tx/0x254735c6c14e4d338b1cc5bca43aab6b0f395ae06085013b1b2527180d270a31), [0xab48](https://etherscan.io/tx/0xab486012f21be741c9e674ffda227e30518e8a1e37a5f1d58d0b0d41f6e76530) | [0x3207](https://etherscan.io/address/0x32075bad9050d4767018084f0cb87b3182d36c45) | [0xE39f](https://etherscan.io/address/0xE39f3C40966DF56c69AA508D8AD459E77B8a2bc1), [0x3207](https://etherscan.io/address/0x32075bad9050d4767018084f0cb87b3182d36c45) |
| 6 | [0xa5fe](https://etherscan.io/tx/0xa5fe9d044e4f3e5aa5bc4c0709333cd2190cba0f4e7f16bcf73f49f83e4a5460) | [0x9a79](https://etherscan.io/address/0x9A79f4105A4e1A050Ba0b42F25351D394fA7E1DC) | [0xc49b](https://etherscan.io/address/0xc49b5e5b9da66b9126c1a62e9761e6b2147de3e1) |
| 7 | [0x485e](https://etherscan.io/tx/0x485e08dc2b6a4b3aeadcb89c3d18a37666dc7d9424961a2091d6b3696792f0f3), [0x09a3](https://etherscan.io/tx/0x09a3a12d58b0bb80e33e3fb8e282728551dc430c65d1e520fe0009ec519d75e8), [0x396a](https://etherscan.io/tx/0x396a83df7361519416a6dc960d394e689dd0f158095cbc6a6c387640716f5475) | [0xaf2a](https://etherscan.io/address/0xaf2acf3d4ab78e4c702256d214a3189a874cdc13) | [0x5027](https://etherscan.io/address/0x50275e0b7261559ce1644014d4b78d4aa63be836), [0xc9b8](https://etherscan.io/address/0xc9b826bad20872eb29f9b1d8af4befe8460b50c6) |
| 8 | [0x7e7f](https://etherscan.io/tx/0x7e7f9548f301d3dd863eac94e6190cb742ab6aa9d7730549ff743bf84cbd21d1), [0xfda0](https://etherscan.io/tx/0xfda0dde38fa4c5b0e13c506782527a039d3a87f93f9208c104ee569a642172d2), [0x7961](https://etherscan.io/tx/0x7961b0d3382bddff4c777e432902ea0b6940414ec16aa1a1dcebc4ebcbd8f867), [0xca87](https://etherscan.io/tx/0xca87f257280e19378dc1890a478514195f068857affacde0b92c851b897dff9e) | - | [0x7a2f](https://etherscan.io/address/0x7a2f4d625fb21f5e51562ce8dc2e722e12a61d1b) |
| 9 | [0x9312](https://optimistic.etherscan.io/tx/0x9312ae377d7ebdf3c7c3a86f80514878deb5df51aad38b6191d55db53e42b7f0) | [sovelo](https://optimistic.etherscan.io/address/0xe3b81318b1b6776f0877c3770afddff97b9f5fe5), [sousdc](https://optimistic.etherscan.io/address/0xec8fea79026ffed168ccf5c627c7f486d77b765f), [soweth](https://optimistic.etherscan.io/address/0xf7b5965f5c117eb1b5450187c9dcfccc3c317e8e) | [0x02fa](https://optimistic.etherscan.io/address/0x02fa2625825917e9b1f8346a465de1bbc150c5b9) |
| 10 | [0x561e](https://etherscan.io/tx/0x561e94c8040c82f8ec717a03e49923385ff6c9e11da641fbc518ac318e588984), [0x20a6](https://etherscan.io/tx/0x20a6dcff06a791a7f8be9f423053ce8caee3f9eecc31df32445fc98d4ccd8365), [0x6003](https://etherscan.io/tx/0x600373f67521324c8068cfd025f121a0843d57ec813411661b07edc5ff781842) | [0x39b1](https://etherscan.io/address/0x39b1dF026010b5aEA781f90542EE19E900F2Db15) | [0x117c](https://etherscan.io/address/0x117C0391B3483E32AA665b5ecb2Cc539669EA7E9), [0x8b4c](https://etherscan.io/address/0x8B4C1083cd6Aef062298E1Fa900df9832c8351b3) |
| 11 | [0x0cc1](https://etherscan.io/tx/0x0cc143ccf3316d47b36a2e45577922f4ebe2374966bb22c1e9cf49c747d46396) | - | - |
| 12 | [0x6129](https://etherscan.io/tx/0x6129dd42778345bc278822a7feadeacb933f5e56ce51114e686832ad239307a8) | [0xbc1b](https://arbiscan.io/address/0x189cf534de3097c08b6beaf6eb2b9179dab122d1) | [0xe2ee](https://arbiscan.io/address/0xe2ee6252509382a2b6504d5a5f7a1c5018a38168) |
| 13 | [0x9aa3](https://explorer.mode.network/tx/0x9aa3fd43a6b0f85b4f1bf74f0c9e79773f238591d9c6fe666287bd2c8ac19009), [0x37e5](https://explorer.mode.network/tx/0x37e53b15cb7f298bd8c45fcbbd914ba90feb3946f5511fc55bc986b7472956df), [0x5db6](https://explorer.mode.network/tx/0x5db6d90a17a44bed6d9ed9ca73d800df2661751fa1a273e71fc2174ad3b6944f) | [0x964d](https://explorer.mode.network/address/0x964dd444e3192f636322229080a576077b06fba3) | [0x9e34](https://explorer.mode.network/address/0x9E34d89C013Da3BF65fc02b59B6F27D710850430) |
| 14 | [0x2619](https://etherscan.io/tx/0x2619570088683e6cc3a38d93c3d98899e5783864e15525d5f5810c11189ba6cb) | [0xfc27](https://etherscan.io/address/0xfc274ec92bbb1a1472884558d1b5caac6f8220ee) | - |
| 15 | [0xd82f](https://etherscan.io/tx/0xd82fe84e63b1aa52e1ce540582ee0895ba4a71ec5e7a632a3faa1aff3e763873), [0x65a9](https://etherscan.io/tx/0x65a92b189e4ae0b8a8a02cd59c5e9f6832586bd5167d41a24eb4f4d2ac692755) | [0xf28a](https://etherscan.io/address/0xf28a352377663ca134bd27b582b1a9a4dad7e534#code) | [0x7742](https://etherscan.io/address/0x7742ed59e9ecf1712bc4c6bdd0c526e903a7f2c8) |
| 16 | [0xd55e](https://etherscan.io/tx/0xd55e43c1602b28d4fd4667ee445d570c8f298f5401cf04e62ec329759ecda95d), [0x8db0](https://etherscan.io/tx/0x8db0ef33024c47200d47d8e97b0fcfc4b51de1820dfb4e911f0e3fb0a4053138) | - | [0x5bac](https://etherscan.io/address/0x5bac20beef31d0eccb369a33514831ed8e9cdfe0), [0x16af](https://etherscan.io/address/0x16af29b7efbf019ef30aae9023a5140c012374a5) |
| 17 | [0x0160](https://starkscan.co/tx/0x0160a5841b3e99679691294d1f18904c557b28f7d5fe61577e75c8931f34a16f) | [0x04c0](https://starkscan.co/contract/0x04c0a5193d58f74fbace4b74dcf65481e734ed1714121bdc571da345540efa05) | [0x04d7](https://starkscan.co/contract/0x04d7191dc8eac499bac710dd368706e3ce76c9945da52535de770d06ce7d3b26) |
| 18 | [0xd82f](https://etherscan.io/tx/0xd82fe84e63b1aa52e1ce540582ee0895ba4a71ec5e7a632a3faa1aff3e763873), [0x65a9](https://etherscan.io/tx/0x65a92b189e4ae0b8a8a02cd59c5e9f6832586bd5167d41a24eb4f4d2ac692755) | [0xc74f](https://etherscan.io/address/0xc74fc202a6d0cf7a0ac38e99607b8629cdf2cb10) | [0x7742](https://etherscan.io/address/0x7742ed59e9ecf1712bc4c6bdd0c526e903a7f2c8) |
| 19 | [0x6e9e](https://optimistic.etherscan.io/tx/0x6e9ebcdebbabda04fa9f2e3bc21ea8b2e4fb4bf4f4670cb8483e2f0b2604f451), [0x1509](https://optimistic.etherscan.io/tx/0x15096dc6a59cff26e0bd22eaf7e3a60125dcec687580383488b7b5dd2aceea93) | [0x8adb](https://optimistic.etherscan.io/address/0x8ADB8131C5F951C61C90418885777DCC9A00728D) | [0x155d](https://optimistic.etherscan.io/address/0x155da45d374a286d383839b1ef27567a15e67528) |
| 20 | [0x26a8](https://etherscan.io/tx/0x26a83db7e28838dd9fee6fb7314ae58dcc6aee9a20bf224c386ff5e80f7e4cf2), [0xdb46](https://etherscan.io/tx/0xdb4616b89ad82062787a4e924d520639791302476484b9a6eca5126f79b6d877) | [0x7259](https://etherscan.io/address/0x7259e152103756e1616A77Ae982353c3751A6a90) | [0x87f5](https://etherscan.io/address/0x87f585809ce79ae39a5fa0c7c96d0d159eb678c9) |
| 21 | [0xc523](https://arbiscan.io/tx/0xc523c6307b025ebd9aef155ba792d1ba18d5d83f97c7a846f267d3d9a3004e8c) | [0x7596](https://arbiscan.io/address/0x7596ACadf6c93f01b877F5A44b49407ffFC53508) | [0xc29d](https://arbiscan.io/address/0xc29d94386ff784006ff8461c170d1953cc9e2b5c) |
| 22 | [0x0497](https://etherscan.io/tx/0x04975648e0db631b0620759ca934861830472678dae82b4bed493f1e1e3ed03a), [0xb5c9](https://etherscan.io/tx/0xb5c94efa0c8fd8f5c8cc2826e374a99620b01061d395b59b8f45dddc9fce1c60), [0xb16b](https://etherscan.io/tx/0xb16bbf03d324b66685c94d62dbe31c739ee23c114b3915d169c74cd7c98eec8c), [0x3947](https://etherscan.io/tx/0x3947e5a4d98104e313e08ee321673e1183db3d6ff8b7207f3eabb36f71436c1d), [0x9ce5](https://etherscan.io/tx/0x9ce5187c7160f531189e4765f21af5975dc2a62d961fb61ae09866d082918256), [0xb068](https://etherscan.io/tx/0xb0688eb1f46c28f36d7397366146fced23d3f8da7e08b760a5f612ce134ee9d2), [0x6273](https://etherscan.io/tx/0x62734ce80311e64630a009dd101a967ea0a9c012fabbfce8eac90f0f4ca090d6) | [0xb02f](https://etherscan.io/address/0xb02f39e382c90160eb816de5e0e428ac771d77b5) | [0x019b](https://etherscan.io/address/0x019bfc71d43c3492926d4a9a6c781f36706970c9) |
| 23 | [0x3932](https://etherscan.io/tx/0x39328ea4377a8887d3f6ce91b2f4c6b19a851e2fc5163e2f83bbc2fc136d0c71) | [0xa35f](https://etherscan.io/address/0xa35f69899796ddbc4a8904511d2f1f040b779cb7) | [0xa3a6](https://etherscan.io/address/0xA3a64255484aD65158AF0F9d96B5577F79901a1D) |
| 24 | [0x025c](https://arbiscan.io/tx/0x025cf2858723369d606ee3abbc4ec01eab064a97cc9ec578bf91c6908679be75) | [0x4b57](https://arbiscan.io/address/0x4b57adc00ac38f74506d29fc4080e3dc65b78a69) | [0x5351](https://arbiscan.io/address/0x5351536145610aa448a8bf85ba97c71caf31909c) |
| 25 | [0x8b74](https://arbiscan.io/tx/0x025cf2858723369d606ee3abbc4ec01eab064a97cc9ec578bf91c6908679be75) | [0x8d67](https://etherscan.io/address/0x8d67db0b205e32a5dd96145f022fa18aae7dc8aa) | [0x10db](https://etherscan.io/address/0x10db234e02c3889d8e408c7084e8ce10892bdad7) |
| 26 | [0x6b37](https://basescan.org/tx/0x6b378c84aa57097fb5845f285476e33d6832b8090d36d02fe0e1aed909228edd) | [0x551f](https://etherscan.io/address/0x551f3110f12c763D1611d5A63B5F015d1c1a954C) | [0x00fa](https://basescan.org/address/0x00fac92881556a90fdb19eae9f23640b95b4bcbd) |
| 27 | [0xa05f](https://etherscan.io/tx/0xa05f047ddfdad9126624c4496b5d4a59f961ee7c091e7b4e38cee86f1335736f) | [0xb91a](https://etherscan.io/address/0xb91ae2c8365fd45030aba84a4666c4db074e53e7) | [0x27de](https://etherscan.io/address/0x27defcfa6498f957918f407ed8a58eba2884768c) |
| 28 | [0xed17](https://arbiscan.io/tx/0xed17089aa6c57b7d5461209e853bdb56bc3460a91805e20d2590609a515ef0b0) | [0x625F](https://arbiscan.io/address/0x625Fe79547828b1B54467E5Ed822a9A8a074bD61) | [0xaf9e](https://arbiscan.io/address/0xAF9e33Aa03CAaa613c3Ba4221f7EA3eE2AC38649) |
| 29 | [0x9efe](https://arbiscan.io/tx/0x9efe855cd3783462207ff8a3d94dc17a74e2b2f00bf1b4c8a7e0135dae83ab5c) | [0x52ee](https://arbiscan.io/address/0x52ee5c0ea2e7b38d4b24c09d4d18cba6c293200e) | [0xb878](https://arbiscan.io/address/0xb87881637b5c8e6885c51ab7d895e53fa7d7c567) |
| 30 | [0x4656](https://etherscan.io/tx/0x46567c731c4f4f7e27c4ce591f0aebdeb2d9ae1038237a0134de7b13e63d8729) | - | [0x6809](https://etherscan.io/address/0x680910cf5fc9969a25fd57e7896a14ff1e55f36b) |
| 31 | [0x138d](https://etherscan.io/tx/0x138daa4cbeaa3db42eefcec26e234fc2c89a4aa17d6b1870fc460b2856fd11a6) | [0xde62](https://etherscan.io/address/0xde62e1b0edaa55aac5ffbe21984d321706418024#code) | [0x6840](https://etherscan.io/address/0x684083f312ac50f538cc4b634d85a2feafaab77a) |
| 32 | [0x92cd](https://etherscan.io/tx/0x92cdcc732eebf47200ea56123716e337f6ef7d5ad714a2295794fdc6031ebb2e) | [0x534a](https://etherscan.io/address/0x534a3bb1ecb886ce9e7632e33d97bf22f838d085), [0x53d2](https://etherscan.io/address/0x53d2D9D2b36d2784D80297E6532e3BD965435021), [0x0d2b](https://etherscan.io/address/0x0d2b0c59D6a51eAE239A6C6eE29cFE73b79cC35b), [0x8f69](https://etherscan.io/address/0x8f690502964348acbab0E3E3E81192A582715d89), [0xc581](https://etherscan.io/address/0xC581d6Ef24146f745d5Bc014cc114C8F0CA74783), [0x460f](https://etherscan.io/address/0x460fDebe3D0B26e9DC194De80B3111b369B29272), [0x3e9f](https://etherscan.io/address/0x3e9F59f371dB249F2D95cf1E6F5224Ff1D7328Ab), [0x52f0](https://etherscan.io/address/0x52F0b1B251FCa6f2b1191803a0aA4d9f4dB6F924) | [0x6710](https://etherscan.io/address/0x67104175fc5fabbdb5A1876c3914e04B94c71741) |
| 33 | [0x8fcd](https://basescan.org/tx/0x8fcdfcded45100437ff94801090355f2f689941dca75de9a702e01670f361c04) | [0x6a0b](https://basescan.org/address/0x6a0b87d6b74f7d5c92722f6a11714dbeda9f3895#code) | [0x012f](https://basescan.org/address/0x012Fc6377F1c5CCF6e29967Bce52e3629AaA6025) |
| 34 | [0x3274](https://etherscan.io/tx/0x3274b6090685b842aca80b304a4dcee0f61ef8b6afee10b7c7533c32fb75486d) | [0xc503](https://etherscan.io/address/0xc503893b3e3c0c6b909222b45f2a3a259a52752d) | - |
| 35 | [0xb2e3](https://etherscan.io/tx/0xb2e3ea72d353da43a2ac9a8f1670fd16463ab370e563b9b5b26119b2601277ce) | [0xcff0](https://etherscan.io/address/0xcff07c4e6aa9e2fec04daaf5f41d1b10f3adadf4) | [0xcff0](https://etherscan.io/address/0xcff07c4e6aa9e2fec04daaf5f41d1b10f3adadf4) |
| 36 | [0xfeed](https://etherscan.io/tx/0xfeedbf51b4e2338e38171f6e19501327294ab1907ab44cfd2d7e7336c975ace7) | [0x9ab6](https://etherscan.io/address/0x9ab6b21cdf116f611110b048987e58894786c244), [0xd0db](https://etherscan.io/address/0xd0db31473caad65428ba301d2174390d11d0c788) | [0x0a33](https://etherscan.io/address/0x0A3340129816a86b62b7eafD61427f743c315ef8), [0xfdc0](https://etherscan.io/address/0xfdc0feaa3f0830aa2756d943c6d7d39f1d587110), [0x0119](https://etherscan.io/address/0x011992114806e2c3770df73fa0d19884215db85f) |
| 37 | - | [0x2a9c](https://scrollscan.com/address/0x2a9c973a2f5cb494eA84Fd0811aA7701f4d56401) | [0x893d](https://scrollscan.com/address/0x893D5C3E6d84785a648902e31f8734d2be648CdC) |
| 38 | [0x242a0f](https://etherscan.io/tx/0x242a0fb4fde9de0dc2fd42e8db743cbc197ffa2bf6a036ba0bba303df296408b), [0xb3f0](https://etherscan.io/tx/0xb3f067618ce54bc26a960b660cfc28f9ea0315e2e9a1a855ede1508eb4017376), [0xca1b](https://etherscan.io/tx/0xca1bbf3b320662c89232006f1ec6624b56242850f07e0f1dadbe4f69ba0d6ac3) | - | [0x841d](https://etherscan.io/address/0x841ddf093f5188989fa1524e7b893de64b421f47) |
| 39 | [0xed11d](https://lineascan.build/tx/0xed11d5b013bf3296b1507da38b7bcb97845dd037d33d3d1b0c5e763889cdbed1), [0x3743](https://lineascan.build/tx/0x37434e674efc4e7cfeed7746095301ace5636028906fe548b786ead286e35eb0), [0x4156](https://explorer.zksync.io/tx/0x4156d73cadc18419220f5bcf10deb4d97a3d3f7533d63ba90daeabc5fd11ba17) | [0xed4e](https://lineascan.build/address/0xed4e130f6f9e68918996f7e1e46a3306b3e12cec) , [0xb7f6](https://lineascan.build/address/0xb7f6354b2cfd3018b3261fbc63248a56a24ae91a) , [0xc030](https://lineascan.build/address/0xc030fba4b741b770f03e715c3a27d02c41fc9dae), [0xf7f7](https://explorer.zksync.io/address/0xf7f76b30a301524fe76508546B1e3762eF2B9267) | [0x8cdc](https://lineascan.build/address/0x8cdc37ed79c5ef116b9dc2a53cb86acaca3716bf) |
| 40 | [0x4ff40](https://etherscan.io/tx/0x4ff4028b03c3df468197358b99f5160e5709e7fce3884cc8ce818856d058e106) | - | [0xdaaa](https://etherscan.io/address/0xdaAa6294C47b5743BDafe0613d1926eE27ae8cf5) |
| 41 | [0x30fe](https://etherscan.io/tx/0x30fef86a72ea7e1109ffeae572439995c78561ffeb968dcbd61c609efc60fdd9), [0xc12a](https://etherscan.io/tx/0xc12a4155c2c90707138e4aef8883c8f724371145823e2f661f19b93e5b3a9d6e) | [0xd3f6](https://etherscan.io/address/0xd3f64baa732061f8b3626ee44bab354f854877ac) | [0xb660](https://etherscan.io/address/0xb660cae1a59336676ea1887b15eb3c0badb90d78),[0x90a7](https://etherscan.io/address/0x90a7482dD7fA28865f440EC0c3B783775AC01266), [0x2f74](https://etherscan.io/address/0x2f744f784000de0b8f1a7da3f0021ad56c09ce1a) |
| 42 | [0xee02](https://etherscan.io/tx/0xee02781eda4108f8fb3cca8355218961ad3a3e769b3de8a869acb8ed1654a67e) | - | [0x9464](https://etherscan.io/address/0x94641c01a4937f2c8ef930580cf396142a2942dc), [0x5217](https://etherscan.io/address/0x5217c6923a4efc5bcf53d9a30ec4b0089f080ed0),[0xe83b](https://etherscan.io/address/0xe83b072433f025ef06b73e0caa3095133e7c5bd0) |
| 43 | [0xc6a5](https://etherscan.io/tx/0xc6a5a7bc31bbc9a7530189e718f7ed96789fa65c56c3a4a08079a95074e280c8), [0x22eb](https://etherscan.io/tx/0x22ebd267d7344780e6d63cf3a76bab57b8f8fa41cf58df1a2e1707d75d8bee89) | [0x70cb](https://etherscan.io/address/0x70cbb871e8f30fc8ce23609e9e0ea87b6b222f58) , [0x40aa](https://etherscan.io/address/0x40aa958dd87fc8305b97f2ba922cddca374bcd7f) , [0x55b3](https://etherscan.io/address/0x55b35bf627944396f9950dd6bddadb5218110c76) | [0xfacf](https://etherscan.io/address/0xFacf375Af906f55453537ca31fFA99053A010239) |
| 44 | [0x0788](https://etherscan.io/tx/0x0788ba222970c7c68a738b0e08fb197e669e61f9b226ceec4cab9b85abe8cceb), [0x2aec](https://etherscan.io/tx/0x2aec4fdb2a09ad4269a410f2c770737626fb62c54e0fa8ac25e8582d4b690cca) | [0xb40b](https://etherscan.io/address/0xb40b6c5c51ac1d16cd427f535eeca87dd4fb3f1e) | [0x5f4c](https://etherscan.io/address/0x5f4c21c9bb73c8b4a296cc256c0cde324db146df) |
| 45 | [0x7ac4](https://explorer.zksync.io/tx/0x7ac4da1ea1b0903dfabda56f713ea5e4a960a3fc34467a844d037f86ee8bfe98), [0x99ef](https://explorer.zksync.io/tx/0x99efebacb3edaa3ac34f7ef462fd8eed85b46be281bd1329abfb215a494ab0ef) | [0x7d87](https://explorer.zksync.io/address/0x7d8772DCe73cDA0332bc47451aB868Ac98F335F0), [0xd5c6](https://explorer.zksync.io/address/0xC5c668DcD437b901DFE877DC99329Ac2ba338035) | [0xf1d0](https://explorer.zksync.io/address/0xf1D076c9Be4533086f967e14EE6aFf204D5ECE7a) |
| 46 | [0xeade](https://bscscan.com/address/0xeade071ff23bcef312dec938ece29f7da62cf45b) | [0x613c](https://bscscan.com/address/0x613cc544053812ab026d60361212cdb67b46f42f) | [0xeade](https://bscscan.com/address/0xEADe071FF23bceF312deC938eCE29f7da62CF45b) |
| 47 | [0xeb87](https://etherscan.io/tx/0xeb87ebc0a18aca7d2a9ffcabf61aa69c9e8d3c6efade9e2303f8857717fb9eb7) | [0x0b09](https://etherscan.io/address/0x0b09c86260c12294e3b967f0d523b4b2bcdfbeab) | [0x1e84](https://etherscan.io/address/0x1e8419e724d51e87f78e222d935fbbdeb631a08b) |
| 48 | [0x44a0](https://arbiscan.io/tx/0x44a0f5650a038ab522087c02f734b80e6c748afb207995e757ed67ca037a5eda) | [0x2719](https://arbiscan.io/address/0x271944d9D8CA831F7c0dBCb20C4ee482376d6DE7) | [0x102b](https://arbiscan.io/address/0x102be4bccc2696c35fd5f5bfe54c1dfba416a741) |
| 49 | [0x36fe](https://arbiscan.io/tx/0x36fef881f7e9560db466a343e541072a31a07391bcd0b9bcdb6cfe8ae4616fc0) | [0x9980](https://arbiscan.io/address/0x99801433f5d7c1360ea978ea18666f7be9b3abf7#code) | [0xf274](https://arbiscan.io/address/0xf2744e1fe488748e6a550677670265f664d96627) |
| 50 | [0xa6f6](https://etherscan.io/tx/0xa6f63fcb6bec8818864d96a5b1bb19e8bd85ee37b2cc916412e720988440b2aa) | [0xb559](https://etherscan.io/address/0xb5599f568D3f3e6113B286d010d2BCa40A7745AA) | [0x5061](https://etherscan.io/address/0x5061F7e6dfc1a867D945d0ec39Ea2A33f772380A) |


---

## 3. Summary of 50 Real-World Smart Contract Incidents 

This appendix provides a detailed examination of attack mechanisms employed in 50 significant smart contract vulnerability incidents. Attacks are categorized by vulnerability type to highlight common patterns within each category. For each attack, the ID corresponds to Table 1 in the main text.

---
## Access Control Incidents 🚨

Access control vulnerabilities occur when permission mechanisms are improperly implemented or entirely absent. These vulnerabilities allow attackers to perform operations they should not be permitted to execute.

### [1] Euler Finance

The attack on Euler Finance occurred because the donateToReserves function lacked proper access control [[1]](#1). This function did not check the account's healthFactor before execution. As a result, the attacker could donate to reserves even when their position was undercollateralized. This failure bypassed standard solvency rules and violated the principle of least privilege.

The attacker also abused a business logic flaw in the softLiquidation mechanism. The protocol offered higher liquidation discounts to accounts with lower healthFactor. The attacker reduced their own healthFactor by repeatedly calling selfBorrow [[2]](#2). This manipulation triggered liquidations with discounts exceeding 90%. The design incentivized this behavior, which showed a serious misalignment between intended logic and real-world outcomes.

Flash loans made the attack practical. The attacker borrowed 30 million DAI using Aave.flashLoan. They then executed the sequence mint, donate, and liquidate in a single transaction [[1]](#1), [[3]](#3), [[2]](#2). Flash loans allowed this sequence to happen without interruption. This atomic execution gave the attacker full control over the system's state within one block and made the exploit hard to stop.

### [2] Nomad Bridge

The exploit mechanism of the Nomad Bridge attack originated from a critical vulnerability in the Replica smart contract. In a contract upgrade, the trusted root parameter, responsible for validating cross-chain messages, was mistakenly initialized to the zero address (0x00) [[4]](#4). This misconfiguration led to a failure in the access control system, as the contract began to treat all messages as valid by default, regardless of their legitimacy. Consequently, the process() function, which handles cross-chain messages, could be invoked without verifying the authenticity of the messages, specifically the Merkle root. This breakdown in access control allowed attackers to submit arbitrary messages and withdraw funds without needing valid proofs or signatures [[5]](#5). Since the attack was permissionless, anyone could copy a previous attack transaction from Etherscan, modify the recipient address, and drain funds from the bridge.

### [6] Infini

The Infini exploit highlights a straightforward Access Control vulnerability, where the attack method was remarkably simple. A former developer, responsible for the contract Infini Vault, deliberately retained administrative privileges even after completing their tasks [[6]](#6). The core security failure occurred when the project administrators failed to revoke these privileged access rights or transfer ownership properly. After waiting nearly 100 days, the attacker executed the exploit by using the still-active admin credentials to gain access to the Morpho MEVCapital's USDC vault. This led to two unauthorized withdrawals of 11.4 million and 38 million USDC, respectively [[7]](#7). No sophisticated technical exploit was necessary the attacker merely used legitimate administrative functions they should have lost access to long ago.

### [11] Holograph

The Holograph exploit highlights a classic Access Control vulnerability, specifically a failure in privileged function access control. In this case, a former developer retained permission to access the contract's mint function even after their involvement with the project ended [[8]](#8), [[9]](#9).

The attacker deployed a malicious smart contract on the Mantle network. This contract used an address that still had privileged access to bypass standard authorization checks. By exploiting this leftover permission, the attacker called the mint function across nine transactions, creating a total of 1 billion HLG tokens.

These tokens were then bridged to the Ethereum network and sold on exchanges. Although some exchanges froze about 200 million tokens, the attacker successfully dumped a significant portion. The token price dropped by 80% within the first nine hours [[8]](#8).

### [12] Deus DAO 

The DEI exploit targeted an access control vulnerability in the token's burnFrom() function [[10]](#10). The root cause was an implementation error in the allowance mechanism where parameters were reversed: _allowances[_msgSender()][account] instead of the correct _allowances[account][_msgSender()] [[10]](#10). This misconfiguration created a critical security flaw in the permission validation logic. By calling burnFrom() with a zero amount parameter, attackers could manipulate the contract into incorrectly granting spending approval to themselves [[11]](#11). The exploit enabled unauthorized access to victim token holdings without proper consent.

### [14] Ronin Bridge 

The Ronin Bridge exploit resulted from an incomplete contract upgrade process [[12]](#12). When upgrading from version 2 to 4, developers called initializeV4() but neglected to call initializeV3() [[13]](#13). This oversight left _totalOperatorWeight uninitialized at zero. Consequently, the minimumVoteWeight security check was effectively disabled, as any signature weight would satisfy a comparison against zero. An MEV bot exploited this access control vulnerability to withdraw 4,000 ETH and 2 million USDC, reaching the bridge's maximum transaction withdrawal limit of $12 million.

### [15] LI.FI 

The LI.FI exploit occurred due to insufficient access control in a newly deployed contract facet [[14]](#14). The vulnerability stemmed from the depositToGasZipERC20 function in GasZipFacet.sol, which directly passed user-controlled data to LibSwap.swap without proper validation [[15]](#15). Unlike other facets of the LI.FI contract that implemented strict whitelisting of allowed contract calls, this new facet lacked these security checks due to a human error during deployment. The attacker exploited this vulnerability by crafting malicious calldata containing transferFrom() function calls [[16]](#16). This technique allowed them to drain tokens from wallets that had granted unlimited approvals to the LI.FI contract.

### [23] Shezmu

The Shezmu exploit stemmed from a critical access control vulnerability in the protocol's collateral token contract [[17]](#17). The attack exploited three interconnected flaws in the platform's design. First, the collateral token contract implemented an unrestricted mint() function that lacked proper access controls. This allowed the attacker to mint arbitrary amounts of collateral tokens without authorization [[18]](#18).

Second, the Shezmu vault contract contained an addCollateral() function that failed to validate the origin of deposited tokens. The function accepted self-minted tokens without verification, enabling the attacker to artificially increase their collateral position within the protocol [[17]](#17). This design flaw effectively bypassed the fundamental principle that collateral should represent genuine external value.

Third, the vault's _borrow() function permitted users to borrow the protocol's stablecoin (ShezUSD) against their collateral shares without additional validation. Since the vault contract possessed the necessary role permissions to mint ShezUSD, the attacker could leverage their artificially inflated collateral position to borrow substantial amounts of newly minted ShezUSD [[17]](#17).

### [31] Dexible

The Dexible exploit demonstrated a critical vulnerability in smart contract parameter validation. The vulnerability existed in Dexible's newly implemented v2 contracts, specifically in the selfSwap function [[19]](#19). This function allowed users to define custom routing information for token swaps. However, the implementation contained a fundamental security flaw: the router address parameter lacked on-chain verification [[20]](#20). The exploit mechanism functioned as follows: When users invoked the selfSwap() method, they provided parameters including tokenID and router information as call data [[19]](#19). This data was subsequently passed to the fill() method, which critically failed to validate the routerID parameter [[19]](#19). The attacker exploited this missing validation by submitting their own contract address as the routerID parameter [[20]](#20). Instead of routing through a legitimate DEX contract, the fill() function performed a delegate call to the attacker-controlled address [[19]](#19). This manipulation enabled the attacker to craft malicious call data that triggered transferFrom calls on token contracts [[20]](#20). The attack targeted user accounts that had previously granted approval to Dexible's contract, allowing the attacker to transfer tokens directly to their wallet [[19]](#19).

### [40] Curio

The Curio exploit targeted a vulnerability in the protocol's DAO voting system [[21]](#21). The attack leveraged an access control flaw in MakerDAO-based smart contracts on Ethereum. The exploit occurred through a series of coordinated steps exploiting governance privileges. First, the attacker acquired a small number of CGT tokens, granting themselves elevated voting privileges within the smart contract [[22]](#22). This privilege escalation occurred due to insufficient validation in the voting power mechanism. With enhanced voting power, the attacker could manipulate governance decisions. Second, the attacker executed the smart contract's plot function, which defined a malicious smart contract as the project's exec library [[22]](#22). The attack was initiated through the cook function of an attack contract, leveraging the IDSChief and IDSPause contracts to execute a governance manipulation scheme [[21]](#21). Third, the vulnerable contract permitted delegatecall operations to this malicious library [[22]](#22). A delegatecall allows execution of external code with the identity and storage context of the calling contract. This enabled the attacker to execute arbitrary code with Curio's contract privileges.

### [49] Swaprum

The Swaprum incident exploited a critical access control vulnerability at the administrative level [[23]](#23). The team abused their unrestricted upgrade privileges to implement a malicious add() function [[24]](#24). This access control flaw manifested through excessive admin rights that allowed arbitrary contract modifications [[24]](#24). The add() function served as a backdoor, enabling the team to bypass normal access restrictions and transfer users' LP tokens directly to their deployer address [[24]](#24). The vulnerability represented a failure in privilege management, where the contract owner possessed unchecked authority over user funds [[23]](#23). CertiK's audit had identified centralization risks but failed to classify them as critical access control vulnerabilities [[24]](#24).

## Reentrancy Vulnerabilities

Reentrancy vulnerabilities occur when contracts update state variables after external calls, allowing attackers to recursively reenter the vulnerable function before state changes are reflected.

### [5] Fei Rari

The exploit leveraged a Reentrancy vulnerability. Initially [[25]](#25), a flash loan of 150 million USDC and 50,000 WETH was taken, and the USDC was deposited as collateral into the vulnerable fUSDC-127 contract. With this collateral, 1,977 ETH was borrowed. However, the borrow() function had a critical flaw: it transferred ETH before updating the borrow records. This allowed for a reentrant call to exitMarket() via the fallback() function, enabling the withdrawal of all the collateral before the loan records were updated. This sequence was repeated with multiple tokens. In the final step, the flash loan was repaid, and the remaining funds were routed to the attacker's address, with some funds sent through Tornado Cash [[26]](#26).

### [8] Penpie

The Penpie exploit leveraged a Reentrancy vulnerability in the harvestBatchMarketRewards() function. The attacker deployed a malicious SY (Synthetic Yield) contract and registered it as a valid Pendle market on Penpie through the platform's permissionless registration system [[27]](#27), [[28]](#28).

The exploit mechanism functioned as follows: When the harvestBatchMarketRewards() function called redeemRewards(), the malicious SY contract reentered the protocol's depositMarket() function. This reentrancy allowed the attacker to deposit additional tokens from a flash loan during reward calculation. Since rewards were computed based on the difference between token balances before and after calling redeemRewards() (amountAfter - amountsBefore[j]), the injected tokens artificially inflated the amountAfter value. This manipulation enabled the attacker to extract significantly more rewards [[27]](#27).

### [25] Conic Finance

The Conic Finance exploit manifested as a dual attack leveraging different vulnerabilities in Ethereum smart contracts [[29]](#29). The primary attack exploited the notorious read-only reentrancy vulnerability in the CurveLPOracleV2 contract. This vulnerability allowed the attacker to reenter specific token functions, notably rETH-f.totalSupply(), during price calculations. The reentrancy protection mechanism failed due to an address confusion between ETH and WETH in Curve V2 pools. The exploiter manipulated token prices through this reentrancy vulnerability. This manipulation created artificial price discrepancies between actual asset values and oracle-reported values. Consequently, the attacker could withdraw significantly more assets than initially deposited. [[29]](#29). A second, distinct attack targeted Conic's crvUSD omnipool through a different mechanism. This attack exploited insufficient bounds checking in pool balancing mechanisms. The attacker performed a systematic approach that involved sequential token exchanges and deposit-withdrawal cycles. First, they exchanged crvUSD to USDC in the Curve pool. Then they deposited crvUSD into Conic. Subsequently, they exchanged USDC back to crvUSD in the Curve pool. Finally, they withdrew funds from Conic. This cycle was repeated multiple times. The second attack leveraged imbalanced pools to create favorable exchange rates. Despite implemented safeguards against imbalanced pool interactions, the configured protection thresholds proved inadequate. The bounds were not sufficiently restrictive to prevent gradual drainage [[29]](#29).

### [33] CloberDEX

The CloberDEX exploit exemplifies a classic reentrancy vulnerability in DeFi protocols [[30]](#30). The attack specifically targeted the Liquidity Vault component deployed on the Base network [[31]](#31). The vulnerability resided in the _burn function of the Rebalancer contract, which violated the checks-effects-interactions pattern [[30]](#30). This critical security principle mandates that state changes should occur before external calls to prevent reentrancy attacks. The flawed implementation executed external token transfers (bookKeyA.quote.transfer and bookKeyA.base.transfer) to users prior to updating critical state variables (pool.reserveA and pool.reserveB) [[30]](#30). This sequence created a window of vulnerability where the contract state remained unchanged during external interactions. The attacker exploited this vulnerability by creating a malicious token contract with a callback function that triggered during the token transfer [[31]](#31). This callback reentered the _burn function before state variables were updated, allowing multiple withdrawals based on the same, unmodified reserve values [[30]](#30). The exploit transaction demonstrated how the attacker leveraged a custom strategy and malicious token to orchestrate the attack [[30]](#30). By reentering the vulnerable function, the attacker could repeatedly extract funds while the contract still reflected pre-withdrawal state values.

### [45] EraLend

The EraLend exploit targeted a critical read-only reentrancy vulnerability in the protocol's liquidity pool implementation [[32]](#32). The root cause was improper callback handling when burning SyncSwap LP tokens. This vulnerable code pattern was directly recycled from SyncSwap, despite containing explicit warning comments about potential security risks [[32]](#32).

The attack exploited a specific sequencing flaw. When burning LP tokens, the protocol allowed callback execution before reserves were updated [[33]](#33). This callback opportunity created a timing gap where old reserve values remained accessible. The attacker leveraged this window to manipulate the oracle's price calculation mechanism [[32]](#32).

By repeatedly entering and exiting contract functions in a precise sequence, the attacker forced the oracle to use stale reserve data [[33]](#33). This artificial price manipulation inflated asset values, allowing the attacker to borrow against overvalued collateral. The exploit specifically targeted USDC deposits on the platform [[32]](#32).

### [47] Sturdy Finance

The Sturdy Finance attack exploited a read-only reentrancy vulnerability in the protocol's price oracle system [[34]](#34). The attacker manipulated the price of B-stETH-STABLE tokens through Balancer's vulnerable pools [[35]](#35). First, the attacker obtained flash loans of 50,000 wstETH and 60,000 WETH from Aave [[35]](#35). They then added liquidity to manipulate the B-stETH-STABLE pool price. During the reentrancy attack, the oracle read an inflated price while the pool was in an inconsistent state [[34]](#34). The attacker deposited the manipulated tokens as collateral in Sturdy Finance. With the artificially inflated collateral value, they borrowed additional assets [[35]](#35). When the transaction completed and prices normalized, the attacker had extracted value through undercollateralized loans. The vulnerability stemmed from the oracle reading pool prices during active transactions, before state changes were finalized [[34]](#34). This read-only reentrancy issue had been previously identified in other protocols like Midas Capital and dForce Network [[34]](#34).

### [50] Orion Protocol

The Orion Protocol exploit leveraged a reentrancy vulnerability in the ExchangeWithAtomic contract's exchange function [[36]](#36). The core issue was that the function lacked proper reentrancy protection while calculating deposits based on token balance differences [[36]](#36).

First, the attacker deposited 0.5 USDC tokens into the ExchangeWithAtomic contract as preparation [[36]](#36). They then obtained a flash loan of 2,847,000 USDT and initiated a token swap through the vulnerable doSwapThroughOrionPool function [[36]](#36).

The attacker crafted a malicious token (ATK) and structured the swap path as "USDC -> ATK -> USDT" [[36]](#36). During the token transfer, the ATK contract's transfer function triggered a reentrant call to the depositAsset function [[36]](#36).

This reentrancy attack allowed the attacker to deposit 2,844,700 USDT while the contract was still processing the swap [[36]](#36). Since the contract calculated the output amount based on the balance difference, it recorded an inflated deposit of 5,689,000 USDT [[36]](#36).

The attacker then withdrew the artificially inflated balance, repaid the flash loan, and converted the excess 2.836 million USDT to WETH [[36]](#36). The same attack method was replicated on BSC, yielding additional profits [[36]](#36).

The vulnerability stemmed from the contract updating user deposits after calculating balance differences without protecting against reentrancy [[37]](#37). This allowed the attacker to manipulate their account balance through recursive calls during token transfers [[36]](#36).

## 🚨 Price Manipulation Incidents 🚨

Price manipulation vulnerabilities occur when protocols rely on manipulable price feeds or fail to implement adequate safeguards against artificial price movements.

### [3] BonqDAO

The BonqDAO [[38]](#38) exploit represents a classic Oracle Manipulation attack where the attacker exploited insufficient price validation in the protocol's oracle integration [[39]](#39). The BonqDAO smart contract lacked essential boundary checks when consuming price data from the Tellor oracle, allowing extreme price manipulations. The attacker staked 10 TRB tokens to gain oracle reporting privileges, then artificially inflated the WALBT token price to borrow excessive BEUR stablecoins against overvalued collateral. Subsequently, the attacker crashed the WALBT price, triggering widespread liquidations of other users' positions, which the attacker then collected. This two-phase attack succeeded because the updateValue() function contained no sanity checks for abnormal price movements [[40]](#40).

### [4] WooFi

The exploit in the WOOFi [[41]](#41) contract originated from a flaw in the _calcBaseAmountSellQuote function, where the token price was calculated directly using a linear formula based on the oracle price and input amount, without incorporating effective slippage control or safeguards against manipulation. The attacker initiated the exploit by taking a flash loan to borrow large amounts of USDC and WOO tokens. They then used part of the USDC to perform a series of swaps within the WOOFi contract, inflating the price of WOO tokens [[42]](#42). At the peak, they swapped a large quantity of WOO for USDC, triggering a dramatic price crash. This allowed them to repurchase WOO tokens at a drastically lower price, repay the flash loan, and extract profit. The vulnerability lay in the pricing formula, which failed to mitigate temporary manipulation within a single transaction, making it susceptible to flash loan-based price distortion.

### [10] Inverse Finance

The Inverse Finance exploit demonstrates a sophisticated Oracle Manipulation attack in the DeFi ecosystem. The attacker first withdrew 901 ETH from Tornado Cash, then injected 500 ETH into the INV/ETH pair on SushiSwap, artificially inflating the INV token price from around $400 to $1.79 million. The critical vulnerability lay in Inverse Finance's reliance on this low-liquidity trading pair for its price oracle, despite using a TWAP mechanism [[43]](#43), [[44]](#44). By simultaneously spamming transactions, the attacker prevented arbitrage bots from normalizing the price. This strategy maintained the manipulated value across multiple blocks. The exploit allowed them to deposit just 1,700 INV tokens (worth approximately $644,000 at fair value) as collateral. With this minimal collateral, they borrowed $15.6 million in assets including WBTC, YFI, DOLA, and ETH, highlighting the dangers of using single-source oracles with low liquidity even when implementing time-weighted averaging [[43]](#43), [[45]](#45).

### [19] Hundred Finance

The Hundred Finance exploit leveraged an Exchange Rate Manipulation vulnerability in the protocol's smart contracts [[46]](#46). The attack targeted the relationship between hWBTC (receipt tokens) and WBTC (underlying asset). The primary vulnerability stemmed from unprotected exchange rate calculations in the getAccountSnapshot function, where exchangeRateMantissa was derived directly from contract balances without validation [[47]](#47). The attacker exploited this vulnerability through several precise steps. First, they obtained a flash loan of 500 WBTC from Aave. They then identified an unused hWBTC contract that existed parallel to the main contract used by the interface. This parallel contract became the attack vector. The attacker donated 500.3 WBTC to this contract, artificially inflating the exchange rate between hWBTC and WBTC. A secondary vulnerability compounded the issue: a rounding error in the redeemUnderlying function. This error became significant when processing transactions with manipulated exchange rates [[46]](#46). When the attacker subsequently redeemed a tiny amount of hWBTC tokens, the manipulated exchange rate allowed them to withdraw disproportionately large amounts of WBTC.

### [21] Lodestar Finance

The Lodestar Finance exploit demonstrates a sophisticated oracle price manipulation vulnerability affecting DeFi lending protocols [[48]](#48). The incident targeted the GLPOracle contract, which calculated the price of plvGLP tokens used as collateral in the protocol. The fundamental vulnerability stemmed from the oracle's inability to account for artificial inflation of asset values within a single transaction block. The attack mechanism involved manipulating the price oracle by exploiting the donate() function in the GlpDepositor contract [[48]](#48). By donating assets to the contract, the attacker could artificially inflate the total assets under management. Since the oracle calculated the plvGLP token price based on the ratio of total assets to total supply, this inflation significantly increased the reported collateral value. The oracle lacked safeguards against instantaneous price fluctuations within the same block, allowing the attacker to execute their strategy without triggering protective measures [[49]](#49).

### [24] Gamma Strategies

The Gamma Strategies exploit exemplifies a sophisticated price manipulation attack within DeFi concentrated liquidity management [[50]](#50). The attack leveraged flash loans to manipulate asset prices beyond predetermined tick ranges in the protocol's vaults. The primary vulnerability came from two interconnected design flaws. First, the protocol set excessively high price change thresholds (50-200%) for certain liquidity pools. These problematic configurations particularly affected pools containing stablecoins and liquid staking tokens [[50]](#50). Second, the system calculated user share tokens based on real-time prices without oracle verification, creating an exploitable attack vector during price fluctuations [[51]](#51). The attack methodology followed a systematic pattern. Initially, the attacker borrowed substantial amounts of tokens through flash loans. The attacker then used these funds to dramatically inflate the price of one asset (e.g., gDAI) beyond the supported tick range. This manipulation allowed the deposit of minimal assets to receive disproportionately large quantities of share tokens. Since the price exceeded the supported range, the protocol incorrectly handled the deposit. The system stored the attacker's tokens while issuing shares based on manipulated prices [[51]](#51). Subsequently, the attacker withdrew all shares, extracting significant liquidity from the pool despite minimal initial contribution. By iteratively manipulating prices above and below the supported range through the removeLiquidity and addLiquidity functions, the attacker systematically drained pool reserves. This process was repeated through multiple transaction cycles to maximize extraction of funds [[51]](#51).

### [26] KiloEx

The KiloEx exploit demonstrated a sophisticated oracle manipulation attack targeting smart contract access control vulnerabilities [[52]](#52). The attack exploited a critical design flaw in the contract permission hierarchy of the multichain protocol. At the core of the vulnerability lay KiloEx's MinimalForwarder contract, which lacked proper signature validation and input data verification [[53]](#53). The exploit leveraged a chain of interconnected contract calls. The attack vector targeted the setPrices function within the KiloPriceFeed contract. This function was ostensibly protected by a specific call sequence. The Keeper contract should only allow trusted calls to this function. The PositionKeeper contract should restrict access to the Keeper. Finally, the MinimalForwarder should validate all incoming requests [[52]](#52). However, the MinimalForwarder's execute function failed to properly validate transaction origins. The contract accepted forged signatures without verification. It also processed arbitrary function call data without validation. This critical flaw undermined the entire security model of the protocol [[53]](#53). The attacker exploited this vulnerability through a precise three-step process. First, they artificially manipulated the price of tokens downward using the compromised setPrices function. Second, they opened leveraged long positions at these artificially depressed prices. Third, they manipulated prices upward and immediately closed their positions for significant profit [[52]](#52).

### [30] Onyx Protocol

The Onyx Protocol hack exploited two vulnerabilities in the protocol's smart contracts [[54]](#54). The primary vulnerability stemmed from a well-known precision issue in Compound v2 forks that affects markets with low liquidity. The attack began with the exploiter obtaining a flash loan of 2,000 ETH from Balancer [[55]](#55). This provided the necessary capital to execute the attack without risking personal funds. The attacker then strategically split these funds, depositing 1,999.5 ETH into the oEther contract while allocating 0.5 ETH to their malicious contract [[55]](#55). The core exploitation leveraged a decimal precision vulnerability in Compound v2 forks [[54]](#54). This vulnerability affects the asset's exchange rate calculation when there is insufficient liquidity in a market. The recently added VUSD market failed to implement essential security measures specifically, the protocol did not follow best practices of minting and burning some tokens to prevent the market from becoming empty [[54]](#54). With this vulnerability exposed, the attacker executed a precise manipulation sequence. They repeatedly minted and redeemed extremely small amounts of oETH (as little as 0.00000001 oETH) [[55]](#55). This process was repeated 56 times, with each iteration further destabilizing the exchange rate calculations [[55]](#55). The cumulative effect of these operations caused significant distortion in the protocol's pricing mechanisms. Additionally, the exploiter identified and leveraged a second vulnerability in the protocol's NFTLiquidation contract [[54]](#54). This contract failed to properly validate untrusted user input, allowing the attacker to manipulate the self-liquidation reward amount [[54]](#54). By exploiting this validation flaw, the attacker could extract additional value during the liquidation process.

### [37] Rho Market

The Rho Market exploit occurred via oracle price manipulation on Scroll Layer 2 [[56]](#56). Initial compromise involved unauthorized ownership transfer through potential private key theft [[57]](#57). Attacker gained control of critical contract parameters. Oracle price feeds were subsequently manipulated, introducing deliberately inaccurate pricing data. This manipulation created exploitable arbitrage opportunities. A MEV bot detected and front-ran the attack, extracting approximately $7.5 million within minutes [[56]](#56). The bot drained USDC and USDT from lending pools by exploiting the differential between manipulated oracle prices and actual market values. Root cause analysis identified human error during deployment rather than code vulnerability [[57]](#57).

### [38] UwuLend

The UwuLend exploit utilized oracle price manipulation against the lending protocol [[58]](#58). The attacker exploited a critical vulnerability in the protocol's oracle system. UwuLend's contract was a fork of AAVE V2 with modified oracle fallback logic [[58]](#58). The attack began with a flash loan acquisition. This provided the attacker with substantial token liquidity [[59]](#59). The fallback oracle calculated asset prices based on several Curve pool states. The attacker manipulated these pool states through large trades using the borrowed tokens [[58]](#58). This manipulation created a price discrepancy between borrowing and liquidation rates. Specifically, the attacker could borrow sUSDe at 0.99 but liquidate positions at an inflated 1.03 rate [[58]](#58). This 4% difference, when applied to large transaction volumes, enabled the substantial theft.

### [44] Zunami Protocol

The Zunami Protocol exploit targeted a critical price manipulation vulnerability in the protocol's stablecoin mechanism [[60]](#60). The root cause was an incorrect computation of LP prices within the totalHoldings function. This function contained a specific weakness in strategies like MIMCurveStakeDao [[61]](#61). The attacker orchestrated a multi-step attack beginning with flash loans of 7 million USD from UniswapV3 and 7 million USDC plus 10,011 WETH from Balancer [[61]](#61). These borrowed funds enabled the manipulation of multiple liquidity pools. The exploit specifically involved intentional inflation of SDT tokens and sdtPrice parameters within the vulnerable contract. By adding substantial liquidity to CurveFinance and performing strategic token swaps, the attacker donated approximately 55,598 SDT tokens into the MIMCurveStakeDao [[61]](#61). This donation was the critical manipulation point. The attacker then stored a manipulated price snapshot within UZD using the cachessetPrice function. This cached price manipulation directly impacted balance calculations as the balance function in the UZD contract relied on this incorrect price [[61]](#61). The exploit drained Zunami's zETH and UZD liquidity pools on Curve, causing the 'zStables' to depeg by 85% and 99% respectively [[60]](#60). After extracting value, the attacker reversed all price manipulation actions, ensuring artificially inflated UZD was swapped for profit.

### [48] Jimbo's Protocol

The Jimbo's Protocol attack exploited a critical vulnerability in slippage control within the JimboController contract's shift() function [[62]](#62). The attacker leveraged this weakness to manipulate token prices and drain liquidity from the protocol [[63]](#63). First, the attacker obtained a flash loan of 10,000 ETH from an external protocol [[63]](#63). Using these borrowed funds, the attacker purchased large amounts of JIMBO tokens through the protocol's ETH-JIMBO trading pair, artificially inflating JIMBO's price [[63]](#63). The attacker then deposited 100 JIMBO tokens into the JimboController contract and called the vulnerable shift() function [[63]](#63). This function, which lacked proper access controls, allowed anyone to execute arbitrary liquidity operations [[63]](#63). The shift() function triggered a rebalancing operation that moved the contract's WETH liquidity back into the pool [[62]](#62). Due to the manipulated price imbalance between WETH and JIMBO tokens, the attacker could extract more WETH than initially invested [[63]](#63). Finally, the attacker sold their remaining JIMBO tokens to drain additional WETH from the pool, repaid the flash loan, and secured approximately 4,090 ETH in profit [[63]](#63). The fundamental vulnerability was the lack of slippage protection in the shift() function, which allowed price manipulation attacks [[62]](#62). Additionally, insufficient access controls permitted any user to trigger critical rebalancing operations [[63]](#63).

## 🚨 Rounding Errors Incidents 🚨

Rounding errors and precision loss vulnerabilities occur when mathematical operations in smart contracts produce unexpected results due to integer division, improper scaling, or inadequate handling of decimal values.

### [9] Sonne Finance

The Sonne Finance exploit demonstrated a critical Rounding Error vulnerability in Solidity's integer arithmetic [[64]](#64), [[65]](#65). The attacker strategically used a flash loan to borrow VELO tokens and target an empty soVELO market with minimal totalSupply. By donating tokens without minting corresponding soTokens, they created a scenario that dramatically inflated the totalCash while artificially maintaining an extremely low token supply. This manipulation engineered an intentionally distorted exchangeRate, where the contract's internal accounting became fundamentally skewed. During the token redemption process, the integer division mechanism systematically rounded the calculation value of 1.999994 down to 1, discarding the fractional component. This rounding error mathematically enabled the extraction of a disproportionate number of tokens with minimal initial collateral [[64]](#64).

### [17] zkLend

The zkLend exploit leveraged a fundamental rounding error and precision loss vulnerability in the protocol's smart contract [[66]](#66), [[67]](#67). The attacker first initiated an extremely small deposit, followed by strategic donations via flash loans to artificially inflate the lending_accumulator to an abnormally high value. Since blockchain smart contracts operate exclusively with integers, mathematical operations must handle decimal values carefully [[68]](#68). The safe_decimal_math::div() function in zkLend's contract performed floor division, causing significant rounding errors when values were scaled down. This rounding behavior meant that when calculating burned deposit certificates during withdrawals, the system consistently burned fewer tokens than it should have. By manipulating this precision loss, the attacker executed repeated deposits and withdrawals of wstETH. Each transaction benefited from the rounding discrepancy, allowing the attacker to artificially inflate their token balance. The contract failed to implement minimum thresholds or accumulator bounds in its design. This deficiency, combined with inadequate precision handling in mathematical operations, transformed what would normally be negligible rounding errors into an exploitable vulnerability for substantial gain.

### [20] Abracadabra Money

The Abracadabra Money exploit occurred due to a critical precision loss vulnerability in the CauldronV4 contracts [[69]](#69). At its core, this precision loss stemmed from a business logic flaw where the debt tracking mechanism failed to synchronize two critical values: elastic and base. The elastic value represents the total token amount to be repaid by borrowers, while the base value represents the total parts of debt held by all borrowers [[70]](#70).

The exploit began with the attacker obtaining a flashloan of MIM tokens from Degenbox. They then donated these tokens to the BentoBox contract, leveraging the ERC-4626 first depositor attack vector. The critical vulnerability emerged when the attacker called the repayForAll() function, which was designed to repay all debt and set totalBorrow.elastic to zero [[70]](#70). However, the function lacked proper logic to also reset totalBorrow.base to zero a fundamental business logic error.

This discrepancy created a state where totalBorrow.elastic was zero while totalBorrow.base remained at its previous value. When these values were used in subsequent calculations, extreme precision loss occurred. The Rebase library's division operations produced rounding errors that normally would be negligible, but became catastrophic in this edge case scenario. The attacker exploited this precision deterioration by repeatedly calling userBorrowPart() and repay() functions, manipulating the part parameter through accumulated rounding errors [[69]](#69).

With each borrowing and repayment cycle, the part value grew exponentially due to division against a fixed totalBorrow.base while totalBorrow.elastic remained at zero. This manipulation effectively bypassed the protocol's solvency checks. The borrowed part values appeared negligible compared to the total debt parts tracked by _totalBorrow.base, allowing the attacker to drain liquidity from the affected cauldrons without triggering protective mechanisms [[69]](#69).

This vulnerability is a combination of business logic flaws and precision loss. The root cause was a flaw in the debt-tracking logic, while the attack itself leveraged precision errors in arithmetic operations, which were worsened by rounding issues in integer division.

### [36] Raft Protocol

The Raft Protocol exploit represents a precision-based vulnerability in token share calculations [[71]](#71). The attack targeted the InterestRatePositionManager contract's storedIndex variable manipulation [[72]](#72). The vulnerability originated in the protocol's implementation of a rebasing token mechanism [[71]](#71). In the rcbETH contract, the balanceOf function calculated token balances by multiplying native balances with a variable called storedIndex to determine final balances [[71]](#71). The attacker initiated the exploit by obtaining 6,000 cbETH through a flash loan [[71]](#71). After transferring 6,001 cbETH to the vulnerable contract, they triggered the liquidate function on a pre-created position [[71]](#71). This function call manipulated the storedIndex variable through a logic vulnerability, artificially inflating it to thousands of times its intended value [[71]](#71). Exploiting a rounding precision flaw in the divUp function of the cbETH contract's minting process, the attacker executed the managePosition function 60 times [[71]](#71). Each call used only 1 wei of cbETH to mint 1 wei of rcbETH-c [[71]](#71). Due to the inflated storedIndex, these minimal rcbETH-c tokens represented significantly higher value within the system [[71]](#71). With the artificially inflated rcbETH-c balance, the attacker leveraged the managePosition function again to borrow 6.7 million R tokens [[72]](#72). These tokens were swapped for various stablecoins and ultimately converted to ETH [[71]](#71). Ironically, the attack failed in its final stage. When attempting to extract profits using delegatecall, the attacker inadvertently sent 1,570 ETH to the zero address due to storage slot initialization issues [[72]](#72). This error resulted in the attacker gaining only 7 ETH after repaying the flash loan [[71]](#71).

## 🚨 Input Validation Failure Incidents 🚨

Input validation failures occur when smart contracts accept and process untrusted inputs without adequate verification, leading to unexpected behaviors or security breaches.

### [13] Ionic Money

This exploit stemmed from a critical vulnerability that combined improper smart contract validation with the absence of access control over token minting. Specifically, the LBTC token contract lacked appropriate constraints, enabling the attacker to arbitrarily mint an unlimited supply of fake tokens. Moreover, Ionic Money's protocol did not implement sufficient authentication or verification mechanisms to assess the legitimacy of the LBTC contract. Despite this oversight, the protocol accepted the counterfeit LBTC tokens as valid collateral. As a result, the attacker was able to supply these illegitimate tokens to the lending pools. They subsequently borrowed real and valuable assets in exchange, causing significant financial damage to the platform [[73]](#73), [[74]](#74).

### [18] LI.FI Protocol

In the LI.FI protocol attack, a critical vulnerability in the smart contract's logic allowed an attacker to drain tokens from user wallets. The exploit combined two key security weaknesses in the depositToGasZipERC20 function of GasZipFacet.sol [[75]](#75). The first was an access control vulnerability in the newly deployed facet. This component lacked the whitelist verification that existed in other parts of the protocol. This meant external calls weren't restricted to trusted addresses. The parameters _swap.callTo and _swap.callData were user-controlled without proper validation [[76]](#76). The second was an unchecked call return value vulnerability [[77]](#77). Low-level calls through LibSwap.swap were executed without validating inputs or properly handling return values. By exploiting these vulnerabilities, the attacker crafted malicious calldata with transferFrom() function calls. This technique enabled draining tokens from wallets that had granted infinite approvals to the LI.FI contract.

### [29] DeltaPrime

The DeltaPrime exploit demonstrated multiple critical vulnerabilities in smart contract input validation mechanisms [[78]](#78). The first vulnerability manifested in the swapDebtParaSwap function, which contained critical input validation flaws. This function failed to properly validate the _repayAmount parameter before passing it to the swap adapter [[78]](#78). The attacker leveraged this weakness to manipulate debt repayment processes. They were able to borrow 1.18 WBTC against 59.9 ETH collateral without triggering repayment verification.

The second vulnerability existed in the claimReward() function's handling of external contract inputs. This function accepted arbitrary contract addresses as the pair parameter without proper validation [[78]](#78). The absence of adequate input sanitization created an exploitable attack vector. The attacker passed a malicious contract address that could manipulate the protocol's internal balance tracking.

The exploitation process followed a carefully orchestrated sequence. First, the attacker initiated a flash loan to obtain the necessary capital [[79]](#79). They then deposited ETH as collateral and borrowed WBTC through the vulnerable lending mechanism. By exploiting the swapDebtParaSwap function, they redirected the borrowed assets to their malicious contract without proper accounting [[78]](#78).

In the final stage, the attacker leveraged the claimReward() vulnerability to manipulate system state. Their malicious contract triggered the wrapNative() function, converting ETH to WETH and altering internal balance records [[78]](#78). This manipulation caused the protocol to incorrectly identify the attacker's collateral as claimable rewards. This allowed them to extract their original collateral while retaining the borrowed assets.

### [32] Dough Finance

The Dough Finance attack exploited a critical lack of input validation in smart contract callbacks [[80]](#80). The vulnerability was centered in the ConnectorDeleverageParaswap contract, which failed to validate external calldata before execution [[80]](#80). The attack began with the attacker initiating flash loans from AAVE [[80]](#80). These borrowed funds were used to repay USDC debt on behalf of victim DoughDsa contracts, creating conditions necessary for the subsequent exploitation [[80]](#80). The exploit targeted Dough's deloop feature, designed to unwind leveraged positions [[80]](#80). This functionality contained a critical validation flaw in its processing of external calls. The contract blindly executed the paraswapCallData parameter without proper verification, allowing arbitrary code execution [[80]](#80). The attacker crafted malicious calldata consisting of two segments: the first legitimately increased USDC collateral while the second contained arbitrary external calls [[80]](#80). After debt repayment, the attacker manipulated victim contracts to withdraw all WETH collateral through these unvalidated function calls [[80]](#80). The second segment of the crafted calldata directly targeted the WETH contract, specifying transferFrom() as the method to execute [[80]](#80). Since the ConnectorDeleverageParaswap contract failed to validate this calldata before execution, it effectively gave the attacker control over users' assets [[80]](#80), [[81]](#81). The attacker repeated this process on multiple DoughDSA contracts, ultimately stealing approximately 2.11 million [[81]](#81). The stolen funds were later laundered through privacy tools including Tornado Cash [[81]](#81). This exploit exemplifies a classic arbitrary call vulnerability, where insufficient input validation allows attackers to execute unauthorized operations with the contract's privileges [[80]](#80).

### [35] Team Finance

The Team Finance attack exploited a critical business logic vulnerability in the protocol's migration functionality [[82]](#82). The core vulnerability resided in the migrate() function, which failed to verify consistency between migrated and locked tokens [[83]](#83). The attack mechanism leveraged a fundamental verification flaw that allowed arbitrary token locking to bypass ownership validation [[83]](#83). By locking unrelated tokens, the attacker could migrate Uniswap V2 liquidity positions that did not belong to them [[82]](#82). The exploit execution involved creating fake token locks and extending their lock time to circumvent migration restrictions [[83]](#83). This preparation enabled the attacker to call the vulnerable migration function with manipulated parameters where the migrated tokens differed from the locked tokens [[83]](#83). The attacker specified a migration ratio of only 1%, causing the v3Migrator.migrate() function to burn the original LP tokens and transfer only a minimal portion to the V3 pool [[83]](#83). The remaining 99% of tokens were refunded to the caller according to the migration logic [[83]](#83).

### [42] Seneca Protocol

The Seneca Protocol exploit targeted a critical vulnerability in the Chamber contract's external call handling mechanism [[84]](#84). The root cause was improper validation of parameters in the performOperations() function. This vulnerability allowed arbitrary external calls with crafted input data [[85]](#85). By setting the actions[0] parameter to 30, the attacker triggered the internal call function. This action enabled execution of malicious external calls [[84]](#84). The attacker constructed calldata designed to invoke the transferFrom() function on approved token contracts. These malicious calls redirected tokens from users' wallets directly to the attacker's address. Users had previously approved the Chamber contract to manage their tokens. As a result, the malicious transactions appeared legitimate to the token contracts. The exploit circumvented intended access controls effectively. The contract failed to verify the legitimacy of external call destinations and parameters [[85]](#85). The protocol lacked emergency mitigation capabilities due to improperly implemented pause functionality. The pause() and unpause() functions were declared as internal-only. This implementation prevented administrators from halting operations during the attack [[85]](#85).

## 🚨 Business Logic Flaws Incidents 🚨

Business logic flaws occur when the implemented contract logic does not correctly model the intended business rules or contains inconsistencies in how operations should be sequenced.

### [7] KyberSwap

In the attack on KyberSwap Elastic, the logical bug that was exploited specifically related to the function isCurrentTickInitialized. This function is responsible for determining whether a tick is active, which is a crucial part of the pricing system and trade computation. In a mechanism similar to Uniswap v3, each tick must have a specific state for a crossing operation to be permitted. To perform this operation, the system needs to check whether there is liquidity at that tick, as this information is vital to decide whether the tick can be crossed [[86]](#86).

However, in this case, the bug stemmed from the fact that isCurrentTickInitialized mistakenly treated the liquidity resulting from reinvestment positions (which represent reinvested earnings) as active liquidity. As a result, the system incorrectly assumed that certain ticks—ones that should not have been active—had active liquidity, and therefore, crossing was deemed unnecessary. The attacker leveraged a flash loan and artificially shifted the price close to these ticks, exploiting the logical flaw to bypass the crossing mechanism and earn a significant profit without triggering defensive safeguards [[87]](#87), [[86]](#86).

### [16] Yearn Finance

The Yearn Finance exploit occurred due to a critical misconfiguration in the yUSDT contract that had remained undetected for over three years [[88]](#88). The vulnerability originated in a copy/paste error in the yUSDT contract code. Specifically, the Fulcrum iUSDC address was incorrectly used in place of the proper Fulcrum iUSDT address within the contract's underlying asset basket [[89]](#89). This mismatch allowed the attacker to manipulate the underlying share price calculations of yUSDT tokens. By exploiting this price discrepancy, the attacker was able to mint an enormous quantity (1.2 quadrillion) of yUSDT tokens using just 10,000 USDT as initial capital. These artificially created tokens were then swapped for legitimate stablecoins across various protocols, resulting in substantial losses before the immutable contract could be addressed.

### [28] Abracadabra Money

The Abracadabra Money incident exposed a significant business logic vulnerability in cross-protocol state management within DeFi lending systems [[90]](#90). This vulnerability manifested as state desynchronization between different contract components, creating a critical security flaw. The attack exploited how the protocol tracked collateral positions across system boundaries [[91]](#91). When users deposited assets into GMX via Abracadabra's cauldrons, the protocol employed an OrderAgent contract to manage these cross-protocol interactions. A flaw in this design created the opportunity for manipulation.

The attacker first initiated a deposit into GMX specifically designed to fail [[90]](#90). Due to improper error handling, these tokens remained in the OrderAgent contract rather than returning to the depositor. This created the first state inconsistency: assets remained in the system despite the failed transaction. Next, the attacker borrowed funds against this position and deliberately pushed it into liquidation territory [[91]](#91). The critical vulnerability emerged during the self-liquidation process. The protocol correctly marked the main position record as liquidated. However, it failed to properly update all associated state variables.

Specifically, the system removed the user's debt record but failed to invalidate the order data containing information about the collateral. This incomplete state update created the central business logic flaw [[90]](#90). The protocol now contained two contradictory states: the primary position record showed the position as liquidated. Yet the order system still recognized valid collateral.

This desynchronization created what security researchers term phantom collateral assets that should no longer be accessible. These assets remained available in the contract's state despite their logical invalidation. In the final exploitation stage, the attacker leveraged this state inconsistency by borrowing against the supposedly liquidated position [[91]](#91).

## 🚨 Dangerous Delegatecall Incidents 🚨

Dangerous delegatecall vulnerabilities occur when contracts use the delegatecall operation without proper validation of the target or execution context, allowing attackers to execute arbitrary code with the caller's privileges.

### [41] Unizen

The Unizen exploit leveraged an unverified external call vulnerability in the protocol's DEX aggregation contract [[92]](#92). This vulnerability was introduced during a contract upgrade intended to optimize gas costs [[93]](#93). The attack targeted users who had previously approved token spending limits. The attack mechanism involved exploiting the external call vulnerability in the upgraded contract. Multiple attackers identified weaknesses in the external call validation logic [[92]](#92). This allowed malicious contracts to execute unauthorized transactions using existing token approvals. The exploit specifically targeted the permission boundaries within the contract's external call implementation [[93]](#93). The attackers executed at least 27 malicious transactions across multiple addresses. Four distinct attackers were identified, utilizing different attack contracts [[92]](#92). The protocol's CTO confirmed the vulnerability was a "minor bug with great consequences" related to the gas optimization upgrade [[93]](#93). This characterization highlights how seemingly small implementation issues in external call validation can lead to significant security breaches.

### [43] OKX DEX

The OKX DEX attack exploited a Private Key Compromise vulnerability in the protocol's proxy upgrade mechanism [[94]](#94). The attacker obtained unauthorized access to the Proxy Admin Owner's private key, enabling execution of malicious contract upgrades [[95]](#95). The exploitation occurred in two phases. The attacker deployed a corrupted implementation for the DEX Proxy contract [[95]](#95). This modified implementation allowed direct invocation of the claimTokens function. A second similar upgrade followed at 11:53 PM UTC to continue the theft. The successful attack was possible because the compromised key held unrestricted authority to replace implementation contracts [[94]](#94). The malicious contract deliberately targeted user-approved tokens by calling transferFrom() on assets previously authorized to the protocol [[95]](#95). The attack leveraged the delegatecall pattern essential to upgradeable contracts. This mechanism allows proxy contracts to execute logic from implementation contracts while maintaining their storage context [[95]](#95). By redirecting this pattern to malicious code, the attacker effectively hijacked all token approvals granted to the protocol.

## 🚨 Storage Collisions Incidents 🚨

Storage collisions occur when different variables in a smart contract inadvertently share the same storage slot, allowing changes to one variable to affect the other.

### [27] SIR Trading

The SIR Trading exploit demonstrates a sophisticated attack targeting Ethereum's newly introduced transient storage feature [[96]](#96). The vulnerability originated from improper implementation of the TSTORE and TLOAD opcodes introduced in Ethereum's Dencun upgrade [[97]](#97). The attack centered on a critical storage collision vulnerability in the protocol's uniswapV3SwapCallback function. This function utilized transient storage slot 0x1 for dual purposes: storing both the Uniswap pool address and the token mint amount [[96]](#96). This dual usage created a security vulnerability where one value would overwrite the other in the same memory location. The attacker executed the exploit through several meticulously planned steps. First, they brute-forced a vanity address that, when interpreted as a number, equaled a mathematically precise value chosen to perfectly align with the exploit's requirements [[96]](#96). This mathematical precision was essential for the exploit. Next, they deployed malicious tokens and a UniswapV3 pool to lay the groundwork for the attack. When the protocol's mint function executed, it stored the legitimate Uniswap pool address in transient storage slot 0x1. However, the function subsequently overwrote this slot with the precisely calculated mint amount. The attacker then deployed their attack contract using CREATE2, ensuring its address matched their calculated value [[96]](#96). This allowed them to call uniswapV3SwapCallback directly. The vulnerability's exploitation hinged on the protocol's security verification. When the callback function checked transient storage slot 0x1 to verify the caller, it found the attacker's address instead of the legitimate pool address [[97]](#97).

## Integer Underflow

Integer underflow vulnerabilities occur when arithmetic operations produce results that are too small to be represented by the variable's type, causing unexpected wrap-around behavior.

### [22] 1Inch

In the 1inch attack, the vulnerability stemmed from an issue in the deprecated _settleOrder function within the Fusion v1 resolver contracts. This function, part of 1inch's older architecture, had a critical calldata corruption vulnerability caused by improper handling of the interactionLength parameter. Specifically, the attacker exploited an integer underflow by setting the interactionLength to a negative value, causing memory pointers to underflow and redirecting function calls to unintended locations. This manipulation allowed the attacker to hijack the function's logic and gain unauthorized access to contract states. By exploiting this issue, the attacker was able to initiate a series of transactions that manipulated the _settleOrder function's logic. The attacker padded the calldata with null bytes and used the negative value to corrupt the function's execution, bypassing security checks in place. This manipulation led to the extraction of funds from the affected resolvers. The exploit underscores the risks associated with using deprecated code in live protocols, where previously unseen vulnerabilities can resurface due to unaddressed architectural flaws. [[98]](#98), [[99]](#99).

### [39] Velocore

The Velocore exploit targeted a vulnerability in the ConstantProductPool contract's fee calculation logic [[100]](#100). The root cause was an unchecked arithmetic operation in the Balancer-style CPMM pool contract. The attack focused on two key vulnerabilities in the smart contract implementation. First, the feeMultiplier variable could be manipulated through direct invocation of the velocore__execute() function [[101]](#101). This function lacked proper caller verification, allowing the attacker to simulate large withdrawals [[100]](#100). These simulated withdrawals increased the feeMultiplier variable to an abnormally high value. Second, an arithmetic underflow occurred in the single-token withdrawal logic [[100]](#100). The effective fee calculation effectiveFee1e9 = (effectiveFee1e9 * feeMultiplier) / 1e9 could exceed 100%, causing the expression 1e18 - ((1e18 - k) * effectiveFee1e9) to underflow [[100]](#100). This transformed what should have been a liquidity withdrawal into a massive liquidity deposit. The attacker executed the exploit in three phases: manipulating the feeMultiplier, contracting the pool with a flash loan, and exploiting the underflow with a small single-token withdrawal [[100]](#100).

## 🚨 Governance Incidents 🚨

Governance vulnerabilities occur when decentralized governance mechanisms are manipulated due to inadequate validation, low participation, or improper implementation.

### [34] Tornado Cash

The Tornado Cash governance attack demonstrates a sophisticated exploitation of smart contract upgrade mechanisms and governance systems [[102]](#102). The vulnerability stemmed from insufficient verification of proposal contract code and the misuse of Ethereum's low-level opcodes [[103]](#103). The attack began with the creation of a malicious governance proposal that mimicked a legitimate previous proposal [[102]](#102). This proposal included hidden malicious functionality, specifically a selfDestruct mechanism that was not apparent to voters [[103]](#103). The community approved this trojan proposal, believing it to be identical to the previously verified one. After approval, the attacker exploited a vulnerability in Ethereum's address derivation mechanism by combining CREATE and CREATE2 opcodes [[102]](#102), [[104]](#104). This technique enabled the deployment of a contract at a deterministic address. The attacker used a deployer contract to create the initial malicious proposal, then employed selfDestruct to erase the approved code [[102]](#102). The critical vulnerability lay in the governance system's failure to verify that the contract code remained unchanged after approval [[103]](#103). After selfDestruct, the attacker redeployed different code to the same address by resetting their nonce, effectively replacing the approved contract with entirely new malicious logic [[102]](#102). This replacement contract contained logic that granted 10,000 TORN tokens to multiple attacker-controlled addresses [[103]](#103). The attacker accumulated 1.2 million governance votes against only 70,000 legitimate votes, seizing control of the entire governance system [[103]](#103).

### [46] Atlantis Loans

The Atlantis Loans exploit targeted critical governance vulnerabilities in a BSC-based lending protocol [[105]](#105). The primary vulnerability resided in the GovernorBravo contract's proposal verification mechanism which only validated the eta parameter (unlock time) during proposal queuing [[106]](#106). The attacker initiated a malicious governance proposal (ID: 52) targeting the GovernorBravo contract [[106]](#106). This proposal aimed to designate multiple ABep20Delegator contracts' administrators as malicious contracts. The project's abandonment resulted in minimal community oversight, allowing the proposal to pass successfully [[105]](#105). Following a mandatory timelock period of 172,800 seconds, the malicious contract gained proxy administration rights for all protocol tokens [[106]](#106). The attacker subsequently modified the ABep20Delegate implementation address, replacing it with a backdoored contract (0x613cc544053812ab026d60361212cdb67b46f42f). This contract modification enabled unauthorized access to user assets through existing token approvals. Despite the protocol having no remaining user deposits due to abandonment, many users retained active approvals to the Atlantis Loans smart contracts [[105]](#105).

---

## References

<a id="1"></a>[1] Immunebytes, "Euler Finance Hack - Mar 13, 2023: Detailed Hack Analysis," Immunebytes Blog, Mar. 2023. [Online]. Available: [https://immunebytes.com/blog/euler-finance-hack-mar-13-2023-detailed-hack-analysis/](https://immunebytes.com/blog/euler-finance-hack-mar-13-2023-detailed-hack-analysis/). [Accessed: 2025-03-29].

<a id="2"></a>[2] SlowMist, "SlowMist: An Analysis of the Attack on Euler Finance," SlowMist Medium, Mar. 2023. [Online]. Available: [https://slowmist.medium.com/slowmist-an-analysis-of-the-attack-on-euler-finance-5143abc0d5ad](https://slowmist.medium.com/slowmist-an-analysis-of-the-attack-on-euler-finance-5143abc0d5ad). [Accessed: 2025-03-29].

<a id="3"></a>[3] Rekt News, "Euler REKT," Rekt News, 2023. [Online]. Available: [https://rekt.news/euler-rekt](https://rekt.news/euler-rekt). [Accessed: 2025-04-15].

<a id="4"></a>[4] Rekt News, "Nomad Bridge - REKT," Rekt News, Aug. 2022. [Online]. Available: [https://rekt.news/nomad-rekt](https://rekt.news/nomad-rekt). [Accessed: 2022-08].

<a id="5"></a>[5] Nomad XYZ, "Nomad Bridge Hack Root Cause Analysis," Medium, 2022. [Online]. Available: [https://medium.com/nomad-xyz-blog/nomad-bridge-hack-root-cause-analysis-875ad2e5aacd](https://medium.com/nomad-xyz-blog/nomad-bridge-hack-root-cause-analysis-875ad2e5aacd). [Accessed: 2025-03-29].

<a id="6"></a>[6] Y. Gushiken, "Rogue Developer Suspected in Infini Neobank's $49.5M Exploit," The Shib Daily, Feb. 24, 2025. [Online]. Available: [https://news.shib.io/2025/02/24/rogue-developer-suspected-in-infini-neobanks-49-5m-exploit/](https://news.shib.io/2025/02/24/rogue-developer-suspected-in-infini-neobanks-49-5m-exploit/).

<a id="7"></a>[7] Rekt News, "Infini - Rekt," Rekt News, 2025. [Online]. Available: [https://rekt.news/infini-rekt](https://rekt.news/infini-rekt). [Accessed: 2025-04-13].

<a id="8"></a>[8] Blockbasis, "Holograph Protocol Hack: Mitigating the $14.4 Million Exploit," Blockbasis, Jun. 2024. [Online]. Available: [https://www.blockbasis.com/p/holograph-protocol-hack-mitigating-the-14-4-million-exploit](https://www.blockbasis.com/p/holograph-protocol-hack-mitigating-the-14-4-million-exploit). [Accessed: 2024-06-19].

<a id="9"></a>[9] Halborn, "Explained: The Holograph Hack (June 2024)," Halborn Blog, Jun. 2024. [Online]. Available: [https://www.halborn.com/blog/post/explained-the-holograph-hack-june-2024](https://www.halborn.com/blog/post/explained-the-holograph-hack-june-2024). [Accessed: 2024-06-20].

<a id="10"></a>[10] QuillAudits, "Decoding Deus DAO $6.5M Exploit," QuillAudits Medium, 2023. [Online]. Available: [https://quillaudits.medium.com/decoding-deus-dao-6-5-million-exploit-quillaudits-588bbecec61f](https://quillaudits.medium.com/decoding-deus-dao-6-5-million-exploit-quillaudits-588bbecec61f). [Accessed: 2025-04-15].

<a id="11"></a>[11] Cyvers.ai, "Deus Finance Hack: An In-Depth Analysis of the $6.5 Million Loss," Cyvers Blog, 2023. [Online]. Available: [https://cyvers.ai/blog/deus-finance-hack-an-in-depth-analysis-of-the-6-5-million-loss](https://cyvers.ai/blog/deus-finance-hack-an-in-depth-analysis-of-the-6-5-million-loss). [Accessed: 2025-04-15].

<a id="12"></a>[12] Rekt News, "RoninNetworkRektII," Rekt News, Aug. 7, 2024. [Online]. Available: [https://rekt.news/roninnetwork-rektII](https://rekt.news/roninnetwork-rektII). [Accessed: 2025-04-17].

<a id="13"></a>[13] Shashank, "RoninBridgeHack Analysis," SolidityScan Blog, Aug. 13, 2024. [Online]. Available: [https://blog.solidityscan.com/ronin-bridge-hack-analysis-d8f64b8fe683](https://blog.solidityscan.com/ronin-bridge-hack-analysis-d8f64b8fe683). [Accessed: 2025-04-17].

<a id="14"></a>[14] LI.FI, "Incident Report - 16th July," LI.FI Knowledge Hub, 2023. [Online]. Available: [https://li.fi/knowledge-hub/incident-report-16th-july/](https://li.fi/knowledge-hub/incident-report-16th-july/). [Accessed: 2025-04-17].

<a id="15"></a>[15] SolidityScan, "LI.FI Hack Analysis," SolidityScan Blog, 2023. [Online]. Available: [https://blog.solidityscan.com/li-fi-hack-analysis-521388128d22](https://blog.solidityscan.com/li-fi-hack-analysis-521388128d22). [Accessed: 2025-04-17].

<a id="16"></a>[16] SlowMist, "SlowMist Monthly Security Report: Total Losses for July Approx. $279 Million," SlowMist Medium, 2023. [Online]. Available: [https://slowmist.medium.com/slowmist-monthly-security-report-total-losses-for-july-approximate-279-million-2bb63973d4bf](https://slowmist.medium.com/slowmist-monthly-security-report-total-losses-for-july-approximate-279-million-2bb63973d4bf). [Accessed: 2025-04-17].

<a id="17"></a>[17] BlockApex, "Shezmu Hack Analysis," BlockApex Medium, 2024. [Online]. Available: [https://blockapex.medium.com/shezmu-hack-analysis-32414e67c7a0](https://blockapex.medium.com/shezmu-hack-analysis-32414e67c7a0). [Accessed: 2025-04-18].

<a id="18"></a>[18] CyberStrategy1, "Crypto Security Truths — Issue #13," Medium, 2024. [Online]. Available: [https://cyberstrategy1.medium.com/crypto-security-truths-issue-13-098b78916272](https://cyberstrategy1.medium.com/crypto-security-truths-issue-13-098b78916272). [Accessed: 2025-04-18].

<a id="19"></a>[19] Shashank, "Dexible Hack Analysis — Never Blindly Trust Smart Contracts," SolidityScan Blog, 2023. [Online]. Available: [https://blog.solidityscan.com/dexible-hack-analysis-never-blindly-trust-smart-contracts-c2aee7943c1a](https://blog.solidityscan.com/dexible-hack-analysis-never-blindly-trust-smart-contracts-c2aee7943c1a). [Accessed: 2025-04-23].

<a id="20"></a>[20] Rekt News, "Dexible - Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/dexible-rekt](https://rekt.news/dexible-rekt). [Accessed: 2025-04-23].

<a id="21"></a>[21] REKT, "Curio – Rekt," Rekt News, Mar. 26, 2024. [Online]. Available: [https://rekt.news/curio-rekt](https://rekt.news/curio-rekt). [Accessed: 2025-04-28].

<a id="22"></a>[22] R. Behnke, "Explained: The Curio Hack (March 2024)," Halborn Blog, Apr. 1, 2024. [Online]. Available: [https://www.halborn.com/blog/post/explained-the-curio-hack-march-2024](https://www.halborn.com/blog/post/explained-the-curio-hack-march-2024). [Accessed: 2025-04-28].

<a id="23"></a>[23] CryptoRank, "The Swaprum Incident: Audited DeFi Protocol Dupes Investors Out $3M," CryptoRank News, 2023. [Online]. Available: [https://cryptorank.io/ru/news/feed/cdce4-the-swaprum-incident-audited-defi-protocol-dupes-investors-out-3m](https://cryptorank.io/ru/news/feed/cdce4-the-swaprum-incident-audited-defi-protocol-dupes-investors-out-3m). [Accessed: 2023].

<a id="24"></a>[24] Rekt News, "Swaprum Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/swaprum-rekt](https://rekt.news/swaprum-rekt). [Accessed: 2023].

<a id="25"></a>[25] REKT News, "Fei Rari - REKT," Rekt News, May 2022. [Online]. Available: [https://rekt.news/fei-rari-rekt](https://rekt.news/fei-rari-rekt). [Accessed: 2025-03-29].

<a id="26"></a>[26] CertiK, "Fei Protocol Incident Analysis," CertiK Medium, 2022. [Online]. Available: [https://certik.medium.com/fei-protocol-incident-analysis-8527440696cc](https://certik.medium.com/fei-protocol-incident-analysis-8527440696cc). [Accessed: 2025-04-13].

<a id="27"></a>[27] Olympix, "Penpie Exploit: A Technical Post-Mortem Analysis," Olympix Medium, Sep. 2024. [Online]. Available: [https://olympixai.medium.com/penpie-exploit-a-technical-post-mortem-analysis-db25af537cc1](https://olympixai.medium.com/penpie-exploit-a-technical-post-mortem-analysis-db25af537cc1). [Accessed: 2024-09-06].

<a id="28"></a>[28] SolidityScan, "Penpie Hack Analysis," SolidityScan Blog, Sep. 2024. [Online]. Available: [https://blog.solidityscan.com/penpie-hack-analysis-29034a6f2a61](https://blog.solidityscan.com/penpie-hack-analysis-29034a6f2a61). [Accessed: 2024-09-05].

<a id="29"></a>[29] REKT News, "Conic Finance - REKT," Rekt News, Jul. 2023. [Online]. Available: [https://rekt.news/conic-finance-rekt](https://rekt.news/conic-finance-rekt).

<a id="30"></a>[30] SolidityScan Team, "CloberDEX Liquidity Vault Hack Analysis," SolidityScan Blog, 2024. [Online]. Available: [https://blog.solidityscan.com/cloberdex-liquidity-vault-hack-analysis-f22eb960aa6f](https://blog.solidityscan.com/cloberdex-liquidity-vault-hack-analysis-f22eb960aa6f). [Accessed: 2025-04-25].

<a id="31"></a>[31] REKT News, "CloberDEX - REKT," Rekt News, 2024. [Online]. Available: [https://rekt.news/cloberdex-rekt](https://rekt.news/cloberdex-rekt). [Accessed: 2025-04-25].

<a id="32"></a>[32] Rekt News, "EraLend REKT: Read-only Re-entrancy Exploit Steals $3.4M," Rekt News, 2023. [Online]. Available: [https://rekt.news/eralend-rekt](https://rekt.news/eralend-rekt). [Accessed: 2025-04-29].

<a id="33"></a>[33] Bitcoinist, "EraLend Exploit: Hackers Steal $3.4 Million From zkSync Lending Protocol," CryptoRank News, 2023. [Online]. Available: [https://cryptorank.io/news/feed/ad957-eralend-exploit-hackers-steal-3-4-million-dollars](https://cryptorank.io/news/feed/ad957-eralend-exploit-hackers-steal-3-4-million-dollars). [Accessed: 2025-04-29].

<a id="34"></a>[34] Rekt News, "Sturdy - Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/sturdy-rekt](https://rekt.news/sturdy-rekt). [Accessed: 2025-05-04].

<a id="35"></a>[35] SolidityScan Team, "Sturdy Finance Hack Analysis," SolidityScan Blog, 2023. [Online]. Available: [https://blog.solidityscan.com/sturdy-finance-hack-analysis-bd8605cd2956](https://blog.solidityscan.com/sturdy-finance-hack-analysis-bd8605cd2956). [Accessed: 2025-05-04].

<a id="36"></a>[36] SlowMist, "An Analysis of the Attack on Orion Protocol," SlowMist Medium, 2023. [Online]. Available: [https://slowmist.medium.com/an-analysis-of-the-attack-on-orion-protocol-c7aef70aff83](https://slowmist.medium.com/an-analysis-of-the-attack-on-orion-protocol-c7aef70aff83). [Accessed: 2025-05-04].

<a id="37"></a>[37] Rekt News, "Orion Protocol – Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/orion-protocol-rekt](https://rekt.news/orion-protocol-rekt). [Accessed: 2025-05-04].

<a id="38"></a>[38] Rekt News, "Rekt News - DeFi Investigations and Analysis," Rekt News, 2025. [Online]. Available: [https://rekt.news/bonq-rekt](https://rekt.news/bonq-rekt). [Accessed: 2025-03-29].

<a id="39"></a>[39] T. Wright, "BonqDAO protocol exploiter steals $120M after oracle manipulation," Cointelegraph, Feb. 2023. [Online]. Available: [https://cointelegraph.com/news/bonqdao-protocol-suffers-120m-loss-after-oracle-hack](https://cointelegraph.com/news/bonqdao-protocol-suffers-120m-loss-after-oracle-hack). [Accessed: 2025-03-29].

<a id="40"></a>[40] Hacken, "The BonqDAO Price Oracle Hack Explained," Hacken Insights, Feb. 2023. [Online]. Available: [https://hacken.io/insights/bonqdao-hack/](https://hacken.io/insights/bonqdao-hack/). [Accessed: 2025-03-29].

<a id="41"></a>[41] Rekt News, "Woofi - Rekt," Rekt News, Mar. 6, 2024. [Online]. Available: [https://rekt.news/woo-rekt](https://rekt.news/woo-rekt). [Accessed: 2025-04-15].

<a id="42"></a>[42] Olympix, "Unpacking the WOOFi Swap Exploit," Olympix Medium, 2023. [Online]. Available: [https://olympixai.medium.com/unpacking-the-woofi-swap-exploit-ae6f172fe736](https://olympixai.medium.com/unpacking-the-woofi-swap-exploit-ae6f172fe736). [Accessed: 2025-04-15].

<a id="43"></a>[43] REKT, "Inverse Finance - REKT," Rekt News, Apr. 2022. [Online]. Available: [https://rekt.news/inverse-finance-rekt/](https://rekt.news/inverse-finance-rekt/). [Accessed: 2022-04-03].

<a id="44"></a>[44] OKLink Academy, "HOT: Inverse Finance Loses Over $15M in Oracle Manipulation," OKLink, Jul. 12, 2022. [Online]. Available: [https://www.oklink.com/academy/en/2022/07/12/hot-inverse-finance-loses-over-15m-in-oracle-manipulation?utm_source=chatgpt.com](https://www.oklink.com/academy/en/2022/07/12/hot-inverse-finance-loses-over-15m-in-oracle-manipulation?utm_source=chatgpt.com). [Accessed: 2025-04-14].

<a id="45"></a>[45] Cycle Trading, "Inverse Finance: A way to survive from the brink of death?," Binance Square, 2023. [Online]. Available: [https://www.binance.com/en/square/post/746243](https://www.binance.com/en/square/post/746243). [Accessed: 2025-04-15].

<a id="46"></a>[46] Rekt News, "Hundred Finance - REKT 2," Rekt News, 2023. [Online]. Available: [https://rekt.news/hundred-rekt2](https://rekt.news/hundred-rekt2). [Accessed: 2025-04-19].

<a id="47"></a>[47] Cointelegraph, "Hundred Finance hacker moves assets year after $7M exploit," Cointelegraph, 2024. [Online]. Available: [https://cointelegraph.com/news/hundred-finance-hacker-moves-assets-year-after-exploit](https://cointelegraph.com/news/hundred-finance-hacker-moves-assets-year-after-exploit). [Accessed: 2025-04-19].

<a id="48"></a>[48] CertiK, "Lodestar Finance Incident Analysis," CertiK Blog, 2022. [Online]. Available: [https://www.certik.com/resources/blog/TqTyq4vYHl8JzS7zyJye9-lodestar-finance-incident-analysis](https://www.certik.com/resources/blog/TqTyq4vYHl8JzS7zyJye9-lodestar-finance-incident-analysis). [Accessed: 2025-04-18].

<a id="49"></a>[49] Rekt News, "Lodestar Finance – Rekt," Rekt News, 2022. [Online]. Available: [https://rekt.news/lodestar-rekt](https://rekt.news/lodestar-rekt). [Accessed: 2025-04-18].

<a id="50"></a>[50] REKT News, "Gamma Strategies - Rekt," Rekt News, 2024. [Online]. Available: [https://rekt.news/gamma-strategies-rekt](https://rekt.news/gamma-strategies-rekt). [Accessed: 2025-04-18].

<a id="51"></a>[51] Verichains, "Gamma Protocol Exploit Analysis," Verichains Blog, 2024. [Online]. Available: [https://blog.verichains.io/p/gamma-protocol-exploit-analysis](https://blog.verichains.io/p/gamma-protocol-exploit-analysis). [Accessed: 2025-04-18].

<a id="52"></a>[52] Halborn Security, "Explained: The KiloEx Hack (April 2025)," Halborn Blog, 2025. [Online]. Available: [https://www.halborn.com/blog/post/explained-the-kiloex-hack-april-2025](https://www.halborn.com/blog/post/explained-the-kiloex-hack-april-2025). [Accessed: 2025-04-18].

<a id="53"></a>[53] Rekt News, "KiloEx – Rekt," Rekt News, 2025. [Online]. Available: [https://rekt.news/kiloex-rekt](https://rekt.news/kiloex-rekt). [Accessed: 2025-04-18].

<a id="54"></a>[54] Halborn, "Explained: The Onyx Protocol Hack (September 2024)," Halborn Blog, 2024. [Online]. Available: [https://www.halborn.com/blog/post/explained-the-onyx-protocol-hack-september-2024?utm_source=chatgpt.com](https://www.halborn.com/blog/post/explained-the-onyx-protocol-hack-september-2024?utm_source=chatgpt.com). [Accessed: 2024-04-23].

<a id="55"></a>[55] REKT, "Onyx Protocol - Rekt II," Rekt News, 2024. [Online]. Available: [https://rekt.news/onyx-protocol-rekt2](https://rekt.news/onyx-protocol-rekt2). [Accessed: 2024-04-23].

<a id="56"></a>[56] REKT, "Rho Market – Rekt," Rekt News, Jul. 19, 2024. [Online]. Available: [https://rekt.news/rho-market-rekt](https://rekt.news/rho-market-rekt). [Accessed: 2025-04-28].

<a id="57"></a>[57] Olympix, "Rho Markets on Scroll Exploit Analysis," Olympix Medium, Jul. 22, 2024. [Online]. Available: [https://olympixai.medium.com/rho-markets-on-scroll-exploit-analysis-965991270f56](https://olympixai.medium.com/rho-markets-on-scroll-exploit-analysis-965991270f56). [Accessed: 2025-04-28].

<a id="58"></a>[58] REKT, "Uwulend – Rekt," Rekt News, Jun. 10, 2024. [Online]. Available: [https://rekt.news/uwulend-rekt](https://rekt.news/uwulend-rekt). [Accessed: 2025-04-28].

<a id="59"></a>[59] Shashank, "Uwulend Hack Analysis," SolidityScan Blog, Jun. 30, 2024. [Online]. Available: [https://blog.solidityscan.com/uwulend-hack-analysis-77eb9181a717](https://blog.solidityscan.com/uwulend-hack-analysis-77eb9181a717). [Accessed: 2025-04-28].

<a id="60"></a>[60] REKT News, "Zunami Protocol - REKT," Rekt News, 2023. [Online]. Available: [https://rekt.news/zunami-protocol-rekt](https://rekt.news/zunami-protocol-rekt). [Accessed: 2025-04-30].

<a id="61"></a>[61] SolidityScan, "Zunami Protocol Hack Analysis – Price Manipulation Exploit," SolidityScan Blog, 2023. [Online]. Available: [https://blog.solidityscan.com/zunami-protocol-hack-analysis-e95981976e11](https://blog.solidityscan.com/zunami-protocol-hack-analysis-e95981976e11). [Accessed: 2025-04-30].

<a id="62"></a>[62] Rekt, "Jimbos Protocol $7.5 Million Hack," Rekt News, 2023. [Online]. Available: [https://rekt.news/jimbo-rekt](https://rekt.news/jimbo-rekt). [Accessed: 2023-05-29].

<a id="63"></a>[63] Numen Cyber Labs, "A Detailed Analysis of Arbitrum-based Jimbos Protocol's $7.5 Million Hack," Numen Cyber Labs Medium, 2023. [Online]. Available: [https://medium.com/numen-cyber-labs/a-detailed-analysis-of-arbitrum-based-jimbos-protocol-7-5-million-hack-36af84faee2](https://medium.com/numen-cyber-labs/a-detailed-analysis-of-arbitrum-based-jimbos-protocol-7-5-million-hack-36af84faee2). [Accessed: 2023-05-29].

<a id="64"></a>[64] CertiK, "Sonne Finance Incident Analysis," Rekt News, May 2024. [Online]. Available: [https://rekt.news/sonne-finance-rekt](https://rekt.news/sonne-finance-rekt). [Accessed: 2024-05-15].

<a id="65"></a>[65] REKT News, "Curve, Vyper - REKT," Rekt News, Jul. 2023. [Online]. Available: [https://rekt.news/curve-vyper-rekt/](https://rekt.news/curve-vyper-rekt/). [Accessed: 2025-03-29].

<a id="66"></a>[66] P. Shukla, "ZkLend Hack Analysis," LinkedIn, 2025. [Online]. Available: [https://www.linkedin.com/pulse/zklend-hack-analysis-piyush-shukla-jsxzf/](https://www.linkedin.com/pulse/zklend-hack-analysis-piyush-shukla-jsxzf/). [Accessed: 2025-04-18].

<a id="67"></a>[67] SlowMist, "In-depth Analysis of zkLend Hack Linked to EraLend Hack," SlowMist Medium, 2025. [Online]. Available: [https://slowmist.medium.com/in-depth-analysis-of-zklend-hack-linked-to-eralend-hack-fba4af9b66ef](https://slowmist.medium.com/in-depth-analysis-of-zklend-hack-linked-to-eralend-hack-fba4af9b66ef). [Accessed: 2025-04-18].

<a id="68"></a>[68] CoinStats News, "ZkLend Exploit Backfires as Hacker Loses $96 Million in ETH to Phishing Scam," CoinStats, 2025. [Online]. Available: [https://coinstats.app/news/8628b254c4ef1cf1bb1d4f92ac3cc586cd17916f04ee8f2ed33b3c2a30d640bf_ZkLend-exploit-backfires-as-hacker-loses-96-million-in-ETH-to-phishing-scam/](https://coinstats.app/news/8628b254c4ef1cf1bb1d4f92ac3cc586cd17916f04ee8f2ed33b3c2a30d640bf_ZkLend-exploit-backfires-as-hacker-loses-96-million-in-ETH-to-phishing-scam/). [Accessed: 2025-04-18].

<a id="69"></a>[69] Rekt News, "Abracadabra - REKT," Rekt News, 2025. [Online]. Available: [https://rekt.news/abra-rekt](https://rekt.news/abra-rekt). [Accessed: 2025-04-19].

<a id="70"></a>[70] Extropy IO, "Breaking Down the $6.5M Abracadabra Money Hack: A Detailed Analysis of the Cauldron V4 Exploit," Extropy IO Medium, 2024. [Online]. Available: [https://extropy-io.medium.com/breaking-down-the-6-5m-abracadabra-money-hack-a-detailed-analysis-of-the-cauldron-v4-exploit-44100da10896](https://extropy-io.medium.com/breaking-down-the-6-5m-abracadabra-money-hack-a-detailed-analysis-of-the-cauldron-v4-exploit-44100da10896). [Accessed: 2025-04-19].

<a id="71"></a>[71] SharkTeam, "SharkTeam Analysis of the Principles of RAFT Attack Incident," SharkTeam Medium, 2023. [Online]. Available: [https://medium.com/@sharkteam/sharkteam-analysis-of-the-principles-of-raft-attack-incident-814127d626bd](https://medium.com/@sharkteam/sharkteam-analysis-of-the-principles-of-raft-attack-incident-814127d626bd). [Accessed: 2025-04-25].

<a id="72"></a>[72] Rekt News, "RAFT Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/raft-rekt](https://rekt.news/raft-rekt). [Accessed: 2025-04-25].

<a id="73"></a>[73] P. Shukla, "Ionic Money $8.5 million Exploit: Hack Analysis," LinkedIn, Feb. 2025. [Online]. Available: [https://www.linkedin.com/pulse/ionic-money-85-million-exploit-hack-analysis-piyush-shukla-7j8if](https://www.linkedin.com/pulse/ionic-money-85-million-exploit-hack-analysis-piyush-shukla-7j8if). [Accessed: 2025-02-09].

<a id="74"></a>[74] Rekt News, "Ionic Money - Rekt," Rekt News, Feb. 6, 2025. [Online]. Available: [https://rekt.news/ionic-money-rekt](https://rekt.news/ionic-money-rekt). [Accessed: 2025-04-17].

<a id="75"></a>[75] SolidityScan, "Li.Fi Hack Analysis - How a Logic Vulnerability Caused a $10M Hack," SolidityScan Blog, 2023. [Online]. Available: [https://blog.solidityscan.com/li-fi-hack-analysis-521388128d22](https://blog.solidityscan.com/li-fi-hack-analysis-521388128d22). [Accessed: 2025-04-18].

<a id="76"></a>[76] LI.FI Team, "Incident Report – 16th July 2023," LI.FI Knowledge Hub, 2023. [Online]. Available: [https://li.fi/knowledge-hub/incident-report-16th-july/](https://li.fi/knowledge-hub/incident-report-16th-july/). [Accessed: 2025-04-18].

<a id="77"></a>[77] Rekt News, "LI.FI Jumper - Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/lifi-jumper-rekt](https://rekt.news/lifi-jumper-rekt). [Accessed: 2025-04-18].

<a id="78"></a>[78] SolidityScan, "DeltaPrime Hack Analysis," SolidityScan Blog, Nov. 2024. [Online]. Available: [https://blog.solidityscan.com/deltaprime-hack-analysis-44edb9b22567](https://blog.solidityscan.com/deltaprime-hack-analysis-44edb9b22567). [Accessed: 2025-04-22].

<a id="79"></a>[79] REKT, "DeltaPrime - Rekt II," Rekt News, Nov. 2024. [Online]. Available: [https://rekt.news/deltaprime-rekt2](https://rekt.news/deltaprime-rekt2). [Accessed: 2025-04-22].

<a id="80"></a>[80] CertiK, "Dough Finance Incident Analysis," CertiK Blog, 2024. [Online]. Available: [https://www.certik.com/resources/blog/3SMOuGMCSttY4pQW6I49W2-dough-finance-incident-analysis](https://www.certik.com/resources/blog/3SMOuGMCSttY4pQW6I49W2-dough-finance-incident-analysis). [Accessed: 2025-04-22].

<a id="81"></a>[81] DeHacker Security, "Dough Finance Incident Analysis," DeHacker Security Medium, 2024. [Online]. Available: [https://medium.com/@dehacker_security/dough-finance-incident-analysis-04db15c22552](https://medium.com/@dehacker_security/dough-finance-incident-analysis-04db15c22552). [Accessed: 2025-04-22].

<a id="82"></a>[82] REKT, "Team Finance - REKT," REKT News, Oct. 2023. [Online]. Available: [https://rekt.news/teamfinance-rekt](https://rekt.news/teamfinance-rekt).

<a id="83"></a>[83] SlowMist, "Analysis & Review of Team Finance Exploit," SlowMist Medium, Oct. 2023. [Online]. Available: [https://slowmist.medium.com/analysis-review-of-team-finance-exploit-f439c2f63e2](https://slowmist.medium.com/analysis-review-of-team-finance-exploit-f439c2f63e2).

<a id="84"></a>[84] BlockApex, "Seneca Protocol Hack Analysis," BlockApex Medium, 2024. [Online]. Available: [https://blockapex.medium.com/seneca-protocol-hack-analysis-546f3bcc1040](https://blockapex.medium.com/seneca-protocol-hack-analysis-546f3bcc1040). [Accessed: 2025-04-30].

<a id="85"></a>[85] Rekt, "Seneca Protocol - $6.4M Exploit," Rekt News, 2024. [Online]. Available: [https://rekt.news/seneca-protocol-rekt](https://rekt.news/seneca-protocol-rekt). [Accessed: 2025-04-30].

<a id="86"></a>[86] SlowMist, "A Deep Dive Into the KyberSwap Hack," SlowMist Medium, Nov. 2023. [Online]. Available: [https://slowmist.medium.com/a-deep-dive-into-the-kyberswap-hack-3e13f3305d3a](https://slowmist.medium.com/a-deep-dive-into-the-kyberswap-hack-3e13f3305d3a). [Accessed: 2023-11-27].

<a id="87"></a>[87] REKT, "KyberSwap - REKT," Rekt News, Nov. 2023. [Online]. Available: [https://rekt.news/kyberswap-rekt](https://rekt.news/kyberswap-rekt). [Accessed: 2023-11-23].

<a id="88"></a>[88] Rekt, "Yearn: Re-Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/yearn2-rekt](https://rekt.news/yearn2-rekt). [Accessed: 2025-04-17].

<a id="89"></a>[89] CertiK, "Misconfigured Earnings: Yearn Finance Exploit Explained," CertiK Blog, 2023. [Online]. Available: [https://www.certik.com/resources/blog/40AqeRsWil5Hof9etrvjH2-earnings-misconfigured-yearn-finance-exploit-explained](https://www.certik.com/resources/blog/40AqeRsWil5Hof9etrvjH2-earnings-misconfigured-yearn-finance-exploit-explained). [Accessed: 2025-04-17].

<a id="90"></a>[90] Halborn Security, "Explained: The Abracadabra Money Hack (March 2025)," Halborn Blog, 2025. [Online]. Available: [https://www.halborn.com/blog/post/explained-the-abracadabra-money-hack-march-2025](https://www.halborn.com/blog/post/explained-the-abracadabra-money-hack-march-2025). [Accessed: 2025-04-22].

<a id="91"></a>[91] Rekt News, "Abracadabra - REKT," Rekt News, 2025. [Online]. Available: [https://rekt.news/abracadabra-rekt2](https://rekt.news/abracadabra-rekt2). [Accessed: 2025-04-22].

<a id="92"></a>[92] Rekt News, "Unizen Rekt," Rekt News, 2024. [Online]. Available: [https://rekt.news/unizen-rekt](https://rekt.news/unizen-rekt). [Accessed: 2025-04-29].

<a id="93"></a>[93] Blockbasis, "Unizen: Navigating the $2.1M Security Breach," Blockbasis, 2024. [Online]. Available: [https://blockbasis.com/p/unizen-navigating-21m-security-breach](https://blockbasis.com/p/unizen-navigating-21m-security-breach). [Accessed: 2025-04-29].

<a id="94"></a>[94] Rekt News, "OKX DEX - REKT," Rekt News, 2023. [Online]. Available: [https://rekt.news/okx-dex-rekt](https://rekt.news/okx-dex-rekt). [Accessed: 2025-04-30].

<a id="95"></a>[95] Olympix AI, "Unmasking the Malicious OKX DEX Upgrade," Olympix AI Medium, 2023. [Online]. Available: [https://olympixai.medium.com/unmasking-the-malicious-okx-dex-upgrade-f6912449f963](https://olympixai.medium.com/unmasking-the-malicious-okx-dex-upgrade-f6912449f963). [Accessed: 2025-04-30].

<a id="96"></a>[96] Rekt News, "SIR.trading - Rekt," Rekt News, Mar. 2025. [Online]. Available: [https://rekt.news/sirtrading-rekt](https://rekt.news/sirtrading-rekt). [Accessed: 2025-04-18].

<a id="97"></a>[97] Cointelegraph, "SIR.trading begs hacker to return $255K or 'no chance for us to survive'," TradingView, Mar. 2025. [Online]. Available: [https://www.tradingview.com/news/cointelegraph:6a2330d53094b:0-sir-trading-begs-hacker-to-return-255k-or-no-chance-for-us-to-survive/](https://www.tradingview.com/news/cointelegraph:6a2330d53094b:0-sir-trading-begs-hacker-to-return-255k-or-no-chance-for-us-to-survive/). [Accessed: 2025-04-18].

<a id="98"></a>[98] REKT, "1inch – REKT," Rekt News, 2024. [Online]. Available: [https://rekt.news/1inch-rekt](https://rekt.news/1inch-rekt). [Accessed: 2025-04-18].

<a id="99"></a>[99] Decurity, "Yul Calldata Corruption: 1inch Postmortem," Decurity Blog, 2024. [Online]. Available: [https://blog.decurity.io/yul-calldata-corruption-1inch-postmortem-a7ea7a53bfd9](https://blog.decurity.io/yul-calldata-corruption-1inch-postmortem-a7ea7a53bfd9). [Accessed: 2025-04-18].

<a id="100"></a>[100] VELOCORE, "Velocore Incident Post-Mortem," Velocore Medium, Jun. 2, 2024. [Online]. Available: [https://velocorexyz.medium.com/velocore-incident-post-mortem-6197020ec3e9](https://velocorexyz.medium.com/velocore-incident-post-mortem-6197020ec3e9). [Accessed: 2025-04-28].

<a id="101"></a>[101] REKT, "Velocore – Rekt," Rekt News, Jun. 3, 2024. [Online]. Available: [https://rekt.news/velocore-rekt](https://rekt.news/velocore-rekt). [Accessed: 2025-04-28].

<a id="102"></a>[102] Rekt News, "Tornado Cash Governance Attack," Rekt News, 2023. [Online]. Available: [https://rekt.news/tornado-gov-rekt](https://rekt.news/tornado-gov-rekt). [Accessed: 2025-04-25].

<a id="103"></a>[103] R. Behnke, "Explained: The Tornado Cash Hack (May 2023)," Halborn Blog, 2023. [Online]. Available: [https://www.halborn.com/blog/post/explained-the-tornado-cash-hack-may-2023](https://www.halborn.com/blog/post/explained-the-tornado-cash-hack-may-2023). [Accessed: 2025-04-25].

<a id="104"></a>[104] ZAN, "Unpacking the Tornado Cash Governance Attack," ZAN Medium, May 2023. [Online]. Available: [https://medium.com/@zan.top/unpacking-the-tornado-cash-governance-attack-15b40691ca2e](https://medium.com/@zan.top/unpacking-the-tornado-cash-governance-attack-15b40691ca2e).

<a id="105"></a>[105] Rekt News, "Atlantis Loans - Rekt," Rekt News, 2023. [Online]. Available: [https://rekt.news/atlantis-loans-rekt](https://rekt.news/atlantis-loans-rekt). [Accessed: 2025-04-29].

<a id="106"></a>[106] Shashank, "Atlantis Loans Hack Analysis," SolidityScan Blog, 2023. [Online]. Available: [https://blog.solidityscan.com/atlantis-loans-hack-analysis-7f3fb2e295e0](https://blog.solidityscan.com/atlantis-loans-hack-analysis-7f3fb2e295e0). [Accessed: 2025-04-29].
