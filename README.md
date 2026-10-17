# Repolex Knowledge Graph of explosion/thinc

RDF knowledge graph data for [explosion/thinc](https://github.com/explosion/thinc), parsed by [repolex](https://repolex.ai).

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
rlex download explosion/thinc
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 6c38b29924b218140e5c10c2cb77e3ff487b0ffa
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 6c38b29924b218140e5c10c2cb77e3ff487b0ffa
│           └── chunk-001.nq.gz
└── blob
    ├── 02601f0d7860475f221e68da486f7d110aad108d.nq.gz
    ├── 026f3eb06d83b33695feb0f0543175e5628aed39.nq.gz
    ├── 027b1560b00e67c5f4a682bde8ccbfce27b647bb.nq.gz
    ├── 046d98940c26f73aff1882a96c85f165a40d5589.nq.gz
    ├── 058573e5bffc14434ddc90a00dbf1c5cd940d0be.nq.gz
    ├── 058d5af24aedb558d6434194c4f5b8759b3c30cb.nq.gz
    ├── 0668ba92c4d11cae917a7835e9b73f73ba94c4d4.nq.gz
    ├── 073ed23f373fe8e5a5d119b9449264a12e50cc26.nq.gz
    ├── 09322ac004ee79c11b9fa3186dee94eb5607039c.nq.gz
    ├── 0b7d712a6b0b23c4c3cd5e1865ed6e89e3a5c92d.nq.gz
    ├── 0c574d6d17cb7d2b878ca01b2b5228da7b270816.nq.gz
    ├── 0cc868cf5f5ae4634c8702cea6ca50d69e3423a9.nq.gz
    ├── 0d98ae8734960a650a044edf6207961a9efdf43f.nq.gz
    ├── 0dca755626117587404abb4f451ee544a5334357.nq.gz
    ├── 0edde97208af2221544e4502ad57c18ac0a8eb61.nq.gz
    ├── 1004b75e75f05abd26b7e62ec6561df28f4ab380.nq.gz
    ├── 103a0ecc2c40ec606bd6a02604fdf1b77a1235b7.nq.gz
    ├── 105d0ff0ad26442eb8c3de6979b0cb4c7a22a5f7.nq.gz
    ├── 10f0b4638265bf5ad75a3ff6f25f79090b033497.nq.gz
    ├── 11e18b775849a09257bbc35c1074f4e90a9816c5.nq.gz
    ├── 13aac78963c9c223f47362c23dd3f1cf18611354.nq.gz
    ├── 14414a5010dbc9dafb90a098f230f7de0314732a.nq.gz
    ├── 14f5d7bd701f48e2b50165fc3e318f375ef64486.nq.gz
    ├── 157047e37b28ac5d968c1c1a5b9b8dab8652f9ab.nq.gz
    ├── 1720dfdcf6b9bc9121e53dab3d7b45ba0bb376ff.nq.gz
    ├── 1758f5fe7aff2905dc6dce7feee626005d9886a1.nq.gz
    ├── 182b769d47384f4ff298091b2dddf60bd974559f.nq.gz
    ├── 193b82d3924a029a3ac66ad5b52aee640baf3285.nq.gz
    ├── 19c7bdba7b1e9bfe80365a50420a6d538ca503c3.nq.gz
    ├── 1bf11398c8bb1d4b01acd454e6e88152f2b7ac9c.nq.gz
    ├── 1cd4689183de12d7d48610dd3d4a8d078a833e29.nq.gz
    ├── 1e059d6d12e7452e59fd6e4fa417458a1440c5eb.nq.gz
    ├── 1f86c8c36a7ddbd71592820c46144d931a7e4e97.nq.gz
    ├── 1fff1a90ff7d5e73574a58a05e2419691386f69c.nq.gz
    ├── 203e81f4be1c1059237a206c0c0bad054c16f961.nq.gz
    ├── 204aa386edc8e6e7c1c4548738edc3812f4c20c8.nq.gz
    ├── 2090ed9a899b4cbc1927fafc2ef177f93f617cf6.nq.gz
    ├── 21790e468800b75da8df722eff5d83852af28dc0.nq.gz
    ├── 219b4ea1c28ad64ce80b6e41306b21e3419ac5b0.nq.gz
    ├── 21b45e7999c2a3035165d6b404fb622c00bea294.nq.gz
    ├── 21dec87971469471ca7fdb2b617bb4899491612d.nq.gz
    ├── 2284e93b280a22d30acbe836b0d27da0425ef476.nq.gz
    ├── 2303871fbc285d44d0a1e3ac9e230e81728b7733.nq.gz
    ├── 2372edd0575f85f5e2e5edb6ea017cd125b22a99.nq.gz
    ├── 23b2bbc9515285bc9bece015e89a05f16cdf03a2.nq.gz
    ├── 24f9dc2d696f90d93db22bbb656d34df2ec0764b.nq.gz
    ├── 25ad7bed3b9afcd9a870a5bf87d6483df163d0f5.nq.gz
    ├── 26f2cdf16038461142aacc79da7549eb4e3f2cf5.nq.gz
    ├── 2703e5dfa5b4620ab559124ecf1ddad3d1b106be.nq.gz
    ├── 28c6368582fb0858b1389f3eb928bb494558ceea.nq.gz
    ├── 2aa91d439a89bdb12c5f6beb12a13b91b6645ddb.nq.gz
    ├── 2b27f6710446029cc7097b20cb1cca66051c2483.nq.gz
    ├── 2e6cbd18e5657d5099a290369cdf4f4032df649a.nq.gz
    ├── 2e855b8754b9a6d5d32275840dcb69fdbd76aaca.nq.gz
    ├── 2fc135e41dfa4a3a3e6fb3d1d12c352a779095fe.nq.gz
    ├── 302764c3f92b47a6ad726b6c36cf2c6901ed00a4.nq.gz
    ├── 308a8b36603414542de46ec985a03030914b27f6.nq.gz
    ├── 3131ebb91657e4472dade89e62b687f517c85250.nq.gz
    ├── 31a8f4e3b0687b052155d831c43221bd9bbbb4bb.nq.gz
    ├── 31b9fa494443b18d7f2350f1f4c944b085a79874.nq.gz
    ├── 3214bdcb7756c0233887aa6951d5d9a8f166cfc9.nq.gz
    ├── 32542b9633223eca3f9f9de0e53957697fed0b5b.nq.gz
    ├── 33579a4de8d2101a71738a314c9cf58f57265cdf.nq.gz
    ├── 3360a6a32161f7c0f877a11ca228630c10f3f38b.nq.gz
    ├── 3416a98b081f9780609b7b1405848b72fdca30de.nq.gz
    ├── 348b7a733f753d8afd23352c7d28d127ea8e134f.nq.gz
    ├── 3578f7918575f64bc29f07d360ef3ae4d3e28d97.nq.gz
    ├── 35dfdc66f7b2919530959ff81c94bb87a1e8febe.nq.gz
    ├── 36bd4ae1e6d5ce19d6e045f784fff955b661cfff.nq.gz
    ├── 3801b703f854c3a971fd300826fab3f2d5c58c5a.nq.gz
    ├── 39c8b95c17a75a1b62df1cb3bcbb6d3d50095aa9.nq.gz
    ├── 39e5965f2a1dea7a3ccd3e47da384f471eb2b8bf.nq.gz
    ├── 3a9a110f17c5992a16ebc5824de6e5aace3b86eb.nq.gz
    ├── 3af8060dba870aac31bba2badb5c2ad1f3847bbc.nq.gz
    ├── 3e31c71f0d9a62e7e887f2d6f131335bc894eacb.nq.gz
    ├── 3fc1d78eeaac19b15da44e181c6301749aeddb72.nq.gz
    ├── 4006224971af5c2c5558a917df38e5ffbd34ca50.nq.gz
    ├── 40c4ad40efd205e6969d3a8eb848432212ae661c.nq.gz
    ├── 434c9608562b0f80b1d7fb03a38104bca7fbb627.nq.gz
    ├── 43a4930fa44fc5cf8e866a8e7af4744ba7bbe691.nq.gz
    ├── 43d45a3300caf4d881b9a6f7f85930714b13c371.nq.gz
    ├── 442ecb463be61974d9e5a3bc63abe52e3ef5a0bb.nq.gz
    ├── 446ac6101784e517ebb9a68a819d953664532498.nq.gz
    ├── 44c90ed4c8d243129e4b16659600d77a144900d4.nq.gz
    ├── 45fa20d7277d4a89816c026ed25b1a1812dfb57d.nq.gz
    ├── 472b6c542b743088d6d1d1b89d78dfb836867481.nq.gz
    ├── 4741f6dc3a4227a86e293a6a5ebe345283f31c45.nq.gz
    ├── 47873cc1cae0aa4ca52d8828267cba3ae40bd476.nq.gz
    ├── 47ed372d64d47bcea2d9759afda7b78de5021492.nq.gz
    ├── 480f82a7c3a59d553efedaeac8e19426d67e05f1.nq.gz
    ├── 48334185aa94d55379f3bf497c9f84312a0f9c29.nq.gz
    ├── 488a1eff7f2b4e013f49db5fe688952f64ee1ea0.nq.gz
    ├── 48b1327ca22d1512f7b31c81cbc4097d496defc0.nq.gz
    ├── 48bb3d66fe9307842da1ef8dd095732b77f4127c.nq.gz
    ├── 4b4eca2b6c7f975ef7954774ccc7ba713aa57606.nq.gz
    ├── 4b776a58cf1eeb16fd8348a2ea5b4dc6c5369121.nq.gz
    ├── 4c593feb2ae775deba672c1fda7e3afbb5895626.nq.gz
    ├── 4cc3a6cf0920e40f33c3a35610753cc8cc968977.nq.gz
    ├── 4d1204375919f5391df23a9afe73507a36d7ef89.nq.gz
    ├── 4e336640b89f858a8e0898bf452841ccf3699e4a.nq.gz
    ├── 4e72db6c4bfb9302ce6996db77421f41a419d3f8.nq.gz
    ├── 4ea2029390a37e7ac813dd5fcb2893b333d87e76.nq.gz
    ├── 506850d97657e21d96b7276efa46a1bfc380bf57.nq.gz
    ├── 5097a8c64ec2fc0cc45ec9687d8d7fd44ca793c8.nq.gz
    ├── 51ff2d9aabbdd762b65bff473c4228eae75320ae.nq.gz
    ├── 5331758a5ba0b51d2a8c974c67d7fade5c9e33ee.nq.gz
    ├── 542b05c7bd05c9d7ce878398558f3c4eba5940f2.nq.gz
    ├── 544db59e9be0b026a6738cf33d7f1668a214be49.nq.gz
    ├── 54f3f7448590a3a09e949b5f73c89e5ba69878bd.nq.gz
    ├── 56820b4d1db52988e1afcdc86fa44185b3e0b0db.nq.gz
    ├── 57e5932eca1d87641baa502a07870be4ea7a9781.nq.gz
    ├── 58f5d4165c64adddf021c1e46c5564fcf7f7474c.nq.gz
    ├── 597f67ec98185e3290e8b306bec8482198b8c77b.nq.gz
    ├── 5b79539faa586ff6e537f72ec96aef1dd7afac23.nq.gz
    ├── 5cc2c81ba0b600c0a273bef2fdc50535dd55a7a4.nq.gz
    ├── 5ccf84b586103c5e2ad67b63a700ee04d8b7c723.nq.gz
    ├── 5cf8be50f55d7fc53531fa3e4ac89e18725b5fec.nq.gz
    ├── 5ea10fc8b85c1b8d9a50f962dd3970a505ccea3b.nq.gz
    ├── 5f063ca2025d4b79d11f57690670a4843e509b7d.nq.gz
    ├── 606d50dae76985726735e5cb1977eef10591b3c1.nq.gz
    ├── 608561e13f03b43e33630c3c15c3e208cc2eb075.nq.gz
    ├── 628398be00055c3860319e5ca09e39068babefc0.nq.gz
    ├── 62ade00f6c145a6e39392a6ec7de2e7e8ebd79f6.nq.gz
    ├── 62dc8d775b6fe3b25a73d54c9f63428198adc8a6.nq.gz
    ├── 63e7dab1dc1865442b2cbdf0f3de92daf9fb1600.nq.gz
    ├── 64a09509a927a7dc96254585a70b0542ddcf2be5.nq.gz
    ├── 64a36073170e6e08d7a3a4ec3abca18c4e9c5736.nq.gz
    ├── 64fb46bd76a8280595c491090937df5ae2694afc.nq.gz
    ├── 651e6ff04f41ed615b4940b448cefa8f67244d59.nq.gz
    ├── 66e2599ec47e4e7154faf1c401bf9064d6326ca5.nq.gz
    ├── 6779bc18f772a9f52e47e7c7dcbcd60527078e27.nq.gz
    ├── 685da1debcf937ccab8d869aaff45f683bd80f34.nq.gz
    ├── 69f1f832eedddff528979d301e1d18277d500562.nq.gz
    ├── 6a8905f7047c0217b06dbf2d09740a2e5cb03a5b.nq.gz
    ├── 6cf01fe76841e9cb2403bc0502e138e22f26915d.nq.gz
    ├── 6cf45d9e80dc580b0655027cea6a6b79f987e368.nq.gz
    ├── 6e12380261ac35f0536ff0064fed8f3a4d235c5b.nq.gz
    ├── 6e2343b9fc745fcfa3ef25983e74cbc76b3fd307.nq.gz
    ├── 6f23c82b146e9964600b8866ea9ac681a92ce5c5.nq.gz
    ├── 6f3d290dec1cc3c44e5b423a32f7f50a27f7c6f0.nq.gz
    ├── 72a4ed65c2a3a2ba9e436f701abd7313d5c7a605.nq.gz
    ├── 7317e3d97076cc4c2563a4da5a4c001920e0c43a.nq.gz
    ├── 73a1638ac834ae697d0639c12280ee8126f6a171.nq.gz
    ├── 73c6e72f6e5ffbb8d7c748b4139007068697d21a.nq.gz
    ├── 755f51155eef95969a38a114d9c8c81675d8c827.nq.gz
    ├── 75d786e9e8e6ec079a0902b51105d90f51ae25b1.nq.gz
    ├── 75da7774214705f7071f16bfded2ef47fecf6328.nq.gz
    ├── 76492f7083f92f350060947dce36e04aa755e875.nq.gz
    ├── 77ca61da9aa6c6c62382f288d295ddb29a997125.nq.gz
    ├── 79163c0278cea8a7e2f32e461ad57d4886750bd5.nq.gz
    ├── 794b57da8903165605fce28be5735ee0ec0a3117.nq.gz
    ├── 7a14cc41a112ca017c32971b53095e97ba465ff6.nq.gz
    ├── 7af180b652ebd0213567a20fb2a3a7681b4ff3ec.nq.gz
    ├── 7db35261aed4004b0d572a19b06bf7124e822f61.nq.gz
    ├── 7ecd9b26a5b6091aa13e49f1d53a4ef56a120dbe.nq.gz
    ├── 7f6b7f10ccf0b4f9b7fc21d58d44d3990e1d8c2a.nq.gz
    ├── 8064bc5771f5b6abc997b50b876aff2d57fb5738.nq.gz
    ├── 81327f5a9b887de5ed1e07216181196a5c22e666.nq.gz
    ├── 81e73376a60ee0f6943c0f1df1f05b93afc6b750.nq.gz
    ├── 825b1239b05ee8958027094e41e86f76f29970b1.nq.gz
    ├── 825f3cc35764f21f69c4ae10663c5611e799eb84.nq.gz
    ├── 82cdaed36b787066211f0e994e0a0aab71b9e11b.nq.gz
    ├── 83dd365f8937d5f5bc6e5efeb4be4663401f4e99.nq.gz
    ├── 841e6c07218f8dfa66bb050c6312049bdc1754f2.nq.gz
    ├── 844d2194015559c396173394e0be79fd2c266a98.nq.gz
    ├── 84595b3790af3fb42326a6ca9842827a9a859cb4.nq.gz
    ├── 84cabdbaa6b1d915d5dbcc800e4514bf285de4cf.nq.gz
    ├── 85e984bc4def20435bc0cfaf6b6b7e8a9b9ff5d8.nq.gz
    ├── 860b05767284c9242cc821ed1e252c684878ab9b.nq.gz
    ├── 86858b7889bb065159bd537b114b9bfd871c1977.nq.gz
    ├── 86d18eb674a512c424468e4da8b71c8e6a5f3573.nq.gz
    ├── 8973c8836f1b420e8d7522b17438fcf581d7750e.nq.gz
    ├── 8b7301af0ddbbf5f4913cfeaa167d24256bd6b2f.nq.gz
    ├── 8d23388ebc484c7eeb4afa4a96d2a98be729f22b.nq.gz
    ├── 8db11bcaea79d7b803982765186c7427c151b70f.nq.gz
    ├── 8dd060c00b18d5064df5bcd02a5e63c5becbf1df.nq.gz
    ├── 8ddf5dfce522c43db99d692e5124b7237d989d76.nq.gz
    ├── 8f4a8a5a5b1b604be9d54b73dcaa7d984ac5c5fd.nq.gz
    ├── 8fdb74fa32f45e2253c68d63565969ab8559d273.nq.gz
    ├── 9070e90fa8873bb3c1d4716e0654bed3afa8fee5.nq.gz
    ├── 90b0a96e8ce43377d95d935aa0126083b4f28508.nq.gz
    ├── 91cff131f9932c78f322a08420f9eef77b6a3a61.nq.gz
    ├── 920fc2f0fc1b475e18690b6187060de21f1e9b36.nq.gz
    ├── 9248725680fe01d6476ef11d67c22a22786bbd9d.nq.gz
    ├── 9289665bde63b86296c1c968a76eae2f8278db41.nq.gz
    ├── 93e77298fe47b3840349372f3c3feb78a9aec212.nq.gz
    ├── 94ecc6e63b3b0dd5ad7397bf8ddae3646b0174ed.nq.gz
    ├── 95808eee15c21725d4c7b2ce913a435ef180e5f7.nq.gz
    ├── 95e2f41c78bd4946c44b4f277ebc69151bc8eea1.nq.gz
    ├── 9658a788f441523b4de045b2ef013586345ae3b0.nq.gz
    ├── 966f574f10d55b879d8d62aefd8eb55602a11987.nq.gz
    ├── 971f4645b24213d7197f91b84189ee2f8e9a5fc9.nq.gz
    ├── 974ed2c8c1a04e8181cb5e0139fda8162622e61f.nq.gz
    ├── 98cbd85f507e4c945d9ecbf9f62b5055bf5a4f78.nq.gz
    ├── 98eba8b960b14c15c2a33de097fd0323c6cb42d2.nq.gz
    ├── 9b04f8923318e3d5267cbb2e8aee372975aa8e68.nq.gz
    ├── 9d413f93a7fa46c4d7a92e3efbf4bbdcc284b6b8.nq.gz
    └── 9d7e78553b4c0c6b51f87e71be6022655fd08153.nq.gz

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

[explosion/thinc](https://github.com/explosion/thinc)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
