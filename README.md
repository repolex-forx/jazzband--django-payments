# Repolex Knowledge Graph of jazzband/django-payments

RDF knowledge graph data for [jazzband/django-payments](https://github.com/jazzband/django-payments), parsed by [repolex](https://repolex.ai).

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
rlex download jazzband/django-payments
```

Consult `rlex --help` for other options, including SPARQL queries, HTTP server, and interactive visualization.

## Data structure

All data is stored as gzip-compressed [N-Quads](https://www.w3.org/TR/n-quads/) (`.nq.gz`), a standard RDF format that can be loaded into any triplestore or graph database.

```
.
├── aggregate
│   ├── ast
│   │   └── 8edfb1fc47f8011a1ec401b878971fb47d104165
│   │       └── chunk-001.nq.gz
│   └── repolex
│       └── 8edfb1fc47f8011a1ec401b878971fb47d104165
│           └── chunk-001.nq.gz
├── blob
│   ├── 0093cf7a747c22eab812f373903bfee9f6afbd59.nq.gz
│   ├── 04d7553168b120b8af8db586b4d67abd00f5919b.nq.gz
│   ├── 056c90277e2b593861d3170e4f3535dbf77e5960.nq.gz
│   ├── 0585038a56f2de4a17d25949596860823b1de1ef.nq.gz
│   ├── 06389b3eec4c3f3b166f7d8a8f85a4cf3e3c5df4.nq.gz
│   ├── 081edaf21097c744f41e4ee9b18c5a21d3a6eed5.nq.gz
│   ├── 0860cef42692956b978949aa9192adb9866688d1.nq.gz
│   ├── 0b84628b52d42c04e2a3fff66d8899a7c732e068.nq.gz
│   ├── 0b90b4dec590a7a496f9e2189e7cdc744fe8df4a.nq.gz
│   ├── 0c2e71ec8e5769f2e8484d29b19766cdfe3e53cf.nq.gz
│   ├── 0f65e6f25d130f72592a37b5eb04036e84410508.nq.gz
│   ├── 12a6e7a77abfabba14be4bdd80bf20629a36c4f6.nq.gz
│   ├── 12e38d1ec7c02f982bfdb94b16e46c4be539c8d4.nq.gz
│   ├── 18114948eb25662bd7e4de44a103b7601bc5f62e.nq.gz
│   ├── 22f2d1ad038ca646dced462ef5ba3a72e5b15ab3.nq.gz
│   ├── 2c238d4e480cc1908d675f370cf4c4f47ca99bea.nq.gz
│   ├── 30f499e483b4323aad1cb262af951b6d4c3d18d6.nq.gz
│   ├── 3159877f2a3c544ca7bd254caaab9540cf3a4a8d.nq.gz
│   ├── 31e563c8b8ee8568d509108ab0bab9594f34937d.nq.gz
│   ├── 32f540c2c4a380799b4f7a72575376849c8ab0a2.nq.gz
│   ├── 34167a3041d070735e9bd45fe9b5ce6dc228fbca.nq.gz
│   ├── 34ee7f42405a46a7930dc671194848379092bcd0.nq.gz
│   ├── 3582a5873a360ed017e5f78d8dddf8167fdca4a1.nq.gz
│   ├── 381c0cec66bb24cb19995a83925ca268056983fa.nq.gz
│   ├── 383a716f0fe2eb014d81cc8fe9440193ed5f3b5b.nq.gz
│   ├── 3b0a6a780b1ccd16aad7b740d6e260135289d4a2.nq.gz
│   ├── 404b73cb7571df7b853b5b02ee605fa819559f94.nq.gz
│   ├── 423d8f93d4eca23471e225807202ae63f777be2b.nq.gz
│   ├── 44e1f24ad8b88b2dde16261eca99922b7b6a300c.nq.gz
│   ├── 461f84ad93b4523914baa89b433a1a12af751476.nq.gz
│   ├── 47073caed45ac931f9235609b99d56e7c2fba831.nq.gz
│   ├── 4a4738578a866b19e5ef16e78e5ebc639ec0d1a2.nq.gz
│   ├── 4a6b19cead3ebc694c5d8584db812edb1c00db6d.nq.gz
│   ├── 4b4a7292cc8b9a134fa3422b32764bcd1830f1f7.nq.gz
│   ├── 517c7dea9e2af2a2ecf4251b0f96a21f9d4a2b61.nq.gz
│   ├── 558c6ed59bb3205327e1aeddcbd215cec6f33a57.nq.gz
│   ├── 565b0521d0c2cdbfe493d19765b04d5c119fa7eb.nq.gz
│   ├── 584303165f9d59742b1f9787fe881caccad802f3.nq.gz
│   ├── 5889292f4e58dad51c9b1032d7ec21a42c554d34.nq.gz
│   ├── 5c0146c4a7b54d3854aec7066f4779b8ddcd4504.nq.gz
│   ├── 5c588c7cff4921ccd4cfe1281aed2699a7a3a524.nq.gz
│   ├── 6237868bf3e8f137b4fc159931939bf3a2e4dda5.nq.gz
│   ├── 68c0b8e233f68454ac647e41a6c90da0c9c37cab.nq.gz
│   ├── 6aa81ec5ea053d17cc6e6338f68388b94133aecf.nq.gz
│   ├── 6b08ea6221502399b9e06f544e02cfafd0b2dce0.nq.gz
│   ├── 6bc452961dbd6fc228c77dd367c24a94994c4edc.nq.gz
│   ├── 6be7b5402b01dd097ea5a1766383be99ba8bfa76.nq.gz
│   ├── 6c62c51100ee34896cd5defc59ebf2586d0a8f3e.nq.gz
│   ├── 6dc2103c60db949e115712aeb7f8ec5d1b96dc00.nq.gz
│   ├── 6e8d5540331940b57a4ed950ed0af522d8370352.nq.gz
│   ├── 6ecd806e22be73c7ca3bf44266107872b9df1d88.nq.gz
│   ├── 70211a82c633f1ee50060c511392f8e44d86ebb9.nq.gz
│   ├── 7027e73e532db21ed2b6787dfa123d08a683fc5f.nq.gz
│   ├── 71c9d30636c1141e73a0d0eacb17bddce916237c.nq.gz
│   ├── 7473bccf52471bf1099a98cf3ebba57a3b334bec.nq.gz
│   ├── 77076a50cfbbf2deaacced38aece0beeb8c2a642.nq.gz
│   ├── 776274dc5815f29bdd68f19433c53ad1f29da07e.nq.gz
│   ├── 78e1d3c9e0020e8b0317267852c9f742617d0345.nq.gz
│   ├── 7993c2a7eca6a8051794651eef61d007c96bcefa.nq.gz
│   ├── 7c913f139800dd05ab25d901607852cec0086016.nq.gz
│   ├── 7d3ef282cd342b4b4f18d5bbe921609e0fa6ea67.nq.gz
│   ├── 7f2a2348a9acdf9afa700e8616565144ca53be65.nq.gz
│   ├── 7f38ef4d2145a69f8d49a0d19728c005b59c3b11.nq.gz
│   ├── 839650a40f5426865d1b64e97a8d18cefabfdee6.nq.gz
│   ├── 87c6143d60eaf7249ba150863c9431809e9dd76d.nq.gz
│   ├── 8cf77d50e1126fb77862cf913ee60ae94a13a929.nq.gz
│   ├── 8fd38a2ab156bc7e08478411a83df52d081da90a.nq.gz
│   ├── 90d74e3c915a8ea052c7fb7a34d056b4b07083db.nq.gz
│   ├── 91412668462fb05f656c48a62bf50fb9ca67f6a0.nq.gz
│   ├── 91918b3d10cb0b6b5eb2d23011bc76a8aaa7bb6c.nq.gz
│   ├── 96c48bc92d241bc3254a19bee0d5009b06b706c8.nq.gz
│   ├── 96eaa158c6e9934f6761966197078637f6b0d1cc.nq.gz
│   ├── 973edff4265b22389b41839bfe438e9b6545eef8.nq.gz
│   ├── 97a77896684a93260b221922100a74ba46b30a3f.nq.gz
│   ├── 9a7af74d04a63be0b971a720e5618563f33fd3c1.nq.gz
│   ├── 9c54e8402f64f9bad4529200d2fb4388183ff3f8.nq.gz
│   ├── 9cb51e8ac84f0b29e06b640fc5b402cecede56af.nq.gz
│   ├── 9dfac223238134da226ba517dfb450de7088c341.nq.gz
│   ├── a0673d9b7b8c7644fd743dd595f178078eded0d5.nq.gz
│   ├── a31e63bd90d04e2cf09fa93098d63f9da7dcd0c7.nq.gz
│   ├── a5b26c0ce04a294ab8cc0389375351a0d9364225.nq.gz
│   ├── a5b48bdfebf9872584cf6f901412b99e0e4988b3.nq.gz
│   ├── a68cf708ed4fc376a4662a2a2250c92281ffb126.nq.gz
│   ├── ac5739e97986a9d5edd55cf9d6c2fe65d4cf9cd5.nq.gz
│   ├── ad78220bf6ae7568b9e1aff6428f7851beaa7865.nq.gz
│   ├── b5bc422b59ce125c1398ceca3dd1180b4bb3f26d.nq.gz
│   ├── b6b33336fe75f2b63ca27df31e01b0fe3049142d.nq.gz
│   ├── b9016440d6c04dbe1ba0601ca815fef33ac03324.nq.gz
│   ├── bd147018ab9093126894b9caada21a7c39bcb775.nq.gz
│   ├── be61c6ab8a6ca913d8e54459df87155db7e2608f.nq.gz
│   ├── c373f78ce00cb158b3016d309f9e65934a4e2ac6.nq.gz
│   ├── c8cc873e499770ba453b02e72197ccc34d2b4725.nq.gz
│   ├── ce31c0362860ff92662cd9c6d6f684e1870a3063.nq.gz
│   ├── cfb4b3873493518806ffe7a38b6a61fea8000a8e.nq.gz
│   ├── d063ddaed012ffd88bc817fd61896d808dbaac82.nq.gz
│   ├── d1edd091746e8492cda6f002441f17bbb641a7df.nq.gz
│   ├── d4bb2cbb9eddb1bb1b4f366623044af8e4830919.nq.gz
│   ├── d52bbbc29bad166e780bdfa0b9bf3b7abd38058f.nq.gz
│   ├── d5ebccb3024ba7a8ab2e032bfb8477537f10548e.nq.gz
│   ├── d7b1cbbc153268a22b4fe5cce0a1c8332fdcd813.nq.gz
│   ├── da71456bd1fb153dcecb05f58c82d2bae7e20a7f.nq.gz
│   ├── db95486f302b1ca15b8ae436999dfa3f1f7e70e0.nq.gz
│   ├── dc4763ae86a339d3ebdcf2bf83ae62fe2dec3093.nq.gz
│   ├── dc576c1b48e555698efc86203966916b66795413.nq.gz
│   ├── e0896171604b2728fc4d2e8abbbfaa19ba6439e1.nq.gz
│   ├── e0d5efab56fb94577e7804603eb6f21f36977cb2.nq.gz
│   ├── e54e3791aec48dc4dfd5d01dc8ab90a20109dc0f.nq.gz
│   ├── e69de29bb2d1d6434b8b29ae775ad8c2e48c5391.nq.gz
│   ├── e6dfc32d39925ff062e3c3746e017f8e88a97d38.nq.gz
│   ├── eb759c37aac2c09bba72e5cd3e2a629838b6c4f7.nq.gz
│   ├── eed108607b0f28353e02293754cdce3840436412.nq.gz
│   ├── f80df2d9f9a6bc4433758476034408a4c546bc5a.nq.gz
│   ├── f901e37fbb9f5e206c1c4364693eeb1c79f90ec8.nq.gz
│   ├── fbc9086efc7b890d13636eab7f0fc79f899cb243.nq.gz
│   └── fc5fc439cff8a7d4f3b877ee302c192b8ad72000.nq.gz
├── branch
│   └── branch.nq.gz
├── commit
│   └── commit.nq.gz
├── filetree
│   └── 8edfb1fc47f8011a1ec401b878971fb47d104165.nq.gz
├── issue
│   └── issue.nq.gz
├── pr
│   └── pr.nq.gz
└── tag
    └── tag.nq.gz

13 directories, 123 files
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

[jazzband/django-payments](https://github.com/jazzband/django-payments)

---
*Parsed on 2026-10-11 by [repolex](https://repolex.ai)*
