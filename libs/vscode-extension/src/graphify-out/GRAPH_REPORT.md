# Graph Report - src  (2026-07-13)

## Corpus Check
- 30 files · ~4,878 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 342 nodes · 497 edges · 14 communities
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `f4e3a3f2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- project.ts
- project.ts
- workflow.ts
- index.ts
- index.ts
- connection.ts
- HttpClient
- JwtTokenHelper
- index.ts
- connection.ts
- workflow.ts
- index.ts
- index.ts
- HttpClient

## God Nodes (most connected - your core abstractions)
1. `HttpClient` - 10 edges
2. `HttpClient` - 10 edges
3. `IProjectWizardContext` - 8 edges
4. `IProjectWizardContext` - 8 edges
5. `FuncVersion` - 6 edges
6. `IProjectTreeItem` - 6 edges
7. `IWorkflowTemplate` - 6 edges
8. `IWorkflowTemplate` - 6 edges
9. `ProjectLanguage` - 5 edges
10. `JwtTokenHelper` - 5 edges

## Surprising Connections (you probably didn't know these)
- `ILogicAppWizardContext` --references--> `FuncVersion`  [EXTRACTED]
  src/lib/models/context.ts → src/lib/models/functions.ts
- `IProjectWizardContext` --references--> `WorkflowProjectType`  [EXTRACTED]
  src/lib/models/project.ts → src/lib/models/workflow.ts
- `IWorkflowTemplate` --references--> `IBindingSetting`  [EXTRACTED]
  src/lib/models/templates/IWorkflowTemplate.ts → src/lib/models/templates/IBindingTemplate.ts
- `ITemplates` --references--> `IWorkflowTemplate`  [EXTRACTED]
  src/lib/models/templates/index.ts → src/lib/models/templates/IWorkflowTemplate.ts
- `ILogicAppWizardContext` --references--> `FuncVersion`  [EXTRACTED]
  lib/models/context.ts → lib/models/functions.ts

## Import Cycles
- None detected.

## Communities (14 total, 0 thin omitted)

### Community 0 - "project.ts"
Cohesion: 0.06
Nodes (39): ICliFeed, IRelease, ITag, IWorkerRuntime, azureFunctionsVersion, FuncVersion, ICommandResult, ICreateFunctionOptions (+31 more)

### Community 1 - "project.ts"
Cohesion: 0.05
Nodes (41): ICliFeed, IRelease, ITag, IWorkerRuntime, azureFunctionsVersion, FuncVersion, ICommandResult, ICreateFunctionOptions (+33 more)

### Community 2 - "workflow.ts"
Cohesion: 0.12
Nodes (18): Artifacts, FileDetails, IArtifactFile, IGitHubReleaseInfo, IParametersFileContent, Parameter, ParametersData, AzureConnectorDetails (+10 more)

### Community 3 - "index.ts"
Cohesion: 0.14
Nodes (17): IBundleDependencyFeed, IBundleFeed, IFunctionWizardContext, BindingSettingValue, IBindingSetting, IBindingTemplate, IEnumValue, ResourceType (+9 more)

### Community 4 - "index.ts"
Cohesion: 0.07
Nodes (21): FetchSchemaData, InitializeData, MapDefinitionData, MessageToVsix, MessageToWebview, SchemaPathData, XsltData, ExtensionCommand (+13 more)

### Community 5 - "connection.ts"
Cohesion: 0.10
Nodes (21): AgentConnectionModel, AgentMcpConnectionModel, AllCustomCodeFiles, APIManagementConnectionModel, ConnectionAcl, ConnectionAndSettings, ConnectionReferenceModel, ConnectionsData (+13 more)

### Community 6 - "HttpClient"
Cohesion: 0.25
Nodes (7): getExtraHeaders(), HttpClient, HttpOptions, isArmResourceId(), isSuccessResponse(), isUrl(), parseResponse()

### Community 7 - "JwtTokenHelper"
Cohesion: 0.28
Nodes (3): IDecodedJwtToken, JwtTokenConstants, JwtTokenHelper

### Community 8 - "index.ts"
Cohesion: 0.08
Nodes (18): FetchSchemaData, InitializeData, MapDefinitionData, MessageToVsix, MessageToWebview, SchemaPathData, XsltData, ExtensionCommand (+10 more)

### Community 9 - "connection.ts"
Cohesion: 0.10
Nodes (21): AgentConnectionModel, AgentMcpConnectionModel, AllCustomCodeFiles, APIManagementConnectionModel, ConnectionAcl, ConnectionAndSettings, ConnectionReferenceModel, ConnectionsData (+13 more)

### Community 10 - "workflow.ts"
Cohesion: 0.12
Nodes (19): Artifacts, FileDetails, IArtifactFile, IGitHubReleaseInfo, IParametersFileContent, Parameter, ParametersData, AzureConnectorDetails (+11 more)

### Community 11 - "index.ts"
Cohesion: 0.13
Nodes (15): IBundleDependencyFeed, IBundleFeed, BindingSettingValue, IBindingSetting, IBindingTemplate, IEnumValue, ResourceType, ValueType (+7 more)

### Community 12 - "index.ts"
Cohesion: 0.14
Nodes (5): getBaseGraphApi(), getBaseGraphApi(), IDecodedJwtToken, JwtTokenConstants, JwtTokenHelper

### Community 13 - "HttpClient"
Cohesion: 0.25
Nodes (7): getExtraHeaders(), HttpClient, HttpOptions, isArmResourceId(), isSuccessResponse(), isUrl(), parseResponse()

## Knowledge Gaps
- **178 isolated node(s):** `IArtifactFile`, `IGitHubReleaseInfo`, `IBundleDependencyFeed`, `ICliFeed`, `IRelease` (+173 more)
  These have ≤1 connection - possible missing edges or undocumented components.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **What connects `IArtifactFile`, `IGitHubReleaseInfo`, `IBundleDependencyFeed` to the rest of the system?**
  _178 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `project.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.06342494714587738 - nodes in this community are weakly interconnected._
- **Should `project.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.054901960784313725 - nodes in this community are weakly interconnected._
- **Should `workflow.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.12380952380952381 - nodes in this community are weakly interconnected._
- **Should `index.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.1380952380952381 - nodes in this community are weakly interconnected._
- **Should `index.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.07126436781609195 - nodes in this community are weakly interconnected._
- **Should `connection.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.09881422924901186 - nodes in this community are weakly interconnected._