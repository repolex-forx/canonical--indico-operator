# Repolex Knowledge Graph of canonical/indico-operator

RDF knowledge graph data for [canonical/indico-operator](https://github.com/canonical/indico-operator), parsed by [repolex](https://repolex.ai).

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
rlex download canonical/indico-operator
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 9bc81f9c4b56e8aa84523ff5a1f5e29131aeb33e
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 9bc81f9c4b56e8aa84523ff5a1f5e29131aeb33e
│           └── chunk-001.nq.gz
└── blob
    ├── 001c68676a8e1459778622ad7616a01702ba161e.nq.gz
    ├── 01f1384fac267326ca676ebf27bfe42ec9ebf70b.nq.gz
    ├── 0220a0df529729f01f57077cf1ca611709b698d8.nq.gz
    ├── 03fe3852086e82d2adc8905b9469f834be290e7a.nq.gz
    ├── 07fa5f6516e740e545a04c3742143551e4cc7c97.nq.gz
    ├── 08f2c08f3d5168271d3db97ccf16d1816c54305e.nq.gz
    ├── 0c11e1d991e956fb190b726d080d4df44bb11c21.nq.gz
    ├── 0f285e4186a2ee9e4641018f56669793b1032bbc.nq.gz
    ├── 10472fa45ef0ef9dad481b002acb1fcbc743c42f.nq.gz
    ├── 10f2a3daf6675813bc9b3e7e9ae6f7b7e91112de.nq.gz
    ├── 118305bedccb60a67643cd558c60dafa0c2756cf.nq.gz
    ├── 135346c0d47f65efdf6298cf7ade243af2077283.nq.gz
    ├── 14dbcf4bc3fb6047abf3ae9cad8ef467b66aaaba.nq.gz
    ├── 15b9e6f9ca5b5fb98f332d9b43419f714e76e91b.nq.gz
    ├── 15f3e626ab301ff964553acff4189bfb96812306.nq.gz
    ├── 16d40bc3fe31ffd49851f5bb67023872d8ca1780.nq.gz
    ├── 176ec5dd25221bbb00eb8cfe84eb07ec594777c6.nq.gz
    ├── 17cca6b11192ec9f4976d36126f0bbf697f859cf.nq.gz
    ├── 18ee42434e5fe536bbb9ddc4a957f0437ca885d5.nq.gz
    ├── 19ba0f017600ff20dc26efa99764a0f5dcc29ba2.nq.gz
    ├── 1a6ae2e7e66b64757bcf13b53d21539d5886115e.nq.gz
    ├── 1dfe8fdacb569f68eea47c5a0391c8f246c03cac.nq.gz
    ├── 1e34714872efbb08901230ef3def3c3b42ff372e.nq.gz
    ├── 1f7549b5c661c1786050fae051c53833611dd012.nq.gz
    ├── 2610cd903a3bcc80a946fb0285398c36f0f98d26.nq.gz
    ├── 26ac226df88c6bc3785214f437d30606702a7736.nq.gz
    ├── 27bb652f1213bb8f6a595a061a795662b3637817.nq.gz
    ├── 28463d0a68693235d0ffd7eb3008885b41d6af51.nq.gz
    ├── 28b808c88154e25c9bd10ea556f7a373dddeff53.nq.gz
    ├── 292f57065a37d9a8c09048e0633163f5e1ce00eb.nq.gz
    ├── 2963c61d00e1a11f18a3c6da4fd102c89db0ae49.nq.gz
    ├── 296fbdc6a9667174c65b15af851eb42665675c38.nq.gz
    ├── 29d45c2ecef1155c5eeb129f7afa2d55a01162cd.nq.gz
    ├── 2b1d398466369927f3dc4a5074edebc12c7d5e0a.nq.gz
    ├── 2cee21957762685db97b31b069a20302b8b36336.nq.gz
    ├── 2d153ef555aa0c7649c373733c52d3b75c0cc734.nq.gz
    ├── 2db7f38922b53bd3323492fe2532042a05ed74cb.nq.gz
    ├── 2e09282bbbfe8180c65e9fe610a77a54fd13020a.nq.gz
    ├── 300befece421df96d88885bf2c433dc23f523c03.nq.gz
    ├── 323657b329d18e2088c9599cbaf405a32a443c0b.nq.gz
    ├── 32b5444813981f26959634ce05c3ebccefd539db.nq.gz
    ├── 33339f32fd22c146961cb30c0eb904862c7e6f00.nq.gz
    ├── 3372cdf832ee05e9662c2b38bd09673703f18820.nq.gz
    ├── 33c8e3bd1dfd68af038ad24a2ac9a9a4ecb7506a.nq.gz
    ├── 343929265751bce08c867607c5fa378dd0593018.nq.gz
    ├── 35141df76702ea64a74e65a2aa3b418d17581762.nq.gz
    ├── 357f55e4ab7b2aad8c1dbe7aae5a6c90284a829f.nq.gz
    ├── 3586261576f4dd25442a5e693f046d5363165735.nq.gz
    ├── 361cd3aca830d47639ce44273b8e3d143e70f698.nq.gz
    ├── 361f4b756203e9f3a937cccaf2869f7f0240e5df.nq.gz
    ├── 3724ad9c3ac01a8d985397d039061ec060900c92.nq.gz
    ├── 3796c50b21196dac8498fcdb387c6a2613faa36b.nq.gz
    ├── 387ac6a47738bcce3f686ea6d43178ab2197e414.nq.gz
    ├── 3c342466ec42b7e36b8498c16ed7e4eddba4a799.nq.gz
    ├── 3d2fe9ebad4fa416bb2f730815644508c26cc32f.nq.gz
    ├── 3f685be832130667499456477f2574666b002066.nq.gz
    ├── 4036c82187b951211aa0f9da7dd27795b793d74a.nq.gz
    ├── 40883c712d1ac801d36c13b7f902dc8cf6a5b130.nq.gz
    ├── 438fdac041eb86f18025e572c2fa95baddcd4cc2.nq.gz
    ├── 466008c7e75c0ddabbb27efab058c417fd675d47.nq.gz
    ├── 46f1824c1c114d7065f9fb0fe8da8c27085bd8e9.nq.gz
    ├── 47834d77d94f8ee2e4a2e4fb34ad91489fbb54d6.nq.gz
    ├── 47af15026c178ea8bd9fe7ce73a36410565ccef1.nq.gz
    ├── 4a4e9530b5e70331eb465e245d7420b2b1c92517.nq.gz
    ├── 4a795b52d421c32596360970b903736d4b003fee.nq.gz
    ├── 4b5798945e98476f482fa573c4f46d8ca39957c4.nq.gz
    ├── 4c607ac12825cccb1f500014acf16095fa012dca.nq.gz
    ├── 4e723c07a2bd0453118f9642c97b1b4d09e76912.nq.gz
    ├── 4e9337f265ea72fad550954982e51c8fdc32adfb.nq.gz
    ├── 4f74b6b5567079110db5a10d3e65beee1dbe7c92.nq.gz
    ├── 4f7ec9ca0b0776a367c23774003d3e93dde3ade3.nq.gz
    ├── 500bb9357e3c80200ef01df9cfa5b370493da9ad.nq.gz
    ├── 5329d5a30ab2c581398a4595862e21f4b31fcaa6.nq.gz
    ├── 53c2c7dd7ffe582f505f51d0708de7f2e81093ff.nq.gz
    ├── 5474504762282fdb8e1f7cf9511f2139d6acc05c.nq.gz
    ├── 55969d643048afbcfabdfa8a3314e271294fff2f.nq.gz
    ├── 560b3c8b0ba34580a609251784cc3c4c473eddb9.nq.gz
    ├── 566cd5a7069020d894addf78ab1317ce259250bf.nq.gz
    ├── 571736363943e022ff04bcbc71e9337bf8318eee.nq.gz
    ├── 57d3d2db001fa90be76979ff79717fbbac9d44df.nq.gz
    ├── 587ee48cea0e62f519e3ac29a6feccc86554bae6.nq.gz
    ├── 58a85cc1412f67ce8b04dbfbc2b595164c041d78.nq.gz
    ├── 59070a9dc8ca19571af61d6956751ef4da241f1b.nq.gz
    ├── 59e8f9b8499516c81baa3c7474a491d7043995be.nq.gz
    ├── 5b0801e5bf80fb7be2c0c416263bc1b25d8e46fa.nq.gz
    ├── 5be1d93158856891c2a493ea37cb1f116fc81f61.nq.gz
    ├── 5be4648dd309fb7589442170765c8250d4ff0cd5.nq.gz
    ├── 5db9d90cc8d12d774569702ef04f03d601d1c61f.nq.gz
    ├── 5fe5099759430650d5542d114b09ae1e7742e3ae.nq.gz
    ├── 632a850d543972b4cf9bb8a3eb7b4e2ad60c5aea.nq.gz
    ├── 6370cec0afeb9a6abb153fdcedbe5cf2a0adb85c.nq.gz
    ├── 644a5bc64d87b31f724d0c00c6ab0919107ca3f7.nq.gz
    ├── 65f4410270649b54a4c1a652b651d51175f64783.nq.gz
    ├── 662f49c0b0e946bc040b5c77b540c53161f0e01a.nq.gz
    ├── 66649de94c98ef7f1e46f41e111b81189077d8bb.nq.gz
    ├── 674890606799025c8635794f11bfdaa35eabeb55.nq.gz
    ├── 69d955c9c4176610f1ec1d34ce928c5679c3a2aa.nq.gz
    ├── 6e0364bc13900ad6edc9e6898674a5a0d97251fc.nq.gz
    ├── 6e102a6a9c4dfcd8faf3ee644f8ca0ed455af288.nq.gz
    ├── 74457b5e5df6aa2b218284e0a835796f5f22ba28.nq.gz
    ├── 74922a52b61ecf0a8f3a3b136dc02faf08a2550e.nq.gz
    ├── 74e4b4b86bd73e0d44d5fba812310ae31d6c3537.nq.gz
    ├── 7960381c4a13d06d6fd45c0feea18cec76d06cc5.nq.gz
    ├── 7b7650ea9a5b03de707271a4dcb53cc5c932afa5.nq.gz
    ├── 7b9d8f73d97d1dc90ea019126b509f2ad5f4b114.nq.gz
    ├── 7c1d7a155f29effe26ddb30fcf4b381e066cde09.nq.gz
    ├── 7c4bcbf0f00168f0128fde6fbeab3a57838c12c3.nq.gz
    ├── 8264f21fe0dfea8d653c55128c1ea3ca66405d01.nq.gz
    ├── 82847ac1e77303281b2d0d89b8658e5d94897e5d.nq.gz
    ├── 82dadfcb7166fe3e6fd15bb26f1b3736cb6b6913.nq.gz
    ├── 83fc432628fa1906bddcd2448fc9198a6e0dd86f.nq.gz
    ├── 859bb1aab16b7df4f997f21aa87dbe3cfef7346f.nq.gz
    ├── 86199f30baf079e60299c238a4fad6637139f6d6.nq.gz
    ├── 8847a3f456d5a4155d393f5a7fc0e42a37365322.nq.gz
    ├── 8a0d0bef69e710dd6f1b69b51209b83792a4e0ce.nq.gz
    ├── 8ab7f285e27e818741f688c454c3fada4f29649d.nq.gz
    ├── 8b080928cf7ae836d0a3ab9a5f72ac23c51d1b56.nq.gz
    ├── 8cecc1ac5b6e41e3a9d8f228d021b6a37272c83e.nq.gz
    ├── 8e487206c95496beefabdc9641709420fc754b5c.nq.gz
    ├── 8f338aa320cec8e5ead8ffb4bba0c2abe84dca50.nq.gz
    ├── 8f742844aafa83b0cc065c773fc9ea33ca066882.nq.gz
    ├── 95ce8570f5510a17475b4b9e07c43e3c4d241e7e.nq.gz
    ├── 9886fc2b40dfc111e4cc7eb94e14591d5ee21aab.nq.gz
    ├── 9a152becdde63ccf89aa9863c433ebf9c01dee01.nq.gz
    ├── 9b4f7fc6710597c1d339f36e4896ad2191453c5e.nq.gz
    ├── 9d18407f157b733046a7286ba3e4cbe04ea15598.nq.gz
    ├── a0b4d1a02f518cdc9274d79365a4e9e0f9f6c149.nq.gz
    ├── a0e7acae13c43f496f4d9901048871ab4c435ae1.nq.gz
    ├── a502f3813602713efa9574d6485b71b89c35601e.nq.gz
    ├── a6c42cbdc6e7324cbcd98ce0f5cc34eaccf93469.nq.gz
    ├── a990a83bf38818a5742d21f3327fd1d25c4728dd.nq.gz
    ├── ac97d401a864cd1e0f49ea30de9da51fe1e57aad.nq.gz
    ├── adc01a3b240b316aa03806e09841edd16a7a7577.nq.gz
    ├── ae5bcf787a31476208e4d561899f20d55c91b881.nq.gz
    ├── ae6e89da128694cd82320c67588ef8276ed3234b.nq.gz
    ├── b08cc3e45d7356c19761cac17fb30ec4c95b090b.nq.gz
    ├── b0ba328285c259c38970e18332094050aa98a811.nq.gz
    ├── b13459fe9b6ad7e9f07ab4aac7b18661ac8584f8.nq.gz
    ├── b22d9f08ec4bc43aaf7f7b721f687c3c8086a683.nq.gz
    ├── b27fc5499f68f998d19a9676125dcc7ae2fa08fa.nq.gz
    ├── b3205fa52e318b524bc130c43cdbb870b35aac86.nq.gz
    ├── b3ad82239ef5f8686635af6425e68e12f27caa92.nq.gz
    ├── b499087db8e4856371d837d06f2304316e4e26ac.nq.gz
    ├── b663b159e7898812c771f35c9894cb92e775d7eb.nq.gz
    ├── b66c84bf5c07daa5666e48e449e3432b1874ef8d.nq.gz
    ├── b8105b92d526dd1086e0839b9f21bc02b9c923ff.nq.gz
    ├── b862743e060f48d12efb814b78e33db046ac058b.nq.gz
    ├── b8cc02bfb2072081e43fc02b02a1f43c61e6a75a.nq.gz
    ├── ba6a6a74cbbd2fafbecc69c74eb1ff05cd7cf6f0.nq.gz
    ├── baa8e7d8f46992a28056285acd2b8e0f2e4740c1.nq.gz
    ├── bc41676249f4701c5f3e5560a7c28f38d7ded3e1.nq.gz
    ├── bde22aef3d95db1f306a8e39fd53fb5e85a8d2f3.nq.gz
    ├── be0392a49109598af79890d74bef1f79563b2ab7.nq.gz
    ├── bf868ac8c28ec91f486004634bef847a7981071a.nq.gz
    ├── bf8a9b01db23031b24cde4ac7c90cdee4d491808.nq.gz
    ├── c0b075801a4497278a0e7c748d7b96a179b2f893.nq.gz
    ├── c0b35a3a058285371a656f208d4194286c72a075.nq.gz
    ├── c3a99a775797ee3cb9275945ac757a5fb3854f80.nq.gz
    ├── c4a371b812c1a5056a6bfe2068b2a73eb8bd3a7a.nq.gz
    ├── c51f8731433ae312f489f87b230c5aa38ef668fa.nq.gz
    ├── c53da844df01ba2cfdb2f14d9780e253e9ec3488.nq.gz
    ├── c57fad8bb3814b8fc2ce177aa319911cf45333fa.nq.gz
    ├── c654cef4e99c5c070ef0f0341a2557acedd0d190.nq.gz
    ├── c6cde83f6f4744fdd2b14145a9aad4c14e242e02.nq.gz
    ├── c872ecb65c8a07369078f6b4e4ce7da494336bfa.nq.gz
    ├── c895d699692601fab2751d257451d7b51a5df0eb.nq.gz
    ├── c8a0888e490c6be44aa1fda4068cb01161512ddd.nq.gz
    ├── ca29970c256f673457d5f0a244100b9a3e3e8b42.nq.gz
    ├── ca7e5380bc842328e4427d233a48278e84f4a4a3.nq.gz
    ├── cb3c60baf10420e25c33e325cc6c994f2b9dd8ed.nq.gz
    ├── cb5286105b7e77decfad7e05f246082302e171dc.nq.gz
    ├── cb77003d633dbc9b06b339a3514808c5500298b5.nq.gz
    ├── cd7d9e5747091656ca4797eb3f6ca5a4faf861d9.nq.gz
    ├── cf6e80c72ab7547892122ad7aab536e31338accb.nq.gz
    ├── d3b50c817e48b992030c432c24a0ce9f5b071f8e.nq.gz
    ├── d457bd1a84d276c07a872525764b64c56c5ac07b.nq.gz
    ├── d58a30c21816a7be23f14464b9f3f38e57f295f2.nq.gz
    ├── d7d64a26b8da566ce922a7fa58fba9ae75a7bc5d.nq.gz
    ├── d9947315d282c9ebbb278f66f917f80bdb8b412d.nq.gz
    ├── da51d8836c6e0fe2da9703489cb3cd97fe59f2da.nq.gz
    ├── dbf4d5bb721e2c91fc81ad9e7bc352896740ad17.nq.gz
    ├── dc97ba2f6bb308e9ef5513ed753cf3a29f26cc4c.nq.gz
    ├── dd3004e26df9bddafd1ff2f5c4d4c14dc135b123.nq.gz
    ├── dddb292a2c1698851f1fe7d4eae27a5c284b55e2.nq.gz
    ├── de6a96a3b72ccf3845324f1582a153d3adb86e83.nq.gz
    ├── de75e74912147d3b209be67c5fde1a35eb9c976d.nq.gz
    ├── ded5cd278ca6c6b1252e4881d04c5ac5698f3dd6.nq.gz
    ├── df541556b4c8b8d1d2040a3acdf1aa8872e9c1a7.nq.gz
    ├── e1a0523badee0162126b511679cfa4e6c11da042.nq.gz
    ├── e28b14c2de9526b516aefaed241cc29d2a8c7bfc.nq.gz
    ├── e3dfee5f85a95a85b5688aab0a6ffe5c564c7933.nq.gz
    ├── e502ab27985800db4bf457aec679cd2ccfb528b5.nq.gz
    ├── e5a920063fe072fac755274c39d109fcc2ce3ba1.nq.gz
    ├── e5fc9f9d902c29a31a0f48c9d7860ff7714b9311.nq.gz
    ├── e8f04ad4780b28a434e9392d540772d5f7269ab9.nq.gz
    ├── e9b32007424eba2a949a1d3b263ce0880189a142.nq.gz
    ├── ec4696228b83dad52104880a825eda73c8526fe1.nq.gz
    └── ee119d2f10c26f4c355b168aad7431c9794ef02e.nq.gz

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

[canonical/indico-operator](https://github.com/canonical/indico-operator)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
