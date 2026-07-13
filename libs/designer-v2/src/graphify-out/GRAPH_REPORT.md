# Graph Report - src  (2026-07-13)

## Corpus Check
- 714 files · ~398,028 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 7434 nodes · 23671 edges · 201 communities (180 shown, 21 thin omitted)
- Extraction: 99% EXTRACTED · 1% INFERRED · 0% AMBIGUOUS · INFERRED: 186 edges (avg confidence: 0.6)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `f4e3a3f2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- helper.ts
- OperationCardNode.tsx
- constants.ts
- DesignerContextualMenu.tsx
- initialize.ts
- initialize.ts
- createConnection.tsx
- serializer.ts
- index.tsx
- connectionSelector.ts
- settings.ts
- templateoverview.tsx
- workflowSlice.ts
- workflowSelectors.ts
- helper.ts
- store.ts
- runs.ts
- errorsTab.hooks.ts
- templateselectors.ts
- global.ts
- constants.ts
- useTemplatesStrings
- operationSelector.ts
- templates.ts
- index.tsx
- usePanelTabs.spec.tsx
- triggerDescriptionDialog.tsx
- index.tsx
- index.ts
- undoRedoTypes.ts
- OperationCardNode.spec.tsx
- templateCard.tsx
- workflowInterfaces.ts
- loops.ts
- DesignerReactFlow.tsx
- designerOptionsSelectors.ts
- panelSelectors.ts
- elklayout.tsx
- panelSlice.ts
- openAIConnector.tsx
- designerOptionsSelectors.ts
- designerViewSelectors.ts
- AppDispatch
- workflowSlice.ts
- workflowSelectors.ts
- panelSelectors.ts
- ScopeCardNode.spec.tsx
- DefaultSearchOperationsService
- BJSDeserializer.ts
- operationSelector.ts
- Binder
- index.ts
- add.ts
- helper.ts
- serializer.ts
- actionCard.tsx
- agentHarnessTab.tsx
- actionMetadataSelector.ts
- workflowNode.ts
- Designer.tsx
- loops.ts
- Designer.tsx
- store.ts
- helper.ts
- store.ts
- configuretemplate.ts
- wrapInScope.ts
- DesignerContextualMenu.tsx
- settings.ts
- role.ts
- SubgraphCardNode.spec.tsx
- index.tsx
- operationMetadataSlice.ts
- mcpPanelSlice.ts
- chat.tsx
- index.tsx
- configuretemplate.ts
- index.tsx
- RootState
- templates.ts
- unitTestSlice.ts
- workflowconnections.tsx
- helper.ts
- store.ts
- McpDataProvider.tsx
- useTemplatesStrings
- Test Coverage
- McpWizard.tsx
- DesignerProvider.tsx
- index.tsx
- Utils.ts
- helper.ts
- SelectOperations.tsx
- devSlice.ts
- usePanelTabs.tsx
- TokenSegmentConvertor
- useOperationVisuals
- dropTarget.tsx
- agentChat.spec.tsx
- resourcepicker.tsx
- AppDispatch
- WorkflowTemplateData
- index.tsx
- inputsbuilder.ts
- OperationSelectionGrid.tsx
- OperationCardNode.spec.tsx
- dynamicdata.ts
- ParseReduxAction.ts
- logicAppSelector.tsx
- createConnection.tsx
- UncastingUtility
- error.test.ts
- actionCard.tsx
- workflowconnections.tsx
- addNodeToWorkflow.ts
- DesignerReactFlow.spec.tsx
- EditOperationPanel.tsx
- deploymentModelResource.tsx
- validation.ts
- errorbar.spec.tsx
- monitoring.spec.ts
- ScopeCardNode.spec.tsx
- ValueSegmentConvertor
- gatewayPicker.tsx
- RootState
- openAIConnector.tsx
- useWizardTabs.tsx
- JsonSplitter
- agentHarnessTab.tsx
- mcpselectionslice.ts
- index.tsx
- settingsection.tsx
- createConnectionInternal.tsx
- trafficlightsvgs.tsx
- onlyEdge.tsx
- iFrameTOS.tsx
- gripper.tsx
- mcpOptionsInterface.ts
- typings.d.ts
- Svg.d.ts
- store.ts
- role.ts
- useCognitiveService.ts
- general.tsx
- outputs.test.ts
- SubgraphCardNode.spec.tsx
- mcp.ts
- EditOperation.tsx
- index.tsx
- errorsTab.hooks.ts
- McpWizard.tsx
- mcpPanelSlice.ts
- index.tsx
- chat.tsx
- createConnection.spec.tsx
- openAIConnector.spec.tsx
- DesignerProvider.tsx
- elklayout.tsx
- Binder
- Test Coverage
- connectionTable.tsx
- monitoringTab.tsx
- monitoring.ts
- workflowparametersselector.ts
- index.tsx
- errorsPanel.tsx
- inputs.test.ts
- agentChat.spec.tsx
- customcodeSlice.ts
- foundryUpdates.ts
- store.ts
- OperationSelectionGrid.tsx
- parametereditor.tsx
- updateParameterWithValues
- workflowparametersselector.ts
- error.test.ts
- index.ts
- PerformanceDebug.tsx
- DesignerReactFlow.spec.tsx
- settingDefaults.ts
- deploymentModelResource.tsx
- errorbar.spec.tsx
- runHistoryEntry.spec.tsx
- helper.ts
- ApiConnectionInputsBinder
- JsonSplitter
- edge.spec.tsx
- gatewayPicker.tsx
- DefaultSearchOperationsService
- logicAppSelector.tsx
- clientSecretInput.tsx
- trafficlightsvgs.tsx
- gripper.tsx
- onlyEdge.tsx
- iFrameTOS.tsx
- workflowParameterErrors.tsx
- mcpOptionsInterface.ts

## God Nodes (most connected - your core abstractions)
1. `getReactQueryClient()` - 75 edges
2. `RootState` - 75 edges
3. `RootState` - 74 edges
4. `getReactQueryClient()` - 70 edges
5. `AppDispatch` - 63 edges
6. `AppDispatch` - 62 edges
7. `RootState` - 59 edges
8. `RootState` - 59 edges
9. `getOperationSettings()` - 57 edges
10. `getOperationSettings()` - 57 edges

## Surprising Connections (you probably didn't know these)
- `InitialWorkflowState` --references--> `ConnectionReferences`  [EXTRACTED]
  src/lib/core/state/templates/workflowSlice.ts → src/lib/common/models/workflow.ts
- `ReduxReset()` --calls--> `resetWorkflowState`  [EXTRACTED]
  src/lib/core/DesignerProvider.tsx → src/lib/core/state/global.ts
- `getRunRepetition()` --calls--> `getReactQueryClient()`  [EXTRACTED]
  src/lib/core/queries/runs.ts → src/lib/core/ReactQueryProvider.tsx
- `deleteCustomCodeInfo()` --calls--> `getParameterFromName()`  [EXTRACTED]
  src/lib/core/actions/bjsworkflow/delete.ts → src/lib/core/utils/parameters/helper.ts
- `getParameterReferencesFromValue()` --indirect_call--> `isTokenValueSegment()`  [INFERRED]
  src/lib/core/configuretemplate/utils/helper.ts → src/lib/core/utils/parameters/segment.ts

## Import Cycles
- 1-file cycle: `lib/core/mcp/utils/queries.ts -> lib/core/mcp/utils/queries.ts`
- 3-file cycle: `lib/core/actions/bjsworkflow/monitoring.ts -> lib/core/index.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/monitoring.ts`
- 3-file cycle: `lib/core/actions/bjsworkflow/mcp.ts -> lib/core/state/mcp/store.ts -> lib/core/state/mcp/mcpselectionslice.ts -> lib/core/actions/bjsworkflow/mcp.ts`
- 3-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/usePanelTabs.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/tabs/reviewCreateTab.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 3-file cycle: `lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/usePanelTabs.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/tabs/customizeWorkflowsTab.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx`
- 3-file cycle: `lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/usePanelTabs.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/tabs/selectWorkflowsTab.tsx -> lib/ui/configuretemplate/panels/configureWorkflowsPanel/configureWorkflowsPanel.tsx`
- 3-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/templates/index.tsx -> lib/ui/templates/templateview.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 3-file cycle: `lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/usePanelTabs.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/tabs/basicsTab.tsx -> lib/ui/panel/templatePanel/createWorkflowPanel/createWorkflowPanel.tsx`
- 3-file cycle: `lib/core/state/customcode/customcodeSlice.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/customcode/customcodeSlice.ts`
- 3-file cycle: `lib/core/actions/bjsworkflow/templates.ts -> lib/core/state/templates/store.ts -> lib/core/state/templates/templateOptionsSlice.ts -> lib/core/actions/bjsworkflow/templates.ts`
- 3-file cycle: `lib/core/actions/bjsworkflow/templates.ts -> lib/core/state/templates/templateSlice.ts -> lib/core/configuretemplate/utils/errors.ts -> lib/core/actions/bjsworkflow/templates.ts`
- 3-file cycle: `lib/core/state/global.ts -> lib/core/state/notes/notesSelectors.ts -> lib/core/state/notes/notesSlice.ts -> lib/core/state/global.ts`
- 3-file cycle: `lib/core/state/notes/notesSlice.ts -> lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/state/notes/notesSlice.ts`
- 3-file cycle: `lib/core/state/undoRedo/undoRedoTypes.ts -> lib/core/store.ts -> lib/core/utils/middleware.ts -> lib/core/state/undoRedo/undoRedoTypes.ts`
- 3-file cycle: `lib/core/store.ts -> lib/core/utils/middleware.ts -> lib/core/utils/undoredo.ts -> lib/core/store.ts`
- 4-file cycle: `lib/core/actions/bjsworkflow/initialize.ts -> lib/core/store.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/monitoring.ts -> lib/core/actions/bjsworkflow/initialize.ts`
- 4-file cycle: `lib/core/BJSWorkflowProvider.tsx -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/monitoring.ts -> lib/core/index.ts -> lib/core/BJSWorkflowProvider.tsx`
- 4-file cycle: `lib/core/actions/bjsworkflow/add.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/monitoring.ts -> lib/core/index.ts -> lib/core/actions/bjsworkflow/add.ts`
- 4-file cycle: `lib/core/actions/bjsworkflow/agent.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/monitoring.ts -> lib/core/index.ts -> lib/core/actions/bjsworkflow/agent.ts`
- 4-file cycle: `lib/core/actions/bjsworkflow/monitoring.ts -> lib/core/index.ts -> lib/core/store.ts -> lib/core/state/workflow/workflowSlice.ts -> lib/core/actions/bjsworkflow/monitoring.ts`

## Communities (201 total, 21 thin omitted)

### Community 0 - "helper.ts"
Cohesion: 0.03
Nodes (148): deleteCustomCodeInfo(), DeleteGraphPayload, deleteMcpServerNode, deleteOperationDetails(), DeleteOperationPayload, DeleteOperationsPayload, removeAllTokensFromNode(), ParameterEditor() (+140 more)

### Community 1 - "OperationCardNode.tsx"
Cohesion: 0.05
Nodes (84): moveOperation, DropZone, ButtonEdge(), EdgeContentProps, LogicAppsEdgeProps, EdgeContentProps, HandoffEdge(), LogicAppsEdgeProps (+76 more)

### Community 2 - "constants.ts"
Cohesion: 0.04
Nodes (80): autoCreateConnectionIfPossible(), ConnectionPayload, connectorHasMultiAuth(), getApiHubAuthentication(), getApiHubAuthenticationIfRequired(), getConnectionMappingForNode(), getConnectionReferenceKeyForManifest(), getConnectionsApiAndMapping() (+72 more)

### Community 3 - "DesignerContextualMenu.tsx"
Cohesion: 0.04
Nodes (53): copyOperation, copyScopeOperation, shouldDisplayRunAfter(), CopyTooltip(), CopyTooltipProps, BulkCopyIcon, BulkCutIcon, BulkDeleteIcon (+45 more)

### Community 4 - "initialize.ts"
Cohesion: 0.04
Nodes (121): AddOperationPayload, addTokensAndVariables(), getNonDuplicateId(), getNonDuplicateNodeId(), getTriggerNodeManifest(), initializeOperationDetails(), initializeSubgraphFromManifest(), tryGetMostRecentlyUsedConnectionId() (+113 more)

### Community 5 - "initialize.ts"
Cohesion: 0.04
Nodes (145): addDefaultSecureSettings(), addTokensAndVariables(), getTriggerNodeManifest(), initializeOperationDetails(), AddConnectorAsOpreationPayload, ConnectorManifest, createNodeData(), initializeConnectorOperationDetails() (+137 more)

### Community 6 - "createConnection.tsx"
Cohesion: 0.06
Nodes (34): ActionList(), ActionListProps, ConnectionActionHeader(), ConnectorActionHeaderProps, needsOAuth(), useTenants(), CreateConnection(), CreateConnectionProps (+26 more)

### Community 7 - "serializer.ts"
Cohesion: 0.04
Nodes (94): AgentConnectionInfo, ApiManagementConnectionInfo, constructInputValues(), FunctionConnectionInfo, getActions(), getAssertions(), getOperationInputsToSerialize(), getRetryPolicy() (+86 more)

### Community 8 - "index.tsx"
Cohesion: 0.04
Nodes (66): NodeStaticResults, StaticResultOption, AppStore, RootState, Window, getCognitiveServiceAccountDeploymentsForConnection(), AddDynamicInputsPayload, AddDynamicOutputsPayload (+58 more)

### Community 9 - "connectionSelector.ts"
Cohesion: 0.11
Nodes (43): AllConnections(), ConnectorCardWrapper(), ConnectorCardWrapperProps, AllConnectionsEmptyState(), closeConnectionsFlow, getConnectionMetadata(), reloadParametersTab, updateNodeConnection (+35 more)

### Community 10 - "settings.ts"
Cohesion: 0.09
Nodes (63): areRequestOptionsSupported(), areTrackedPropertiesSupported(), ConcurrencySettings, CorrelationSettings, getAsynchronous(), getConcurrency(), getConditionExpressions(), getCorrelationSettings() (+55 more)

### Community 11 - "templateoverview.tsx"
Cohesion: 0.14
Nodes (18): isMultiWorkflowTemplate(), loadTemplate, CreateWorkflowPanelProps, TemplateDetailFilterType, TemplatesFullGalleryView(), QuickViewPanel(), QuickViewPanelHeader(), QuickViewPanelProps (+10 more)

### Community 12 - "workflowSlice.ts"
Cohesion: 0.04
Nodes (107): UnsupportedException, UnsupportedExceptionCode, initializeInputsOutputsBinding, isWorkflowOperationNode(), ScopeDefinition, scopeDefinitions, WrapScopeType, WrapSelectedNodesPayload (+99 more)

### Community 13 - "workflowSelectors.ts"
Cohesion: 0.03
Nodes (74): deleteGraphNode, deleteOperation, addAgentHandoff, AddAgentHandoffPayload, removeAgentHandoff, RemoveAgentHandoffPayload, storeStateToUndoRedoHistory, CollapsedNode() (+66 more)

### Community 14 - "helper.ts"
Cohesion: 0.03
Nodes (131): deleteCustomCodeInfo(), DeleteGraphPayload, deleteMcpServerNode, deleteOperationDetails(), DeleteOperationPayload, DeleteOperationsPayload, removeAllTokensFromNode(), updateTokenMetadataInParameters() (+123 more)

### Community 15 - "store.ts"
Cohesion: 0.10
Nodes (22): saveWorkflowsData, updateWorkflowParameter, TemplatePayload, ReactQueryProvider(), DisplayParameters(), ParametersPanel(), ConfigPanelView, initialState (+14 more)

### Community 16 - "runs.ts"
Cohesion: 0.04
Nodes (73): AgentChat(), AgentChatProps, parseChatHistory(), useRefreshChatMutation(), fetchBuiltInToolRunData, useIsFirstDesignerV2Load(), useMonitoringView(), useWorkflowHasAgentLoop() (+65 more)

### Community 17 - "errorsTab.hooks.ts"
Cohesion: 0.10
Nodes (36): ConnectionEntry(), ConnectionEntryProps, ConnectorConnectionsCard(), ConnectorConnectionsCardProps, ConnectionDisplayName(), CollapseIcon, ErrorCategory(), ErrorCategoryProps (+28 more)

### Community 18 - "templateselectors.ts"
Cohesion: 0.16
Nodes (17): ResourceSection(), ResourceSectionProps, useStyles, WorkflowName(), WorkflowTriggerDescription(), ReviewAddPanel(), ReviewCreatePanelProps, SummaryPanel() (+9 more)

### Community 19 - "global.ts"
Cohesion: 0.11
Nodes (27): initialConnectionsState, useNotesChangeCount(), initialState, notesSlice, updateExistingInputTokenTitles(), SettingSectionName, SettingsState, initialState (+19 more)

### Community 20 - "constants.ts"
Cohesion: 0.04
Nodes (89): isManagedMcpConnector(), MCP_AUTH_PROPERTY_KEYS, TODO: Prefix the existing profiling events to have this key, SCHEMA, SWAGGER, VARIABLE_TYPE, AllCustomCodeFiles, CustomCode (+81 more)

### Community 21 - "useTemplatesStrings"
Cohesion: 0.08
Nodes (42): DescriptionWithLink(), ErrorBar(), tableHeaderStyle, useParameterDefinition(), getLogicAppsCategories(), useResourceStrings(), InfoToastContent(), TemplateInfoToast() (+34 more)

### Community 22 - "operationSelector.ts"
Cohesion: 0.05
Nodes (43): DropTarget(), DropTargetProps, canDropItem(), DropItem, getDownstreamDependencies(), AllowDropTarget(), AllowDropTargetProps, BlockDropTarget() (+35 more)

### Community 23 - "templates.ts"
Cohesion: 0.06
Nodes (49): ConfigureTemplateServiceOptions, initializeConfigureTemplateServices, loadCustomTemplate, getWorkflowAndManifest(), GetWorkflowAndManifestHandler, initializeTemplateServices, initializeWorkflowMetadata, loadCustomTemplates (+41 more)

### Community 24 - "index.tsx"
Cohesion: 0.10
Nodes (28): ConnectorIcon(), ConnectorIconProps, parseRepetitions(), TimelineRepetitionWithActions, TimelineRepetition, useTimelineRepetitionCount(), useTimelineRepetitions(), MonitoringTimeline() (+20 more)

### Community 25 - "usePanelTabs.spec.tsx"
Cohesion: 0.47
Nodes (4): createStore(), mocks, renderTabs(), wrapper()

### Community 26 - "triggerDescriptionDialog.tsx"
Cohesion: 0.38
Nodes (7): CombineInitializeVariableDialog(), TriggerDescriptionDialog(), TriggerDescriptionDialogProps, useIsCombineVariableModalOpen(), useIsTriggerDescriptionModalOpen(), useResolveCombineVariable(), useShouldPromptForTriggerDescription()

### Community 27 - "index.tsx"
Cohesion: 0.13
Nodes (20): isAgentSubgraphFromMetadata(), WorkflowParameter, AgentUtils, getSKUDefaultHostOptions(), isDynamicConnection(), isOpenApiSchemaVersion(), titleCase(), suffixConnectionsWithIdentifier() (+12 more)

### Community 28 - "index.ts"
Cohesion: 0.10
Nodes (24): NodeLinkButton(), addConnectorAsOperation, clearPendingFoundryUpdate(), consumeVersionRefresh(), flushPendingFoundryUpdates(), getPendingFoundryUpdate(), hasPendingFoundryUpdates(), needsVersionRefresh() (+16 more)

### Community 29 - "undoRedoTypes.ts"
Cohesion: 0.12
Nodes (27): onRedoClick, onUndoClick, getMockedInitialRootState(), initialState, undoRedoSlice, CompressedSliceMap, StateHistory, StateHistoryItem (+19 more)

### Community 30 - "OperationCardNode.spec.tsx"
Cohesion: 0.05
Nodes (36): mockDispatch, mockUseActionMetadata, mockUseAllOperations, mockUseConnectorName, mockUseFlowErrorsForNode, mockUseIsA2AWorkflow, mockUseIsCopilotModifiedNode, mockUseIsLeafNode (+28 more)

### Community 31 - "templateCard.tsx"
Cohesion: 0.09
Nodes (27): loadCustomTemplateArtifacts, BlankWorkflowTemplateCard(), LoadingTemplateCard(), iconStyle, TemplateCard(), templateCardBodyStyles, TemplateCardProps, templateCardStyles (+19 more)

### Community 32 - "workflowInterfaces.ts"
Cohesion: 0.12
Nodes (17): initialState, mockGraph, WorkflowNode, AddNodePayload, UpdateAgenticGraphPayload, updateAgenticSubgraph(), mockReassignEdgeSources, mockRemoveEdge (+9 more)

### Community 33 - "loops.ts"
Cohesion: 0.05
Nodes (60): AssertionsPanel(), getVariableTokens(), useTokens(), getLoopsCount(), getRepetitionName(), getFilteredOutputs(), MockResultsTab(), isWorkflowGraph() (+52 more)

### Community 34 - "DesignerReactFlow.tsx"
Cohesion: 0.05
Nodes (53): pasteOperation, pasteScopeOperation, addOperationRunAfter, EdgeRunAfterPayload, removeOperationRunAfter, DraftEdge(), DropZoneProps, HiddenEdge() (+45 more)

### Community 35 - "designerOptionsSelectors.ts"
Cohesion: 0.09
Nodes (21): useAddButtonStyles, AddButton(), AddButtonProps, Plus(), AgentChatHeader(), AgentChatHeaderProps, CollapseIcon, RefreshIcon (+13 more)

### Community 36 - "panelSelectors.ts"
Cohesion: 0.03
Nodes (130): addOperation, BrowseView(), BrowseViewProps, CategoryCard(), CategoryCardProps, ConnectorBrowse(), ConnectorBrowseProps, priorityConnectors (+122 more)

### Community 37 - "elklayout.tsx"
Cohesion: 0.15
Nodes (12): convertWorkflowGraphToElkGraph(), defaultLayoutOptions, elk, exportForTesting, LayoutContext, LayoutContextType, readOnlyOptions, spacing (+4 more)

### Community 38 - "panelSlice.ts"
Cohesion: 0.06
Nodes (40): mcpConnectionParameterSets, McpToolWizard(), useMcpWizardAllowedTools(), useMcpWizardConnectionId(), useMcpWizardHeaders(), useMcpWizardOperation(), useMcpWizardStep(), initialState (+32 more)

### Community 39 - "openAIConnector.tsx"
Cohesion: 0.06
Nodes (40): SubscriptionDropdown(), SubscriptionDropdownProps, useSubscriptions(), ConnectionParameterRow(), ConnectionParameterRowParameterRowSelfProps, ConnectionParameterRowProps, ACASessionConnector(), RefreshIcon (+32 more)

### Community 40 - "designerOptionsSelectors.ts"
Cohesion: 0.03
Nodes (100): filterOperationsByConnector(), filterOperationsFromList(), isManagedConnector(), pagedOpts, queryOpts, useAllActions(), useAllConnectors(), useAllOperations() (+92 more)

### Community 41 - "designerViewSelectors.ts"
Cohesion: 0.04
Nodes (91): fetchBuiltInToolRunData, fetchAgentActionsRepetition(), getAgentActionsRepetition(), getAgentRepetition(), getAgentRepetitions(), getNodeRepetitions(), getRun(), getRunRepetition() (+83 more)

### Community 42 - "AppDispatch"
Cohesion: 0.15
Nodes (14): addWorkflowsData, deleteWorkflowData, saveTemplateData, ConfigureTemplateWizard(), summaryTab(), TemplateWizardTabProps, profileTab(), useConfigureTemplateWizardTabs() (+6 more)

### Community 43 - "workflowSlice.ts"
Cohesion: 0.26
Nodes (17): isWorkflowOperationNode(), addNodeToWorkflow(), deleteMcpServerNodeFromWorkflow(), deleteNodeFromWorkflow(), DeleteNodePayload, deleteWorkflowNode(), moveNodeInWorkflow(), pasteScopeInWorkflow() (+9 more)

### Community 44 - "workflowSelectors.ts"
Cohesion: 0.03
Nodes (103): pasteOperation, pasteScopeOperation, addAgentHandoff, removeAgentHandoff, addOperationRunAfter, removeOperationRunAfter, useIsDraggingNode(), useClampPan() (+95 more)

### Community 45 - "panelSelectors.ts"
Cohesion: 0.04
Nodes (90): addOperation, useConnectionResource(), getPanelState(), useCurrentPanelMode(), useDiscoveryPanelFavoriteOperations(), useDiscoveryPanelIsOperationFavorited(), useDiscoveryPanelRelationshipIds(), useDiscoveryPanelSearchTerm() (+82 more)

### Community 46 - "ScopeCardNode.spec.tsx"
Cohesion: 0.07
Nodes (29): mockDispatch, mockUseActionMetadata, mockUseAllOperations, mockUseBrandColor, mockUseConnectorName, mockUseFlowErrorsForNode, mockUseHandoffActionsForAgent, mockUseIconUri (+21 more)

### Community 48 - "BJSDeserializer.ts"
Cohesion: 0.07
Nodes (45): addActionsInstanceMetaData(), addTriggerInstanceMetaData(), buildGraphFromActions(), Deserialize(), DeserializedWorkflow, deserializeUnitTestDefinition(), flattenObject(), getAllActionNames() (+37 more)

### Community 49 - "operationSelector.ts"
Cohesion: 0.06
Nodes (86): copyScopeOperation, moveOperation, useNodeRepetition(), useMonitoringView(), useNodeSelectAdditionalCallback(), useReadOnly(), getOperationState(), getTopErrorInOperation() (+78 more)

### Community 50 - "Binder"
Cohesion: 0.05
Nodes (20): Binder, getDynamicListLookupValue(), getDynamicTreeLookupValue(), InputsBinder, ApiConnectionInputsBinder, DefaultInputsBinder, ManifestInputsBinder, parseInputs() (+12 more)

### Community 51 - "index.ts"
Cohesion: 0.06
Nodes (82): useIsAgentSubGraph(), addConnectorAsOperation, autoCreateConnectionIfPossible(), closeConnectionsFlow, getConnectionMetadata(), hasOnlyOAuthParameters(), reloadParametersTab, updateNodeConnection (+74 more)

### Community 52 - "add.ts"
Cohesion: 0.04
Nodes (78): ApiHubAuthentication, AddOperationPayload, TODO: This seems redundant now since in line: 143 outputs are already updated wi, NOTE: If no connection is available from local storage, first connection will be, tryGetMostRecentlyUsedConnectionId(), trySetDefaultConnectionForNode(), ConnectionPayload, connectorHasMultiAuth() (+70 more)

### Community 53 - "helper.ts"
Cohesion: 0.05
Nodes (66): isMultiWorkflowTemplate(), loadCustomTemplateArtifacts, loadTemplate, useFilteredTemplateNames(), useTemplateManifest(), useWorkflowTemplate(), validateParameter(), checkWorkflowNameWithRegex() (+58 more)

### Community 54 - "serializer.ts"
Cohesion: 0.05
Nodes (69): AgentConnectionInfo, ApiManagementConnectionInfo, constructInputValues(), FunctionConnectionInfo, getActions(), getOperationInputsToSerialize(), getRetryPolicy(), getRunAfter() (+61 more)

### Community 55 - "actionCard.tsx"
Cohesion: 0.17
Nodes (15): ActionCard(), ActionCardProps, colors, useCardStyles, CardErrorBadge(), CardRunStatusBadge(), ChevronDown, ChevronUp (+7 more)

### Community 56 - "agentHarnessTab.tsx"
Cohesion: 0.12
Nodes (19): AgentHarnessData, AgentHarnessInputFile, AgentHarnessSkill, AgentHarnessTab(), ExpressionTokenPill(), extractErrorDetail(), getExpressionTitle(), inputFileColumns (+11 more)

### Community 57 - "actionMetadataSelector.ts"
Cohesion: 0.28
Nodes (14): useSwagger(), QueryResult, useConnectorDescription(), useConnectorDocumentation(), useConnectorEnvironmentBadge(), useConnectorName(), useConnectorStatusBadge(), useNodeAttribute() (+6 more)

### Community 58 - "workflowNode.ts"
Cohesion: 0.14
Nodes (13): WorkflowEdge, flattenWorkflowNodes(), updateChildrenDimensions(), agentMcpWorkflowDefinitionInput, expectedAgentMcpWorkflowDefinitionOutput, expectedScopedWorkflowDefinitionOutput, scopedWorkflowDefinitionInput, expectedSimpleWorkflowDefinitionOutput (+5 more)

### Community 59 - "Designer.tsx"
Cohesion: 0.05
Nodes (61): copyOperation, copyOperations, cutOperations, duplicateOperations, deleteGraphNode, deleteOperation, deleteOperations, onRedoClick (+53 more)

### Community 60 - "loops.ts"
Cohesion: 0.05
Nodes (62): initializeRepetitionInfos(), isWorkflowGraph(), getAllNodesInsideNode(), getAllSourceNodeIds(), getTriggerNodeId(), getUpstreamNodeIds(), buildSegmentPath(), checkArrayInRepetition() (+54 more)

### Community 61 - "Designer.tsx"
Cohesion: 0.04
Nodes (66): copyOperations, cutOperations, duplicateOperations, deleteOperations, CollapseExpandControl(), MultiSelectDeleteModal(), MultiSelectDeleteTag(), useMultiSelectDeleteModalStyles (+58 more)

### Community 62 - "store.ts"
Cohesion: 0.11
Nodes (14): ExportDataProvider(), ExportDataProviderProps, ExportWizardContext, ExportWizardContextContext, ExportWizardProvider(), ExportWizardProviderProps, initialState, resourceSlice (+6 more)

### Community 63 - "helper.ts"
Cohesion: 0.07
Nodes (35): OutputsBinder, getTemplateParameters(), getCustomSwaggerIfNeeded(), getSwaggerFromService(), getInputsOutputsBinding(), getParametersToBind(), InitInputsOutputsPayload, InputsOutputsBinding (+27 more)

### Community 64 - "store.ts"
Cohesion: 0.17
Nodes (13): ParameterEditor(), AppDispatch, AppStore, rootReducer, RootState, EditOperationProps, mcpEditorsPlugin, ParameterEditorProps (+5 more)

### Community 65 - "configuretemplate.ts"
Cohesion: 0.08
Nodes (44): getAllParametersForWorkflows(), getConnectionsForConsumption(), getConnectionsForStandard(), getDefinitionAndUsedConnectionMappings(), getFeaturedConnectorsForWorkflows(), getTemplateConnections(), getTemplateValidationError, getUpdatedTemplateManifest() (+36 more)

### Community 66 - "wrapInScope.ts"
Cohesion: 0.18
Nodes (15): ScopeDefinition, scopeDefinitions, WrapScopeType, wrapSelectedNodesInScope, WrapSelectedNodesPayload, buildLinearState(), buildParallelState(), makeEdge() (+7 more)

### Community 67 - "DesignerContextualMenu.tsx"
Cohesion: 0.04
Nodes (54): useSuppressDefaultNodeSelectFunctionality(), useNodeContextMenuData(), useOperationAlternateSelectedNode(), useUndoRedoClickToggle(), useRunMode(), isOperationNameValid(), validateParameter(), BulkCopyIcon (+46 more)

### Community 68 - "settings.ts"
Cohesion: 0.08
Nodes (67): areRequestOptionsSupported(), areTrackedPropertiesSupported(), ConcurrencySettings, CorrelationSettings, getAsynchronous(), getConcurrency(), getConditionExpressions(), getCorrelationSettings() (+59 more)

### Community 69 - "role.ts"
Cohesion: 0.15
Nodes (15): appIdentityRoleAssignmentsQueryOpts(), queryOpts, resourceRoleDefinitionQueryOpts(), roleDefinitionByNameQueryOpts(), roleQueryKeys, useAppIdentityRoleAssignmentsForResourceQuery(), useResourceRoleDefinitionsQuery(), useRoleDefinitionsByNameQuery() (+7 more)

### Community 70 - "SubgraphCardNode.spec.tsx"
Cohesion: 0.10
Nodes (20): mockDispatch, mockUseActionMetadata, mockUseFlowErrorsForNode, mockUseIconUri, mockUseIsGraphCollapsed, mockUseIsLeafNode, mockUseMonitoringView, mockUseNewAdditiveSubgraphId (+12 more)

### Community 71 - "index.tsx"
Cohesion: 0.07
Nodes (57): useDependencies(), usePanelLocation(), AgentParameterDeclaration, getTypeForTokenFiltering(), remapEditorViewModelWithNewIds(), remapValueSegmentsWithNewIds(), TokenGroup, getAvailableVariables() (+49 more)

### Community 72 - "operationMetadataSlice.ts"
Cohesion: 0.05
Nodes (54): ConnectionReference, ReferenceKey, getNonDuplicateId(), getNonDuplicateNodeId(), buildActionClipboardEntry(), buildScopeClipboardEntry(), buildScopeParams(), CopyOperationPayload (+46 more)

### Community 73 - "mcpPanelSlice.ts"
Cohesion: 0.16
Nodes (11): initializeOperationsMetadata, initialSelectionState, mcpSelectionSlice, McpSelectionState, ConfigPanelView, initialState, mcpPanelSlice, PanelState (+3 more)

### Community 74 - "chat.tsx"
Cohesion: 0.12
Nodes (13): ChatAvailabilitySectionProps, ChatButton(), ChatButtonProps, ChatIcon, CloseIcon, ConnectToAgentSectionProps, CopyIcon, CredentialFieldProps (+5 more)

### Community 75 - "index.tsx"
Cohesion: 0.08
Nodes (48): updateParameterConditionalVisibilityAndRefreshOutputs, useHostOptions(), useRawInputParameters(), RunAfter(), DataHandling(), DataHandlingSectionProps, General(), GeneralSectionProps (+40 more)

### Community 76 - "configuretemplate.ts"
Cohesion: 0.07
Nodes (53): getAllParametersForWorkflows(), getConnectionsForConsumption(), getConnectionsForStandard(), getDefinitionAndUsedConnectionMappings(), getFeaturedConnectorsForWorkflows(), getTemplateConnections(), getTemplateValidationError, getWorkflowDefinitionForConsumption() (+45 more)

### Community 77 - "index.tsx"
Cohesion: 0.15
Nodes (16): AllowedTriggerTypes, FloatingRunButton(), FloatingRunButtonProps, getPublishedRunUrl(), PayloadData, RunIcon, RunWithPayloadIcon, PayloadPopover() (+8 more)

### Community 78 - "RootState"
Cohesion: 0.07
Nodes (48): deleteWorkflowData, getUpdatedTemplateManifest(), updateWorkflowParameter, useParameterDefinition(), formatNameWithIdentifierToDisplay(), getConnectorKind(), getDateTimeString(), getSupportedSkus() (+40 more)

### Community 79 - "templates.ts"
Cohesion: 0.06
Nodes (51): ConfigureTemplateServiceOptions, initializeConfigureTemplateServices, loadCustomTemplate, getWorkflowAndManifest(), GetWorkflowAndManifestHandler, initializeTemplateServices, initializeWorkflowMetadata, loadCustomTemplates (+43 more)

### Community 80 - "unitTestSlice.ts"
Cohesion: 0.22
Nodes (15): AddAssertionPayload, DeleteAssertionsPayload, InitDefintionPayload, OutputMock, UnitTestState, UpdateAssertioExpressionPayload, UpdateAssertionPayload, updateMockPayload (+7 more)

### Community 81 - "workflowconnections.tsx"
Cohesion: 0.07
Nodes (46): updateMcpConnection, updateTemplateConnection, updateNewConnectionInQueryCache(), getOperation(), useConnector(), useGateways(), useGatewayServiceConfig(), getOperationsGroupedByReferences() (+38 more)

### Community 82 - "helper.ts"
Cohesion: 0.11
Nodes (26): loadResourceDetailsFromWorkflowSource, validateWorkflowName(), WorkflowTemplateData, ConfigureWorkflowsPanel(), ConfigureWorkflowsTabProps, useStyles, useConfigureWorkflowPanelTabs(), EditWorkflowPanelProps (+18 more)

### Community 83 - "store.ts"
Cohesion: 0.12
Nodes (22): TemplatePayload, createQueryClient(), getPersister(), queryKeyDefaultWhitelist, ReactQueryProvider(), ReactQueryProviderProps, ConfigPanelView, initialState (+14 more)

### Community 84 - "McpDataProvider.tsx"
Cohesion: 0.15
Nodes (13): initializeMcpServices, McpServiceOptions, resetMcpStateOnResourceChange, McpDataProvider(), McpDataProviderProps, InitialResourceState, initialState, resourceSlice (+5 more)

### Community 85 - "useTemplatesStrings"
Cohesion: 0.10
Nodes (32): validateTriggerDescription(), useAllLogicApps(), useLocations(), useLogicApps(), useResourceGroups(), useSubscriptions(), useTemplateConnections(), useTemplateParameterDefinitions() (+24 more)

### Community 86 - "Test Coverage"
Cohesion: 0.12
Nodes (16): 1. Basic Rendering, 2. Chat Dialog Functionality, 3. Info Dialog - Draft Mode, 4. Info Dialog - Production Mode, 5. Child Components, 6. useAgentUrl Hook, 7. Tooltip Behavior, Chat Button Test Suite (+8 more)

### Community 87 - "McpWizard.tsx"
Cohesion: 0.21
Nodes (12): connectorTableCellStyles, lastCellStyles, ListConnectors(), lastCellStyles, ListOperations(), toolNameCellStyles, toolTableCellStyles, McpServerCreateData (+4 more)

### Community 88 - "DesignerProvider.tsx"
Cohesion: 0.21
Nodes (9): DesignerProviderProps, ProviderWrappedContext, store, DesignerOptionsState, PANEL_TAB_NAMES, ServiceOptions, designerOptionsSlice, initialDesignerOptionsState (+1 more)

### Community 89 - "index.tsx"
Cohesion: 0.10
Nodes (28): useTimelineRepetitionIndex(), ConnectorIcon(), ConnectorIconProps, parseRepetitions(), TimelineRepetitionWithActions, TimelineRepetition, useTimelineRepetitionCount(), useTimelineRepetitions() (+20 more)

### Community 90 - "Utils.ts"
Cohesion: 0.11
Nodes (18): isAgentSubgraphFromMetadata(), ConnectionTable(), ConnectionTableProps, ConnectionTableDetailsButton(), ConnectionTableDetailsButtonProps, compareFlattenedConnections(), ConnectionWithFlattenedProperties, flattenConnection() (+10 more)

### Community 91 - "helper.ts"
Cohesion: 0.09
Nodes (33): ConnectionReferences, getTemplateParameters(), findParameterExpressions(), getAllNodeData(), getOperationDataInDefinitions(), getParameterReferencesFromValue(), getReferencesFromConnections(), ConnectorWithParsedSwagger (+25 more)

### Community 92 - "SelectOperations.tsx"
Cohesion: 0.20
Nodes (8): ConnectorBrowseView(), ConnectorBrowseViewProps, SelectConnectors(), useConnectorSelectionStyles, fuseOptions, SelectOperations(), useAllManagedConnectors(), useOperationsByConnectorQuery()

### Community 93 - "devSlice.ts"
Cohesion: 0.53
Nodes (3): DevState, devSlice, initialState

### Community 94 - "usePanelTabs.tsx"
Cohesion: 0.08
Nodes (27): StaticResultOption, usePanelTabHideKeys(), useHasSchema(), useStaticResultProperties(), useStaticResultSchema(), useRetryHistory(), CodeViewTab(), InputsPanel() (+19 more)

### Community 95 - "TokenSegmentConvertor"
Cohesion: 0.11
Nodes (6): createExpressionToken(), ValueSegmentConvertor, TokenSegmentConvertor, expectOutputTokenSegment(), expectParameterTokenSegment(), expectVariableTokenSegment()

### Community 96 - "useOperationVisuals"
Cohesion: 0.08
Nodes (30): useOperationVisuals(), useNodeIds(), NodeErrors(), NodeErrorsProps, ActionMenuItem(), NodeSearchCard(), fuseOptions, NodeSearchDialog() (+22 more)

### Community 97 - "dropTarget.tsx"
Cohesion: 0.08
Nodes (27): useIsDarkMode(), useNodesTokenDependencies(), useOperationsInputParameters(), useAllGraphParents(), renderWithRedux(), intlOnError, queryClient, useAddButtonStyles (+19 more)

### Community 98 - "agentChat.spec.tsx"
Cohesion: 0.16
Nodes (11): capturedChatbotUIProps, createPanelContainerRef(), mockCancelRun, mockDispatch, mockInvokeAgentChat, mockRefetchChatHistory, mockRefreshChat, renderAgentChat() (+3 more)

### Community 99 - "resourcepicker.tsx"
Cohesion: 0.18
Nodes (14): useLocations(), useLogicApps(), useResourceGroups(), useSubscriptions(), ResourceField(), BaseResourcePickerProps, ResourcePicker(), ResourcePickerProps (+6 more)

### Community 100 - "AppDispatch"
Cohesion: 0.13
Nodes (22): validateWorkflowName(), validateWorkflowsBasicInfo, useExistingWorkflowNames(), AppDispatch, useWorkflowBasicsEditable(), getCurrentWorkflowNames(), CreateWorkflowPanelHeader(), CreateWorkflowTabProps (+14 more)

### Community 101 - "WorkflowTemplateData"
Cohesion: 0.11
Nodes (29): addWorkflowsData, loadResourceDetailsFromWorkflowSource, saveWorkflowsData, TemplateErrors, WorkflowErrors, WorkflowTemplateData, ApiValidationError, appendToError() (+21 more)

### Community 102 - "index.tsx"
Cohesion: 0.26
Nodes (8): DeleteIcon, NoteNode(), MarkdownRenderer(), YoutubeEmbed(), useNoteNodeStyles, useIsNotesDirty(), useNote(), NotesState

### Community 103 - "inputsbuilder.ts"
Cohesion: 0.08
Nodes (35): transformInputParameter(), buildOperationDetailsFromControls(), countOccurrence(), createMultipart(), deletePropertyValueWithSpecifiedPathSegment(), getFormDataValue(), getPathInputs(), getPropertyValueWithSpecifiedPathSegments() (+27 more)

### Community 104 - "OperationSelectionGrid.tsx"
Cohesion: 0.22
Nodes (8): OperationProgress(), OperationCellProps, OperationSelectionGrid(), OperationSelectionGridProps, useOperationSelectionGridStyles, getDynamicSchemaDependencies(), isDependentStaticParameter(), operationHasEmptyStaticDependencies()

### Community 105 - "OperationCardNode.spec.tsx"
Cohesion: 0.06
Nodes (35): mockDispatch, mockUseActionMetadata, mockUseAllOperations, mockUseConnectorName, mockUseFlowErrorsForNode, mockUseIsA2AWorkflow, mockUseIsCopilotModifiedNode, mockUseIsLeafNode (+27 more)

### Community 106 - "dynamicdata.ts"
Cohesion: 0.05
Nodes (83): addDefaultSecureSettings(), initializeOperationDetailsForManagedMcpServer(), createQueryClient(), getReactQueryClient(), queryKeyDefaultWhitelist, ReactQueryProviderProps, evaluateParameter(), evaluateTemplateExpressions() (+75 more)

### Community 107 - "ParseReduxAction.ts"
Cohesion: 0.09
Nodes (24): Workflow, initializeDiscoveryPanelFavoriteOperations(), updateWorkflowParameters(), BJSWorkflowProvider(), BJSWorkflowProviderProps, DataProviderInner(), DeserializedWorkflow, buildConnectionReferencesFromConnectionsParameter() (+16 more)

### Community 108 - "logicAppSelector.tsx"
Cohesion: 0.70
Nodes (3): LogicAppSelector(), useMcpDetailsStyles, useEmptyLogicApps()

### Community 109 - "createConnection.tsx"
Cohesion: 0.09
Nodes (20): needsOAuth(), useTenants(), isA2AKind(), useShouldEnableAPIMGatewayConnection(), CreateButtonTexts, CreateConnection(), isServicePrincipalParameterVisible(), ParamType (+12 more)

### Community 111 - "error.test.ts"
Cohesion: 0.29
Nodes (9): EXPECTED_EMPTY_ERROR_PROPS, TEST_CODES, TEST_ERROR_RUNS, TEST_MESSAGES, ErrorProps, ErrorRun, extractErrorInfo(), getMonitoringError() (+1 more)

### Community 112 - "actionCard.tsx"
Cohesion: 0.12
Nodes (15): ActionCard(), ActionCardProps, colors, useCardStyles, CardErrorBadge(), CardRunStatusBadge(), ChevronDown, ChevronUp (+7 more)

### Community 113 - "workflowconnections.tsx"
Cohesion: 0.11
Nodes (21): updateTemplateConnection, ConnectionsList(), CompactConnectorConnectionStatus(), ConnectorConnectionName(), ConnectorIcon(), ConnectorIconWithName(), ConnectorWithDetails(), textStyles (+13 more)

### Community 114 - "addNodeToWorkflow.ts"
Cohesion: 0.55
Nodes (10): addAgentToolToWorkflow(), addChildEdge(), addChildNode(), addMcpServerToWorkflow(), addSwitchCaseToWorkflow(), createSubgraphNode(), handleExtraScopeNodeSetup(), createWorkflowEdge() (+2 more)

### Community 115 - "DesignerReactFlow.spec.tsx"
Cohesion: 0.20
Nodes (8): capturedReactFlowProps, mockAllAgentIds, mockDisconnectedNodes, mockDispatch, mockNodesMetadata, mockNotes, mockPanelSelectedNodeIds, mockSetViewport

### Community 116 - "EditOperationPanel.tsx"
Cohesion: 0.23
Nodes (12): CloseIcon, SelectionPanel(), useMcpConnectorPanelTabs(), CloseIcon, EditOperationPanel(), useOperationDynamicInputsError(), McpPanelRoot(), McpPanelView (+4 more)

### Community 117 - "deploymentModelResource.tsx"
Cohesion: 0.36
Nodes (4): CustomDeploymentModelResource(), deploymentModelNameStyle, useDeploymentModelResourceStyles, mockCreateNewDeployment

### Community 118 - "validation.ts"
Cohesion: 0.11
Nodes (24): RFC-3339, RFC-5322, getTitleOrSummary(), isOneOf(), isParameterRequired(), isValidArrayFormat(), isValidJSONObjectFormat(), parameterHasOnlyTokenBinding() (+16 more)

### Community 120 - "monitoring.spec.ts"
Cohesion: 0.29
Nodes (6): initializeInputsOutputsBinding, mockGetAgentActionsRepetition, mockGetAgentRepetition, mockGetContent, mockParseInputs, mockParseOutputs

### Community 121 - "ScopeCardNode.spec.tsx"
Cohesion: 0.07
Nodes (29): mockDispatch, mockUseActionMetadata, mockUseAllOperations, mockUseBrandColor, mockUseConnectorName, mockUseFlowErrorsForNode, mockUseHandoffActionsForAgent, mockUseIconUri (+21 more)

### Community 122 - "ValueSegmentConvertor"
Cohesion: 0.13
Nodes (6): createExpressionToken(), ValueSegmentConvertor, expectOutputTokenSegment(), expectParameterTokenSegment(), expectVariableTokenSegment(), UncastingUtility

### Community 123 - "gatewayPicker.tsx"
Cohesion: 0.43
Nodes (5): GatewayPicker(), GatewayPickerProps, GatewaysWithNewOption, NewGatewayOption, useGatewayPickerStyles

### Community 124 - "RootState"
Cohesion: 0.16
Nodes (15): MultiWorkflowBasics(), WorkflowItem, TemplateResourcePicker(), SingleWorkflowBasics(), WorkflowConnections(), CreateWorkflowPanel(), CreateWorkflowPanelHeader(), CreateWorkflowTabProps (+7 more)

### Community 125 - "openAIConnector.tsx"
Cohesion: 0.17
Nodes (20): useSubscriptions(), ConnectionParameterRow(), ConnectionParameterRowParameterRowSelfProps, ConnectionParameterRowProps, ACASessionConnector(), RefreshIcon, SubscriptionDropdown(), SubscriptionDropdownProps (+12 more)

### Community 126 - "useWizardTabs.tsx"
Cohesion: 0.17
Nodes (17): saveTemplateData, ConfigureTemplateWizard(), getImageFileContent(), getSaveMenuButtons(), getWorkflowFolderContent(), getZippedTemplateForDownload(), zipFolder(), initialState (+9 more)

### Community 128 - "agentHarnessTab.tsx"
Cohesion: 0.11
Nodes (21): useHostOptions(), AgentHarnessData, AgentHarnessInputFile, AgentHarnessSkill, AgentHarnessTab(), ExpressionTokenPill(), extractErrorDetail(), getExpressionTitle() (+13 more)

### Community 129 - "mcpselectionslice.ts"
Cohesion: 0.14
Nodes (16): queryOpts, useAllManagedConnectors(), useOperationsByConnectorQuery(), initialSelectionState, mcpSelectionSlice, McpSelectionState, ConnectorBrowseView(), ConnectorBrowseViewProps (+8 more)

### Community 130 - "index.tsx"
Cohesion: 0.18
Nodes (16): SettingSectionName, SettingsState, useExpandedSections(), initialState, settingsSlice, isSecureOutputsLinkedToInputs(), isISO8601(), RunAfterSettings() (+8 more)

### Community 131 - "settingsection.tsx"
Cohesion: 0.14
Nodes (18): updateParameterConditionalVisibilityAndRefreshOutputs, SettingData, AdvancedSettingsMessage(), NavigateIcon, HeaderClickHandler, formatSettingName(), formatSettingValue(), HostSettings() (+10 more)

### Community 132 - "createConnectionInternal.tsx"
Cohesion: 0.13
Nodes (20): useConnector(), useGateways(), useGatewayServiceConfig(), ConnectionSelection(), CreateConnectionInTemplate(), useConnectionSelectionStyles, getConnectionParametersForAzureConnection(), getSupportedParameterSets() (+12 more)

### Community 142 - "store.ts"
Cohesion: 0.11
Nodes (14): ExportDataProvider(), ExportDataProviderProps, ExportWizardContext, ExportWizardContextContext, ExportWizardProvider(), ExportWizardProviderProps, initialState, resourceSlice (+6 more)

### Community 143 - "role.ts"
Cohesion: 0.15
Nodes (18): appIdentityRoleAssignmentsQueryOpts(), getMissingRoleDefinitions(), queryOpts, resourceRoleDefinitionQueryOpts(), roleDefinitionByNameQueryOpts(), roleQueryKeys, useAppIdentityRoleAssignmentsForResourceQuery(), useHasRoleAssignmentsWritePermissionQuery() (+10 more)

### Community 144 - "useCognitiveService.ts"
Cohesion: 0.18
Nodes (20): useSelectedConnection(), buildProxyContext(), foundryQueryOpts, getFoundryProxyContext(), getServiceAccountId(), queryKeys, queryOpts, useCognitiveServiceAccountDeploymentsForNode() (+12 more)

### Community 145 - "general.tsx"
Cohesion: 0.17
Nodes (18): useOutputParameters(), DropdownSelectionChangeHandler, NumberChangeHandler, SectionProps, TextChangeHandler, ToggleHandler, DataHandling(), DataHandlingSectionProps (+10 more)

### Community 146 - "outputs.test.ts"
Cohesion: 0.14
Nodes (7): ApiConnectionOutputsBinder, ManifestOutputsBinder, OutputsBinder, nodeParameters, operationMetadata, outputParametersByName, parsedOutputs

### Community 147 - "SubgraphCardNode.spec.tsx"
Cohesion: 0.10
Nodes (20): mockDispatch, mockUseActionMetadata, mockUseFlowErrorsForNode, mockUseIconUri, mockUseIsGraphCollapsed, mockUseIsLeafNode, mockUseMonitoringView, mockUseNewAdditiveSubgraphId (+12 more)

### Community 148 - "mcp.ts"
Cohesion: 0.15
Nodes (14): initializeMcpServices, McpServiceOptions, TODO: Initialize dynamic data without user inputs in this section., resetMcpStateOnResourceChange, McpDataProvider(), McpDataProviderProps, resetMcpState, initialState (+6 more)

### Community 149 - "EditOperation.tsx"
Cohesion: 0.22
Nodes (15): isDependentStaticParameter(), Snapshot, useEditSnapshot(), AppDispatch, useOperationDynamicInputsError(), getGroupIdFromParameterId(), CloseIcon, EditOperationPanel() (+7 more)

### Community 150 - "index.tsx"
Cohesion: 0.16
Nodes (15): useChangeCount(), getNotesState(), useIsNotesDirty(), useNote(), useNotes(), useNotesChangeCount(), NotesState, useWorkflowChangeCount() (+7 more)

### Community 151 - "errorsTab.hooks.ts"
Cohesion: 0.28
Nodes (17): useAllConnectionErrors(), useFlowErrors(), ErrorsTab(), getAllInputErrors, getHostCheckerErrors, useAllInputErrors(), useAllSettingErrors(), useHostCheckerErrors() (+9 more)

### Community 152 - "McpWizard.tsx"
Cohesion: 0.20
Nodes (14): deinitializeOperations, McpServerCreateData, McpPanelView, RootState, connectorTableCellStyles, lastCellStyles, ListConnectors(), lastCellStyles (+6 more)

### Community 153 - "mcpPanelSlice.ts"
Cohesion: 0.19
Nodes (13): initializeConnectionMappings, initializeOperationsMetadata, ConfigPanelView, initialState, mcpPanelSlice, PanelState, CloseIcon, SelectionPanel() (+5 more)

### Community 154 - "index.tsx"
Cohesion: 0.19
Nodes (14): resetDesignerDirtyState, useIsDesignerDirty(), AllowedTriggerTypes, FloatingRunButton(), FloatingRunButtonProps, getPublishedRunUrl(), PayloadData, RunIcon (+6 more)

### Community 155 - "chat.tsx"
Cohesion: 0.12
Nodes (13): ChatAvailabilitySectionProps, ChatButton(), ChatButtonProps, ChatIcon, CloseIcon, ConnectToAgentSectionProps, CopyIcon, CredentialFieldProps (+5 more)

### Community 156 - "createConnection.spec.tsx"
Cohesion: 0.18
Nodes (15): CreateConnectionProps, findConnectionsParamContainer(), findInput(), findLegacyMultiAuth(), findMultiAuthInput(), findParameterComponents(), findParameterSetsDropdown(), findTenantPicker() (+7 more)

### Community 157 - "openAIConnector.spec.tsx"
Cohesion: 0.11
Nodes (15): capturedOnOptionSelect, defaultProps, mockFetchAccountById, mockFetchAccountKeysById, mockRefetchAPIMAccountApis, mockRefetchAPIMAccounts, mockRefetchServiceAccounts, mockRefetchServiceProjects (+7 more)

### Community 158 - "DesignerProvider.tsx"
Cohesion: 0.21
Nodes (10): DesignerProviderProps, ReduxReset(), ProviderWrappedContext, DesignerOptionsState, PANEL_TAB_NAMES, ServiceOptions, designerOptionsSlice, initialDesignerOptionsState (+2 more)

### Community 159 - "elklayout.tsx"
Cohesion: 0.18
Nodes (15): convertElkGraphToReactFlow(), convertWorkflowGraphToElkGraph(), defaultLayoutOptions, elk, elkLayout(), exportForTesting, LayoutContext, LayoutContextType (+7 more)

### Community 160 - "Binder"
Cohesion: 0.22
Nodes (3): Binder, getDynamicListLookupValue(), getDynamicTreeLookupValue()

### Community 161 - "Test Coverage"
Cohesion: 0.12
Nodes (16): 1. Basic Rendering, 2. Chat Dialog Functionality, 3. Info Dialog - Draft Mode, 4. Info Dialog - Production Mode, 5. Child Components, 6. useAgentUrl Hook, 7. Tooltip Behavior, Chat Button Test Suite (+8 more)

### Community 162 - "connectionTable.tsx"
Cohesion: 0.26
Nodes (12): ConnectionTable(), ConnectionTableProps, ConnectionTableDetailsButton(), ConnectionTableDetailsButtonProps, compareFlattenedConnections(), ConnectionWithFlattenedProperties, flattenConnection(), getLabelForConnection() (+4 more)

### Community 163 - "monitoringTab.tsx"
Cohesion: 0.18
Nodes (10): InputsPanel(), InputsPanelProps, MonitoringPanel(), monitoringTab(), OutputsPanel(), OutputsPanelProps, PropertiesPanel(), PropertiesPanelProps (+2 more)

### Community 164 - "monitoring.ts"
Cohesion: 0.16
Nodes (10): getInputsOutputsBinding(), getParametersToBind(), InitInputsOutputsPayload, InputsOutputsBinding, mockGetAgentActionsRepetition, mockGetAgentRepetition, mockGetContent, mockParseInputs (+2 more)

### Community 165 - "workflowparametersselector.ts"
Cohesion: 0.32
Nodes (11): deleteWorkflowParameter, useLegacyWorkflowParameters(), getWorkflowParametersState(), useIsWorkflowParametersDirty(), useWorkflowParameters(), useWorkflowParametersChangeCount(), useWorkflowParameterValidationErrors(), capturedProps (+3 more)

### Community 166 - "index.tsx"
Cohesion: 0.20
Nodes (8): useConnectionById(), ConnectionDisplayName(), ConnectionEntry(), ConnectionEntryProps, ConnectorConnectionsCardProps, NodeLinkButton(), mockDispatch, mockUseNodeDisplayName

### Community 167 - "errorsPanel.tsx"
Cohesion: 0.26
Nodes (10): useErrorsPanelSelectedTabId(), CollapseIcon, ErrorCategory(), ErrorCategoryProps, ExpandIcon, CloseIcon, ErrorsPanel(), useHostCheckerWarnings() (+2 more)

### Community 168 - "inputs.test.ts"
Cohesion: 0.19
Nodes (5): ManifestInputsBinder, inputParametersByName, nodeParameters, operationMetadata, parsedInputs

### Community 169 - "agentChat.spec.tsx"
Cohesion: 0.16
Nodes (11): cache, intl, mockUseIntl(), capturedChatbotUIProps, createPanelContainerRef(), mockCancelRun, mockDispatch, mockInvokeAgentChat (+3 more)

### Community 170 - "customcodeSlice.ts"
Cohesion: 0.28
Nodes (9): AddCustomCodePayload, CustomCodeState, DeleteCustomCodePayload, RenameCustomCodePayload, customCodeSlice, initialState, AllCustomCodeFiles, CustomCode (+1 more)

### Community 171 - "foundryUpdates.ts"
Cohesion: 0.24
Nodes (11): clearPendingFoundryUpdate(), consumeVersionRefresh(), flushPendingFoundryUpdates(), getPendingFoundryUpdate(), hasPendingFoundryUpdates(), needsVersionRefresh(), PendingFoundryUpdate, pendingUpdates (+3 more)

### Community 172 - "store.ts"
Cohesion: 0.18
Nodes (7): McpWizardContext, McpWrappedContext, McpWizardProvider(), McpWizardProviderProps, AppStore, mcpStore, rootReducer

### Community 173 - "OperationSelectionGrid.tsx"
Cohesion: 0.24
Nodes (9): getDynamicSchemaDependencies(), operationHasEmptyStaticDependencies(), OperationProgress(), getColumnsCount(), OperationCellProps, OperationSelectionGrid(), OperationSelectionGridProps, useOperationSelectionGridStyles (+1 more)

### Community 174 - "parametereditor.tsx"
Cohesion: 0.33
Nodes (11): useConnectionReferenceForKey(), getDisplayValueFromPickerSelectedItem(), getValueFromPickerSelectedItem(), loadDynamicTreeItemsForParameter(), loadDynamicValuesForParameter(), showErrorWhenDependenciesNotReady(), updateParameterAndDependencies, mcpEditorsPlugin (+3 more)

### Community 175 - "updateParameterWithValues"
Cohesion: 0.23
Nodes (13): getExtraSegments(), reduceRedundantSegments(), updateParameterWithValues(), getExtensionInputs(), getQueriesInputs(), isEmptySegment(), loadBodyValue(), loadExtensionValue() (+5 more)

### Community 176 - "workflowparametersselector.ts"
Cohesion: 0.33
Nodes (8): deleteWorkflowParameter, useLegacyWorkflowParameters(), capturedProps, defaultProps, mockDispatch, useWorkflowParameters(), useWorkflowParameterValidationErrors(), WorkflowParametersPanel()

### Community 177 - "error.test.ts"
Cohesion: 0.29
Nodes (9): ErrorProps, ErrorRun, extractErrorInfo(), getMonitoringError(), getMonitoringTabError(), EXPECTED_EMPTY_ERROR_PROPS, TEST_CODES, TEST_ERROR_RUNS (+1 more)

### Community 178 - "index.ts"
Cohesion: 0.31
Nodes (4): DefaultInputsBinder, DefaultOutputsBinder, parseInputs(), parseOutputs()

### Community 179 - "PerformanceDebug.tsx"
Cohesion: 0.33
Nodes (6): useShowPerformanceDebug(), useReduxActionCounts(), useNodesAndDynamicDataInitialized(), PerformanceDebugTool(), InitializationTimer(), ReduxActionCounts()

### Community 180 - "DesignerReactFlow.spec.tsx"
Cohesion: 0.20
Nodes (8): capturedReactFlowProps, mockAllAgentIds, mockDisconnectedNodes, mockDispatch, mockNodesMetadata, mockNotes, mockPanelSelectedNodeIds, mockSetViewport

### Community 181 - "settingDefaults.ts"
Cohesion: 0.57
Nodes (6): applySettingDefaults(), fetchSettingDefaults(), getSupportedSettingKeys(), isDefaultRetryPolicy(), isKnownSettingKey(), mergeSettingDefaults()

### Community 182 - "deploymentModelResource.tsx"
Cohesion: 0.39
Nodes (4): CustomDeploymentModelResource(), deploymentModelNameStyle, useDeploymentModelResourceStyles, mockCreateNewDeployment

### Community 184 - "runHistoryEntry.spec.tsx"
Cohesion: 0.25
Nodes (5): mockCancelRun, mockInvalidateQueries, mockRefetchRun, mockResubmitRun, queryClient

### Community 185 - "helper.ts"
Cohesion: 0.36
Nodes (6): collapseFlowTree(), isA2AKind(), isAgentWorkflow(), pruneTree(), shouldClearNodeRunData(), traverseForMapping()

### Community 188 - "edge.spec.tsx"
Cohesion: 0.29
Nodes (6): LogicAppsEdgeProps, mockUseActionMetadata, mockUseIsNodeSelectedInOperationPanel, mockUseNodeEdgeTargets, mockUseNodeMetadata, mockUseReadOnly

### Community 189 - "gatewayPicker.tsx"
Cohesion: 0.43
Nodes (5): GatewayPicker(), GatewayPickerProps, GatewaysWithNewOption, NewGatewayOption, useGatewayPickerStyles

### Community 191 - "logicAppSelector.tsx"
Cohesion: 0.70
Nodes (3): useEmptyLogicApps(), LogicAppSelector(), useMcpDetailsStyles

### Community 192 - "clientSecretInput.tsx"
Cohesion: 0.50
Nodes (4): ClientSecretInput(), ClientSecretInputProps, getBase64String(), IClientCertificateMetadata

## Knowledge Gaps
- **1441 isolated node(s):** `cache`, `intl`, `SCHEMA`, `SWAGGER`, `VARIABLE_TYPE` (+1436 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **21 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `ValueSegmentConvertor` connect `ValueSegmentConvertor` to `index.ts`, `loops.ts`, `helper.ts`?**
  _High betweenness centrality (0.011) - this node is a cross-community bridge._
- **Why does `ApiConnectionInputsBinder` connect `ApiConnectionInputsBinder` to `Binder`, `monitoring.ts`, `inputs.test.ts`?**
  _High betweenness centrality (0.011) - this node is a cross-community bridge._
- **Are the 8 inferred relationships involving `getReactQueryClient()` (e.g. with `getCustomTemplates()` and `getTemplate()`) actually correct?**
  _`getReactQueryClient()` has 8 INFERRED edges - model-reasoned connections that need verification._
- **What connects `cache`, `intl`, `SCHEMA` to the rest of the system?**
  _1441 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `helper.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.026775629526277323 - nodes in this community are weakly interconnected._
- **Should `OperationCardNode.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.05284147557328016 - nodes in this community are weakly interconnected._
- **Should `constants.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.03608247422680412 - nodes in this community are weakly interconnected._