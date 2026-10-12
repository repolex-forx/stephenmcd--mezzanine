# Repolex Knowledge Graph of stephenmcd/mezzanine

RDF knowledge graph data for [stephenmcd/mezzanine](https://github.com/stephenmcd/mezzanine), parsed by [repolex](https://repolex.ai).

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
rlex download stephenmcd/mezzanine
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 85dfd412445ebdd851078b4af4a8ed21b3c55e02
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 85dfd412445ebdd851078b4af4a8ed21b3c55e02
│           └── chunk-001.nq.gz
└── blob
    ├── 0097492c60d77a13cee8fcc22043c812325c73d5.nq.gz
    ├── 013f6d20a0b082dd8ce19afd23ce517c3d00c63e.nq.gz
    ├── 01c6c03411cd3c16e5029314365824fd13ee64b0.nq.gz
    ├── 02bef7c23c787d931ad24df96c2e2ee054a3cdeb.nq.gz
    ├── 0370d976c114c3ccd5f1b37594e908a6c1a728c7.nq.gz
    ├── 041cfd12cef2480c01d5e882aaf638a88da0a296.nq.gz
    ├── 0468c9a50df0fb2883e9dc15ec935a3baaaee374.nq.gz
    ├── 04b3bc6c02f0c8d4c9e4926f7fb05b1e24c8c847.nq.gz
    ├── 064dc386fac9d5f3389bc653f3211b6de5fccfed.nq.gz
    ├── 0668351edc88ebd14f0a755ec974945521e56483.nq.gz
    ├── 06bcc5c9cb1e68625dcee7e4b3e67a1bd25afab9.nq.gz
    ├── 06fb629af4a4d7f684b9b4c3e0c041c1537ef678.nq.gz
    ├── 0821707ef2da76d8d82f224c0835e92cfd54d61c.nq.gz
    ├── 0870ed5df19039e6b878675347fdb73b80369bc7.nq.gz
    ├── 0950d0f510ea6665c6331a31219a2c52e694865f.nq.gz
    ├── 098de060ba339f490eac5ae8eddb3c2b5801a0c2.nq.gz
    ├── 09e211f8a94027588ecd4dd641779923633f24ad.nq.gz
    ├── 0a862c2eb8dbac3b4ea5ef263231e6d8b68dec49.nq.gz
    ├── 0acdebc54fe0f7610da0afe257375c13e84a1917.nq.gz
    ├── 0ae4cc0567d23d1030f16c5fdb61e85ee5ae27d5.nq.gz
    ├── 0b2808c1f783015f5e8ea1715744bfe6b335ccc4.nq.gz
    ├── 0b35e043b73a53cde08f6b15cad10ca887fd0cbe.nq.gz
    ├── 0b7a15e9285699d1e2302327ff072b80a8358c6f.nq.gz
    ├── 0baa09a1eeb474fcb3179dfd09d5d52089101b24.nq.gz
    ├── 0c998c2812ef21a3d5d9eadbe8084639640c536f.nq.gz
    ├── 0cc9bb71cca4cdeafbb248ce7e07c3708c1cbd64.nq.gz
    ├── 0d69159df61fcd0f8e8ddda7c14378c9138fd02c.nq.gz
    ├── 0d8040f633688750fe2d350563be3a68aa4fbb11.nq.gz
    ├── 0d9aa1470bc8dd56d574928dc91b91ad0bd0ff79.nq.gz
    ├── 0da1abd551f8eb69dc298d265f2273267481bc52.nq.gz
    ├── 0e33bb543c95fca044041b48b3c182f7f7448c42.nq.gz
    ├── 0e8fd29bd090445f1e8e9aa350700390244a6bf7.nq.gz
    ├── 0ef3ca3fc170e8d1d5aabbf916ea50fae443f941.nq.gz
    ├── 0f132cf872f86f9b51eac711ef1a593acef0159d.nq.gz
    ├── 1055138ae7911fd040d7e917a5b710fda2a89553.nq.gz
    ├── 10b665ce91793dec43dbd401f9637c08de19e3d4.nq.gz
    ├── 118e81f7ba375eaab48cabc500a85138909872a5.nq.gz
    ├── 1215390344f5485b0850f33eae4cf4398443c994.nq.gz
    ├── 12ca4e6df26905ba9ed77e269ace9c080cca2b05.nq.gz
    ├── 13101cf4f829f87ed0f848f4ee6d93bc0dbc221a.nq.gz
    ├── 1390224d34946506286327cabf738bb112e8bfae.nq.gz
    ├── 140f67558f8568a222ccc4de885768392b6562f2.nq.gz
    ├── 14be06e9f39fe996651f0e12274f3eba9ca0f0dc.nq.gz
    ├── 14d1e99cbd158c32f62d0f2349859d0f72a5935b.nq.gz
    ├── 150ee89dd6048be5f5fec7d4fb773c39e1b8ec4b.nq.gz
    ├── 1566688fada0936ce7570f88811f2347d48d4e97.nq.gz
    ├── 1567985273458c6258a3682c0f07f18f463c6053.nq.gz
    ├── 158cc12d3be72a32db9de821dc0c7d0d2f536626.nq.gz
    ├── 1678d59a914f246f67995d1aa86fa9f718b30d20.nq.gz
    ├── 16bf4406971813faec8c031d59b99a266b8dab50.nq.gz
    ├── 1741c4d920c721dc90367db7ab5ff703dea4e4e6.nq.gz
    ├── 1765114f3a6255eb9066aded8d2e0a2dd891b047.nq.gz
    ├── 17a906ee674021ad59f810826ab7cd1c3ee5210c.nq.gz
    ├── 1837b0acbe16906b8643f1ded1a32f5b05d64e36.nq.gz
    ├── 1886667c51c19f8beb2e968d7b91f790b5fd09d4.nq.gz
    ├── 194b01a23cc934d520dbf36e17a68c1c24804710.nq.gz
    ├── 198ca788bd2cc8438369dcbe7519cad0247ffb36.nq.gz
    ├── 19ae2446c201f8cae2b93f4c60e82a9fdfffee56.nq.gz
    ├── 19e3fb3c19978e90c6755fe87b3165181b54ca36.nq.gz
    ├── 1a1d5964ba30244e14f9345a5a6f1fec7c7e6614.nq.gz
    ├── 1a9d39834ecfce14544abbffcbd130d7fc5eb5f3.nq.gz
    ├── 1b02081f937468d7d51fd355eff97a2f861c01bc.nq.gz
    ├── 1ba38ad9f4de9562a818843dcc278a3fd4a9e8cf.nq.gz
    ├── 1bd58441af8c3252b3fbf94c16ddde4b50a465bd.nq.gz
    ├── 1bebe4dabc279684c385223f59b75b203db9ff29.nq.gz
    ├── 1cd13d92263b9e5aed54437de65193ad12f9d840.nq.gz
    ├── 1d16a87b105b0f61230dc503ebdd753f3baea165.nq.gz
    ├── 1d620bbfad6a64e0e2004811bb557ae261566fc7.nq.gz
    ├── 1e198920b22224e84e30ab5f08c7a6e9934add79.nq.gz
    ├── 1e23e7334729e176c5cf4f9a66325ecaae5e6903.nq.gz
    ├── 1e30a6bd66be5c0f29887ea963fa0e915106dd9e.nq.gz
    ├── 1ee6f8077de87ecb85d05e6d17a08c04bdf66843.nq.gz
    ├── 1f01377fb26344529b966d7f181fd575322b7e40.nq.gz
    ├── 1faa12d3c4d1e987777e1bfd87c940734351923c.nq.gz
    ├── 2075dc16058f1f17912167675ce5cfb9986fc71d.nq.gz
    ├── 20bddf265abc111c860991e071f803e3444f0f79.nq.gz
    ├── 213fb3bb83d1a1f948ddca48c2ea2381bb136658.nq.gz
    ├── 21bde97397c09a52be6e7e645326dcadd088e5cd.nq.gz
    ├── 21f3505617d9e7b0f9ef4a4935bbfec39b67b08b.nq.gz
    ├── 21fde817c59c5e2451865129b07e43a6609a76c3.nq.gz
    ├── 21fe9c6881b9a6273a03b395506ad084dfee559f.nq.gz
    ├── 246aaf9a055bd33974bdfec4376f076562cba01e.nq.gz
    ├── 249c1d7924c9204c4eb3583658c6de79dfccc96f.nq.gz
    ├── 24bac44c29f756e3b205db0cd52cc2554530149b.nq.gz
    ├── 25075f5e5fab1c2c73981d7fdb78723715bdc0fc.nq.gz
    ├── 25260aa2e5f90e7a8484118eccb2f5da258bf32e.nq.gz
    ├── 25b0bce5a67a76b0a442bceda644d6d85a8c6932.nq.gz
    ├── 262bb494e99ad0acf74b5c00c939b56379d423cb.nq.gz
    ├── 26eb7ba4ec4b5566eb74db4eabc07ec90ed6a627.nq.gz
    ├── 277ea4fe3e71219201de49444311bba2602a497b.nq.gz
    ├── 278f1ddd07233dfbb9f7f58fd67c00c242ee90ac.nq.gz
    ├── 27923b54e371a36320dfdf123e5255d5c6da1a30.nq.gz
    ├── 2859e459fdc406aeeb55b55f842ddd3788655c4d.nq.gz
    ├── 29fec79486cad0354e9a50f363849e4a4da6eed3.nq.gz
    ├── 2a267cb371f31b1a831b78c91942dadef202d126.nq.gz
    ├── 2ae8c9188f6bdb6009d00ddeecabc77d11bb0e61.nq.gz
    ├── 2b65e00a9264483b6c371799a4240a19e6c3b202.nq.gz
    ├── 2b763dadcb9262aa78430f4efcf8940906275786.nq.gz
    ├── 2b87affbbd9937c3dfa7c27f2d97331d6f8eec2e.nq.gz
    ├── 2bcccb5eb50b0a773b898fc16bacd39eb6620d51.nq.gz
    ├── 2e976f9f41df0a09678a6d42808804b08e9bf4ad.nq.gz
    ├── 2efcbd84eb23f2843765763a7b30ff5075329230.nq.gz
    ├── 2f114e6853490a397b1927ba0a3289813c60df42.nq.gz
    ├── 2f5b8d1a617a94f6347b12a0219b42227cf069cf.nq.gz
    ├── 3005d31df7189f50fcfca6b2ed27a1979ca130b4.nq.gz
    ├── 30eb7e24e1c6bfd825f0607cd2b0f9c89642e2d1.nq.gz
    ├── 31554f69222a02bf692dcfb6390aebae75f83241.nq.gz
    ├── 31b6d664aa8448f3a78914543cfed96a7fe00db5.nq.gz
    ├── 32eac49c9584cdf4c962c0a6b6d40e57d03a3f9a.nq.gz
    ├── 340bc07ea66fc7e750a6d96501d43f941c50f095.nq.gz
    ├── 34393c37817edeb9eaf5c6d600287eb0325c9a25.nq.gz
    ├── 34ba4736b1881173a0a6735436c89475f6f7deae.nq.gz
    ├── 355afd106083beb70f1636e33a745d109cd4a5f6.nq.gz
    ├── 3572ff4a7af3dabc26c30e6abe84f57c58e8616a.nq.gz
    ├── 36517ea1a3f2e9004d7853e0341855fd62cb5c5b.nq.gz
    ├── 36b11ea36c04d43b73c8b5f0b495a466a7971d17.nq.gz
    ├── 36ce73ae34750f460f8687bd9170236d0b93f68b.nq.gz
    ├── 3839c0db8fce5cae580cd165f6fa79f3a2e893b3.nq.gz
    ├── 385c0ab64f62ccdccbbdb850b17946deb905ad94.nq.gz
    ├── 39003c189de1650897fd3e6a2e0ee588a36267e5.nq.gz
    ├── 393de3bc625510a672ccd864f90ae6143f27fbbd.nq.gz
    ├── 3962a9427d3e44241553a9a6753ad795153233c1.nq.gz
    ├── 39b5be7d1636f727b08eb0123c1f510e317ba231.nq.gz
    ├── 3a910cbd539dc10b428aedfdb574420caf13fe8f.nq.gz
    ├── 3ab6d49a7852dfcccab248f8b315dae165a37316.nq.gz
    ├── 3b16648220fbc3fc83ac066e6e563027ca292627.nq.gz
    ├── 3b88e90bb4d938e897e619710f1d71310c0d6da0.nq.gz
    ├── 3bdb0d73d282151493b818b76e92ea3102dc1d24.nq.gz
    ├── 3cbaea5821129bb1225ae63184e0cfeb6ec1d3c0.nq.gz
    ├── 3ce1a7e7ede874522efaaf980c9ec19181664774.nq.gz
    ├── 3fe4851399a37337891ccf5452ee5d59bbedeec7.nq.gz
    ├── 3fe9adf92e09b0a0beac686d6fb78ee2f2e6d271.nq.gz
    ├── 4012ee0f19b82111c00d928127bb64c8c6a196c7.nq.gz
    ├── 4017a629ee212c3648c223ffabef6b5bc654166d.nq.gz
    ├── 406faaeaf4d1d16ded6f9808aac8244d65df0364.nq.gz
    ├── 40d2c87cfeaefa4518ca848f6da360bff94de0ae.nq.gz
    ├── 413ac98df3dc7a1c4caf0574e39334ffce8ffecf.nq.gz
    ├── 41b9da8c2020574fb882e190b316218d9d0a79a8.nq.gz
    ├── 423bd5d3a20b804f596e04e5cd02fb4f16cfcbc1.nq.gz
    ├── 42a24878b859c04f04938bb19b7163155581bf15.nq.gz
    ├── 42ee10f1a762c8b3da9dad80762af6df7cb47076.nq.gz
    ├── 43ae94555d67025bde7510b50f2c547ef64a32cb.nq.gz
    ├── 442fa9050cb3d90e30b3749c1d35856b5842b1fb.nq.gz
    ├── 449b0c01b3537c045d5982b14e7e2471765f8251.nq.gz
    ├── 44a5035a317f1adcbf1af82a3ceae1890dffa2b3.nq.gz
    ├── 45149b73a83a7a8901b574a353ade8c120ce2623.nq.gz
    ├── 45648d79610f1cdf6bbf5bcfb346e437f4da3ae1.nq.gz
    ├── 4627a7c21569145d44fbbb2c0daec4445cd346ca.nq.gz
    ├── 46e9a56936e8fe56532d42de41d9d02c95dcea4d.nq.gz
    ├── 4708a3ce22431b0eace2ee5d9e68808025e3d606.nq.gz
    ├── 473f9849bfd41bf5c13a2fdf4773e7d1dbcee4be.nq.gz
    ├── 477f4b503e5b0ba0f85b2b3bc1885b5565a3cb15.nq.gz
    ├── 47daae7c71679678937ff1b5323b54c27ef20384.nq.gz
    ├── 48236df19aefe1cc590f7216614420eba32c5a70.nq.gz
    ├── 491d01240c1fc06837f7dff0b9c75bc687fc4397.nq.gz
    ├── 4981a440b0a7a7a6fd634bf5857b021200c63332.nq.gz
    ├── 49a9bf1b40ae1993f8a8427fe9a8c3c7951d65e3.nq.gz
    ├── 49ba83b9ab4396150c2a2de4bd67c18027f705ad.nq.gz
    ├── 4a2f2db8cef62b9edc311a0c8774bbb496c62e60.nq.gz
    ├── 4ab0b781bc4a9b9b79b8a170d7c06d63d84ffec2.nq.gz
    ├── 4b4ec378065fe33c882cbb4badab253024c3cb47.nq.gz
    ├── 4b7a717991e6c5522fa83e6e581e1a61f3440ae7.nq.gz
    ├── 4bf3893a26d8a718f9f0b8ca0b401a015bf26303.nq.gz
    ├── 4c0e31fd6cff798ac55ad6574045c8eb0f5f76bb.nq.gz
    ├── 4c49f6c866d967b787c1c4107e07f1bef9f0c974.nq.gz
    ├── 4cea74e3ea1f27a282d8720bbf24f9676c4a5122.nq.gz
    ├── 4d12e5d4b2967d5b95d09fbef2d1870848ad015b.nq.gz
    ├── 4d653c2caad731adc20c312ae1e981d8b014e3d1.nq.gz
    ├── 4d92311c5d02c20368a0efd571f98cd3e93d35bd.nq.gz
    ├── 4dd0dc259096df8104565c2ddee1ec9865d5c0ee.nq.gz
    ├── 4e0b7cb55a61622b845f91f7756c3205a3233e02.nq.gz
    ├── 4efe3d6c4b1b653ec9ce8ec370cbe52b36b3b7f3.nq.gz
    ├── 4fa28856d120ff3175d480ac5b45b9b253bda468.nq.gz
    ├── 502c24b96245954ee64767e8825cc9e675254293.nq.gz
    ├── 5036c7a4097ed2a794d5f96b98bb5b018a6eda98.nq.gz
    ├── 50583de13eb4ad3254945d4fee0db4fb3c843f6c.nq.gz
    ├── 505fc4433fbc1806ae6b310d8b33100eca17f335.nq.gz
    ├── 5273f511e68ec72a3f4321667afbf367f95922f0.nq.gz
    ├── 5356c25fdc4995375a63c61f00668dcf0676f939.nq.gz
    ├── 54999b2fea0b6efef32b4cf0670ce9e7a523fd25.nq.gz
    ├── 549c71c667998e842fcfa962af5455476723a717.nq.gz
    ├── 550d600ee8531545eb17aa6d73e63280c6329287.nq.gz
    ├── 550ed452ad6f4c02658cf24a99d57b040f5ba5f3.nq.gz
    ├── 551e26db65848779407317e75021a238992ac883.nq.gz
    ├── 5653c229e88f7b20aed6319b26d249751913af90.nq.gz
    ├── 570e597001d55ed5c74e91eb81948da303539373.nq.gz
    ├── 57382be3812da3e97b97cb280ad13403ff3f1cbe.nq.gz
    ├── 57f9a718ac0f683af0dae89d19a96996b593639e.nq.gz
    ├── 5835c03aead462d8cf1022c06de76b1c6f19f64f.nq.gz
    ├── 585d152a57f9bd89ebb63932547272912cd88ae0.nq.gz
    ├── 589881eaf2f833991e1d2a5c72cc39785835ced7.nq.gz
    ├── 58af7ad1999c5f19b9742d11faae1229e90397b9.nq.gz
    ├── 598242fee2abb402c7f8977bb4899a2fd3d70492.nq.gz
    ├── 5a46b47cb16631068aee9e0bd61269fc4e95e5cd.nq.gz
    ├── 5acd4aeecfe184238fb4cdfdeff5b4e2c7ed1763.nq.gz
    ├── 5b39a3154a8ab5fa85665f6a765a8982601a5674.nq.gz
    ├── 5b7e699c28023c7b32fe9044ee0744e4cd5cae92.nq.gz
    └── 5ba85682c761044fe475a88162d6da258756ddd9.nq.gz

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

[stephenmcd/mezzanine](https://github.com/stephenmcd/mezzanine)

---
*Parsed on 2026-10-12 by [repolex](https://repolex.ai)*
