### Forum RoadMap :

* BigMap :  https://forum.dfinity.org/t/big-map-for-scaling-canisters-across-subnets/6155/16

* Source Code of BigMap : https://forum.dfinity.org/t/releasing-the-source-of-the-bigmap-poc-demo/7601
* Asset Canister : https://github.com/dfinity/sdk/blob/master/docs/design/asset-canister.adoc

### Summary：

* 宗旨 ： 子网内存升级后的目标： 跨子网存储， 让内存不再有限制



### Canister Storage Model：

*   Canister中的内存作为执行内存
*   Stable内存作为主存
*   执行时从Stable内存转移到WASM 内存， 结果从WASM 内存到 Stable内存[reference](https://forum.dfinity.org/t/big-map-for-scaling-canisters-across-subnets/6155/9)
*   

