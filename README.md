# ipp5-backend-batch-launcher

~~~~~ sh
npm install e53e04ac/ipp5-backend-batch-launcher
~~~~~

~~~~~ mjs
import { Ipp5BackendBatchLauncher } from 'ipp5-backend-batch-launcher';
~~~~~

~~~~~ mermaid
graph RL;
  A["package.json\npackage-lock.json"];
  subgraph "dependencies";
    B_0(["azure-terraformer"]);
    B_1(["event-emitter"]);
    B_2(["file-entry-native"]);
    B_3(["hold"]);
  end;
  subgraph "devDependencies";
    B_4(["@types/node"]);
    B_5(["file-entry"]);
    B_6(["ipp5-types"]);
  end;
  subgraph "github";
    C_0(["e53e04ac/azure-terraformer\n88063530559233a0139b1cd10d84f9dc3d356366"]);
    C_1(["e53e04ac/event-emitter\nb07aafda2d8ddb14a40a0fe63ea41de2b8b58ca3"]);
    C_2(["e53e04ac/file-entry-native\nd75a642bb73e256d7304076bb54771d9a807ff33"]);
    C_3(["e53e04ac/hold\n6ce132702778d99c7f80a785e982419974dca8e5"]);
    C_5(["e53e04ac/file-entry\n43d558c1cb0725770c2f06b00bd2d174c543a145"]);
    C_6(["e53e04ac/ipp5-types\ncd72b950987429097963f0dd40c801794c0d09bf"]);
  end;
  subgraph "npmjs";
    C_4(["@types/node\n18.15.11"]);
  end;
  A ----> B_0;
  A ----> B_1;
  A ----> B_2;
  A ----> B_3;
  A ----> B_4;
  A ----> B_5;
  A ----> B_6;
  B_0 ----> C_0;
  B_1 ----> C_1;
  B_2 ----> C_2;
  B_3 ----> C_3;
  B_4 ----> C_4;
  B_5 ----> C_5;
  B_6 ----> C_6;
  click C_0 "https://github.com/e53e04ac/azure-terraformer/tree/88063530559233a0139b1cd10d84f9dc3d356366";
  click C_1 "https://github.com/e53e04ac/event-emitter/tree/b07aafda2d8ddb14a40a0fe63ea41de2b8b58ca3";
  click C_2 "https://github.com/e53e04ac/file-entry-native/tree/d75a642bb73e256d7304076bb54771d9a807ff33";
  click C_3 "https://github.com/e53e04ac/hold/tree/6ce132702778d99c7f80a785e982419974dca8e5";
  click C_4 "https://www.npmjs.com/package/@types/node/v/18.15.11";
  click C_5 "https://github.com/e53e04ac/file-entry/tree/43d558c1cb0725770c2f06b00bd2d174c543a145";
  click C_6 "https://github.com/e53e04ac/ipp5-types/tree/cd72b950987429097963f0dd40c801794c0d09bf";
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/ipp5-backend-batch-launcher";
    E_0(["namespace Ipp5BackendBatchLauncher"]);
    E_1(["type Ipp5BackendBatchLauncher"]);
    E_2(["const Ipp5BackendBatchLauncher"]);
  end;
  M["index.d.ts"]
  subgraph "azure-terraformer";
    I_0_0(["AzureTerraformer"]);
  end;
  subgraph "event-emitter";
    I_1_0(["EventEmitter"]);
  end;
  subgraph "file-entry";
    I_2_0(["FileEntry"]);
  end;
  subgraph "hold";
    I_3_0(["Get"]);
    I_3_1(["ValueOrGet"]);
  end;
  subgraph "ipp5-types";
    I_4_0(["Ipp5BackendBatchEnvMap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_2_0;
  M ----> I_3_0;
  M ----> I_3_1;
  M ----> I_4_0;
  E_0 ----> M;
  E_1 ----> M;
  E_2 ----> M;
~~~~~

~~~~~ mermaid
graph RL;
  subgraph "e53e04ac/ipp5-backend-batch-launcher";
    E_0(["Ipp5BackendBatchLauncher"]);
  end;
  M["index.mjs"]
  subgraph "azure-terraformer";
    I_0_0(["AzureTerraformer"]);
  end;
  subgraph "event-emitter";
    I_1_0(["EventEmitter"]);
  end;
  subgraph "file-entry-native";
    I_2_0(["FileEntry"]);
  end;
  subgraph "hold";
    I_3_0(["hold"]);
    I_3_1(["unwrap"]);
  end;
  M ----> I_0_0;
  M ----> I_1_0;
  M ----> I_2_0;
  M ----> I_3_0;
  M ----> I_3_1;
  E_0 ----> M;
~~~~~
