# testnet for local e2e tests

## ETH1 localnet contract addresses

### Infrastructure

- Deposit contract: `0x5f4e510503d83bd1a5436bdae2923489da0be454` deployed at block `70`
- ENS: `0x5f6f7e8cc7346a11ca2def8f827b7a0b612c56a1`
- DAO_FACTORY: `0x5d94e3e7aec542ab0f9129b9a7badeb5b3ca0f77`
- MINIME_FACTORY: `0xd526b7aba39cccf76422835e7fd5327b98ad73c9`
- FIFResolvingRegistrar: `0xf1f8aac64036cdd399886b1c157b7e3b361093f3`
- Aragon APM: `aragonpm.eth` -> ``
- Lido APM: `lido.eth` -> `0x1902a0410EFe699487Dd85F12321aD672bE4ada2`
  
### Apps and template repos

- Lido App: `lido.lido.eth` -> `0x2e25c8F88c5cCcbC9400e5bc86cF9C58C7604327` [ipfs](http://localhost:8080/ipfs/QmQKqHhw8CicmDMnQ8NAGuCjtJiPqW77nDL2ogB8ydQpda)
- LidoOracle App: `lidooracle.lido.eth` -> `0x019F12a7DAa44A34CD0FF35055b0e2D4679D8521` [ipfs](http://localhost:8080/ipfs/Qme8dN9tVBaf6g3qEp7QkQkDuogKkqhD4Aph6oGfCcKoQk)
- Node Operators Registry App: `node-operators-registry.lido.eth` -> `0xfe18BCBeDD6f46e0DfbB3Aea02090F23ED1c4a28` [ipfs](http://localhost:8080/ipfs/QmfFYDKzUwPpdcqLVd5WwuDAY3iLknDs9CgBeV9nqt2ENm)
- StETH token App: `steth.lido.eth` -> `0xD13a7D8A728692eB2c56135B5EB5A1951b3F8395` [ipfs](http://localhost:8080/ipfs/QmZChra7tQPPBw58fJBVSaVF1kpMsR45HCMtjVosUAgb35)
- Lido DAO Template: `lido-template.lido.eth` -> `0xc7a5b4d533a18370f3EB88f48971B3A3276546fb`

> Lido APM: ens.addr('lido.eth')
> Lido apps: As APM repos, e.g. apm.getLatest('lido.lido.eth')
> Templates: As APM repos, e.g. apm.getLatest('lido-template.lido.eth')

### Deployed DAO and Apps instances

- Aragon Agent: `0x2CE1b3669f72727D3000D37F8B431C2e3731E3F4`
- Aragon Finance: `0xd2c0889B4c73C82d9403EAd5e562031d2067A96F`
- Aragon Tokens: `0xF8FdFCEC370576442E1358fCF970b841809509f6`
- Aragon Voting: `0xDa160A5164A40831735eEB5416fEd3573a50FE27`
- Lido: `0x1Ae44Ea2B3e422E3D0c0eaD84617ECE55517EED7`
- Operators Registry: `0xE4d6602497077C44cB39Df55131A97BCFc8ed454`
- LidoOracle: `0x5ec5DDf7A0cdD3235AD1bCC0ad04F059507EC5a3`
- StETH: `0x12aa6ec7d603dc79eD663792E40a520B54A7ae6A`
- CStETH: `0xbc1B7f0e9C764deedA0cC56Ad10e5855f3140227`
- Lido DAO: `lido-dao.aragon.id` -> `0xD20F21CEb31a8E302603dC3ff994f00aa9312A66`
- Lido DAO Token: `0xf2804D07A941F77F34EEEb252D172E4268d0e9D4`
- DAO ACL: `0xE0CA61949ed8c7CF31E73B819E9cEe02eDfa31Fa`
- DAO Registry: `0xB0a7CD50842fEFE74F0D69D2B79E235261d16987`

### Permission roles ID

- Lido
  - MANAGE_WITHDRAWAL_KEY: `0x96088a8483023eb2f67b12aabbaf17d1d055e6ef387e563902adc1bba1e4028b`
  - SET_APPS: `0x11eba3f259e2be865238d718fd308257e3874ad4b3a642ea3af386a4eea190bd`

- NOS Registry
  - ADD_NODE_OPERATOR_ROLE = '0xe9367af2d321a2fc8d9c8f1e67f0fc1e2adf2f9844fb89ffa212619c713685b2'
  - SET_NODE_OPERATOR_NAME_ROLE = '0x58412970477f41493548d908d4307dfca38391d6bc001d56ffef86bd4f4a72e8'
  - SET_NODE_OPERATOR_ACTIVE_ROLE = '0xd856e115ac9805c675a51831fa7d8ce01c333d666b0e34b3fc29833b7c68936a'
  - SET_NODE_OPERATOR_ADDRESS_ROLE = '0xbf4b1c236312ab76e456c7a8cca624bd2f86c74a4f8e09b3a26d60b1ce492183'
  - SET_NODE_OPERATOR_LIMIT_ROLE = '0x07b39e0faf2521001ae4e58cb9ffd3840a63e205d288dc9c93c3774f0d794754'
  - REPORT_STOPPED_VALIDATORS_ROLE = '0x18ad851afd4930ecc8d243c8869bd91583210624f3f1572e99ee8b450315c80f'
  - MANAGE_SIGNING_KEYS: `0x75abc64490e17b40ea1e66691c3eb493647b24430b358bd87ec3e5127f1621ee`

- Lido Oracle
  - MANAGE_MEMBERS: `0xbf6336045918ae0015f4cdb3441a2fdbfaa4bcde6558c8692aac7f56c69fb067`
  - MANAGE_QUORUM: `0xa5ffa9f45fa52c446078e834e1914561bd9c2ab1e833572d62af775da092ccbc`
  
## eth1 DAO accounts

mnemonic: `explain tackle mirror kit van hammer degree position ginger unfair soup bonus`

addresses & pk: <details><summary>SHOW</summary>

- Address #1: 0xb4124cEB3451635DAcedd11767f004d8a28c6eE7 (account used to deploy DAOs, has more permissions)
    Private key: a8a54b2d8197bc0b19bb8a084031be71835580a01e70a45a13babd16c9bc1563

- Address #2: 0x8401Eb5ff34cc943f096A32EF3d5113FEbE8D4Eb
    Private key: ce8e3bda3b44269c147747a373646393b1504bfcbb73fc9564f5d753d8116608

- Address #3: 0x306469457266CBBe7c0505e8Aad358622235e768
    Private key: 8716d2701596f51aa39d061a685d5ae5ec946eb2c7adb059d29024b5bb3b02c8

- Address #4: 0xd873F6DC68e3057e4B7da74c6b304d0eF0B484C7
    Private key: 62d7bb725787d84b059eb4950f6eea060d898183250ca3ea673a36b8e113018f

- Address #5: 0xDcC5dD922fb1D0fd0c450a0636a8cE827521f0eD
    Private key: 705df2ae707e25fa37ca84461ac6eb83eb4921b653e98fdc594b60bea1bb4e52

- Address #6: 0x27E9727FD9b8CdDdd0854F56712AD9DF647FaB74
    Private key: 6b12b45143fc6c7721d0ffbb9811905e773868376501fd1f46c64bf34ae29991

- Address #7: 0x9766D2e7FFde358AD0A40BB87c4B88D9FAC3F4dd
    Private key: 33f3f34569f997abb165d6967895d963a2b15ec609efcec844e65b60ee8340c7

- Address #8: 0xBd7055AB500cD1b0b0B14c82BdBe83ADCc2e8D06
    Private key: 5a013cc48f0a3196b0986fc7a7a9dd320ac75e89e33302a7ff4ea6b9dc4f7b00

- Address #9: 0xe8898A4E589457D979Da4d1BDc35eC2aaf5a3f8E
    Private key: 418cc0b07bfef998f577384b185b97ad544204b5be43ac9b3abf16db2012ab5c

- Address #10: 0xED6A91b1CFaae9882875614170CbC989fc5EfBF0
    Private key: 698eece6f9915b08b4d1a63958dc4f3996ee5a8d685b29d17c28beab912a77cd
</detail>
