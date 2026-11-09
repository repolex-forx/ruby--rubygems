# Repolex Knowledge Graph of ruby/rubygems

RDF knowledge graph data for [ruby/rubygems](https://github.com/ruby/rubygems), parsed by [repolex](https://repolex.ai).

> **Note**: This data is experimental and subject to change without notice.

## How to use this data

The easiest way to get started is to install the [rlex](https://github.com/repolex-ai/rlex) query tool:

```bash
cargo install --git https://github.com/repolex-ai/rlex
```

Verify the install:

```bash
rlex --help
```

**rlex is designed to be used primarily by LLMs in a terminal.** Start up your favorite AI assistant and ask it to use rlex. It handles the SPARQL — you just ask questions in plain English.

To load this repo's data:

```bash
rlex download ruby/rubygems
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 7f323abe7c9ce5077cd66c0b69cdf1b65baf866b
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 7f323abe7c9ce5077cd66c0b69cdf1b65baf866b
│           └── chunk-001.nq.gz
└── blob
    ├── 009cac79345f3a087c561ee5bc3d2821bad4f823.nq.gz
    ├── 00f09320fc64d5e4551df490da348235219407d1.nq.gz
    ├── 011cd778189b7b2e8dcecaf0b9f81398a6e21252.nq.gz
    ├── 016c59541dda237eb66dd6756b9533fab0adbf07.nq.gz
    ├── 01a456e7294e2f76fbceab48ed16a6d79ac41179.nq.gz
    ├── 0205ba2235b84d3e6558a497cc594d3499c51048.nq.gz
    ├── 02e894760dd67e0387bdd2bdc366567f6c436cc4.nq.gz
    ├── 02ec62d41749127fdd757e9fcfbe1e0333577de7.nq.gz
    ├── 0329c1eec321eb7bdebbb0c99703060967d212e2.nq.gz
    ├── 041fc347b49d1b57cbe15758b0a1392fb646e99a.nq.gz
    ├── 044c71fd98cad13cbdc7ee9184665f2419ba5216.nq.gz
    ├── 046e8953085ec9e55ef13f36844b3fa650db0452.nq.gz
    ├── 04c9c74c50e974f8cfeafe5e2e5accb5d4cd4b89.nq.gz
    ├── 0550dc473d338ce485c611cae6d0840b3d733792.nq.gz
    ├── 05762c432b631ccdf33c55f85858ff237f9b1c65.nq.gz
    ├── 05a6d15129607909664165aacb350492c799a31e.nq.gz
    ├── 0626f04e0f6dd21b48370904c4cf33e0b1691fed.nq.gz
    ├── 074b473edc1ba68f9dba9d872134b369c566bb7e.nq.gz
    ├── 078158fd5628eeb141fa345e1fe8500e96dcf686.nq.gz
    ├── 0787eefae735f5f67b1b28760391e7fd8c42f72e.nq.gz
    ├── 088f69c1b8f6fa327b303517040acfb9aa95625b.nq.gz
    ├── 09ba47fea26ab36e0bf85ca91ed46d4941e4f904.nq.gz
    ├── 09ce97682d316bb38e9f959420b80baac5e14a21.nq.gz
    ├── 0a10d5c3fa763fbdf7d30188c6662bd5e054f4a1.nq.gz
    ├── 0a4e22978d822f2af095ef4e0db3c43c18ead8c3.nq.gz
    ├── 0a89e42c878df13326caeb94097904faed506ae9.nq.gz
    ├── 0c66888b2e3810754225be7d47a32e7be9768813.nq.gz
    ├── 0c7f8ba348fe407ca972d97bf62722d0dcf125b1.nq.gz
    ├── 0ceb67b382f578dd255fc638ef73b4caeec819f3.nq.gz
    ├── 0e3dde074949c6983b758937c1203976e89061ee.nq.gz
    ├── 0e9976cad39156872a01b6c2e143d0b9f7f1d1bc.nq.gz
    ├── 103d1059e8aff008cbcd8ec5ddd9538fb74c6afb.nq.gz
    ├── 10a56866eaf896e78bba58dee110693b755438da.nq.gz
    ├── 10dfe90b95fab53a1ffb98c03653d3add701f13e.nq.gz
    ├── 11df7606dd6359eb04aca7c00e3d90b3ea190911.nq.gz
    ├── 12c8943a58031c72225cfa308a65460d4667c113.nq.gz
    ├── 1302c5e3b023ecadebf3b09a2ba312e186f49d43.nq.gz
    ├── 13091e29bac33ff78c8cfa01d060060b0f0946d4.nq.gz
    ├── 13170be14d13634e9905aec78f77a02137e4d1fd.nq.gz
    ├── 131746fc654ed80d809123f50add8696ad85ac4a.nq.gz
    ├── 13be92593b1c47d8883990adbba5d823d6ca2c09.nq.gz
    ├── 13ebc04efc05ff967c7fbdbcdf64f5608f42bb82.nq.gz
    ├── 152ac985ac497980ed98408df06638cb8c90a37f.nq.gz
    ├── 179a619818c731937ca7948c9944a9d1415f0d4b.nq.gz
    ├── 195328a8bb986ddfa2e71433b6f8dd51dd7fd364.nq.gz
    ├── 19d9361a4965aa68eab6102871dee60f790717ae.nq.gz
    ├── 1a03f13c90e0ffbd73c9402c5a3f4558e2a00cfa.nq.gz
    ├── 1aa3b6532436ece6496c06becfbcefdf3ef1a78a.nq.gz
    ├── 1bd1f68779e1b79f5411a42ea22c297ae17723cf.nq.gz
    ├── 1be1138ce256fb1165027c59541827f25270791a.nq.gz
    ├── 1bf3b77875a680e60a372795a3d05fd451505746.nq.gz
    ├── 1c8d098dcc3ac3b01dc4c6a13818d7a7bc32b545.nq.gz
    ├── 1e91f493a64eb5f9367beeb3ea507faeb7288152.nq.gz
    ├── 1f356bb42c305913f73ffabe4f9a7cdd9b443030.nq.gz
    ├── 20251805fcf6f181acd2ab54f6a969bfa58de2cc.nq.gz
    ├── 202c5607b58bd9c2752ffbb47758e37d6d10ada6.nq.gz
    ├── 2069d3e712b373c04ed95c7cd77ca93ba725ca14.nq.gz
    ├── 20d028bb86a9e8acacb93001e4e175e58f525d76.nq.gz
    ├── 20d1772d7bca599545d9c509bc43eaf720cf4b71.nq.gz
    ├── 2111d6e7d4b782606e258e1d0b393ce06d8da506.nq.gz
    ├── 21e7fbbbc9736aea68b343056c4407982defc27a.nq.gz
    ├── 21fef10bb1037e2531060f91949d13ea4c51a6da.nq.gz
    ├── 22371d87b4538b4a795426cc8cf87f2e9c49715b.nq.gz
    ├── 2247c49c81ec4c75ea601e21fc2f266c6aac024e.nq.gz
    ├── 225063c73e09525dc382c37ee9f830d6e651314d.nq.gz
    ├── 229cb8b6ffce72c70af3d52cdec0de982115f495.nq.gz
    ├── 22df8c7e6b5487b44ae4dba4bc1f5c851b55b39a.nq.gz
    ├── 232da4143a242986bafe23df8103cba2952de590.nq.gz
    ├── 2349ad309a841874eacdfab899f538e36b6ee955.nq.gz
    ├── 234c6bd37dcf6e7db481714412ac5597692f14ce.nq.gz
    ├── 235a5497352379adf43a810cc1f993c3bb0ff3d8.nq.gz
    ├── 23786666e44384431f3f88fd5ca9683859351fde.nq.gz
    ├── 24629d8acb9f67c88fd95f9ae109d69fb41fc0b1.nq.gz
    ├── 25bfd2a514d72880d8821f15e2019e71bd275b48.nq.gz
    ├── 27115fd2f9eac50d6d31cc9182e463fda5e51482.nq.gz
    ├── 276f81368b668ffb3c1cbcf9bb868da2f9259b7c.nq.gz
    ├── 288da7c31feee702c49ebd1df581240d69e1580d.nq.gz
    ├── 28ba84634860c9adfb2c35dfb4ff41388504dc5e.nq.gz
    ├── 28cfbb59fbf95e9f5e29a3fb27e5d99886b5e555.nq.gz
    ├── 28d8eb41ad3762f900014baadf886d5cf3469121.nq.gz
    ├── 2b20fcafa12120e57a9e9089a61104517193e276.nq.gz
    ├── 2ca21e9cd71ef985db40d475ab0fcd398717d621.nq.gz
    ├── 2cdca06d0d617008d56e13386e39b48bd48933fd.nq.gz
    ├── 2e69821f68fc7a656f4bfffcd0773ed861a5dcb8.nq.gz
    ├── 2eb9967198fb2e1d689f8c78009c54143a29d122.nq.gz
    ├── 2ec78bcabaa85b202aa67db6462a3638807509a6.nq.gz
    ├── 2ed9f8c1c0442c18668922d86eeb3a6ca5c7fb2b.nq.gz
    ├── 2f3ec73937dab968975ce6c3be744f9a8e28a01c.nq.gz
    ├── 2fd93959f63ba1d8bff8163f6e129b8a0c481cc1.nq.gz
    ├── 3150fa2dbf593c061701710a5d4441bd525e181a.nq.gz
    ├── 31973c096501705d0692db33387e861f05936ac7.nq.gz
    ├── 31f01704339a349c84c5b5306852cc9e727566c2.nq.gz
    ├── 325f58088a963e86baa2122e33183880e7ac2b3b.nq.gz
    ├── 32ca4554396d050682c57997b0237fd043140cd3.nq.gz
    ├── 332e41afa04c513332757847a24b0b23ea5216de.nq.gz
    ├── 3344449e82a848e4d699a84dc3d9a33cbb64e19a.nq.gz
    ├── 339b362db073e755e1b412785e79eb88808984ea.nq.gz
    ├── 33d982c1c4d80bc47fb91a920b00dc30b119a981.nq.gz
    ├── 33e6d4b732e0ae98bca00cd7333ea5cc0e9388ee.nq.gz
    ├── 346cdedc42b1eaebe7f15db44d5233852bafe000.nq.gz
    ├── 3476083fcdb773008276a97353b607b2bea8fe49.nq.gz
    ├── 34dfffd10d749b9304fbda22d061a1fea0830d11.nq.gz
    ├── 3555996a032f2678afa330220242ee7cf3bfd994.nq.gz
    ├── 358e91f680de5fc37418986b4981bd69795e9b38.nq.gz
    ├── 364730e12e6e0f314c6b1b231057c579f7994513.nq.gz
    ├── 377e5bfe5a58ca2aa980aac556c6a0e337592310.nq.gz
    ├── 38cd19f4312cb6600e0533284668d50adcc5bf9d.nq.gz
    ├── 391aa0cef6575adf270bb95341c454c9b3f3aa14.nq.gz
    ├── 3a101fe9db4746eb42551b97dec6e2484b4a587e.nq.gz
    ├── 3a20bb8e6e344be2a6a219bd618f9869df946062.nq.gz
    ├── 3a252d819e7e642bf487eec2a5c7504a6452aa72.nq.gz
    ├── 3a692d4566f713a0b88fa2d820710e5de0226724.nq.gz
    ├── 3ab1b0b209704dcdc068869dde29596189a95cc6.nq.gz
    ├── 3ac1d9e6236165942c52d290423897b7eb166b96.nq.gz
    ├── 3caf5c36727054278ce48510c503d2b01c48f7fe.nq.gz
    ├── 3d5540e577b6c8895cf3deb870a76322bfe7ce44.nq.gz
    ├── 3d6cabdf11ebcbbc571091545645c99f7dad85d3.nq.gz
    ├── 3dcbe7742a8ef653dc4eaf330c61c7697b565617.nq.gz
    ├── 3deb9331396de2997c6d7eb8e7dd6704e3a03886.nq.gz
    ├── 3f576b704c08314b67523a5d68612241d51db37a.nq.gz
    ├── 3f6d99025787fb1c2f82d29a784b344495437424.nq.gz
    ├── 3f82622999027796cdfa150a3add91912aeb2555.nq.gz
    ├── 402f5d150994d9140a2f27cfc81c2641ddec685b.nq.gz
    ├── 4210ee4e70d84e8086fd66da6de0caf03a4fbd1a.nq.gz
    ├── 427e0acb0b4ce17f6ea87e4599f9754cd70c960d.nq.gz
    ├── 432d7249cc40c3991d7b268d6adb3cc8df786d5c.nq.gz
    ├── 44c4b2a8846bd72cf09b5de6b649cf0cd78b1180.nq.gz
    ├── 44d2e46aea9be261bc394cde77c7c1076f67d7fb.nq.gz
    ├── 44ef61444146a75ae0aaad890526e8440d6a8803.nq.gz
    ├── 4510b97f0d63b307f1e6b8ea145d3e947abab369.nq.gz
    ├── 452abd7d41017168cbaf06af892c64feecc3dbfa.nq.gz
    ├── 453f06fb90d4772691cf721cc4a39513a10ed087.nq.gz
    ├── 4667f5d8a2b5886434ed7d3b4de6558f45b26f45.nq.gz
    ├── 484a802fe536e44a012a20c996b9681a693e6c70.nq.gz
    ├── 487c497b1c1a137f1469facb60007bfdd7de5d9d.nq.gz
    ├── 49b0f638387d8542e24ffdf8f9545780002c9dce.nq.gz
    ├── 49d2518078b20648a3b2f26341761970d280f922.nq.gz
    ├── 4a373363e08f4f1f88fd14ff718eec0bcf53820b.nq.gz
    ├── 4bfbb25657a7adf13f7a1c97c5a882dc963a0b20.nq.gz
    ├── 4c59871b66ad55443cb88908ef1acd1e1746814c.nq.gz
    ├── 4c7af2222b6932541252d23f3f2d14b5597495ca.nq.gz
    ├── 4ca32cb66443a2616df098a33c0ba2264368f1b2.nq.gz
    ├── 4ce4da4eb67e1a1db4be68877d6cec6388a1e02c.nq.gz
    ├── 4d2a3e83100846ef122eaed8cf1932b28b069944.nq.gz
    ├── 4d827f498088413c07e51874b3843639a37d8853.nq.gz
    ├── 4d86b1ac89b77acd0ae5116a457433661b39d2a7.nq.gz
    ├── 4e5d85e903b2df87ac4429b1ac6a12e481ac1485.nq.gz
    ├── 4e8f155309fade46add0bb6f56e06a448e75aadf.nq.gz
    ├── 4f82bf381219465f44a2253e93b9b3c87a64de73.nq.gz
    ├── 4fa669e9d6e2edc9bbe6bd52584b899e1d8bf83d.nq.gz
    ├── 501bc269a5561005643a16daaa5e666129df3ad1.nq.gz
    ├── 510323d3d590fe8fa633d40d7f61c8149e0bb4c9.nq.gz
    ├── 51baaef0f989897d752f3e4631a4ff31c3d5c363.nq.gz
    ├── 5202010dacfed57b68f6cc2ac5f9fac786cc64a9.nq.gz
    ├── 528694ad1b62844af026f7f5b6cf9afd133b9c8b.nq.gz
    ├── 5327b14db8e17a96719246ddb050992f07e0381f.nq.gz
    ├── 54726ea4bb11244aac7aae1ebc32d14832da8fe5.nq.gz
    ├── 54d11c44ceeceecb0a5e78b9ded16398e5638802.nq.gz
    ├── 551fa1acd87abaf504834298e766f20f750cd99f.nq.gz
    ├── 56a7419e6edf158eb7dadf68432fc4894a7329b5.nq.gz
    ├── 570ff08fd42d1fa3d2044af9a05b71ae9ab759a7.nq.gz
    ├── 5739efd989b4ee2a33371b1294ab6fbe678b68f7.nq.gz
    ├── 57f1ce4f69779d43a4688f61f2acf6ee85950e38.nq.gz
    ├── 5ac3ca4234cb9af4079db285c95ce72f1b51785f.nq.gz
    ├── 5ac952e8672fe9a752f45b7dd74938105aca5d56.nq.gz
    ├── 5b10273b1368e3203202be4330315a5cac1d666a.nq.gz
    ├── 5c61c6fc053a5937ed409e6fbede056b5dda8237.nq.gz
    ├── 5d2e2b8ffc67bc6b7ab8b4db750b614940da3cb2.nq.gz
    ├── 5df6eed82ea6c0c5ac1eb9b1b0adae37c51d0c50.nq.gz
    ├── 5f130527dd02563cc9e166b079b6f6495e697ba9.nq.gz
    ├── 5fd6a73d91965433322a49ddc7d12890c60f6877.nq.gz
    ├── 5ff1686df4b56db0a9911a1d6a640f17fd4a5f3e.nq.gz
    ├── 602d856bb3ca7508006f888b664df4c5d2ce2886.nq.gz
    ├── 60918f3bc53abc47d783d04e26a33bdba0d51bfe.nq.gz
    ├── 61cf8a611a0fd7dd9f2a2dca59ca9c1421352c75.nq.gz
    ├── 61cfd62aa228069c137d701a77b9145f0a32524d.nq.gz
    ├── 61fbbb8e8b54e0e40a02c4a4360195fa03394ad2.nq.gz
    ├── 641f0addb4a23c8d4c2f85a7f538e37610cbd47d.nq.gz
    ├── 64b9ed9c676b178683eda3fac0a3ed8b8e214756.nq.gz
    ├── 6519b969f47de706e6990da11f92f496c3595464.nq.gz
    ├── 6524add8923c071a289d39fa01c70334ddeac39f.nq.gz
    ├── 654d638e1fe0f58b9bc19053f025af2f0cb138a6.nq.gz
    ├── 65f6ff14c8e033e96a83c0cf1d9588d8f8ccbb24.nq.gz
    ├── 662dfb1dfa16b5d4b077a78160ffab0e3037ef98.nq.gz
    ├── 668fe6c0832421a0569bea16b412def609ce7497.nq.gz
    ├── 67a2580fc090d785e9b9be858863a2ab63f5d833.nq.gz
    ├── 67a32354d081b98321a9e1327eccaa8232eb6bd7.nq.gz
    ├── 67be454a31654c2dab5a29d5ceb7086c07c9ffbd.nq.gz
    ├── 68041874333c5f648182af9737e3aca3c89af46e.nq.gz
    ├── 681f0bce9d1950c0528231770b8a2cba2845f967.nq.gz
    ├── 68781c66ead572d435abf64aac306d6fd7c665fe.nq.gz
    ├── 687eb738b06bea77b54caddfada5b7ac1dcfa094.nq.gz
    ├── 6888b7472f6e7bcd2fcb4a7f6a52ec2077d7023f.nq.gz
    ├── 68f1a3e570524bc1b5be79b32615a1dbdda5b909.nq.gz
    ├── 69b366b7d85ecb5e305e9d65f87f437ccedfc4e3.nq.gz
    ├── 6ac2e9aedf9c1203b66f2d566582cf0c7a04a7ad.nq.gz
    ├── 6ba5a23bc4332274a59583866afe57ffb1db0cb8.nq.gz
    └── 6c424d19e989ed338467f36732f8e4a3977c269d.nq.gz

7 directories, 200 files
```

| Directory | What it contains |
|-----------|-----------------|
| `blob/` | Per-file AST graphs, content-addressed by git blob SHA. Each file in the source repo gets its own graph. |
| `aggregate/ast/` | Combined AST graph per parsed commit. Merges all blob graphs for a snapshot of the entire codebase at that point. |
| `aggregate/lsp/` | Language Server Protocol enrichment: resolved symbols, definitions, references, and type information. |
| `aggregate/dataflow/` | Interprocedural data flow edges between functions and modules. |
| `aggregate/repolex/` | Combined graph (AST + LSP + dataflow) per commit. |
| `commit/` | Git commit metadata (author, date, message, parent links). |
| `branch/` | Branch metadata. |
| `tag/` | Tag metadata. |
| `filetree/` | File tree snapshots per commit (which files existed and their blob SHAs). |
| `audit/` | Code architecture and graph audit reports per commit. |

## Source repository

[ruby/rubygems](https://github.com/ruby/rubygems)

---
*Parsed on 2026-11-09 by [repolex](https://repolex.ai)*
