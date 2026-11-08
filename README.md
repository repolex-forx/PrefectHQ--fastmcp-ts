# Repolex Knowledge Graph of PrefectHQ/fastmcp-ts

RDF knowledge graph data for [PrefectHQ/fastmcp-ts](https://github.com/PrefectHQ/fastmcp-ts), parsed by [repolex](https://repolex.ai).

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
rlex download PrefectHQ/fastmcp-ts
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── daaf443f8d0a9e8d90beb7fe0c487d06c72a2d3f
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── daaf443f8d0a9e8d90beb7fe0c487d06c72a2d3f
│           └── chunk-001.nq.gz
└── blob
    ├── 0036dea2450da2ad5c444fa8fafdb55d9a4a8b19.nq.gz
    ├── 008076e9f3974234406e747aa0fe2d78d4c4b541.nq.gz
    ├── 011905bb7c1c86d91ec3d132a62ac17bfbf2bff7.nq.gz
    ├── 01da70c604899a8a127b6eaa0d78fffc55f44ce6.nq.gz
    ├── 03a6c7818c04c38cfb77104f7e80466e26ae2e88.nq.gz
    ├── 0551ad173e1bdd7f4106d9609abe6e628670e898.nq.gz
    ├── 0592b0bcbb5826b28c87e227f78ee9c941188d89.nq.gz
    ├── 05c81344d5d9106cf912bfa7346d5a711cd95c95.nq.gz
    ├── 06fe172d6558ed6ca90a4874b2a58fbe4402abb5.nq.gz
    ├── 070528c2dfdb5b4e28cd1935cdf53c78a082a3c7.nq.gz
    ├── 081ceac366bb1f68a3fd83953b77d632f19b6299.nq.gz
    ├── 082db4a498445f23168f47126fc9ae2156e030d2.nq.gz
    ├── 0858fd0470bfd14bcf93439171e2a4424091d285.nq.gz
    ├── 09927c4aa0001c77ec4a76ae8fc52cfcd3465530.nq.gz
    ├── 0a45450fd11ec052746fff5e9e8c887f255514cc.nq.gz
    ├── 0a883a4c81d9e259d37a9ec639a114a4a70d77c4.nq.gz
    ├── 0b5a29ac6c33d24459175d147301b6d1f88beb9a.nq.gz
    ├── 0b85770b242abc8ea28b8f2f3446aeac7f31c27b.nq.gz
    ├── 0b9db7e5922d6feed0bd36faede446aac6fee8e4.nq.gz
    ├── 0be3570594c95e6f9f64e087bd0f7491b5bd2827.nq.gz
    ├── 0c12a682623b85d852b143bb0a8ccc47c1b21f0d.nq.gz
    ├── 0ccba2a1f9384183e63798b7445f36a30e13b03f.nq.gz
    ├── 0d03ba48bc3b19d5db6b820db1d518f678b7982e.nq.gz
    ├── 0fd7c59bb8571ec3b6ea42ce9e615eaabf974a3d.nq.gz
    ├── 10ab15abf557666615dd19031715e1c82686a6a2.nq.gz
    ├── 10e809a3bf242629d5d1948d9e5bc2cbc443104f.nq.gz
    ├── 119fdeb55d830582f60aa96fe38fd08e8d0131e6.nq.gz
    ├── 11b2ecabdfbfe2905fb9c81b0c0ce47560088dee.nq.gz
    ├── 1284169a6251515c42d6b96c5565e5639214b28a.nq.gz
    ├── 12dbfd3fedf7f1ef6eb992e216b498fe4898dc88.nq.gz
    ├── 12fa36b38a03a3a3841e407253f13a08cb6abc26.nq.gz
    ├── 13251861e93e8b2689387b9bec4c3e21b18d07d1.nq.gz
    ├── 134d292b286af6eeff9100840d0fbb8bc19a9ef7.nq.gz
    ├── 13f2cffbd8dbeecfdc43ad37eec15ec4d75a5421.nq.gz
    ├── 14824565df270535e7ec556ebf66cebf9fcc15ba.nq.gz
    ├── 14b416e8c1f189f08650f0fac20eb1bea11b9a46.nq.gz
    ├── 154c419bcef1d8ff9fec8a83ec79bcd84d52168c.nq.gz
    ├── 159da00ff05a53e3f46e8c2d14b2edbdde35978c.nq.gz
    ├── 163c2439ab807ae4af80e1b9e5ed39247170268b.nq.gz
    ├── 1699ee173544d6214c0781f709fafa0ff2aade41.nq.gz
    ├── 1765086752e384de6d4d086b58826c37060d6c7f.nq.gz
    ├── 176570cbe5160e9e3fdbbd69dfafb02b4274d83f.nq.gz
    ├── 17bf55ad3c5d845c490df1a6edf871800d3ccc3c.nq.gz
    ├── 1a1097705848dc8199a6869f9151d78d732d8829.nq.gz
    ├── 1a3a784aae7aaf7fcd8cbaeac26a849de56e0f3a.nq.gz
    ├── 1a82e42b92ab7a4ffc12c7d29b6270ff9ce1b831.nq.gz
    ├── 1ac722ed1066e0e0413cc414f13e11efc1dd40b3.nq.gz
    ├── 1b4e8c7b2d851425b60bae994311f6b5221e1a7a.nq.gz
    ├── 1bb48ec72d0de4c576660810c0028b5fd8563d9b.nq.gz
    ├── 1c4bfe1bbaa0ae0a44d2d8f89b647e9fb1ac1932.nq.gz
    ├── 1c7021518c7429549bd91584293b5b2e2754cde7.nq.gz
    ├── 1ce55be001fcc66ab1d4a0f0a202f07c5d5b3f44.nq.gz
    ├── 1dd64bb31391ad3d86933d97aba6178435d87455.nq.gz
    ├── 1dd7567a92240d2f5a50e6aa809eb5eb28de3505.nq.gz
    ├── 1dde16cc03022d858c2803c91988a3a7c9279be8.nq.gz
    ├── 1e0e24f9637f706cd021bd24523b739d7ccfd141.nq.gz
    ├── 1e392eb4fdef0a7e6d0360666f55a72d3df291b8.nq.gz
    ├── 1efc66ad5bdfb3f4a1116bc4a001c63b1a071a07.nq.gz
    ├── 1f7e3696b5feacd274b194daf312d6e9069bd076.nq.gz
    ├── 20f761ac19ca3c44ccaa9bc7c3f23f57583cbd49.nq.gz
    ├── 211ec55b3d0132f0e189d32f52da1c8112c57a80.nq.gz
    ├── 21e4c14e7d2ad18e39ce44a0627c368e2d995dc5.nq.gz
    ├── 21ea740b5c71372b3909602476270695bd455c3b.nq.gz
    ├── 22059ebf4f0a201ff3106c0e4422b38b79e90826.nq.gz
    ├── 228f508dd802ee11e59d54a21712adcb5414e011.nq.gz
    ├── 23d4c60f72089e2b33e2db99a79e65570f6e3fae.nq.gz
    ├── 23e37b82874e8879ddb4903bfcb6ed264fc77117.nq.gz
    ├── 24b62d1c105fd6345224694d5fb61d8965301813.nq.gz
    ├── 25691ad6e36e86715c83d8843b610998b0bccdac.nq.gz
    ├── 25a02912221d5f03f73f459ebad478fb818d6697.nq.gz
    ├── 25a491897ef55433711841b9f5ae23d818117f7d.nq.gz
    ├── 2657185821a6adac809e31d3243ad9d097ffd9e2.nq.gz
    ├── 267e009a7b9a907167db722765b95f5199565d0c.nq.gz
    ├── 27bbcfb1f0cb6205194ebfc14ff5b3e774b0f9cb.nq.gz
    ├── 29072515586c34a4d7d8bca35f469d2f739ea233.nq.gz
    ├── 293b25577a623c0d21ad36f17e8e7142be162a45.nq.gz
    ├── 2b11417316ac1398cf324f850b65663a64e59d69.nq.gz
    ├── 2b13e2fe2b753f279b3038f6f3e1ff7067533d88.nq.gz
    ├── 2b53f9061d9e29fdf070d9b5b98f4feb12fc6696.nq.gz
    ├── 2c5ad12b3aecf512c03820b5c0909658ebee9208.nq.gz
    ├── 2c84df9ee8fc48c68377b8c389c3f0d9e8256922.nq.gz
    ├── 2ca32446fd391cc728f229adbbb61ee6e79c6bf7.nq.gz
    ├── 2ce2a9cc466d51517cdc94d1e468d040a02b9476.nq.gz
    ├── 2d4db76b353003ac1004ee8d85aed4e4a4c8021c.nq.gz
    ├── 2d68524e892420512444e61e8c17e49c033148e7.nq.gz
    ├── 2eba4cca564d1328c0923bb4d297d36934a965fd.nq.gz
    ├── 2f3abfecee8d17974b56ebd5de8d962eebcfb2ad.nq.gz
    ├── 2f6792b036fd0e8cfb0ae6f1266bf531b6fc0e6b.nq.gz
    ├── 316a53e05e5e851657119126838b8eb3636bad32.nq.gz
    ├── 31b38dbe427c1e4d767238d0a4a3296f3af041a4.nq.gz
    ├── 321301ddd9437c772cd1c81fe8f092f38fd0dff0.nq.gz
    ├── 32246e5ed0a64b83b3b82c0ad63293a4f08fc242.nq.gz
    ├── 3291a87d40967114e3523588a0aacff671954b76.nq.gz
    ├── 329b32941226ef5d237589c50817eff02cc74be2.nq.gz
    ├── 32d05e82ff97978385fa03b9505e38fdde801d49.nq.gz
    ├── 32fbf65e73f96d6123ce777a84e6476ec7c8bd5c.nq.gz
    ├── 33588e03c4986872c6c2ed036a100fe9421c6f74.nq.gz
    ├── 343c73f360a29fccdb1e969c7b11b112b0c14b51.nq.gz
    ├── 347e52064f3b24a4fd206b9479771aed9e6e3f99.nq.gz
    ├── 34a1b283898ca4a5b7f4914589c2991cc7334875.nq.gz
    ├── 3548b504307257ff0f810a88fd6964f88514bd8a.nq.gz
    ├── 359f315b58183bedd185f247df0d6a818397a725.nq.gz
    ├── 35c7f6fc45d19fb643d94a73e608757c3dbdf80b.nq.gz
    ├── 3628556fedd209c3746baddd4a24d7ec827cdec2.nq.gz
    ├── 3706bb6c2583447a081a41a64b3ecc78f78b8e79.nq.gz
    ├── 376d336a4d54e9bc3cad2f4e81af9ec6387a8358.nq.gz
    ├── 38965bde831f5a40ca743052f13fb938a45ff28b.nq.gz
    ├── 38fc1e8489d5449fd26945ab3a5b93e645191b99.nq.gz
    ├── 395bb19d22b17396527adab2a4affa0d45176dd6.nq.gz
    ├── 399de1db39d0a2bde5c608665f0fd858709dcc51.nq.gz
    ├── 39f72c7112029a55e7dbe8d92b1902d6011e0047.nq.gz
    ├── 3a2ea5cb95cf00036ab37eae5494abecbc202050.nq.gz
    ├── 3a99273ac60ea50601723077b557dcbc421432f0.nq.gz
    ├── 3aada11af3048bff784e22e294dc871c774576b6.nq.gz
    ├── 3aea93998117c562b79ad8d9d06423c8e9b836d1.nq.gz
    ├── 3c50b56e335cd82845268cf13b93f2afe5c6125b.nq.gz
    ├── 3cc1e5354d9f817d398efeae01081a8d970289a1.nq.gz
    ├── 3d49232b06f7c0c54c6797e5abcf5c74ccdda9a8.nq.gz
    ├── 3ed5e740ffd8541d92a60b7899495509889b8a02.nq.gz
    ├── 3f64626597189874b7ddb62375545df449f20875.nq.gz
    ├── 3f6e2d2e8a19eb50e938e8a9c5b055fe00ea17d9.nq.gz
    ├── 3f774987d65606cde60c5a7fa38b2b1ad3f3beb0.nq.gz
    ├── 3f7c418cb7670961bb89494804303342a19791ac.nq.gz
    ├── 404ee93cc02d530a59e0d8af580b0f0a83a64d0a.nq.gz
    ├── 405fdb61d29a76b4f418f6bb0868749f0b0f8ada.nq.gz
    ├── 40af270fb2a99ae84a354e6ad8bf67705d2a811d.nq.gz
    ├── 40ef365ad56c7627ec2db5463e7985fda1627d49.nq.gz
    ├── 4159126cbe1c4dcb1c1068c4fc424499715cb50f.nq.gz
    ├── 41cfb163fd8a17c874b10ccc70550b2bd7b13831.nq.gz
    ├── 41e9acf8fe93d04e9712df3f1e4a66f1bb9bd8f3.nq.gz
    ├── 423c89646bb32ff16b63eade3e44e7218476259e.nq.gz
    ├── 42982c0ab7330bd489273f03d8bd2051fcc35d2d.nq.gz
    ├── 4366b97b7b0e8948ff124c9523d731ad3ae65aba.nq.gz
    ├── 43beb2ce53127f176174089c6d4824c658cb3318.nq.gz
    ├── 43cf799b8a13a28aaa60063cb426e46cf8708d46.nq.gz
    ├── 440094df74873602cfd322e00a5ffc75ed8b3abd.nq.gz
    ├── 4442f16ba19627a111d894201a950146084c9a2a.nq.gz
    ├── 4535e939ed1e7d7257a6c8e56ff7fe85c1adf163.nq.gz
    ├── 454bb4c2ff1e1c256ae9563580c7661683dd81cc.nq.gz
    ├── 4951e08f6b1615b2f3e3bd62cdf1d215e5b2a2fd.nq.gz
    ├── 4a03a8a0c3bfae1eac0fc45206919698cd1f476d.nq.gz
    ├── 4a0b1cc5fc4fe2ad28a37ca175325fe3ce08cd93.nq.gz
    ├── 4bd8aba6aa1fe435316db5dae37d79998247974f.nq.gz
    ├── 4c1c76d0c281e15aea2c4c2b38ce577c13eef8e1.nq.gz
    ├── 4cb1da87e5ef80f458084ab00d0a4c00a4525411.nq.gz
    ├── 4ce9a85374e4903f412f26a0834b164bde7cd416.nq.gz
    ├── 4d530ea421bbbbe85d78d3ffcf629d234627779d.nq.gz
    ├── 4e071c556af6dbde11f6aa0ba29eaa4c7f95797a.nq.gz
    ├── 4ea0ba4f77e6c940ce81ea2d13f011679f5c1121.nq.gz
    ├── 4f51b7a89acb656c6596dd484adc8f86adf598b7.nq.gz
    ├── 505160f0ca96b887e13bc806078cda8c8f84d880.nq.gz
    ├── 5073c16ec62fcf252457ca5798c3681fa6d6a3c8.nq.gz
    ├── 50f6c47f48785ad47d8888832b7ad11f378519cb.nq.gz
    ├── 5115d006ca6e86794f3c530408bb875dca710336.nq.gz
    ├── 517b2730ee2cb21fb5b282a8d91d04fe45c8a5f7.nq.gz
    ├── 51a044074f34a5c0bd81d580c03442992164e20a.nq.gz
    ├── 51a8f87f6dfb7bc398b214081e9d427ace99e1af.nq.gz
    ├── 51da69646709d8f7eb704bd441a587fdf59aa956.nq.gz
    ├── 51f5a204ed950a3ad644370d7fbb50668ae3f061.nq.gz
    ├── 5291100d201f60776964946bc77271d8459a348a.nq.gz
    ├── 5328899fd66761da5aeea5953cc749a5260c57b4.nq.gz
    ├── 538a55d3ab326c9e2f7b4a0389fdb1ecc05336c1.nq.gz
    ├── 53bfdbeb1bbfa432a9a0ffe0fc9721c36ebb67c3.nq.gz
    ├── 54c931a0c727ffb01581b8633d842faabe09e783.nq.gz
    ├── 54eb257136e7da642ab273f1154135bdd069a031.nq.gz
    ├── 54f0ee795278ce5ea5222da72abce59ba155787f.nq.gz
    ├── 5511887b97cc6cdf3923ff14bddaf69080a11879.nq.gz
    ├── 554bdd2dd968bebfb898e2f08e4167a2e5315d5a.nq.gz
    ├── 5591075e4ab92130592ab2eddc087194ef9fe1d2.nq.gz
    ├── 55a98ed8383ac3d0c3319bae0454666121956654.nq.gz
    ├── 5701e0ceaa3c4bea9b6f35b003753ed9f561ade0.nq.gz
    ├── 57a0d9e357a3a3c0a29e57341848fb69584f3165.nq.gz
    ├── 58d2c6a9a6aa97fade4aeccac55229c823218e21.nq.gz
    ├── 59c4131ab760531db8c122a6b148c23f05324505.nq.gz
    ├── 5a7fd3e3a8d48829c1d76e46c25cbc11889f3bd6.nq.gz
    ├── 5a820f1a0f1e1a725ef449a5b6732a9256aabe85.nq.gz
    ├── 5ac7ac99363d0818e285a886fde3a523450d2cc8.nq.gz
    ├── 5cadbde4acb32102cec7f717fc8dbc6225c53897.nq.gz
    ├── 5d1d2fd685294ac68f69266f65cfd16635df4572.nq.gz
    ├── 5dbf2711fb6cb1a84057363c1daaafc27aefa90a.nq.gz
    ├── 5e0bc91b59439e8fbc45b5d8af57c78e82d694c3.nq.gz
    ├── 5ee1f52f616b724c094db8dbc5c26021cad3ca05.nq.gz
    ├── 5f218fbf0d495d7d346f56af29bc2d812d6a5966.nq.gz
    ├── 5fa3aff2d57313c4c8ecf557f7243e90acb80e31.nq.gz
    ├── 6087fd1db620e7273902aabca0df5856a6c63641.nq.gz
    ├── 60ffde187b76784f0e30c452f1399f805367fed1.nq.gz
    ├── 61b29af045b80a142d3ef7353a8ec556e5c4232e.nq.gz
    ├── 61bef9d42d782ee6a4ccfef512a0ce0527be7808.nq.gz
    ├── 62267fb68f6d8cb337f9475733499083051572e8.nq.gz
    ├── 62b2b503713698ee0bf7d66a2b6021cbdbdfcd96.nq.gz
    ├── 62f3816c5ff94be1ddf98027cee0feefc644bddc.nq.gz
    ├── 63371e9df3ab6d20dbc0fbe04d8e0bce08677b26.nq.gz
    ├── 640e6ac341159c279e01daba59a97312c265d55b.nq.gz
    ├── 64282ff003d4847af40502459d56470e7d2d42e0.nq.gz
    ├── 6431733f3e0de63bba795044b74ac69f66ee2e53.nq.gz
    ├── 64a038c3b20d2847df23bd12f0c131a4d63ea8b8.nq.gz
    ├── 6511ac248c0989733680ca078e8f2065771a8d81.nq.gz
    └── 6627d660da37f91942df4fc6ec990fb0d4d8a5b8.nq.gz

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

[PrefectHQ/fastmcp-ts](https://github.com/PrefectHQ/fastmcp-ts)

---
*Parsed on 2026-11-08 by [repolex](https://repolex.ai)*
