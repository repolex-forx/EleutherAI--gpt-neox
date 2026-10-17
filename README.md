# Repolex Knowledge Graph of EleutherAI/gpt-neox

RDF knowledge graph data for [EleutherAI/gpt-neox](https://github.com/EleutherAI/gpt-neox), parsed by [repolex](https://repolex.ai).

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
rlex download EleutherAI/gpt-neox
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 28c81ed9f75e45cc58cabd631385de7d29c95115
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 28c81ed9f75e45cc58cabd631385de7d29c95115
│           └── chunk-001.nq.gz
└── blob
    ├── 0058f1c0e64aa75769c6508f8ce514fcd0113293.nq.gz
    ├── 00a174433736a7fec39ba185efb7fff947c1c007.nq.gz
    ├── 0176d0a78db26cfd2c4bb8ba66489e055f171f62.nq.gz
    ├── 01d22aa597ea6fd40ea1add6e20cc7e637abb1dd.nq.gz
    ├── 04422a2139eacce12a9ab36a44d80fc6a2f05fda.nq.gz
    ├── 04427e9fd90b8e7095e9938100115059b5ddb0d5.nq.gz
    ├── 04bae2701850c8a23c02eca73e84aafea0d55d07.nq.gz
    ├── 079a5c31dc47af154e0cae9a9f2e8811202863ba.nq.gz
    ├── 087b7d763aad98636945bc89f30b98fd47168379.nq.gz
    ├── 099af6a48fc3ee7344b723ddbabc6c4eff0ece7b.nq.gz
    ├── 09dfa1fb9366ef35c491ee4608f172c4a701b0d3.nq.gz
    ├── 0a4ce63354a9ab66b17c92e33cafd123b0d9f229.nq.gz
    ├── 0d7c40b24284423bee65aa823ffafc6555477389.nq.gz
    ├── 0f6191662de013f9df88f0b02a4fc6f2966475a1.nq.gz
    ├── 11311f441042f4efed10abbda0c6b48c6ab1588b.nq.gz
    ├── 11900feebf14940c15175b975c0e1e6e0fb2574c.nq.gz
    ├── 126525966a97759759cb556dd19e7cf92f0928eb.nq.gz
    ├── 128d279ccf691b53086d67c393454e0d9fff3c65.nq.gz
    ├── 12ff7b3883899a36e19d938bab207929fda3d8a1.nq.gz
    ├── 14526d8da07924ff7f9c7f03adfbe4786e1fcd62.nq.gz
    ├── 14c7ad1126fa9021352f99543c8f68487c866841.nq.gz
    ├── 16b8c073b851d9becd3faeac012e8e92edd165b7.nq.gz
    ├── 16bc5ee7d0fdcc6500c1e01b60c07911c5c23cf5.nq.gz
    ├── 191683fa5e064636e9c3c2011843ec5b7fb3380b.nq.gz
    ├── 19469091743b98c3ecc509717ffe0f2d0eca1049.nq.gz
    ├── 19e848e31e0a014ea90e4017d29cd7fd9ec61141.nq.gz
    ├── 1a693c7f4f4f428c80da6f9c9d62667bb79417d1.nq.gz
    ├── 1b97f51b4a44eea66fa1e93e5e659c28c1fe241a.nq.gz
    ├── 1d76ee9ff1f25afd541d210971011a6d10baef81.nq.gz
    ├── 1d8c5ba3badbd7c5089288e2bf676e1ccc2cf95c.nq.gz
    ├── 1df18b0518347176f207ddd5dff98f592feee20c.nq.gz
    ├── 20e8ad0dd63ad31c9b682f497d1d0fffde72b56b.nq.gz
    ├── 21567bd80ab8c39c13c64711ff73b9c2941b6fae.nq.gz
    ├── 21906f0e2c889c511b5325fbc53f94afd633f0f2.nq.gz
    ├── 21b67521ded6eece8edf0ae4731511f7d411d6c5.nq.gz
    ├── 234445c7728fe544ceeb6a845e6b23e38c51bbf3.nq.gz
    ├── 248d01c81ca0c11403f2094e22c35785fc77294f.nq.gz
    ├── 24f58dc6215e5eeda35188676082c43a940efc26.nq.gz
    ├── 2864c799bd1d634b2a0a475b88a67a7156c94869.nq.gz
    ├── 287f3b388b9abab47eea7057bf533f0a27e03399.nq.gz
    ├── 28f45c7cd014c0957d85a5bc512ad58f90c8f60a.nq.gz
    ├── 2a5b02d6063d5be36f17a1e56c7d257ebd0b3dc7.nq.gz
    ├── 2ac60e53417ddc23f9e369e063c720b37883a66a.nq.gz
    ├── 2ad9989579d775df6e05f9422a7da15ebe07b42b.nq.gz
    ├── 2b228e90f22ffc31e40d16254dfca5acba27106f.nq.gz
    ├── 2cab2e70dfda42bac5b94e3b4b04bb62ae439125.nq.gz
    ├── 2ed231d450d2744f982f89ccb59b0d902f007941.nq.gz
    ├── 31ba0b4bb414ab6e8fa5a62009bd6416d713c619.nq.gz
    ├── 32618d7574fb39fe0d7e8e9c00f483325c8b43c3.nq.gz
    ├── 32f8db816c3d01c134cf9d4011be0f416759f4d1.nq.gz
    ├── 349e3b39a92d3d39bbe4f3ae6ecab01f93f06e73.nq.gz
    ├── 3524307bad2b57ab5c2f60ff729b453608e322f4.nq.gz
    ├── 363cf4315b4da64382fa211b98206a444d056847.nq.gz
    ├── 36441f181c139278f399d087d309322607f776ee.nq.gz
    ├── 36ecc6568e6afe93f84420467639dc5083378b5a.nq.gz
    ├── 37dbb21e3c38b74de27fd1cc57ac1996b6304517.nq.gz
    ├── 38485d6a644ba23ea3dae492141441d8adb67999.nq.gz
    ├── 385b474871325976442c718dcaa1f8fc2bd4c00a.nq.gz
    ├── 38790238fcd2123afcbf8c4dd41416f53b85b6ad.nq.gz
    ├── 387ac5ad63b908909887caad545ce3f48560be43.nq.gz
    ├── 3aa3f374268df07e3b110cff4429a5b50ce2087a.nq.gz
    ├── 3b382f83f2aef216abb32c9e4048830c998b43e2.nq.gz
    ├── 3ca2186be9bec47745a57ef573fe3f802af1a1c1.nq.gz
    ├── 3cb082e801db942fea244b77a74aabed58a19815.nq.gz
    ├── 3cf5bb0076ce6cad1fb09e183a5a584978372942.nq.gz
    ├── 3d7aadf68118c08dc79ee835356d748accd8ca12.nq.gz
    ├── 3e2f1a5aceb9504632f46ad6bbb3c3ab81597b8f.nq.gz
    ├── 3ecd974890c3719787929e78514cec495fa4eccf.nq.gz
    ├── 3fa3429641adb30c5effb3982a8ba12561966ea7.nq.gz
    ├── 3fd251147d9bc6bf7b137c81e36007e9a8155118.nq.gz
    ├── 418ed08a13b83a9831fa3a37724e4470419c53a7.nq.gz
    ├── 43117bf95e0f618f3bdd6b279c0f4c0bed0ae719.nq.gz
    ├── 43ce025c0d89923e2ee7181afe5da60e80033aa2.nq.gz
    ├── 442d61cf3a480e6b9b3aad5a90743b5da107df01.nq.gz
    ├── 44a6e5adcae7a8346b39105807df767a5755fbce.nq.gz
    ├── 45933260943b3051dd0621efcd6246df51f17d90.nq.gz
    ├── 466492f7be4f8661141b7eefa7f6d1ba83896eca.nq.gz
    ├── 467318f2419b2b38d61b32195bbdd90530e80871.nq.gz
    ├── 46f76d8b580467384001fdce023ec862efcfabc4.nq.gz
    ├── 47e50185274f19fd0cad360e2a37c049028d0c6d.nq.gz
    ├── 48f5ae0d87997bc81c1fdaa7b400f73edc423632.nq.gz
    ├── 4ac5113f7779595555d9e2a09002253325b21435.nq.gz
    ├── 4ae2a6c0c1eeb642bbc2b661f4c5a19c2ade4793.nq.gz
    ├── 4aef7e81315d33e3346fb3e2b3ae8c337b40d5de.nq.gz
    ├── 4b9ce5c56151247a51453a9a0af70cd2ac676a8f.nq.gz
    ├── 4c39a36f6f198d83684b08304f288554429f4a8b.nq.gz
    ├── 4c40c1896c79471710dff78c8c85e51659470211.nq.gz
    ├── 4d011f1b47c3027b601eec17ff3badef39263a62.nq.gz
    ├── 4d197a5e08881ee582b34f6d4691638f053cda22.nq.gz
    ├── 4fb9559a86b4e7313a7701d279dcafe20c7b2f94.nq.gz
    ├── 514ccba26daeba0bcc561df912c680eaf041a5d9.nq.gz
    ├── 523b10c3935b97ecd77529c5b82560ce1e07ac4e.nq.gz
    ├── 52c99449b50f87c09c6a66b3b491afdde8116752.nq.gz
    ├── 5586c7d4cc3023fc828c6464b1db4ce03c92b5ce.nq.gz
    ├── 55b00f6ba4b11ee7b534ec6ae6f53ab06b09cd4f.nq.gz
    ├── 57cec99e3a0ed09af925bad38df523ef011d76e0.nq.gz
    ├── 57e20c5244c551fe5c1eb309d64d0600004dfd44.nq.gz
    ├── 5a17e3809b735ac685d9cabee5fdc90b451b4f81.nq.gz
    ├── 5a49d61e56f3f98c0c7b38cb65ded05e6c1be527.nq.gz
    ├── 5b03357dc7399e762012c6d9dc63d452d79f1878.nq.gz
    ├── 5e0ada3343a4cbad04b6d1b9788b869e270fdf0f.nq.gz
    ├── 5e2edaaddb75fe3e0aa60b33338f683b01f7080a.nq.gz
    ├── 622b6404275014cabb991fd534501aeee867453d.nq.gz
    ├── 643d547c77f6c4a12dc2a511106eb7a5c30e9190.nq.gz
    ├── 653aa21d8244878f67965aa55be0d9ce198e78eb.nq.gz
    ├── 65708e29cf3e667c4b3c865b662a9d5049962053.nq.gz
    ├── 6598238cd97d23ba469adb244eabb89a950436d9.nq.gz
    ├── 66f5db6ee6068f145a4950ebc5139b90b162a2ef.nq.gz
    ├── 6734fbe2137122840e1cce5c523ee5154b4234a4.nq.gz
    ├── 6845e757fbeb8c46931ef3760466d888465f8caf.nq.gz
    ├── 6910b8a1c0d7fe536e02112eed139c0c35beacb7.nq.gz
    ├── 6935e480a805f6b12a372ffa9af58bdbd10fecaa.nq.gz
    ├── 6b0d07e94ada9b64a0a054fa003f1e3c90a2bd07.nq.gz
    ├── 6b1c8927d4c540dac35345b95dca5cb9e90677f2.nq.gz
    ├── 6b9723cc481070294091ae9cc65281ea6dde26c5.nq.gz
    ├── 6d5967364055a0604235fd5d0195083f4b45664f.nq.gz
    ├── 6d62dc0f37ec65b9778f4fe8b3c651c83b23723a.nq.gz
    ├── 6dd16ac313fb23409c086fd712581528ddfc602b.nq.gz
    ├── 6ed2e410955ab2c3b7a9a4dd7a7ee349f0a5af34.nq.gz
    ├── 6f2dbe486d50720ce3d40bce5a4a606d563be124.nq.gz
    ├── 70c72ec2a23bc1889be29f5e8aba957727fc1a00.nq.gz
    ├── 71eff5a8d98b9810d86f81938e88be8691b80b07.nq.gz
    ├── 72314c7dda9c2925ad6e862b435eac6ae70b3e25.nq.gz
    ├── 7251c88b7583c1c4896cc3de3293d278371af743.nq.gz
    ├── 745e07bdeff459226f4fdaff7cfd0a38cdc1e023.nq.gz
    ├── 7563d7dcf76d8f2cb150372c9921b9e57a66adc7.nq.gz
    ├── 76a4568c708d720fd935edfa44e749039e314a48.nq.gz
    ├── 76bb825e4e89a2017e8d3237527df5dd779c26ab.nq.gz
    ├── 76fb2656e82f2acda31268fd80c9fd5cd9fc0d71.nq.gz
    ├── 770cfb9c637721ab4384ce12de5c2859133d53ed.nq.gz
    ├── 787104d4c0fc21a220d5aaa6e89630c8f194aa5d.nq.gz
    ├── 78fc28946d1de0b362a05fd5a7b1f584eb81e975.nq.gz
    ├── 798e8cdbdfc7589b52806a5a1f378559cff7d0da.nq.gz
    ├── 79bbfa9003d1c021cbc9c76fedbef0e0b5600d87.nq.gz
    ├── 7b06256bf47bdabe86ea359a169f38cdcc4bd0ff.nq.gz
    ├── 7c313e0d9c6b0ff0b62956b264ee6d97ae2781f1.nq.gz
    ├── 7d355e357a0996012eeb9adb67244c6e8f3a96c0.nq.gz
    ├── 7df5ad3ea3e1ed633b8f63b015715152bb7e0196.nq.gz
    ├── 8207d0cfcca843823b57bb374dd399b6de238ad1.nq.gz
    ├── 8308adf2fd7d5dc55b4c6a029a3d4aaa7af5f23e.nq.gz
    ├── 861723f95366966c8677f601440277a09dafa239.nq.gz
    ├── 869129f30ba39803c549aca4af2d23c355dd6ec7.nq.gz
    ├── 87cb8ef3188ea00b3040cf41146d928b8b5e7360.nq.gz
    ├── 87d62f4c3787b11f464a62d64e41d7f4af00db10.nq.gz
    ├── 87e86e7fbba9a5bc460e564e8b0343ea8a4e3183.nq.gz
    ├── 882bf7e63d57ab99b60b3ae4ac8f5c1a4a0e9219.nq.gz
    ├── 88ca5a21f23c7602619eab411c23a000bd382f0d.nq.gz
    ├── 88e8f513cc3f5f8c14e9589c632f1d67b51ad738.nq.gz
    ├── 8955409bba781d3806e2be1602a0bc1dacf552bd.nq.gz
    ├── 89d810d10f1e01803812670a8909cd6e15c9fac0.nq.gz
    ├── 89e31be457965404c3f65200df166e22cbcf25d0.nq.gz
    ├── 8a75caef066bfb7381e10179164afce636a57cc5.nq.gz
    ├── 8b29243467bf9bb01b1ea43158770bd4b11960c4.nq.gz
    ├── 8d3c4e59453e928c1d678bc82fa680af3da259ed.nq.gz
    ├── 8d8e04462ee4242ad471f8ba65b4b8a7f15b1731.nq.gz
    ├── 8dfd5595ca48759f8087e5b90fcc012f89a1be50.nq.gz
    ├── 8dff734a90a03890e2bf77a80963df065dc334e9.nq.gz
    ├── 8e15a454c16852d64977d932223a4658f655ce8b.nq.gz
    ├── 8f9db7686696fbea6c94b998db4b40ef426c748d.nq.gz
    ├── 8ffffe24153b7d3cede87ee219d6bd4f52787ea6.nq.gz
    ├── 904301eaaf4eeed4ef796d6a6eb433dc99c6a1f4.nq.gz
    ├── 917dd8543bbdb8a23d273c48f21dc737b7d66a7a.nq.gz
    ├── 9187542ca1b93fafe5cc4c98498714d2fd061678.nq.gz
    ├── 9187684a86b4f692c833d8c5efc84b9d93a55b87.nq.gz
    ├── 91d6fc1dd73e70ba576e10c232578359e5ab4294.nq.gz
    ├── 92da0b7001fbe1a3682504f488a08e391432ae41.nq.gz
    ├── 930cad9ae43693256c4bfdaf78629f9318bc5774.nq.gz
    ├── 940cef428438224f39c845ada37bf6ea38720e69.nq.gz
    ├── 949aefc80bd4752dc9ea23669bc1a61ea3c16736.nq.gz
    ├── 950e36fedfdb4141eb79a723f4cd2547333eacf7.nq.gz
    ├── 95a307240e4a18f95ce9384490b780eecade5b44.nq.gz
    ├── 979c749bb99368c211f88174debe5ce055de6c77.nq.gz
    ├── 981f54a306a92245c8e49b2a0596676208d42eca.nq.gz
    ├── 987c45b84c9d3e34fe1a01600fdadc6c3247d955.nq.gz
    ├── 987db3434ae22bc5986608ec00f81d8ead5c14f0.nq.gz
    ├── 99caab58590b4229aefe5998fe3e4c36a47e9aba.nq.gz
    ├── 9de71da3c070026af44aafb61557219979621d29.nq.gz
    ├── 9e6a47e1544f157580ed5be50d16f4db5c925ea1.nq.gz
    ├── a004e807578d35f1cae8df3ef0d3ab48b26cdee8.nq.gz
    ├── a024707ad51b5b7c75128ae4ea9651aac8989b7d.nq.gz
    ├── a0627715c223da04b5427a17989765bf79ce3d88.nq.gz
    ├── a0cb99aefff2dadf0af1e37ebd25f8413e08fa45.nq.gz
    ├── a15473a2825158deeab6b21b8aedc0bc931f20dc.nq.gz
    ├── a184f066f4a6b57ea74d92d1d1c2071e4feac5b7.nq.gz
    ├── a3633eeb83b16f659ce47ec1d32081a94884353f.nq.gz
    ├── a4777d168e9e447c7588bd8795f7e1b606e5f325.nq.gz
    ├── a70ec1b2c66acc894b51003551fc9412c442e267.nq.gz
    ├── a7470cae826db47cfa9415a5e29a24627994d93d.nq.gz
    ├── aa9a1cc6e899504b0e5602ab4ff0489470d95574.nq.gz
    ├── abd0cdfa92b4e286639fa168113942139f5f5fc8.nq.gz
    ├── abe601faadcca3e7c354fe8b7df01c867895f01c.nq.gz
    ├── ac20ed89ba459e4a4a5a10aefcde979386644a06.nq.gz
    ├── ac9b7affa108386804f31af6da46be3defd0e751.nq.gz
    ├── aeaf33aa6692b3ab002dcaacc0f82b687745c404.nq.gz
    ├── af3009a23907bbee358dcd9e62ffe26fda0dc6f0.nq.gz
    ├── b19403f2ab4351d9515e192cf12466d2db91e013.nq.gz
    ├── b2591aed0dc05607c83d3a76953a0e95a15213bb.nq.gz
    └── b2cb01a5538b3820c9c46db87e6bb484a4d4379f.nq.gz

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

[EleutherAI/gpt-neox](https://github.com/EleutherAI/gpt-neox)

---
*Parsed on 2026-10-17 by [repolex](https://repolex.ai)*
