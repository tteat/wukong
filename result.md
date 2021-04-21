wukong
├─LICENSE
├─README.md
├─pom.xml
├─src
|  ├─main
|  |  ├─java
|  |  |  ├─io
|  |  |  | ├─github
|  |  |  | |   ├─pdoslab
|  |  |  | |   |    ├─wukong
|  |  |  | |   |    |   ├─Analyzer.java
|  |  |  | |   |    |   ├─StartAnalyzer.java
|  |  |  | |   |    |   ├─utils
|  |  |  | |   |    |   |   ├─ClassUtils.java
|  |  |  | |   |    |   |   ├─JSONUtils.java
|  |  |  | |   |    |   |   ├─JavaUtils.java
|  |  |  | |   |    |   |   ├─KubeUtils.java
|  |  |  | |   |    |   |   └StringUtils.java
|  |  |  | |   |    |   ├─model
|  |  |  | |   |    |   |   └JDKInfo.java
|  |  |  | |   |    |   ├─core
|  |  |  | |   |    |   |  ├─Heuristicv1.java
|  |  |  | |   |    |   |  └Heuristicv2.java
|  |  |  | |   |    |   ├─analyzer
|  |  |  | |   |    |   |    ├─RequestWithObjectPatternAnalyzer.java
|  |  |  | |   |    |   |    └RequestWithParameterPatternAnalyzer.java
├─results
|    ├─aliyun-3.3.0
|    ├─aliyun-4.17.8
|    ├─amazon-1.11.692
|    ├─amzon-1.0.77
|    ├─azure-1.0.0
|    └azure-1.28.0
├─img
|  ├─api.png
|  └架构2.png
├─docs
|  ├─AliyunECS-Analysis.md
|  ├─AliyunECS-json.md
|  ├─AmazonEc2-Analysis.md
|  ├─AmazonEc2-json.md
|  ├─AmazonEcs-Analysis.md
|  ├─AzureVM-Analysis.md
|  ├─AzureVM-json.md
|  ├─BaiduBCE-Analysis.md
|  ├─BaiduBCE-json.md
|  ├─GoogleCCE-Analysis.md
|  ├─GoogleCCE-json.md
|  ├─JDCloudVM-Analysis.md
|  ├─JDCloudVM-json.md
|  ├─Kubernetes-Analysis.md
|  ├─OpenShift-Analysis.md
|  ├─Operations.md
|  ├─QingcloudVM-json.md
|  ├─TencentVM-Analysis.md
|  └TencentVM-json.md
├─conf
|  ├─jdkinfo.conf
|  ├─jdkinfo.conf-JDVM
|  ├─jdkinfo.conf-aliyunecs
|  ├─jdkinfo.conf-amazonec2
|  ├─jdkinfo.conf-azurevm
|  ├─jdkinfo.conf-baiduvm
|  ├─jdkinfo.conf-googlegce
|  ├─jdkinfo.conf-openstack
|  ├─jdkinfo.conf-qingcloudVM
|  ├─jdkinfo.conf-tencentVM
|  ├─maven.conf
|  ├─maven.conf-JDVM
|  ├─maven.conf-QingcloudVM
|  ├─maven.conf-aliyunecs
|  ├─maven.conf-amazonec2
|  ├─maven.conf-azurevm
|  ├─maven.conf-baiduvm
|  ├─maven.conf-googlegce
|  ├─maven.conf-openstack
|  └maven.conf-tencentVM
├─.idea
|   ├─modules.xml
|   ├─vcs.xml
|   ├─workspace.xml
|   ├─wukong.iml
|   ├─inspectionProfiles
├─.git
|  ├─COMMIT_EDITMSG
|  ├─HEAD
|  ├─config
|  ├─description
|  ├─index
|  ├─packed-refs
|  ├─refs
|  |  ├─tags
|  |  ├─remotes
|  |  |    ├─origin
|  |  |    |   ├─HEAD
|  |  |    |   └main
|  |  ├─heads
|  |  |   └main
|  ├─objects
|  |    ├─pack
|  |    ├─info
|  |    ├─ff
|  |    | └7c288d51534d2839699e6fc69c8bf3cc4499b1
|  |    ├─fe
|  |    | └1fb10b1eea5a1fce14f44cf01b50cebaf38e46
|  |    ├─fb
|  |    | └05493d9ebe1b86f4e0d49c6c3982baf18e439d
|  |    ├─ee
|  |    | └3a479c2ae76daa646044328050fce8fe50a4ab
|  |    ├─ed
|  |    | └e8d274ac74f493291a46f80ac19840ea1f72f8
|  |    ├─e4
|  |    | └fef0155beb7a93a8cf94c20c7399620e764123
|  |    ├─e0
|  |    | └570f01beb1e91e509403e1b6555174fd044b01
|  |    ├─df
|  |    | └0d9b9b4faafb5b195b5e3d87ee27a6083385af
|  |    ├─da
|  |    | └f9ebb379b2386e1f8e1d33685819134ca96fac
|  |    ├─d7
|  |    | └7b91a7cc56a6391651c0ff8c65444381e13a8b
|  |    ├─d6
|  |    | ├─56a3553e041e5a8e9689e20de057fc7a971599
|  |    | └ebd4805981b8400db3e3291c74a743fef9a824
|  |    ├─d5
|  |    | └66338be3c3a3fcdd0abc28131a940a26c3f876
|  |    ├─d3
|  |    | └c1882b70a5af7eb85c0e1d5c8bf6168e68f80a
|  |    ├─d2
|  |    | ├─0c30dd12dcbbedab50bb6ca58cb5ce83a004ae
|  |    | └4074c19a63301bcb3a22cee349fda03619fdaa
|  |    ├─cc
|  |    | └9484a11b3b2325627d7c77d7cd051bd6ae96a3
|  |    ├─cb
|  |    | └c7e667f39e747824fb7a9709ea52f749467fab
|  |    ├─ca
|  |    | └4867ff2760d9f9f8bf36b75d07a43e0a10944b
|  |    ├─c6
|  |    | └8f74790e087940738a2f1dd1bb2dc8aa5e840a
|  |    ├─c4
|  |    | └8377a68e061e3a4c103b17498ec7c16577f737
|  |    ├─bf
|  |    | ├─828d3d05acdc69bb67071e403332dc9c94c200
|  |    | ├─bee1a50b5dbc776b2f5c81b5a259c12153b28c
|  |    | └cd3a181f25f5d05c1c03d906be4b2a113dea08
|  |    ├─bd
|  |    | ├─4f410cfb92aae07b7c9962835cf81995abb292
|  |    | └778fcd7fdc8ca053d40f8674a9af949acbabd3
|  |    ├─ba
|  |    | └e6a9e89d3182ee399482a4767e48e6f1806acd
|  |    ├─b9
|  |    | └39e4b9bf792f27e494c496f5631d1295c62efd
|  |    ├─b7
|  |    | └3ac76360625ffb4274e88036cb34ecb779c07e
|  |    ├─ae
|  |    | ├─cad2a51d672345a05df31bb1e5b51eb80f1fad
|  |    | └d95648874aa9d3444f1916bcaebd7fb123dc24
|  |    ├─a7
|  |    | └d807e5cbce10abb3838c62757619aafb69c7c8
|  |    ├─a3
|  |    | └e0a5d89ec6fa84b1eb5b890fc133d157c5b9da
|  |    ├─a0
|  |    | └109920f475f3be5ebc192b0953543edc77f56e
|  |    ├─9f
|  |    | └71537c50383dee012ff4e05589a1de6e4c021b
|  |    ├─99
|  |    | └1a8c59b93806178df2746ca2cca3b3eb3a85e3
|  |    ├─94
|  |    | └b7fd9edb3c9ee57cfa57b9de06e5da0bb8f4ff
|  |    ├─93
|  |    | └1c1b4a07717443bc10577a6e679a678a00c7d4
|  |    ├─92
|  |    | └ad663f3e460d7e0b85f8ade366f532faf30ed8
|  |    ├─90
|  |    | └ec1c05010ca2e472662058697d8734bf0bd70b
|  |    ├─8c
|  |    | └47696c8df245e1d6f87d1c939be2d0eaad5b4e
|  |    ├─86
|  |    | └c9b495f43482c4953841f0f2238aa62cfce3d8
|  |    ├─83
|  |    | └e72e887dd2d4c9e19882ef35d9f957d85775c7
|  |    ├─7e
|  |    | └f6e9f161cf2c9aed37941023e52f9115e82803
|  |    ├─7a
|  |    | └9369ec888d56841620bdc06fa746c9fc4f7dd4
|  |    ├─78
|  |    | ├─0065df12bfb5c9818c12017e332e9e7bd2a53e
|  |    | └711f65d74ca1bdf826b1df025d9d8daec85fad
|  |    ├─70
|  |    | └725a8fecb9db1d0361208e320c883b9bc04fcd
|  |    ├─6c
|  |    | └ca050c6010fbb2296289dd4a4d32bb494377b3
|  |    ├─6b
|  |    | └9ef05c107a3a219308858719cc4b4edd1d4f70
|  |    ├─67
|  |    | └a41062bf9813197005db8cb22f16ddffd11e9a
|  |    ├─63
|  |    | └cf7a006a23fc4b6ce7356c5ad9318bae64c846
|  |    ├─61
|  |    | └f8005d60013f1caf4dc1162884d3f75af273ee
|  |    ├─5c
|  |    | ├─1cb0ca8ce6c05647dd617126647cdc6f8140a2
|  |    | ├─3598aa40a9d8435527f671e41b39b1bdf32de1
|  |    | └e8664bd9b7b5383e644e9674aa1e1ba2714ea9
|  |    ├─55
|  |    | └07f8c368392d640880c9b642be6f81cf282c50
|  |    ├─53
|  |    | └145dfcc1d6521fa89b887148d116d8cc019af8
|  |    ├─49
|  |    | └25e577914fb94ca55298a4126e93b69f0701ca
|  |    ├─41
|  |    | └6bb9e5bd0ffd406073e8a092bdfed2c35ac1b1
|  |    ├─3f
|  |    | └d42987d5c621fb24dcc59d3ae022faba6b4e48
|  |    ├─3c
|  |    | └021c05fc7c1c68b26215c10576600cc9ba2ae4
|  |    ├─3b
|  |    | └19893fd41df37c4041cb90b1f294b5b7c1c319
|  |    ├─3a
|  |    | ├─42e8e5ee1c8ea34c5b70a62190d58197661f92
|  |    | └dbae1c7dab9f506e915728509b181924e522fc
|  |    ├─37
|  |    | └9d5ad6a4eeb342a4e65ec657e3edbd5256c3c0
|  |    ├─35
|  |    | └eb1ddfbbc029bcab630581847471d7f238ec53
|  |    ├─34
|  |    | └743700842e5ba6345b86a12649824e75dd7a35
|  |    ├─33
|  |    | └6e4f106b648c1e33358c4ad49ec190eb2967bc
|  |    ├─31
|  |    | ├─1041e8a5ffc96281bf947939e68603d4bd51c5
|  |    | ├─534d183a1e2de0840d0ae1bc46a981d6af2ad7
|  |    | └d41514cd41387480ad3425be4cc44ba2721062
|  |    ├─2e
|  |    | └32d63cc092b50bd3dc5fa2b64b6790be50f4fc
|  |    ├─2d
|  |    | ├─315027cb43aef6a8e761a35d1d916b22cd1ad7
|  |    | └faed0782bd4662b087a555e4db72c15d9c4c6a
|  |    ├─2c
|  |    | └d3e00b67c5e1e65eba92317d46263d7063eb97
|  |    ├─2b
|  |    | └7afac912463bb8be23f960f67c3554d76b9aa1
|  |    ├─26
|  |    | ├─1eeb9e9f8b2b4b0d119366dda99c6fd7d35c64
|  |    | └ba0d1455064c0f4a83555043fc1eefa1121ea3
|  |    ├─25
|  |    | └2795a24d1c79c40597e1ef49378aeb5330a5aa
|  |    ├─22
|  |    | └23d9c31a03c650f7afdcd8a5492a87bb0c6089
|  |    ├─20
|  |    | └5d895e154e4973387484738bde98a7361d106d
|  |    ├─1e
|  |    | └07fe47ec6fc54e50dafc3c34f3da90bf2755ee
|  |    ├─1a
|  |    | └7f2f0df86a6e7f89831fc5b64dc70b752d27ea
|  |    ├─19
|  |    | └a7d0b44f2cd538a8080f849a1b849c4dad3197
|  |    ├─15
|  |    | └703454c26baa1e4b6bd4c25cb3ef1b58db8492
|  |    ├─13
|  |    | ├─0d38b1d672d9102563aa55f5d19658a2aa0794
|  |    | └3032fcbd3e56508afbe50d298cc4858db6393b
|  |    ├─0f
|  |    | ├─bc04b5d66a4613468091288c9236a507d3d5d1
|  |    | └fc33681c46be52f4599636694655d0235136c2
|  |    ├─0c
|  |    | ├─3e91ea1bb575c1d7aacc5452a08538b694bb70
|  |    | └866c0743c25ccdf8599305620d331d32128126
|  |    ├─0a
|  |    | └c07010e1a387d87a0d3a28ef6f1922b0fe9b6e
|  |    ├─05
|  |    | ├─7897ea9bc7aa75b125bbb1f3057c7d0895a2e8
|  |    | └7f1606fcd9c1128f8b8bf7039c772378babd4a
|  |    ├─01
|  |    | └13b8d75f3b139f3a2174fa5ad62f8e7ce92a20
|  |    ├─00
|  |    | └c5fafd87b2466e2c11c609172c0a7ecee78287
|  ├─logs
|  |  ├─HEAD
|  |  ├─refs
|  |  |  ├─remotes
|  |  |  |    ├─origin
|  |  |  |    |   ├─HEAD
|  |  |  |    |   └main
|  |  |  ├─heads
|  |  |  |   └main
|  ├─info
|  |  └exclude
|  ├─hooks
|  |   ├─applypatch-msg.sample
|  |   ├─commit-msg.sample
|  |   ├─fsmonitor-watchman.sample
|  |   ├─post-update.sample
|  |   ├─pre-applypatch.sample
|  |   ├─pre-commit.sample
|  |   ├─pre-merge-commit.sample
|  |   ├─pre-push.sample
|  |   ├─pre-rebase.sample
|  |   ├─pre-receive.sample
|  |   ├─prepare-commit-msg.sample
|  |   └update.sample