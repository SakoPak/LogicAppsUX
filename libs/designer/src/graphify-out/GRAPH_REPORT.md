# Graph Report - src  (2026-07-13)

## Corpus Check
- 725 files · ~406,215 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 7270 nodes · 23451 edges · 218 communities (197 shown, 21 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 200 edges (avg confidence: 0.62)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `f4e3a3f2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- DesignerContextualMenu.tsx
- helper.ts
- initialize.ts
- connections.ts
- operation.ts
- outputs.test.ts
- serializer.ts
- generatekeys.tsx
- settings.ts
- templates.ts
- OperationCardNode.tsx
- initialize.ts
- useTemplatesStrings
- helper.ts
- index.tsx
- outputs.ts
- Designer.tsx
- index.tsx
- segment.ts
- helper.ts
- AppDispatch
- openAIConnector.tsx
- workflowSlice.ts
- createConnection.tsx
- logicapp.ts
- loops.ts
- operationMetadataSlice.ts
- dynamicdata.ts
- agentChat.tsx
- serializer.ts
- templateCard.tsx
- monitoringTab.tsx
- RootState
- graph.ts
- workflowSlice.ts
- panelSlice.ts
- knowledgehub.tsx
- workflowSelectors.ts
- panelSelectors.ts
- inputsbuilder.ts
- constants.ts
- McpWizard.tsx
- usePanelTabs.tsx
- connections.ts
- getReactQueryClient
- workflowNode.ts
- index.tsx
- EdgeContextualMenu.tsx
- mcpPanelSlice.ts
- loops.ts
- panelSelectors.ts
- index.tsx
- mcpservers.tsx
- PerformanceDebug.tsx
- AppDispatch
- mcp.ts
- RootState
- Designer.tsx
- RootState
- simplecreate.tsx
- createConnection.spec.tsx
- agentHarnessTab.tsx
- BJSDeserializer.ts
- serializer.ts
- OperationCardNode.tsx
- store.ts
- validation.ts
- role.ts
- actionMetadataSelector.ts
- Binder
- addfile.tsx
- errorsTab.hooks.ts
- connectionSelector.ts
- useWizardTabs.tsx
- usepaneltabs.tsx
- panelSlice.ts
- index.ts
- index.tsx
- settings.ts
- connectionselection.tsx
- unitTestSlice.ts
- nodeDetailsPanel.tsx
- ParseReduxAction.ts
- index.tsx
- useIsA2AWorkflow
- openAIConnector.spec.tsx
- clonedataprovider.tsx
- DesignerContextualMenu.tsx
- getReactQueryClient
- operationSelector.ts
- SubgraphCardNode.spec.tsx
- workflowSelectors.ts
- designerViewSlice.ts
- operation.ts
- configurelogicapps.tsx
- resourcepicker.tsx
- agentChat.tsx
- openAIConnector.tsx
- store.ts
- createConnection.tsx
- basics.tsx
- operationMetadataSlice.ts
- simplecreatereview.tsx
- global.ts
- dynamicdata.ts
- index.ts
- optionsSlice.ts
- cloneslice.ts
- BJSDeserializer.ts
- segment.ts
- addNodeToWorkflow.ts
- workflowInterfaces.ts
- useRunData
- errorsTab.hooks.ts
- store.ts
- UncastingUtility
- servers.tsx
- monitoring.ts
- logicapp.ts
- useNodeDisplayName
- helper.ts
- index.tsx
- notification.tsx
- helper.spec.ts
- AppDispatch
- index.tsx
- constants.ts
- templateCard.tsx
- gatewayPicker.tsx
- store.ts
- templateoverview.tsx
- mcpPanelSlice.ts
- generatekeys.tsx
- store.ts
- universalConnectionParameter.tsx
- initialize.spec.ts
- intl-test-helper.tsx
- trafficlightsvgs.tsx
- store.ts
- designerOptionsSelectors.ts
- onlyEdge.tsx
- iFrameTOS.tsx
- gripper.tsx
- edit.tsx
- mcpOptionsInterface.ts
- typings.d.ts
- Svg.d.ts
- ValueSegmentConvertor
- undoRedoTypes.ts
- connections.ts
- ListConnectors.tsx
- uploadfile.tsx
- simplecreate.tsx
- knowledgehub.tsx
- index.tsx
- store.ts
- panelSlice.ts
- agentHarnessTab.tsx
- role.ts
- useWizardTabs.tsx
- queries.ts
- EditOperation.tsx
- workflowconnections.tsx
- delete.ts
- mcpservers.tsx
- runafteractiondetails.tsx
- edit.tsx
- connectionTable.tsx
- designerViewSlice.ts
- Binder
- elklayout.tsx
- clonedataprovider.tsx
- inputs.test.ts
- resourcepicker.tsx
- DesignerProvider.tsx
- SubgraphCardNode.spec.tsx
- elklayout.tsx
- configurelogicapps.tsx
- cloneslice.ts
- connections.spec.ts
- connection.tsx
- basics.tsx
- servers.tsx
- index.ts
- ServerNotificationData
- OperationSelectionGrid.tsx
- triggerDescriptionDialog.tsx
- errors.ts
- errors.ts
- PerformanceDebug.tsx
- createhelper.ts
- redux-test-helper.tsx
- notification.tsx
- deploymentModelResource.tsx
- errorbar.spec.tsx
- clonewizardprovider.tsx
- KnowledgeWizardProvider.tsx
- JsonSplitter
- gatewayPicker.tsx
- DesignerReactFlow.spec.tsx
- cosmosConnector.spec.tsx
- ApiConnectionInputsBinder
- ConnectorBrowseView.tsx
- DefaultSearchOperationsService
- intl-test-helper.tsx
- clientSecretInput.tsx
- trafficlightsvgs.tsx
- advancedSettingsMessage.tsx
- gripper.tsx
- onlyEdge.tsx
- iFrameTOS.tsx
- ThemeObservable.tsx
- mcpOptionsInterface.ts

## God Nodes (most connected - your core abstractions)
1. `getReactQueryClient()` - 89 edges
2. `getReactQueryClient()` - 85 edges
3. `RootState` - 71 edges
4. `RootState` - 70 edges
5. `RootState` - 62 edges
6. `RootState` - 62 edges
7. `getOperationSettings()` - 57 edges
8. `getOperationSettings()` - 57 edges
9. `AppDispatch` - 57 edges
10. `AppDispatch` - 56 edges

## Surprising Connections (you probably didn't know these)
- `DesignerReactFlow()` --indirect_call--> `HiddenNode()`  [INFERRED]
  src/lib/ui/DesignerReactFlow.tsx → src/lib/ui/CustomNodes/HiddenNode.tsx
- `resetQueriesOnUpdateServers()` --calls--> `getReactQueryClient()`  [INFERRED]
  lib/core/mcp/utils/queries.ts → lib/core/ReactQueryProvider.tsx
- `dispatchParamUpdate()` --calls--> `createLiteralValueSegment()`  [INFERRED]
  lib/ui/panel/nodeDetailsPanel/tabs/parametersTab/index.tsx → lib/core/utils/parameters/segment.ts
- `ConnectionPayload` --references--> `ApiHubAuthentication`  [EXTRACTED]
  src/lib/core/actions/bjsworkflow/connections.ts → src/lib/common/models/workflow.ts
- `InitialWorkflowState` --references--> `ConnectionReferences`  [EXTRACTED]
  src/lib/core/state/templates/workflowSlice.ts → src/lib/common/models/workflow.ts

## Import Cycles
- 1-file cycle: `lib/core/mcp/utils/queries.ts -> lib/core/mcp/utils/queries.ts`
- 3-file cycle: `lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/usePanelTabs.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/tabs/customizeWorkflowsTab.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx`
- 3-file cycle: `lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/usePanelTabs.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/tabs/selectWorkflowsTab.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx`
- 3-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/usePanelTabs.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/tabs/reviewCreateTab.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 3-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/templates/index.tsx -> lib/ui/templates/templateview.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 3-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/usePanelTabs.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/tabs/basicsTab.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 3-file cycle: `lib/core/state/global.ts -> lib/core/state/workflow/workflowSelectors.ts -> lib/core/state/operation/operationMetadataSlice.ts -> lib/core/state/global.ts`
- 3-file cycle: `lib/core/state/global.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/state/operation/operationMetadataSlice.ts -> lib/core/state/global.ts`
- 3-file cycle: `lib/core/actions/bjsworkflow/configuretemplate.ts -> lib/core/state/templates/store.ts -> lib/core/state/templates/panelSlice.ts -> lib/core/actions/bjsworkflow/configuretemplate.ts`
- 3-file cycle: `lib/core/actions/bjsworkflow/connections.ts -> lib/core/store.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/connections.ts`
- 4-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/usePanelTabs.tsx -> lib/ui/templates/index.tsx -> lib/ui/templates/templateview.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 4-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/templates/index.tsx -> lib/ui/templates/templateview.tsx -> lib/ui/templates/templateoverview.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 4-file cycle: `lib/core/state/connection/connectionSlice.ts -> lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/connection/connectionSlice.ts`
- 4-file cycle: `lib/core/state/customcode/customcodeSlice.ts -> lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/customcode/customcodeSlice.ts`
- 4-file cycle: `lib/core/state/designerView/designerViewSlice.ts -> lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/designerView/designerViewSlice.ts`
- 4-file cycle: `lib/core/state/dev/devSlice.ts -> lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/dev/devSlice.ts`
- 4-file cycle: `lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/operation/operationMetadataSlice.ts -> lib/core/state/global.ts`
- 4-file cycle: `lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/panel/panelSlice.ts -> lib/core/state/global.ts`
- 4-file cycle: `lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/setting/settingSlice.ts -> lib/core/state/global.ts`
- 4-file cycle: `lib/core/state/global.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/staticresultschema/staticresultsSlice.ts -> lib/core/state/global.ts`

## Communities (218 total, 21 thin omitted)

### Community 0 - "DesignerContextualMenu.tsx"
Cohesion: 0.08
Nodes (23): copyOperation, copyScopeOperation, shouldDisplayRunAfter(), CopyTooltip(), CopyTooltipProps, DesignerContextualMenu(), NodeMenuPriorities, useNodeSelectAdditionalCallback() (+15 more)

### Community 1 - "helper.ts"
Cohesion: 0.04
Nodes (83): updateDynamicDataForValidConnection(), canConvertToComplexCondition(), castTokenSegmentsInValue(), compressSegments(), containsExpression(), convertPathToBracketsFormat(), convertStringToInputParameter(), createParameterInfo() (+75 more)

### Community 2 - "initialize.ts"
Cohesion: 0.04
Nodes (109): AddOperationPayload, addTokensAndVariables(), getNonDuplicateId(), getNonDuplicateNodeId(), getTriggerNodeManifest(), initializeOperationDetails(), tryGetMostRecentlyUsedConnectionId(), trySetDefaultConnectionForNode() (+101 more)

### Community 3 - "connections.ts"
Cohesion: 0.05
Nodes (66): autoCreateConnectionIfPossible(), ConnectionPayload, connectorHasMultiAuth(), getApiHubAuthentication(), getApiHubAuthenticationIfRequired(), getConnectionMappingForNode(), getConnectionProperties(), getConnectionPropertiesIfRequired() (+58 more)

### Community 4 - "operation.ts"
Cohesion: 0.10
Nodes (31): addDefaultSecureSettings(), getInputDependencies(), addRecurrenceParametersInGroup(), getDependenciesToUpdate(), getDependentParameters(), loadParameterValuesFromDefault(), parameterHasValue(), parameterValidForDynamicCall() (+23 more)

### Community 5 - "outputs.test.ts"
Cohesion: 0.14
Nodes (7): OutputsBinder, ApiConnectionOutputsBinder, ManifestOutputsBinder, nodeParameters, operationMetadata, outputParametersByName, parsedOutputs

### Community 6 - "serializer.ts"
Cohesion: 0.06
Nodes (62): AgentConnectionInfo, ApiManagementConnectionInfo, constructInputValues(), FunctionConnectionInfo, getActions(), getAssertions(), getNodeOutputOperations(), getOperationInputsToSerialize() (+54 more)

### Community 7 - "generatekeys.tsx"
Cohesion: 0.16
Nodes (14): useMcpServerPanelStyles, CloseIcon, CreateServer(), CloseIcon, GenerateKeys(), TimePickerWithDatePicker(), McpServerPanel(), getHostConfig() (+6 more)

### Community 8 - "settings.ts"
Cohesion: 0.09
Nodes (63): areRequestOptionsSupported(), areTrackedPropertiesSupported(), ConcurrencySettings, CorrelationSettings, getAsynchronous(), getConcurrency(), getConditionExpressions(), getCorrelationSettings() (+55 more)

### Community 9 - "templates.ts"
Cohesion: 0.06
Nodes (48): ConfigureTemplateServiceOptions, initializeConfigureTemplateServices, loadCustomTemplate, getWorkflowAndManifest(), GetWorkflowAndManifestHandler, initializeTemplateServices, initializeWorkflowMetadata, loadCustomTemplates (+40 more)

### Community 10 - "OperationCardNode.tsx"
Cohesion: 0.06
Nodes (78): moveOperation, NodeStaticResults, StaticResultOption, DraftEdge(), DropZone, ButtonEdge(), EdgeContentProps, LogicAppsEdgeProps (+70 more)

### Community 11 - "initialize.ts"
Cohesion: 0.04
Nodes (124): CustomCodeFileNameMapping, ConnectionReference, ReferenceKey, AddOperationPayload, addTokensAndVariables(), getNonDuplicateId(), getNonDuplicateNodeId(), getTriggerNodeManifest() (+116 more)

### Community 12 - "useTemplatesStrings"
Cohesion: 0.06
Nodes (46): MultiWorkflowBasics(), WorkflowItem, ResourceSection(), ResourceSectionProps, useStyles, WorkflowName(), WorkflowTriggerDescription(), SingleWorkflowBasics() (+38 more)

### Community 13 - "helper.ts"
Cohesion: 0.19
Nodes (11): getCurrentWorkflowNames(), getFilteredTemplates(), getTemplatePublishCategories(), _sortTemplateManifestEntriesByTitle(), templateSearchOptions, validateConnectionsValue(), validateParameterDetail(), validateParameterValue() (+3 more)

### Community 14 - "index.tsx"
Cohesion: 0.06
Nodes (53): getPendingFoundryUpdate(), buildProxyContext(), CosmosDbAccount, foundryQueryOpts, getCognitiveServiceAccountDeploymentsForConnection(), getFoundryProxyContext(), getServiceAccountId(), isFoundryAuthError() (+45 more)

### Community 15 - "outputs.ts"
Cohesion: 0.14
Nodes (19): AssertionsPanel(), getVariableTokens(), useTokens(), generateExpressionFromKey(), getExpressionValueForOutputToken(), getTokenExpressionMethodFromKey(), getTokenValueFromToken(), segmentsAreBodyReference() (+11 more)

### Community 16 - "Designer.tsx"
Cohesion: 0.05
Nodes (56): deleteGraphNode, deleteMcpServerNode, deleteOperation, addAgentHandoff, addOperationRunAfter, EdgeRunAfterPayload, removeOperationRunAfter, HiddenEdge() (+48 more)

### Community 17 - "index.tsx"
Cohesion: 0.11
Nodes (26): parseRepetitions(), TimelineRepetitionWithActions, TimelineRepetition, useTimelineRepetitionCount(), useTimelineRepetitions(), MonitoringTimeline(), useMonitoringTimelineStyles, ChevronDownIcon (+18 more)

### Community 18 - "segment.ts"
Cohesion: 0.07
Nodes (15): updateTokenTitlesInViewModel(), JsonSplitter, createAgentParameterToken(), createExpressionToken(), createOutputToken(), createParameterToken(), createTokenValueSegment(), createVariableToken() (+7 more)

### Community 19 - "helper.ts"
Cohesion: 0.03
Nodes (129): updateTokenMetadataInParameters(), NodeDependencies, useConnectionReferenceForKey(), getFirstParentOfType(), updateTokenMetadataInForeachInputs(), getUpdatedManifestForSchemaDependency(), addCastToExpression(), addFoldingCastToExpression() (+121 more)

### Community 20 - "AppDispatch"
Cohesion: 0.05
Nodes (68): TemplateResourcePicker(), addWorkflowsData, deleteWorkflowData, saveTemplateData, saveWorkflowsData, updateWorkflowParameter, WorkflowTemplateData, DescriptionWithLink() (+60 more)

### Community 21 - "openAIConnector.tsx"
Cohesion: 0.15
Nodes (23): SubscriptionDropdown(), SubscriptionDropdownProps, useSubscriptions(), ConnectionParameterRow(), ConnectionParameterRowParameterRowSelfProps, ConnectionParameterRowProps, ACASessionConnector(), RefreshIcon (+15 more)

### Community 22 - "workflowSlice.ts"
Cohesion: 0.06
Nodes (77): isWorkflowOperationNode(), exportForTesting, createSharedEdge(), elkGraphLayoutOptions, elkSubgraphLayoutOptions, addAgentToolToWorkflow(), addChildEdge(), addChildNode() (+69 more)

### Community 23 - "createConnection.tsx"
Cohesion: 0.12
Nodes (15): CreateConnection(), CreateConnectionProps, ParamType, parseParameterValues(), IndependentPublisherDisclaimer(), IndependentPublisherDisclaimerProps, useStyles, useStyles (+7 more)

### Community 24 - "logicapp.ts"
Cohesion: 0.09
Nodes (36): queryOpts, quickReviewTab(), areProvidersRegistered(), ArmTemplate, ArmTemplateResource, checkDeploymentCreateOperations(), checkDeploymentStatus(), createLogicAppFromTemplate() (+28 more)

### Community 25 - "loops.ts"
Cohesion: 0.09
Nodes (35): OutputInfo, getExpressionTokenTitle(), getParameterFromId(), RepetitionContext, RepetitionReference, updateTokenMetadata(), updateTokenMetadataInParameters(), getAllParentsForNode() (+27 more)

### Community 26 - "operationMetadataSlice.ts"
Cohesion: 0.05
Nodes (76): onRedoClick, onUndoClick, storeStateToUndoRedoHistory, ChannelsTab(), ConnectionReferenceMap, connectionSlice, initialConnectionsState, AppStore (+68 more)

### Community 27 - "dynamicdata.ts"
Cohesion: 0.09
Nodes (42): getSwaggerOutputAndTokenData(), updateOutputsAndTokens(), updateSplitOnSetting(), evaluateParameter(), evaluateTemplateExpressions(), getDynamicInputParameterFromDynamicParameter(), getDynamicInputsFromSchema(), getDynamicOutputsFromSchema() (+34 more)

### Community 28 - "agentChat.tsx"
Cohesion: 0.06
Nodes (44): AgentChat(), AgentChatProps, AgentChatHeader(), AgentChatHeaderProps, CollapseIcon, RefreshIcon, StopIcon, parseChatHistory() (+36 more)

### Community 29 - "serializer.ts"
Cohesion: 0.04
Nodes (103): Impersonation, ImpersonationSource, WorkflowParameter, getConnectionsApiAndMapping(), getConnectionsMappingForNodes(), AgentConnectionInfo, ApiManagementConnectionInfo, constructInputValues() (+95 more)

### Community 30 - "templateCard.tsx"
Cohesion: 0.09
Nodes (28): loadCustomTemplateArtifacts, loadTemplate, BlankWorkflowTemplateCard(), LoadingTemplateCard(), iconStyle, TemplateCard(), templateCardBodyStyles, TemplateCardProps (+20 more)

### Community 31 - "monitoringTab.tsx"
Cohesion: 0.10
Nodes (25): InputsPanel(), InputsPanelProps, MonitoringPanel(), OutputsPanel(), OutputsPanelProps, PropertiesPanel(), PropertiesPanelProps, emptyData (+17 more)

### Community 32 - "RootState"
Cohesion: 0.10
Nodes (27): isMultiWorkflowTemplate(), ConnectionsList(), ConnectorWithDetails(), CreateWorkflowPanel(), CreateWorkflowPanelHeader(), CreateWorkflowPanelProps, useStyles, useCreateWorkflowPanelTabs() (+19 more)

### Community 33 - "graph.ts"
Cohesion: 0.15
Nodes (18): exportForTesting, isWorkflowGraph(), createSharedEdge(), elkGraphLayoutOptions, elkSubgraphLayoutOptions, createElkEdge(), createElkNode(), getAllNodesInsideNode() (+10 more)

### Community 34 - "workflowSlice.ts"
Cohesion: 0.22
Nodes (20): WorkflowEdge, RelationshipIds, AddNodePayload, addNodeToWorkflow(), deleteMcpServerNodeFromWorkflow(), deleteNodeFromWorkflow(), DeleteNodePayload, deleteWorkflowNode() (+12 more)

### Community 35 - "panelSlice.ts"
Cohesion: 0.12
Nodes (17): CloseIcon, CreateConnectionPanel(), ConfigPanelView, initialState, KnowledgePanelView, panelSlice, PanelState, RootState (+9 more)

### Community 36 - "knowledgehub.tsx"
Cohesion: 0.11
Nodes (23): CreateGroup(), DeleteModal(), useModalStyles, ServerNotificationData, mockCreateKnowledgeHub, mockUseAllKnowledgeHubs, mockValidateHubNameAvailability, mockDeleteKnowledgeHubArtifacts (+15 more)

### Community 37 - "workflowSelectors.ts"
Cohesion: 0.06
Nodes (37): initializeSubgraphFromManifest(), AddAgentHandoffPayload, removeAgentHandoff, RemoveAgentHandoffPayload, CollapsedNode(), AddIcon, HandoffSelector(), useHandoffTabStyles (+29 more)

### Community 38 - "panelSelectors.ts"
Cohesion: 0.05
Nodes (86): addOperation, addConnectorAsOperation, filterOperationsByConnector(), filterOperationsFromList(), isManagedConnector(), pagedOpts, queryOpts, useAllActions() (+78 more)

### Community 39 - "inputsbuilder.ts"
Cohesion: 0.11
Nodes (32): serializeParameterWithPath(), deletePropertyValueWithSpecifiedPathSegment(), getAndEscapeSegment(), getExtraSegments(), getPropertyValueWithSpecifiedPathSegments(), reduceRedundantSegments(), transformInputParameter(), updateParameterWithValues() (+24 more)

### Community 40 - "constants.ts"
Cohesion: 0.08
Nodes (29): TemplatePayload, validateWorkflowsBasicInfo, SCHEMA, SWAGGER, VARIABLE_TYPE, WorkflowConnections(), ReactQueryProvider(), CreateWorkflowTabProps (+21 more)

### Community 41 - "McpWizard.tsx"
Cohesion: 0.16
Nodes (13): ListConnectors(), LogicAppSelector(), useMcpDetailsStyles, useValidMcpConnection(), ListOperations(), McpPanelRoot(), useAllMcpServersFromVfs(), useEmptyLogicApps() (+5 more)

### Community 42 - "usePanelTabs.tsx"
Cohesion: 0.09
Nodes (26): usePanelTabHideKeys(), monitoringTab(), useParameterStaticResult(), getStaticResultForNodeId(), useHasSchema(), useStaticResultProperties(), useStaticResultSchema(), monitorRetryTab() (+18 more)

### Community 43 - "connections.ts"
Cohesion: 0.04
Nodes (76): isManagedMcpConnector(), autoCreateConnectionIfPossible(), ConnectionPayload, connectorHasMultiAuth(), getApiHubAuthentication(), getApiHubAuthenticationIfRequired(), getConnectionProperties(), getConnectionPropertiesIfRequired() (+68 more)

### Community 44 - "getReactQueryClient"
Cohesion: 0.05
Nodes (71): getAllParametersForWorkflows(), getConnectionsForConsumption(), getConnectionsForStandard(), getDefinitionAndUsedConnectionMappings(), getFeaturedConnectorsForWorkflows(), getTemplateConnections(), getTemplateParameters(), getTemplateValidationError (+63 more)

### Community 45 - "workflowNode.ts"
Cohesion: 0.14
Nodes (16): initialState, mockGraph, WorkflowNode, UpdateAgenticGraphPayload, updateAgenticSubgraph(), mockReassignEdgeSources, mockRemoveEdge, collapseFlowTree() (+8 more)

### Community 46 - "index.tsx"
Cohesion: 0.05
Nodes (72): isAgentSubgraphFromMetadata(), AgentUtils, getSKUDefaultHostOptions(), isDynamicConnection(), titleCase(), clearPendingFoundryUpdate(), consumeVersionRefresh(), flushPendingFoundryUpdates() (+64 more)

### Community 47 - "EdgeContextualMenu.tsx"
Cohesion: 0.09
Nodes (21): pasteOperation, pasteScopeOperation, DropZoneProps, useEdgeContextMenuData(), CustomMenu(), CustomMenuProps, AddIcon, AgentIcon (+13 more)

### Community 48 - "mcpPanelSlice.ts"
Cohesion: 0.08
Nodes (25): deinitializeOperations, initializeConnectionMappings, initializeOperationsMetadata, ConnectorBrowseView(), ConnectorBrowseViewProps, ConnectionDisplayName(), connectorTableCellStyles, lastCellStyles (+17 more)

### Community 49 - "loops.ts"
Cohesion: 0.05
Nodes (79): updateOutputsAndTokens(), updateSplitOnSetting(), OutputInfo, updateExistingInputTokenTitles(), updateTokenTitlesInViewModel(), getNewNodeId(), getTriggerNode(), getTriggerNodeId() (+71 more)

### Community 50 - "panelSelectors.ts"
Cohesion: 0.06
Nodes (77): ActionList(), ActionListProps, AllConnections(), ConnectorCardWrapper(), ConnectorCardWrapperProps, AllConnectionsEmptyState(), closeConnectionsFlow, getConnectionMetadata() (+69 more)

### Community 51 - "index.tsx"
Cohesion: 0.15
Nodes (14): CreateConnectionModal(), BadgeArtifact(), HubOption(), KnowledgeHubEditor(), KnowledgeHubEditorOptions, useConnectionStyles, useKnowledgeStyles, mockPanelTabs (+6 more)

### Community 52 - "mcpservers.tsx"
Cohesion: 0.11
Nodes (16): AddServerButtons(), Authentication(), AuthenticationSettings(), ToolHandler, useMcpAuthenticationStyles, useMcpServerAddStyles, mockUseMcpEligibleWorkflows, mockOpenMcpPanelView (+8 more)

### Community 53 - "PerformanceDebug.tsx"
Cohesion: 0.33
Nodes (6): useShowPerformanceDebug(), useReduxActionCounts(), useNodesAndDynamicDataInitialized(), PerformanceDebugTool(), InitializationTimer(), ReduxActionCounts()

### Community 54 - "AppDispatch"
Cohesion: 0.05
Nodes (67): addOperation, addConnectorAsOperation, AppDispatch, useEnableNestedAgentLoops(), useIsAgenticWorkflow(), useDiscoveryPanelFavoriteOperations(), useDiscoveryPanelIsAddingTrigger(), useDiscoveryPanelIsOperationFavorited() (+59 more)

### Community 55 - "mcp.ts"
Cohesion: 0.14
Nodes (17): initializeMcpData, McpServiceOptions, resetMcpStateOnResourceChange, McpDataProvider(), McpDataProviderProps, McpServerDataProvider(), CreateDetails, InitialResourceState (+9 more)

### Community 56 - "RootState"
Cohesion: 0.12
Nodes (26): CloseIcon, SelectionPanel(), useMcpConnectorPanelTabs(), ParameterEditor(), CloseIcon, CreateAppPanel(), useCreateAppPanelTabs(), AppDispatch (+18 more)

### Community 57 - "Designer.tsx"
Cohesion: 0.05
Nodes (62): pasteOperation, pasteScopeOperation, addAgentHandoff, addOperationRunAfter, removeOperationRunAfter, useLayout(), useIsDraggingNode(), useIsVSCode() (+54 more)

### Community 58 - "RootState"
Cohesion: 0.07
Nodes (56): deleteWorkflowData, workflowsHaveErrors(), formatNameWithIdentifierToDisplay(), getDateTimeString(), useTemplateWorkflowResources(), RootState, useTemplateConnections(), useTemplateParameterDefinitions() (+48 more)

### Community 59 - "simplecreate.tsx"
Cohesion: 0.14
Nodes (18): SimpleCreate(), useDetailsSectionItems(), useCreateDetailsStyles, useCreatePopupStyles, AppInsightsSelector(), validateAvailability(), AppPlanSelector(), AppPlanSelectorProps (+10 more)

### Community 60 - "createConnection.spec.tsx"
Cohesion: 0.20
Nodes (14): mockConnectionParameters, mockConnectionParameterSets, mockOauthWithTenantParameters, mockParameterSetsWithCredentialMapping, mockParameterSetWithClientCertAuth, mockParameterSetWithOAuth, mockParameterSetWithSPAuth, findConnectionsParamContainer() (+6 more)

### Community 61 - "agentHarnessTab.tsx"
Cohesion: 0.12
Nodes (19): AgentHarnessData, AgentHarnessInputFile, AgentHarnessSkill, AgentHarnessTab(), ExpressionTokenPill(), extractErrorDetail(), getExpressionTitle(), inputFileColumns (+11 more)

### Community 62 - "BJSDeserializer.ts"
Cohesion: 0.18
Nodes (21): addActionsInstanceMetaData(), addTriggerInstanceMetaData(), buildGraphFromActions(), Deserialize(), deserializeUnitTestDefinition(), flattenObject(), getAllActionNames(), hasMultipleTriggers() (+13 more)

### Community 63 - "serializer.ts"
Cohesion: 0.14
Nodes (16): ParameterEditor(), NodeOperation, useConnectionReferenceForKey(), getAuthenticationDetails(), getConnectionsToUpdate(), getUpdatedConnectionForManagedApiReference(), hasNewConnectionRuntimeUrl(), hasNewKeys() (+8 more)

### Community 64 - "OperationCardNode.tsx"
Cohesion: 0.10
Nodes (53): copyOperation, copyScopeOperation, moveOperation, useNodeRepetition(), useMcpClientToolEnabled(), useMonitoringView(), useReadOnly(), useShowEdgeDrawing() (+45 more)

### Community 65 - "store.ts"
Cohesion: 0.10
Nodes (15): McpWizardContext, McpWrappedContext, McpWizardProvider(), McpWizardProviderProps, AppStore, mcpStore, rootReducer, lastCellStyles (+7 more)

### Community 66 - "validation.ts"
Cohesion: 0.14
Nodes (25): getTitleOrSummary(), isOneOf(), getInferredParameterType(), isParameterRequired(), isValidJSONArrayFormat(), isValidJSONObjectFormat(), parameterValueToJSONString(), parameterValueToStringWithoutCasting() (+17 more)

### Community 67 - "role.ts"
Cohesion: 0.15
Nodes (16): appIdentityRoleAssignmentsQueryOpts(), getMissingRoleDefinitions(), queryOpts, resourceRoleDefinitionQueryOpts(), roleDefinitionByNameQueryOpts(), roleQueryKeys, useAppIdentityRoleAssignmentsForResourceQuery(), useResourceRoleDefinitionsQuery() (+8 more)

### Community 68 - "actionMetadataSelector.ts"
Cohesion: 0.12
Nodes (26): useSwagger(), useHostOptions(), CombineInitializeVariableDialog(), TriggerDescriptionDialog(), TriggerDescriptionDialogProps, useIsCombineVariableModalOpen(), useIsTriggerDescriptionModalOpen(), useResolveCombineVariable() (+18 more)

### Community 69 - "Binder"
Cohesion: 0.05
Nodes (20): Binder, getDynamicListLookupValue(), getDynamicTreeLookupValue(), ApiConnectionInputsBinder, DefaultInputsBinder, InputsBinder, ManifestInputsBinder, ApiConnectionOutputsBinder (+12 more)

### Community 70 - "addfile.tsx"
Cohesion: 0.24
Nodes (10): AddFilesModal(), AddFilePanel(), CloseIcon, FileList(), FileUpload(), FileUploadProps, useFileHooks(), AppDispatch (+2 more)

### Community 71 - "errorsTab.hooks.ts"
Cohesion: 0.10
Nodes (35): deleteWorkflowParameter, useLegacyWorkflowParameters(), CollapseIcon, ErrorCategory(), ErrorCategoryProps, ExpandIcon, CloseIcon, ErrorsPanel() (+27 more)

### Community 72 - "connectionSelector.ts"
Cohesion: 0.11
Nodes (54): useIsAgentSubGraph(), ApiHubAuthentication, ConnectionMapping, closeConnectionsFlow, getConnectionMetadata(), reloadParametersTab, updateNodeConnection, useConnectionsForConnector() (+46 more)

### Community 73 - "useWizardTabs.tsx"
Cohesion: 0.17
Nodes (13): AppDispatch, initialState, tabSlice, TabState, useExistingWorkflowNamesOfResource(), configureTab(), CloneWizardTabProps, reviewTab() (+5 more)

### Community 74 - "usepaneltabs.tsx"
Cohesion: 0.20
Nodes (14): useCreateConnectionPanelTabs(), intl, mockCreateConnection, mockSetQueryData, mockBasicsTab, mockCosmosDbParams, mockCreateOrUpdateConnection, mockModelTab (+6 more)

### Community 75 - "panelSlice.ts"
Cohesion: 0.09
Nodes (20): ConnectionEntry(), ConnectionEntryProps, ConnectorConnectionsCard(), ConnectorConnectionsCardProps, NodeLinkButton(), initialState, panelSlice, ActionPanelFavoriteItem (+12 more)

### Community 76 - "index.ts"
Cohesion: 0.06
Nodes (55): ConfigureTemplateServiceOptions, initializeConfigureTemplateServices, loadCustomTemplate, getNodeOutputOperations(), getWorkflowAndManifest(), GetWorkflowAndManifestHandler, initializeTemplateServices, initializeWorkflowMetadata (+47 more)

### Community 77 - "index.tsx"
Cohesion: 0.06
Nodes (53): updateParameterConditionalVisibilityAndRefreshOutputs, useRawInputParameters(), RunAfter(), DataHandling(), DataHandlingSectionProps, General(), GeneralSectionProps, NetworkingSectionProps (+45 more)

### Community 78 - "settings.ts"
Cohesion: 0.08
Nodes (67): areRequestOptionsSupported(), areTrackedPropertiesSupported(), ConcurrencySettings, CorrelationSettings, getAsynchronous(), getConcurrency(), getConditionExpressions(), getCorrelationSettings() (+59 more)

### Community 79 - "connectionselection.tsx"
Cohesion: 0.07
Nodes (33): updateMcpConnection, parseWorkflowParameterValue(), ConnectionSelection(), useConnectionSelectionStyles, isAgentSubgraphFromMetadata(), getOperationsGroupedByReferences(), useAllReferenceKeys(), useAreMappingsInitialized() (+25 more)

### Community 80 - "unitTestSlice.ts"
Cohesion: 0.14
Nodes (22): getFilteredOutputs(), MockResultsTab(), getOperationsState(), AddAssertionPayload, DeleteAssertionsPayload, InitDefintionPayload, OutputMock, UnitTestState (+14 more)

### Community 81 - "nodeDetailsPanel.tsx"
Cohesion: 0.06
Nodes (41): DropTarget(), DropTargetProps, canDropItem(), DropItem, getDownstreamDependencies(), useIsDarkMode(), useSuppressDefaultNodeSelectFunctionality(), AllowDropTarget() (+33 more)

### Community 82 - "ParseReduxAction.ts"
Cohesion: 0.08
Nodes (28): DeserializedWorkflow, initializeDiscoveryPanelFavoriteOperations(), updateWorkflowParameters(), BJSWorkflowProvider(), BJSWorkflowProviderProps, DataProviderInner(), DesignerProviderProps, ProviderWrappedContext (+20 more)

### Community 83 - "index.tsx"
Cohesion: 0.08
Nodes (51): updateParameterConditionalVisibilityAndRefreshOutputs, SettingData, useOperationDownloadChunkMetadata(), useOperationUploadChunkMetadata(), useOutputParameters(), SettingSectionName, SettingsState, initialState (+43 more)

### Community 84 - "useIsA2AWorkflow"
Cohesion: 0.08
Nodes (28): useIsA2AWorkflow(), ActionMenuItem(), DeleteIcon, DeleteMenuItem(), DeleteMenuItemProps, ConnectorIcon(), ConnectorIconProps, useOperationVisuals() (+20 more)

### Community 85 - "openAIConnector.spec.tsx"
Cohesion: 0.11
Nodes (15): capturedOnOptionSelect, defaultProps, mockFetchAccountById, mockFetchAccountKeysById, mockRefetchAPIMAccountApis, mockRefetchAPIMAccounts, mockRefetchServiceAccounts, mockRefetchServiceProjects (+7 more)

### Community 86 - "clonedataprovider.tsx"
Cohesion: 0.16
Nodes (11): CloneServiceOptions, initializeCloneServices, CloneDataProvider(), ExportDataProviderProps, cloneOptionsSlice, initialState, McpOptionsState, initialState (+3 more)

### Community 87 - "DesignerContextualMenu.tsx"
Cohesion: 0.05
Nodes (45): useNodeSelectAdditionalCallback(), useSuppressDefaultNodeSelectFunctionality(), useNodeContextMenuData(), useOperationAlternateSelectedNode(), useOperationAlternateSelectedNodeId(), useCanRedo(), useCanUndo(), useUndoRedoClickToggle() (+37 more)

### Community 88 - "getReactQueryClient"
Cohesion: 0.07
Nodes (56): getAllParametersForWorkflows(), getConnectionsForConsumption(), getConnectionsForStandard(), getDefinitionAndUsedConnectionMappings(), getFeaturedConnectorsForWorkflows(), getTemplateConnections(), getTemplateValidationError, getUpdatedTemplateManifest() (+48 more)

### Community 89 - "operationSelector.ts"
Cohesion: 0.06
Nodes (54): usePanelTabHideKeys(), getNodeOperationData(), getOperationState(), getTopErrorInOperation(), mockDeps, TokenDependencies, useAllOperationErrors(), useDependencies() (+46 more)

### Community 90 - "SubgraphCardNode.spec.tsx"
Cohesion: 0.12
Nodes (15): mockDispatch, mockUseActionMetadata, mockUseIsGraphCollapsed, mockUseIsLeafNode, mockUseMcpClientToolEnabled, mockUseMonitoringView, mockUseNewAdditiveSubgraphId, mockUseNodeDisplayName (+7 more)

### Community 91 - "workflowSelectors.ts"
Cohesion: 0.06
Nodes (51): useOperationsVisuals(), filterOutGraphChildren(), filterOutNodeIdsRecursive(), getAllChildren(), getChildrenOfNodeId(), getParentsUncollapseFromGraphState(), getWorkflowAndOperationState(), getWorkflowGraphPath() (+43 more)

### Community 92 - "designerViewSlice.ts"
Cohesion: 0.50
Nodes (5): DesignerViewState, EdgeContextMenuObject, NodeContextMenuObject, designerViewSlice, initialState

### Community 93 - "operation.ts"
Cohesion: 0.07
Nodes (51): addDefaultSecureSettings(), getTemplateParameters(), getConnectionMappingForNode(), getLegacyConnectionReferenceKey(), getManifestBasedConnectionMapping(), getSwaggerOutputAndTokenData(), NodeInputsWithDependencies, getAllNodeData() (+43 more)

### Community 94 - "configurelogicapps.tsx"
Cohesion: 0.31
Nodes (10): ConfigureLogicApps(), useCloneWorkflowItem(), useSourceItems(), useCloneTabStyles, useSubscriptions(), useResourceStrings(), CloneReviewList(), useDestinationItems() (+2 more)

### Community 95 - "resourcepicker.tsx"
Cohesion: 0.24
Nodes (11): useLocations(), useLogicApps(), useResourceGroups(), ResourceField(), ResourceFieldProps, ResourceFieldRenderType, BaseResourcePickerProps, ResourceKind (+3 more)

### Community 96 - "agentChat.tsx"
Cohesion: 0.06
Nodes (48): fetchBuiltInToolRunData, getAgentActionsRepetition(), getAgentRepetition(), getRun(), parseFailedRepetitions(), queryOpts, runsQueriesKeys, useActionsChatHistory() (+40 more)

### Community 97 - "openAIConnector.tsx"
Cohesion: 0.07
Nodes (44): useSubscriptions(), ConnectionParameterRow(), ConnectionParameterRowParameterRowSelfProps, ConnectionParameterRowProps, ACASessionConnector(), RefreshIcon, SubscriptionDropdown(), SubscriptionDropdownProps (+36 more)

### Community 98 - "store.ts"
Cohesion: 0.11
Nodes (26): updateWorkflowParameter, TemplatePayload, useParameterDefinition(), createQueryClient(), getPersister(), queryKeyDefaultWhitelist, ReactQueryProvider(), ReactQueryProviderProps (+18 more)

### Community 99 - "createConnection.tsx"
Cohesion: 0.06
Nodes (39): needsOAuth(), useTenants(), isA2AKind(), useShouldEnableAPIMGatewayConnection(), ActionListProps, ConnectionActionHeader(), ConnectorActionHeaderProps, CreateConnection() (+31 more)

### Community 100 - "basics.tsx"
Cohesion: 0.22
Nodes (12): ConnectionMultiAuthInputProps, ConnectionParameterProps, UniversalConnectionParameter(), useCreatePanelStyles, Basics(), basicsTab(), comboboxStyles, dropdownStyles (+4 more)

### Community 101 - "operationMetadataSlice.ts"
Cohesion: 0.06
Nodes (39): getRetryPolicy(), SerializedParameter, NodeStaticResults, StaticResultOption, mockGetMyOffice365ProfileOpenApiManifest, mockPostTeamsAdaptiveCardOpenApiManifest, mockSendAnOfficeOutlookEmailOpenApiManifest, makeAgentModelTypeParam() (+31 more)

### Community 102 - "simplecreatereview.tsx"
Cohesion: 0.22
Nodes (10): SuccessToast(), useDefaultSettingsItems(), CreateStatus(), ListResources(), SimpleCreateReview(), toolNameCellStyles, toolTableCellStyles, useCreateReviewStyles (+2 more)

### Community 103 - "global.ts"
Cohesion: 0.10
Nodes (32): AllCustomCodeFiles, CustomCode, CustomCodeWithData, NodeId, ConnectionReferenceMap, connectionSlice, initialConnectionsState, AddCustomCodePayload (+24 more)

### Community 104 - "dynamicdata.ts"
Cohesion: 0.10
Nodes (40): getDynamicSchemaProperties(), getDynamicTreeItems(), getDynamicTreeValueIdFromCollectionDataValue(), getFirstArrayProperty(), getLegacyDynamicSchema(), getLegacyDynamicTreeItems(), getLegacyDynamicValues(), getListDynamicValues() (+32 more)

### Community 105 - "index.ts"
Cohesion: 0.09
Nodes (27): ConnectionActionHeader(), ConnectorActionHeaderProps, clearPendingFoundryUpdate(), consumeVersionRefresh(), flushPendingFoundryUpdates(), hasPendingFoundryUpdates(), needsVersionRefresh(), PendingFoundryUpdate (+19 more)

### Community 106 - "optionsSlice.ts"
Cohesion: 0.27
Nodes (7): initializeData, KnowledgeServiceOptions, KnowledgeDataProvider(), KnowledgeDataProviderProps, initialState, optionsSlice, OptionsState

### Community 107 - "cloneslice.ts"
Cohesion: 0.19
Nodes (9): cloneSlice, CloneState, initialState, SourceWorkflowState, TargetWorkflowState, WorkflowState, RootState, CloneResourcePicker() (+1 more)

### Community 108 - "BJSDeserializer.ts"
Cohesion: 0.09
Nodes (37): UnsupportedException, UnsupportedExceptionCode, Workflow, initializeDiscoveryPanelFavoriteOperations(), updateWorkflowParameters(), BJSWorkflowProvider(), BJSWorkflowProviderProps, DataProviderInner() (+29 more)

### Community 109 - "segment.ts"
Cohesion: 0.08
Nodes (26): ConnectionReferences, deleteCustomCodeInfo(), DeleteGraphPayload, deleteOperationDetails(), DeleteOperationPayload, removeAllTokensFromNode(), findParameterExpressions(), getParameterReferencesFromValue() (+18 more)

### Community 110 - "addNodeToWorkflow.ts"
Cohesion: 0.55
Nodes (10): addAgentToolToWorkflow(), addChildEdge(), addChildNode(), addMcpServerToWorkflow(), addSwitchCaseToWorkflow(), createSubgraphNode(), handleExtraScopeNodeSetup(), createWorkflowEdge() (+2 more)

### Community 111 - "workflowInterfaces.ts"
Cohesion: 0.16
Nodes (13): expectedScopedWorkflowDefinitionOutput, scopedWorkflowDefinitionInput, expectedSimpleWorkflowDefinitionOutput, simpleWorkflowDefinitionInput, expectedSwitchWorkflowDefinitionOutput, expectedSwitchWorkflowDefinitionOutputWithoutAddCase, switchWorkflowDefinitionInput, ErrorMessage (+5 more)

### Community 112 - "useRunData"
Cohesion: 0.07
Nodes (34): ErrorProps, ErrorRun, extractErrorInfo(), getMonitoringError(), getMonitoringTabError(), EXPECTED_EMPTY_ERROR_PROPS, TEST_CODES, TEST_ERROR_RUNS (+26 more)

### Community 113 - "errorsTab.hooks.ts"
Cohesion: 0.10
Nodes (36): deleteWorkflowParameter, useLegacyWorkflowParameters(), useIsDesignerDirty(), useAllConnectionErrors(), useErrorsPanelSelectedTabId(), useFlowErrors(), getWorkflowParametersState(), useIsWorkflowParametersDirty() (+28 more)

### Community 114 - "store.ts"
Cohesion: 0.22
Nodes (7): ExportWizardContext, ExportWizardContextContext, CloneWizardProvider(), ExportWizardProviderProps, AppStore, cloneStandardStore, rootReducer

### Community 116 - "servers.tsx"
Cohesion: 0.29
Nodes (8): AddServerModal(), DeleteModal(), EmptyWorkflowsModal(), MCPServers(), ServerTools(), ToolHandler, useMcpServerStyles, mockWriteClipboard

### Community 117 - "monitoring.ts"
Cohesion: 0.15
Nodes (13): fetchBuiltInToolRunData, getInputsOutputsBinding(), getParametersToBind(), initializeInputsOutputsBinding, InitInputsOutputsPayload, InputsOutputsBinding, mockGetAgentActionsRepetition, mockGetAgentRepetition (+5 more)

### Community 118 - "logicapp.ts"
Cohesion: 0.09
Nodes (40): areProvidersRegistered(), ArmTemplate, ArmTemplateResource, checkDeploymentCreateOperations(), checkDeploymentStatus(), createLogicAppFromTemplate(), DependentResourceDetails, extractErrorInfo() (+32 more)

### Community 119 - "useNodeDisplayName"
Cohesion: 0.09
Nodes (35): deleteGraphNode, deleteMcpServerNode, deleteOperation, removeAgentHandoff, useShowDeleteModalNodeId(), useOperationParameterByName(), useOperationVisuals(), getNodesWithGraphId() (+27 more)

### Community 120 - "helper.ts"
Cohesion: 0.10
Nodes (32): addWorkflowsData, getWorkflowsWithDefinitions(), loadResourceDetailsFromWorkflowSource, saveWorkflowsData, WorkflowTemplateData, ConnectionsAndWorkflowsData, ParametersAndWorkflowsData, useWorkflowsInApp() (+24 more)

### Community 121 - "index.tsx"
Cohesion: 0.31
Nodes (4): CustomDeploymentModelResource(), deploymentModelNameStyle, useDeploymentModelResourceStyles, mockCreateNewDeployment

### Community 122 - "notification.tsx"
Cohesion: 0.32
Nodes (5): NotificationType, ToasterNotification(), ToasterNotificationProps, mockDispatchToast, mockUseToastController

### Community 123 - "helper.spec.ts"
Cohesion: 0.36
Nodes (6): mockExecuteResourceAction, mockLog, createKnowledgeHub(), deleteKnowledgeHubArtifacts(), validateArtifactNameAvailability(), validateHubNameAvailability()

### Community 124 - "AppDispatch"
Cohesion: 0.12
Nodes (25): validateTriggerDescription(), validateWorkflowName(), validateWorkflowsBasicInfo, useExistingWorkflowNames(), AppDispatch, useWorkflowBasicsEditable(), CreateWorkflowPanelHeader(), CreateWorkflowTabProps (+17 more)

### Community 125 - "index.tsx"
Cohesion: 0.11
Nodes (26): useTimelineRepetitionIndex(), parseRepetitions(), TimelineRepetitionWithActions, TimelineRepetition, useTimelineRepetitionCount(), useTimelineRepetitions(), MonitoringTimeline(), useMonitoringTimelineStyles (+18 more)

### Community 126 - "constants.ts"
Cohesion: 0.08
Nodes (30): RFC-3339, RFC-5322, MCP_AUTH_PROPERTY_KEYS, TODO: Prefix the existing profiling events to have this key, SCHEMA, SWAGGER, VARIABLE_TYPE, getTitleOrSummary() (+22 more)

### Community 127 - "templateCard.tsx"
Cohesion: 0.09
Nodes (29): loadCustomTemplateArtifacts, loadTemplate, useFilteredTemplateNames(), getTemplatePublishCategories(), getUniqueConnectorsFromConnections(), BlankWorkflowTemplateCard(), LoadingTemplateCard(), iconStyle (+21 more)

### Community 128 - "gatewayPicker.tsx"
Cohesion: 0.43
Nodes (5): GatewayPicker(), GatewayPickerProps, GatewaysWithNewOption, NewGatewayOption, useGatewayPickerStyles

### Community 129 - "store.ts"
Cohesion: 0.22
Nodes (7): KnowledgeWizardContext, KnowledgeWrappedContext, KnowledgeWizardProvider(), KnowledgeWizardProviderProps, AppStore, knowledgeStore, rootReducer

### Community 130 - "templateoverview.tsx"
Cohesion: 0.12
Nodes (27): isMultiWorkflowTemplate(), useTemplateManifest(), useWorkflowTemplate(), getQuickViewTabs(), getUniqueConnectors(), CreateWorkflowPanel(), CreateWorkflowPanelProps, QuickViewPanel() (+19 more)

### Community 131 - "mcpPanelSlice.ts"
Cohesion: 0.12
Nodes (23): initializeConnectionMappings, initializeOperationsMetadata, useAllManagedConnectors(), useOperationsByConnectorQuery(), initialSelectionState, mcpSelectionSlice, McpSelectionState, ConfigPanelView (+15 more)

### Community 132 - "generatekeys.tsx"
Cohesion: 0.12
Nodes (25): isHttpRequestTrigger(), getHostConfig(), resetQueriesOnServerAuthUpdate(), useMcpAuthentication(), useMcpEligibleWorkflows(), addExpiryToCurrent(), generateKeys(), updateAuthSettings() (+17 more)

### Community 133 - "store.ts"
Cohesion: 0.11
Nodes (23): ConfigPanelView, initialState, KnowledgePanelView, panelSlice, PanelState, AppDispatch, AppStore, rootReducer (+15 more)

### Community 134 - "universalConnectionParameter.tsx"
Cohesion: 0.25
Nodes (4): ClientSecretInputProps, IClientCertificateMetadata, LegacyManagedIdentityDropdown(), LegacyManagedIdentityDropdownProps

### Community 135 - "initialize.spec.ts"
Cohesion: 0.70
Nodes (3): mockGetMyOffice365ProfileOpenApiManifest, mockPostTeamsAdaptiveCardOpenApiManifest, mockSendAnOfficeOutlookEmailOpenApiManifest

### Community 138 - "store.ts"
Cohesion: 0.11
Nodes (22): initializeMcpData, McpServiceOptions, TODO: Initialize dynamic data without user inputs in this section., resetMcpStateOnResourceChange, McpDataProvider(), McpDataProviderProps, McpServerDataProvider(), LogicAppResourceDetails (+14 more)

### Community 139 - "designerOptionsSelectors.ts"
Cohesion: 0.15
Nodes (23): isConnectionRequiredForOperation(), useIsOperationMissingConnection(), useSwagger(), useHostOptions(), QueryResult, useAllowUserToChangeConnection(), useConnectorDescription(), useConnectorDocumentation() (+15 more)

### Community 143 - "edit.tsx"
Cohesion: 0.12
Nodes (24): createOrUpdateConnection(), getAllConnectionParameters(), getConnectionParametersForEdit(), getCosmosDbConnectionParameters(), getOpenAIConnectionParameters(), intl, mockCreateConnection, mockSetQueryData (+16 more)

### Community 149 - "ValueSegmentConvertor"
Cohesion: 0.13
Nodes (6): createExpressionToken(), ValueSegmentConvertor, expectOutputTokenSegment(), expectParameterTokenSegment(), expectVariableTokenSegment(), UncastingUtility

### Community 150 - "undoRedoTypes.ts"
Cohesion: 0.17
Nodes (18): onRedoClick, onUndoClick, storeStateToUndoRedoHistory, initialState, undoRedoSlice, StateHistory, StateHistoryItem, undoableActionTypes (+10 more)

### Community 151 - "connections.ts"
Cohesion: 0.11
Nodes (21): ConnectorWithParsedSwagger, getConnection(), getConnectionFromResource(), getConnectionsForConnector(), getUniqueConnectionName(), useConnectionById(), useConnectionResource(), useNodeConnectionName() (+13 more)

### Community 152 - "ListConnectors.tsx"
Cohesion: 0.13
Nodes (22): deinitializeOperations, useLocation(), useSubscription(), ConnectionDisplayName(), connectorTableCellStyles, lastCellStyles, ListConnectors(), getPricingPlanValue() (+14 more)

### Community 153 - "uploadfile.tsx"
Cohesion: 0.16
Nodes (18): createKnowledgeHub(), deleteKnowledgeHubArtifacts(), validateArtifactNameAvailability(), validateHubNameAvailability(), useAllKnowledgeHubs(), mockExecuteResourceAction, mockLog, CreateGroup() (+10 more)

### Community 154 - "simplecreate.tsx"
Cohesion: 0.17
Nodes (19): validateNameAvailability(), useAppInsights(), useAppServicePlans(), useStorageAccounts(), AppInsightsSelector(), validateAvailability(), AppPlanSelector(), AppPlanSelectorProps (+11 more)

### Community 155 - "knowledgehub.tsx"
Cohesion: 0.16
Nodes (19): DeleteModal(), mockDeleteKnowledgeHubArtifacts, EmptyKnowledgeBaseView(), KnowledgeHubWizard(), NoConnectionsView(), createAllItems(), createArtifactItems(), getArtifactItemsInHub() (+11 more)

### Community 156 - "index.tsx"
Cohesion: 0.12
Nodes (19): getCosmosDbEndpoint(), queryOpts, useConnection(), mockExecuteResourceAction, mockGetConnections, mockGetResource, mockLog, updateNodeMetadataOnParameterUpdate() (+11 more)

### Community 157 - "store.ts"
Cohesion: 0.16
Nodes (16): useExistingWorkflowNamesOfResource(), AppDispatch, AppStore, rootReducer, RootState, initialState, tabSlice, TabState (+8 more)

### Community 158 - "panelSlice.ts"
Cohesion: 0.13
Nodes (12): initialState, panelSlice, ActionPanelFavoriteItem, ConnectionPanelContentState, DiscoveryPanelContentState, ErrorPanelContentState, NodeSearchPanelContentState, OperationPanelContentState (+4 more)

### Community 159 - "agentHarnessTab.tsx"
Cohesion: 0.12
Nodes (19): AgentHarnessData, AgentHarnessInputFile, AgentHarnessSkill, AgentHarnessTab(), ExpressionTokenPill(), extractErrorDetail(), getExpressionTitle(), inputFileColumns (+11 more)

### Community 160 - "role.ts"
Cohesion: 0.15
Nodes (18): appIdentityRoleAssignmentsQueryOpts(), getMissingRoleDefinitions(), queryOpts, resourceRoleDefinitionQueryOpts(), roleDefinitionByNameQueryOpts(), roleQueryKeys, useAppIdentityRoleAssignmentsForResourceQuery(), useHasRoleAssignmentsWritePermissionQuery() (+10 more)

### Community 161 - "useWizardTabs.tsx"
Cohesion: 0.22
Nodes (13): saveTemplateData, ConfigureTemplateWizard(), getSaveMenuButtons(), initialState, tabSlice, TabState, connectionsTab(), TemplateWizardTabProps (+5 more)

### Community 162 - "queries.ts"
Cohesion: 0.19
Nodes (13): getStandardLogicAppId(), AuthType, queryOpts, resetQueriesOnRegisterMcpServer(), useAllMcpServersFromVfs(), useEmptyLogicApps(), LogicAppSelector(), useMcpDetailsStyles (+5 more)

### Community 163 - "EditOperation.tsx"
Cohesion: 0.20
Nodes (15): isDependentStaticParameter(), Snapshot, useEditSnapshot(), useOperationDynamicInputsError(), getGroupIdFromParameterId(), updateParameterAndDependencies, McpPanelRoot(), CloseIcon (+7 more)

### Community 164 - "workflowconnections.tsx"
Cohesion: 0.18
Nodes (18): getConnector(), ConnectorInfo, useConnectorInfo(), CompactConnectorConnectionStatus(), ConnectorIcon(), ConnectorIconWithName(), ConnectorWithDetails(), textStyles (+10 more)

### Community 165 - "delete.ts"
Cohesion: 0.18
Nodes (16): deleteCustomCodeInfo(), DeleteGraphPayload, deleteOperationDetails(), DeleteOperationPayload, removeAllTokensFromNode(), addCastToExpression(), addFoldingCastToExpression(), concatenateAndInterpolateExpressions() (+8 more)

### Community 166 - "mcpservers.tsx"
Cohesion: 0.17
Nodes (9): useAllMcpServers(), McpPanelView, McpServerPanel(), AddServerButtons(), useMcpServerAddStyles, mockUseMcpEligibleWorkflows, EmptyMcpServersView(), McpServersWizard() (+1 more)

### Community 167 - "runafteractiondetails.tsx"
Cohesion: 0.14
Nodes (14): RunAfter(), RunAfterProps, ChevronDownIcon, ChevronRightIcon, DeleteButton(), DeleteButtonProps, DeleteIcon, LabelProps (+6 more)

### Community 168 - "edit.tsx"
Cohesion: 0.13
Nodes (14): CloseIcon, EditConnectionPanel(), queryOpts, useEditPanelStyles, mockConnection, mockCreateOrUpdateConnection, mockGetConnectionParametersForEdit, mockUseConnection (+6 more)

### Community 169 - "connectionTable.tsx"
Cohesion: 0.23
Nodes (12): ConnectionTable(), ConnectionTableDetailsButton(), ConnectionTableDetailsButtonProps, compareFlattenedConnections(), ConnectionWithFlattenedProperties, flattenConnection(), getLabelForConnection(), getSubLabelForConnection() (+4 more)

### Community 170 - "designerViewSlice.ts"
Cohesion: 0.18
Nodes (10): DesignerViewState, EdgeContextMenuObject, NodeContextMenuObject, designerViewSlice, initialState, DraftEdge(), ArrowCap(), HandoffIcon() (+2 more)

### Community 171 - "Binder"
Cohesion: 0.21
Nodes (3): Binder, getDynamicListLookupValue(), getDynamicTreeLookupValue()

### Community 172 - "elklayout.tsx"
Cohesion: 0.15
Nodes (13): convertWorkflowGraphToElkGraph(), defaultLayoutOptions, elk, LayoutContext, LayoutContextType, LayoutProvider(), readOnlyOptions, spacing (+5 more)

### Community 173 - "clonedataprovider.tsx"
Cohesion: 0.17
Nodes (11): CloneServiceOptions, initializeCloneServices, CloneDataProvider(), ExportDataProviderProps, cloneOptionsSlice, initialState, McpOptionsState, initialState (+3 more)

### Community 174 - "inputs.test.ts"
Cohesion: 0.18
Nodes (6): InputsBinder, ManifestInputsBinder, inputParametersByName, nodeParameters, operationMetadata, parsedInputs

### Community 175 - "resourcepicker.tsx"
Cohesion: 0.23
Nodes (12): useAllLogicApps(), useLocations(), useLogicApps(), useResourceGroups(), useSubscriptions(), ResourceField(), ResourceFieldProps, ResourceFieldRenderType (+4 more)

### Community 176 - "DesignerProvider.tsx"
Cohesion: 0.22
Nodes (9): DesignerProviderProps, ReduxReset(), ProviderWrappedContext, DesignerOptionsState, PANEL_TAB_NAMES, ServiceOptions, designerOptionsSlice, initialDesignerOptionsState (+1 more)

### Community 177 - "SubgraphCardNode.spec.tsx"
Cohesion: 0.12
Nodes (15): mockDispatch, mockUseActionMetadata, mockUseIsGraphCollapsed, mockUseIsLeafNode, mockUseMcpClientToolEnabled, mockUseMonitoringView, mockUseNewAdditiveSubgraphId, mockUseNodeDisplayName (+7 more)

### Community 178 - "elklayout.tsx"
Cohesion: 0.20
Nodes (13): convertElkGraphToReactFlow(), convertWorkflowGraphToElkGraph(), defaultLayoutOptions, elk, elkLayout(), LayoutContext, LayoutContextType, LayoutProvider() (+5 more)

### Community 179 - "configurelogicapps.tsx"
Cohesion: 0.34
Nodes (9): useCloneStrings(), ConfigureLogicApps(), useCloneWorkflowItem(), useSourceItems(), useCloneTabStyles, CloneReviewList(), useDestinationItems(), useSourceItems() (+1 more)

### Community 180 - "cloneslice.ts"
Cohesion: 0.23
Nodes (10): getCloneWorkflowName(), getWorkflowResourcesInTemplate(), cloneSlice, CloneState, initialState, SourceWorkflowState, TargetWorkflowState, WorkflowState (+2 more)

### Community 181 - "connections.spec.ts"
Cohesion: 0.18
Nodes (9): isOpenApiConnectionType(), createConnectionUpdateHarness(), harnessInitialState(), mockApiConnection, mockHttp, mockOpenApiConnection, serviceOptions, updateDynamicDataInNodeMock (+1 more)

### Community 182 - "connection.tsx"
Cohesion: 0.22
Nodes (7): initialState, modalSlice, ModalState, DesignerDialog(), CreateConnectionModal(), useConnectionStyles, mockPanelTabs

### Community 183 - "basics.tsx"
Cohesion: 0.33
Nodes (8): Basics(), comboboxStyles, dropdownStyles, getSelectedAuthIndex(), secretFieldStyles, Model(), useCreatePanelStyles, ConnectionMultiAuthInputProps

### Community 184 - "servers.tsx"
Cohesion: 0.26
Nodes (9): AddServerModal(), DeleteModal(), EmptyWorkflowsModal(), MCPServers(), ServerTools(), ToolHandler, useMcpServerStyles, mockWriteClipboard (+1 more)

### Community 185 - "index.ts"
Cohesion: 0.29
Nodes (4): DefaultInputsBinder, parseInputs(), parseOutputs(), DefaultOutputsBinder

### Community 186 - "ServerNotificationData"
Cohesion: 0.27
Nodes (8): initializeData, KnowledgeServiceOptions, KnowledgeDataProvider(), KnowledgeDataProviderProps, initialState, optionsSlice, OptionsState, ServerNotificationData

### Community 187 - "OperationSelectionGrid.tsx"
Cohesion: 0.27
Nodes (8): getDynamicSchemaDependencies(), operationHasEmptyStaticDependencies(), OperationProgress(), getColumnsCount(), OperationCellProps, OperationSelectionGrid(), OperationSelectionGridProps, useOperationSelectionGridStyles

### Community 188 - "triggerDescriptionDialog.tsx"
Cohesion: 0.32
Nodes (9): useIsCombineVariableModalOpen(), useIsTriggerDescriptionModalOpen(), useResolveCombineVariable(), useShouldPromptForTriggerDescription(), useRootTriggerId(), CombineInitializeVariableDialog(), TriggerDescriptionDialog(), TriggerDescriptionDialogProps (+1 more)

### Community 189 - "errors.ts"
Cohesion: 0.24
Nodes (10): TemplateErrors, WorkflowErrors, ApiValidationError, appendToError(), ErrorDetails, ErrorInfoWithTarget, parseValidationError(), TemplateValidationError (+2 more)

### Community 190 - "errors.ts"
Cohesion: 0.27
Nodes (9): TemplateErrors, WorkflowErrors, ApiValidationError, appendToError(), ErrorDetails, ErrorInfoWithTarget, parseValidationError(), TemplateValidationError (+1 more)

### Community 191 - "PerformanceDebug.tsx"
Cohesion: 0.33
Nodes (6): useShowPerformanceDebug(), useReduxActionCounts(), useNodesAndDynamicDataInitialized(), PerformanceDebugTool(), InitializationTimer(), ReduxActionCounts()

### Community 192 - "createhelper.ts"
Cohesion: 0.47
Nodes (8): isOpenApiSchemaVersion(), alterOperationConnectionReference(), convertDesignerWorkflowToConsumptionWorkflow(), getConsumptionWorkflowPayloadForCreate(), isBuiltInMcpConnectionReference(), replaceWorkflowIdentifier(), traverseDefinition(), updateConnectionsDataWithNewConnections()

### Community 193 - "redux-test-helper.tsx"
Cohesion: 0.31
Nodes (6): AppStore, ExtendedRenderOptions, renderWithRedux(), intlOnError, queryClient, mockIsDarkMode

### Community 194 - "notification.tsx"
Cohesion: 0.36
Nodes (6): getToastIntent(), NotificationType, ToasterNotification(), ToasterNotificationProps, mockDispatchToast, mockUseToastController

### Community 195 - "deploymentModelResource.tsx"
Cohesion: 0.39
Nodes (4): CustomDeploymentModelResource(), deploymentModelNameStyle, useDeploymentModelResourceStyles, mockCreateNewDeployment

### Community 197 - "clonewizardprovider.tsx"
Cohesion: 0.33
Nodes (5): ExportWizardContext, ExportWizardContextContext, CloneWizardProvider(), ExportWizardProviderProps, cloneStandardStore

### Community 198 - "KnowledgeWizardProvider.tsx"
Cohesion: 0.33
Nodes (5): KnowledgeWizardContext, KnowledgeWrappedContext, KnowledgeWizardProvider(), KnowledgeWizardProviderProps, knowledgeStore

### Community 200 - "gatewayPicker.tsx"
Cohesion: 0.43
Nodes (5): GatewayPicker(), GatewayPickerProps, GatewaysWithNewOption, NewGatewayOption, useGatewayPickerStyles

### Community 201 - "DesignerReactFlow.spec.tsx"
Cohesion: 0.29
Nodes (5): capturedReactFlowProps, mockAllAgentIds, mockDisconnectedNodes, mockDispatch, mockNodesMetadata

### Community 202 - "cosmosConnector.spec.tsx"
Cohesion: 0.29
Nodes (5): defaultProps, mockExecuteResourceAction, mockRefetch, mockUseAllCosmosDbServiceAccounts, mockUseSubscriptions

### Community 204 - "ConnectorBrowseView.tsx"
Cohesion: 0.53
Nodes (5): ConnectorBrowseView(), ConnectorBrowseViewProps, matchesSearch(), sortConnectors(), supportsActions()

### Community 207 - "clientSecretInput.tsx"
Cohesion: 0.50
Nodes (4): ClientSecretInput(), ClientSecretInputProps, getBase64String(), IClientCertificateMetadata

## Knowledge Gaps
- **1188 isolated node(s):** `cache`, `intl`, `SCHEMA`, `SWAGGER`, `VARIABLE_TYPE` (+1183 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **21 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `getReactQueryClient()` connect `getReactQueryClient` to `generatekeys.tsx`, `store.ts`, `initialize.ts`, `edit.tsx`, `helper.ts`, `connections.ts`, `index.tsx`, `role.ts`, `queries.ts`, `workflowconnections.tsx`, `mcpservers.tsx`, `connections.ts`, `index.tsx`, `cloneslice.ts`, `connections.spec.ts`, `redux-test-helper.tsx`, `index.ts`, `operation.ts`, `agentChat.tsx`, `store.ts`, `operationMetadataSlice.ts`, `dynamicdata.ts`, `logicapp.ts`?**
  _High betweenness centrality (0.020) - this node is a cross-community bridge._
- **Why does `ManifestOutputsBinder` connect `outputs.test.ts` to `Binder`?**
  _High betweenness centrality (0.010) - this node is a cross-community bridge._
- **Why does `getReactQueryClient()` connect `getReactQueryClient` to `helper.ts`, `initialize.ts`, `connections.ts`, `operation.ts`, `generatekeys.tsx`, `templates.ts`, `index.tsx`, `logicapp.ts`, `dynamicdata.ts`, `agentChat.tsx`, `edit.tsx`, `constants.ts`, `EdgeContextualMenu.tsx`, `panelSelectors.ts`, `mcpservers.tsx`, `mcp.ts`, `serializer.ts`, `role.ts`, `usepaneltabs.tsx`, `ParseReduxAction.ts`, `index.ts`?**
  _High betweenness centrality (0.007) - this node is a cross-community bridge._
- **Are the 16 inferred relationships involving `getReactQueryClient()` (e.g. with `getAllAppInsights()` and `getAllWorkspaces()`) actually correct?**
  _`getReactQueryClient()` has 16 INFERRED edges - model-reasoned connections that need verification._
- **What connects `cache`, `intl`, `SCHEMA` to the rest of the system?**
  _1188 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `DesignerContextualMenu.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.08199643493761141 - nodes in this community are weakly interconnected._
- **Should `helper.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.0442002442002442 - nodes in this community are weakly interconnected._