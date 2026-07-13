# Graph Report - src  (2026-07-13)

## Corpus Check
- 581 files · ~188,440 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 4433 nodes · 10720 edges · 210 communities (188 shown, 22 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 42 edges (avg confidence: 0.75)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `f4e3a3f2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- index.tsx
- templatesSectionModel.ts
- util.ts
- index.tsx
- index.tsx
- panelcontainer.tsx
- fabric.ts
- util.ts
- ValueSegment
- settingTokenField.tsx
- index.tsx
- index.tsx
- render
- CodeMirrorEditor.tsx
- ChangeHandler
- util.ts
- index.tsx
- index.tsx
- assertion.tsx
- helper.ts
- parsesegments.ts
- conversationItem.ts
- EventHandler
- util.ts
- Format.tsx
- statusicon.tsx
- filepickerPopoverHeader.tsx
- tokenpickerfooter.tsx
- RichTextToolbar.tsx
- chatBubble.tsx
- flowPreview.tsx
- index.tsx
- templatefunctions.ts
- constants.ts
- progressCardWithStopButton.tsx
- browseResults.tsx
- index.tsx
- index.tsx
- index.tsx
- DropdownColorPicker.tsx
- OpenTokenPicker.tsx
- index.tsx
- filepickerEditor.tsx
- index.tsx
- workflowparametersField.tsx
- searchResult.tsx
- operationsNeedAttentionMessage.tsx
- TokenPickerMode
- index.tsx
- index.tsx
- CopyInputControlWithAgent.tsx
- PasswordNode
- outputMocks.tsx
- designTokens.ts
- index.ts
- assistantReplyWithFlow.tsx
- index.tsx
- index.tsx
- index.tsx
- index.ts
- workflowparameters.tsx
- hooks.ts
- connectionsSetupMessage.tsx
- workflowparameter.tsx
- ExtendedTextNode
- promptGuideContextualMenu.tsx
- cardfooter.tsx
- browseResults.tsx
- index.tsx
- index.tsx
- index.tsx
- index.tsx
- index.tsx
- settingreactiveinput.tsx
- workflowparametersButtons.tsx
- index.tsx
- index.tsx
- migrationHelpers.ts
- settingdropdown.tsx
- index.tsx
- nodeErrorCard.tsx
- textInput.tsx
- index.tsx
- index.tsx
- ValueSegment
- settingtextfield.tsx
- index.tsx
- index.tsx
- index.tsx
- tokenpickersection.tsx
- index.tsx
- index.tsx
- settingmultiselect.tsx
- templatesSectionModel.ts
- index.tsx
- index.ts
- fxIcon.tsx
- allowdroptarget.tsx
- blockdroptarget.tsx
- index.tsx
- connectiontypeselector.styles.ts
- types.ts
- mixins.ts
- Svg.d.ts
- index.tsx
- workflowparameter.tsx
- util.ts
- settingTokenField.tsx
- util.ts
- index.tsx
- index.tsx
- index.tsx
- panelcontainer.tsx
- index.tsx
- conversationItem.ts
- index.tsx
- parsesegments.ts
- searchResult.tsx
- RichTextToolbar.tsx
- index.tsx
- createLiteralValueSegment
- nodeErrorCard.tsx
- index.tsx
- statusicon.tsx
- Format.tsx
- index.ts
- PasswordNode
- index.tsx
- index.ts
- flowPreview.tsx
- index.tsx
- CodeMirrorEditorRef
- progressCardWithStopButton.tsx
- index.tsx
- designTokens.ts
- index.tsx
- index.tsx
- initialConfig.ts
- filepickerPopoverHeader.tsx
- useCardKeyboardInteraction
- operationsNeedAttentionMessage.tsx
- CopyInputControlWithAgent.tsx
- tokenpickeroption.tsx
- assistantReplyWithFlow.tsx
- index.tsx
- index.tsx
- index.tsx
- index.tsx
- index.tsx
- index.tsx
- index.tsx
- chatBubble.tsx
- CodeMirrorEditor.tsx
- index.tsx
- panelcontent.tsx
- index.tsx
- HTMLChangePlugin.tsx
- promptGuideContextualMenu.tsx
- tokenpickerfooter.tsx
- connectionsSetupMessage.tsx
- xml.tsx
- OpenTokenPicker.tsx
- DropdownColorPicker.tsx
- index.tsx
- index.tsx
- generator.ts
- index.tsx
- CodeMirrorEditorProps
- index.tsx
- simpledictionary.tsx
- generator.ts
- functions.ts
- createEventExtensions
- migrationHelpers.ts
- TokenTypeahead.tsx
- index.tsx
- index.tsx
- CloseTokenPicker.tsx
- SelectAgentParameter.tsx
- index.tsx
- assertionField.tsx
- index.tsx
- index.tsx
- DeleteNodeModal.tsx
- interactionTagList.tsx
- index.tsx
- index.tsx
- interactionTagList.tsx
- useId
- index.tsx
- alert.tsx
- index.ts
- index.tsx
- index.tsx
- Value
- utils.ts
- fluent.ts
- DropdownBlockFormat.tsx
- index.tsx
- index.tsx
- workflowparametersFooter.tsx
- index.ts
- allowdroptarget.tsx
- blockdroptarget.tsx
- index.tsx
- connectiontypeselector.styles.ts
- types.ts
- mixins.ts

## God Nodes (most connected - your core abstractions)
1. `ValueSegment` - 101 edges
2. `ValueSegment` - 101 edges
3. `createLiteralValueSegment()` - 55 edges
4. `createLiteralValueSegment()` - 45 edges
5. `BaseEditorProps` - 39 edges
6. `BaseEditorProps` - 39 edges
7. `ChangeHandler` - 33 edges
8. `ChangeHandler` - 31 edges
9. `convertStringToSegments()` - 29 edges
10. `useId()` - 28 edges

## Surprising Connections (you probably didn't know these)
- `CreateNaturalLanguageToFlowInputInternal()` --calls--> `useId()`  [INFERRED]
  lib/copilotGetStarted/components/createNaturalLanguageToFlowInput.tsx → src/lib/useId.ts
- `CreateAgentParameter()` --calls--> `useId()`  [INFERRED]
  lib/tokenpicker/tokenpickersection/agentparameter/CreateAgentParameter.tsx → src/lib/useId.ts
- `SimpleQueryBuilder()` --calls--> `useId()`  [INFERRED]
  lib/querybuilder/SimpleQueryBuilder.tsx → src/lib/useId.ts
- `ConnectionStatus()` --calls--> `useConnectionContainerStyles`  [EXTRACTED]
  lib/chatbot/components/connectionStatus.tsx → src/lib/connectioncontainer.styles.ts
- `TokenPickerButtonLegacy()` --indirect_call--> `TokenNode`  [INFERRED]
  src/lib/editor/base/plugins/TokenPickerButtonLegacy.tsx → src/lib/editor/base/nodes/tokenNode.tsx

## Import Cycles
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingtextfield.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingtoggle.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingtagpicker.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingdictionary.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingslider.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingexpressioneditor.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingTokenField.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingmultiselect.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingdropdown.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `lib/settings/settingsection/index.tsx -> lib/settings/settingsection/settingreactiveinput.tsx -> lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingtoggle.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingreactiveinput.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingtextfield.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingdropdown.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingdictionary.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingexpressioneditor.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingmultiselect.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingslider.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingtagpicker.tsx -> src/lib/settings/settingsection/index.tsx`
- 2-file cycle: `src/lib/settings/settingsection/index.tsx -> src/lib/settings/settingsection/settingTokenField.tsx -> src/lib/settings/settingsection/index.tsx`

## Communities (210 total, 22 thin omitted)

### Community 0 - "index.tsx"
Cohesion: 0.05
Nodes (53): ClockIcon, Colorizer(), ColorizerProps, CopyIcon, ErrorSection(), ErrorSectionProps, ErrorShape, ChevronLeftIcon (+45 more)

### Community 1 - "templatesSectionModel.ts"
Cohesion: 0.05
Nodes (39): KnowledgeConnectionTabProps, KnowledgeTabProps, OnTabNavigation, McpConnectorTabProps, McpCreateAppTabProps, McpPanelTabProps, FieldSectionItem(), FieldSectionItemProps (+31 more)

### Community 2 - "util.ts"
Cohesion: 0.08
Nodes (38): CreateIcon, InitializeVariableEditor(), InitializeVariableEditorProps, InitializeVariableProps, useInitializeVariableStyles, convertVariableEditorSegmentsAsSchema(), createVariableEditorSegments(), getParameterValue() (+30 more)

### Community 3 - "index.tsx"
Cohesion: 0.10
Nodes (50): GetTokenPickerHandler, loadParameterValueFromStringHandler, ValueSegmentType, addIcon, AddSection(), AddSectionProps, calloutProps, Group() (+42 more)

### Community 4 - "index.tsx"
Cohesion: 0.09
Nodes (53): ActiveDirectoryAuthentication(), ActiveDirectoryAuthenticationProps, AuthenticationOAuthType, zipDropDownOptions(), AadOAuthCredentials(), AadOAuthCredentialsProps, AuthenticationDropdown(), AuthenticationDropdownProps (+45 more)

### Community 5 - "panelcontainer.tsx"
Cohesion: 0.07
Nodes (38): PanelContainer(), PanelContainerProps, MoreHorizontal, OverflowMenuItemProps, OverflowMenuProps, PanelContent(), PanelContentProps, PanelResizer() (+30 more)

### Community 6 - "fabric.ts"
Cohesion: 0.12
Nodes (17): Checkbox(), CheckboxProps, CheckboxState, useCheckboxDescriptionCalloutStyles, useCheckboxStyles, buttonStyles, caretDownButtonStyles, checkboxStyles (+9 more)

### Community 7 - "util.ts"
Cohesion: 0.06
Nodes (43): addItemButtonIconProps, calloutTextFieldStyles, cancelButtonStyles, newPropertyTextFieldStyles, PropertyEditor(), PropertyEditorProps, saveButtonStyles, ContextMenuKeys (+35 more)

### Community 8 - "ValueSegment"
Cohesion: 0.08
Nodes (52): CollapsedArray(), CollapsedArrayProps, addItemButtonIconProps, ExpandedComplexArray(), ExpandedComplexArrayProps, addItemButtonIconProps, ContextMenuKeys, ExpandedSimpleArray() (+44 more)

### Community 9 - "settingTokenField.tsx"
Cohesion: 0.08
Nodes (40): CastHandler, useCodeEditorStyles, EditableFileNameProps, CodeEditor(), CodeEditorProps, customCodeIconStyle, FileNameChangeHandler, buildInlineCodeTextFromToken() (+32 more)

### Community 10 - "index.tsx"
Cohesion: 0.09
Nodes (34): DynamicallyAddedParameterIcon, generateDynamicParameterKey(), getDefaultTitleForDynamicallyAddedParameterType(), getDescriptionForDynamicallyAddedParameterType(), getIconForDynamicallyAddedParameterType(), DynamicallyAddedParameter(), DynamicallyAddedParameterProps, DynamicallyAddedParameterType (+26 more)

### Community 11 - "index.tsx"
Cohesion: 0.31
Nodes (7): useAgentInstructionStyles, AgentInstructionEditor(), NavigateIcon, AGENT_INSTRUCTION_TYPES, AgentInstructions, parseAgentInstruction(), serializeAgentInstructions()

### Community 12 - "render"
Cohesion: 0.09
Nodes (21): CollapsedCard, CollapsedCardProps, FileDropZone(), FileDropZoneProps, FileHandler, useStyles, FoundryAgentPicker(), FoundryAgentPickerProps (+13 more)

### Community 13 - "CodeMirrorEditor.tsx"
Cohesion: 0.11
Nodes (21): CodeMirrorEditor, getLanguageExtension(), keybindingsCompartment, languageCompartment, readOnlyCompartment, themeCompartment, CodeMirrorEditorProps, CodeMirrorEditorRef (+13 more)

### Community 14 - "ChangeHandler"
Cohesion: 0.14
Nodes (17): AgentInstructionEditorProps, ChangeHandler, DropdownEditor(), DropdownEditorProps, DropdownItem, getSelectedKey(), getSelectedKeys(), SerializationOptions (+9 more)

### Community 15 - "util.ts"
Cohesion: 0.15
Nodes (20): cleanHtmlString(), cleanStyleAttribute(), decodeSegmentValueInDomContext(), decodeSegmentValueInLexicalContext(), encodeOrDecodeSegmentValue(), encodeSegmentValueInDomContext(), encodeSegmentValueInLexicalContext(), htmlEditorSupportedAttributes (+12 more)

### Community 16 - "index.tsx"
Cohesion: 0.11
Nodes (21): ChatButton(), ChatButtonProps, ChatIcon, CloseIcon, filterTextFieldStyles, navigateForwardIconProps, Overview(), OverviewProps (+13 more)

### Community 17 - "index.tsx"
Cohesion: 0.10
Nodes (16): DictionaryCallbackProps, ArrowNavigation(), AutoFocus(), AutoLink(), MATCHERS, ClearEditor(), ClearEditorProps, FocusChangePlugin() (+8 more)

### Community 18 - "assertion.tsx"
Cohesion: 0.14
Nodes (17): Assertion(), AssertionAddEvent, AssertionAddHandler, AssertionDeleteEvent, AssertionDeleteHandler, AssertionProps, AssertionUpdateEvent, AssertionUpdateHandler (+9 more)

### Community 19 - "helper.ts"
Cohesion: 0.07
Nodes (41): parseAuthEditor(), updateValues(), BuiltinToolOption, BuiltinToolsEditor(), BuiltinToolsEditorProps, useBuiltinToolsStyles, CollapsedDictionary(), CollapsedDictionaryProps (+33 more)

### Community 20 - "parsesegments.ts"
Cohesion: 0.05
Nodes (47): DynamicLoadStatus, ParameterDetails, ParameterInfo, TokenType, $createExtendedTextNode(), SerializedExtendedTextNode, $createPasswordNode(), $isPasswordNode() (+39 more)

### Community 21 - "conversationItem.ts"
Cohesion: 0.10
Nodes (27): useAzureCopilotButton(), useExternalLink(), useFeedbackMessage(), useReportBugButton(), AgentHeader(), AssistantError(), AssistantErrorProps, AssistantGreeting() (+19 more)

### Community 22 - "EventHandler"
Cohesion: 0.16
Nodes (16): SimpleDictionary(), SimpleDictionaryProps, useStyles, SimpleDictionaryChangeModel, SimpleDictionaryItem(), SimpleDictionaryItemProps, SimpleDictionaryRowModel, useStyles (+8 more)

### Community 23 - "util.ts"
Cohesion: 0.07
Nodes (71): useAgentInstructionStyles, AgentInstructionEditor(), AgentInstructionEditorProps, NavigateIcon, AGENT_INSTRUCTION_TYPES, AgentInstructions, parseAgentInstruction(), serializeAgentInstructions() (+63 more)

### Community 24 - "Format.tsx"
Cohesion: 0.20
Nodes (11): FormatBoldButton(), FormatBoldButtonProps, FormatButton(), FormatButtonProps, FormatItalicButton(), FormatItalicButtonProps, FormatLinkButton(), FormatLinkButtonProps (+3 more)

### Community 25 - "statusicon.tsx"
Cohesion: 0.12
Nodes (15): ToolReplyItem, badge, ToolReply(), Aborted(), Cancelled(), Failed(), Handoff(), Skipped() (+7 more)

### Community 26 - "filepickerPopoverHeader.tsx"
Cohesion: 0.17
Nodes (11): FilePickerPopover(), FilePickerProps, FilePickerPopoverHeader(), FilePickerPopoverHeaderItem(), FilePickerPopoverHeaderProps, useStyles, FilePickerPopoverItem(), FilePickerPopoverItemProps (+3 more)

### Community 27 - "tokenpickerfooter.tsx"
Cohesion: 0.15
Nodes (18): NoAgentParameters(), SearchVisual, AddIcon, SelectAgentParameterProps, ExpressionEditorEvent, TokenNodeProps, INSERT_TOKEN_NODE, InsertTokenNode() (+10 more)

### Community 28 - "RichTextToolbar.tsx"
Cohesion: 0.15
Nodes (13): HtmlViewToggleButton(), HtmlViewToggleButtonProps, RedoButton(), RedoButtonProps, UndoButton(), UndoButtonProps, CLOSE_DROPDOWN_COMMAND, DropdownProps (+5 more)

### Community 29 - "chatBubble.tsx"
Cohesion: 0.18
Nodes (10): ChatBubble(), ChatBubbleProps, ChatEntryReaction, CopyIcon, ChatEntryReaction, FeedbackMessage(), FeedbackMessageProps, IThumbsReactionButtonProps (+2 more)

### Community 30 - "flowPreview.tsx"
Cohesion: 0.12
Nodes (20): OperationInfo, FlowPreview(), FlowPreviewProps, IFlowDefinition, OperationContract, OperationPreview(), OperationPreviewProps, OperationsPreview() (+12 more)

### Community 31 - "index.tsx"
Cohesion: 0.10
Nodes (22): CreateAgentParameter(), CreateAgentParameterProps, generateDefaultAgentParamDescription(), generateDefaultAgentParamName(), options, SelectAgentParameter(), CLOSE_TOKENPICKER, CloseTokenPicker() (+14 more)

### Community 32 - "templatefunctions.ts"
Cohesion: 0.14
Nodes (16): FunctionDefinition, FunctionGroupDefinition, FunctionGroupDefinitions, intl, ParameterDetails, Resources, SignatureInfo, allCompletions (+8 more)

### Community 33 - "constants.ts"
Cohesion: 0.16
Nodes (13): getBrandColorWithOpacity(), opacityHexValues, CONDITION_RELATIONSHIP_VALUES, PANEL_TAB_NAMES, WORKFLOW_PARAMETER_SERIALIZED_TYPE, WORKFLOW_PARAMETER_TYPE, DELETE_TOKEN_NODE, OPEN_TOKEN_PICKER (+5 more)

### Community 34 - "progressCardWithStopButton.tsx"
Cohesion: 0.11
Nodes (17): animations, fadeIn, scaleFromLeft, scaleFromRight, slideFromBottom, backgroundMotion, ContainerWithProgressBar(), ContainerWithProgressBarProps (+9 more)

### Community 35 - "browseResults.tsx"
Cohesion: 0.12
Nodes (18): OperationGroupDetailsPageProps, mockOperationActionsData, mockOperationApi, OperationSearchCardProps, BrowseGrid(), BrowseGridProps, useBrowseResultStyles, Grid() (+10 more)

### Community 36 - "index.tsx"
Cohesion: 0.19
Nodes (13): ErrorBanner(), ErrorBannerProps, ICON_MAP, iconStyles, useCardKeyboardInteraction(), Card, CardProps, Gripper() (+5 more)

### Community 37 - "index.tsx"
Cohesion: 0.14
Nodes (23): HTTP_STATUS_CODE_OPTIONS, SettingProps, Expression(), ExpressionChangeHandler, ExpressionProps, Expressions(), ExpressionsEditor(), ExpressionsEditorProps (+15 more)

### Community 39 - "index.tsx"
Cohesion: 0.14
Nodes (14): ArrayEditorProps, CallbackHandler, ClearIcon, Combobox(), ComboboxItem, ComboboxProps, getDisplayValue(), getMode() (+6 more)

### Community 40 - "DropdownColorPicker.tsx"
Cohesion: 0.13
Nodes (15): basicColors, FONT_FAMILY_OPTIONS, FONT_SIZE_OPTIONS, DropDown(), FontDropDown(), FontDropdownProps, FontDropDownType, keyMoveMap (+7 more)

### Community 41 - "OpenTokenPicker.tsx"
Cohesion: 0.22
Nodes (11): Token, INITIALIZE_TOKENPICKER_AGENT_PARAMETER, TokenPickerAgentParameterHandler(), TokenPickerHandlerProps, INITIALIZE_TOKENPICKER_EXPRESSION, TokenPickerExpressionHandler(), TokenPickerHandlerProps, OPEN_TOKEN_PICKER (+3 more)

### Community 42 - "index.tsx"
Cohesion: 0.21
Nodes (10): calculateDuration(), StatusPill(), StatusPillProps, useStatusPillStyles, removeNewlinesAndSpaces(), getDurationString(), getDurationStringFromTimes(), getDurationStringPanelMode() (+2 more)

### Community 43 - "filepickerEditor.tsx"
Cohesion: 0.10
Nodes (18): EditorWrapper(), HTMLEditor(), FilePickerEditor(), FilePickerEditorProps, EditorChangePlugin(), EditorChangePluginProps, ChangeProps, EditorValueChange() (+10 more)

### Community 44 - "index.tsx"
Cohesion: 0.14
Nodes (18): DropdownControl(), DropdownProps, dropdownStyle, DropdownType, hoursDropdownStyles, timezoneDropdownStyles, Recurrence, ScheduleEditor() (+10 more)

### Community 45 - "workflowparametersField.tsx"
Cohesion: 0.24
Nodes (10): useWorkflowParameterStyles, WorkflowParameterUpdateHandler, getFieldBooleanValue(), getWorkflowParameterTypeDisplayNames(), isSecureParameter(), ParameterFieldDetails, stringifyValue(), textStyles (+2 more)

### Community 46 - "searchResult.tsx"
Cohesion: 0.20
Nodes (10): AriaSearchResultsAlert(), AriaSearchResultsAlertProps, useAriaSearchResultsStyles, SearchResultSortOption, SearchResultSortOptions, getDefaultRuntimeCategories(), RuntimeFilterTagList(), RuntimeFilterTagListProperties (+2 more)

### Community 47 - "operationsNeedAttentionMessage.tsx"
Cohesion: 0.13
Nodes (13): OperationsNeedingAttentionItem, OperationsNeedingAttentionOnUserAction, IFlowDiffPreviewProps, OperationInfoItemProps, OperationItem(), OperationItemProps, OperationItemsList(), OperationItemsListProps (+5 more)

### Community 48 - "TokenPickerMode"
Cohesion: 0.25
Nodes (7): TokenOption, TokenTypeAheadPlugin(), TokenTypeAheadPluginProps, TokenPickerMode, hideButtonOptions, TriggerFn, useTokenTypeaheadTriggerMatch()

### Community 49 - "index.tsx"
Cohesion: 0.16
Nodes (14): ChatInput, ChatInputHandle, ChatInputSubmitButtonProps, IChatInputProps, SendIcon, StopIcon, useStyles, ChatSuggestion() (+6 more)

### Community 50 - "index.tsx"
Cohesion: 0.17
Nodes (11): useConnectorSummaryCardStyles, ConnectorSummaryCard(), ConnectorSummaryCardProps, OperationRuntimeBadges(), OperationRuntimeBadgesProps, InfoDot(), InfoDotProps, useInfoDotStyles (+3 more)

### Community 51 - "CopyInputControlWithAgent.tsx"
Cohesion: 0.24
Nodes (11): AgentUrlButton, AgentUrlButtonProps, AgentUrlViewer(), AgentUrlViewerProps, IframeState, CopyInputControlWithAgent, CopyInputControlWithAgentProps, CopyIcon (+3 more)

### Community 53 - "outputMocks.tsx"
Cohesion: 0.19
Nodes (12): ActionResult(), ActionResultProps, OutputsSettings(), OutputsSettingsProps, ActionResults, ActionResultUpdateEvent, ActionResultUpdateHandler, MockUpdateEvent (+4 more)

### Community 54 - "designTokens.ts"
Cohesion: 0.21
Nodes (6): useBatchStyles, useDropdownDarkStyles, useStaticResultStyles, useCommonDarkThemeStyles, useCommonStyles, DesignTokens

### Community 55 - "index.ts"
Cohesion: 0.06
Nodes (14): CardContextMenuProps, FUIReactMenuItem, FloatingActionMenuKind, CardContextMenuProps, FUIReactMenuItem, CollapsedCard, CollapsedCardProps, FloatingActionMenuKind (+6 more)

### Community 56 - "assistantReplyWithFlow.tsx"
Cohesion: 0.13
Nodes (13): AssistantReplyWithFlow(), AssistantReplyWithFlowProps, changeIconMap, targetTypeDisplayNameMap, targetTypeIconMap, useStyles, AssistantReplyWithFlowItem, ConversationItemType (+5 more)

### Community 57 - "index.tsx"
Cohesion: 0.17
Nodes (13): ConnectorAvatar(), ConnectorAvatarProps, IApiReference, BaseRecommendationPanelCardProps, isOperationData(), OperationGroupData, OperationsData, RecommendationPanelCard() (+5 more)

### Community 58 - "index.tsx"
Cohesion: 0.19
Nodes (8): OperationSearchHeader(), OperationSearchHeaderProps, OperationSearchHeaderProps, OperationTypeFilter, OperationTypeFilterProps, DesignerSearchBox(), SearchBoxProps, useSearchBoxStyles

### Community 59 - "index.tsx"
Cohesion: 0.23
Nodes (9): useAddActionCardStyles, AddActionCardPropsV2, AddActionCardV2(), useAddActionCardV2Styles, ADD_CARD_TYPE, AddActionCard(), AddActionCardProps, getCardStyle() (+1 more)

### Community 60 - "index.ts"
Cohesion: 0.27
Nodes (6): isBuiltInConnector(), isCustomConnector(), getOperationCardDataFromOperation(), OperationActionDataFromOperation(), getConnectorAllCategories(), getConnectorCategoryString()

### Community 61 - "workflowparameters.tsx"
Cohesion: 0.23
Nodes (10): isHighContrastBlack(), useWorkflowParametersStyles, WorkflowParameterDeleteHandler, CloseIcon, CreateIcon, InfoBar(), OnClickHandler, WorkflowParameters() (+2 more)

### Community 62 - "hooks.ts"
Cohesion: 0.25
Nodes (8): WorkflowParametersErrorCardProps, hasModifier(), isDeleteKey(), isDownArrowKey(), isEnterKey(), isEscapeKey(), isSpaceKey(), isUpArrowKey()

### Community 63 - "connectionsSetupMessage.tsx"
Cohesion: 0.17
Nodes (12): ConnectionsSetup(), ConnectionsSetupMessage(), ConnectionsSetupMessageProps, ConnectionsSetupProps, ConnectionsLoading(), ConnectionStatus(), ConnectionStatusList(), ConnectionStatusListProps (+4 more)

### Community 64 - "workflowparameter.tsx"
Cohesion: 0.18
Nodes (10): DotProps, TrafficLightDot(), CollapseIcon, DeleteIcon, ExpandIcon, RegisterLanguageHandler, WorkflowParameter(), WorkflowParameterDeleteEvent (+2 more)

### Community 66 - "promptGuideContextualMenu.tsx"
Cohesion: 0.18
Nodes (9): PromptGuideCardProps, contextualMenuStyles, headerBackButtonStyles, IPromptGuideContextualMenuProps, PromptGuideContextualMenu(), PromptGuideItem, PromptGuideItemKey, PromptGuideMenuKey (+1 more)

### Community 67 - "cardfooter.tsx"
Cohesion: 0.15
Nodes (13): CardBadgeBar(), CardBadgeBarProps, CardBadgeProps, CardFooter, CardFooterProps, CommentBoxProps, CommentChangeEvent, MenuItemType (+5 more)

### Community 68 - "browseResults.tsx"
Cohesion: 0.12
Nodes (19): RecommendationPanelConstants, BrowseGrid(), BrowseGridProps, useBrowseResultStyles, Grid(), GridProps, useGridStyles, filterOperationData() (+11 more)

### Community 69 - "index.tsx"
Cohesion: 0.24
Nodes (7): Completed(), Empty(), MockStatusIcon(), MockStatusIconProps, useMockStatusIconStyles, OutputMock, getMockStatusString()

### Community 70 - "index.tsx"
Cohesion: 0.05
Nodes (52): useErrorStyles, HTTP_STATUS_CODE_OPTIONS, SettingProps, InputChangeHandler, SettingDictionary(), SettingDictionaryProps, useStyles, ValuesInDictionary() (+44 more)

### Community 71 - "index.tsx"
Cohesion: 0.29
Nodes (7): SearchableDropdown(), SearchableDropdownOption, SearchableDropdownProps, useSearchableDropdownStyles, SearchableDropdownWithAddAll(), SearchableDropdownWithAddAllProps, useSearchableDropdownWithAddAllStyles

### Community 72 - "index.tsx"
Cohesion: 0.26
Nodes (8): useConditionExpressionStyles, buttonStyles, ConditionExpression(), ConditionExpressionProps, getWindowDimensions(), pivotStyles, TokenPickerPivot(), TokenPickerPivotProps

### Community 73 - "index.tsx"
Cohesion: 0.26
Nodes (7): buildFoundryPortalUrl(), FoundryAgentDetails(), FoundryAgentDetailsProps, guidToBase64Url(), useFoundryAgentDetailsStyles, baseAgent, baseModels

### Community 74 - "settingreactiveinput.tsx"
Cohesion: 0.32
Nodes (7): ReactiveToggle(), ReactiveToggleProps, TextInputChangeHandler, SettingToggle(), SettingToggleProps, useStyles, ToggleChangeHandler

### Community 75 - "workflowparametersButtons.tsx"
Cohesion: 0.23
Nodes (8): WorkflowParameterDefinition, ButtonProps, DeleteIcon, EditIcon, EditOrDeleteButton(), EditOrDeleteButtonProps, WorkflowParameterDeleteEvent, WorkflowParameterDeleteHandler

### Community 76 - "index.tsx"
Cohesion: 0.29
Nodes (7): useAboutStyles, About(), AboutProps, BadgeProps, DocLinkClickedEventHandler, DocumentationItem(), DocumentationItemProps

### Community 77 - "index.tsx"
Cohesion: 0.29
Nodes (8): FavoriteButton(), IFavoriteButtonProps, useStyles, OperationSearchGroup(), OperationSearchGroupProps, OperationGroupHeaderNew(), OperationGroupHeaderNewProps, useOperationSearchGroupStyles

### Community 78 - "migrationHelpers.ts"
Cohesion: 0.25
Nodes (10): colorVariableMap, cssToCamelCase(), fontVariableMap, generateImports(), generateStyleHook(), sizeVariableMap, spacingVariableMap, transformRule() (+2 more)

### Community 79 - "settingdropdown.tsx"
Cohesion: 0.24
Nodes (8): DropdownIcon, DropdownItem, DropdownSelectionChangeHandler, IDropdownOption, SelectionChangedEvent, SettingDropdown(), SettingDropdownProps, useStyles

### Community 80 - "index.tsx"
Cohesion: 0.36
Nodes (7): BuiltInTextProps, LargeText(), MediumText(), SmallText(), TextProps, XLargeText(), XXLargeText()

### Community 81 - "nodeErrorCard.tsx"
Cohesion: 0.36
Nodes (4): MessageLevel, NodeMessage, ErrorSubsectionProps, NodeErrorCardProps

### Community 82 - "textInput.tsx"
Cohesion: 0.39
Nodes (7): BaseTextProps, convertStringToNumberArray(), MinuteTextInput(), MinuteTextProps, useStyles, TextInput(), TextProps

### Community 83 - "index.tsx"
Cohesion: 0.43
Nodes (4): useActionButtonV2Styles, ActionButtonV2(), ActionButtonV2Props, Plus()

### Community 84 - "index.tsx"
Cohesion: 0.29
Nodes (5): AssistedConnectionProps, AzureResourcePickerProps, fuseOptions, GetResourceCallback, ResourceEntryProps

### Community 85 - "ValueSegment"
Cohesion: 0.06
Nodes (42): CollapsedAuthEditorItems, CollapsedDictionaryValidation(), serializeDictionary(), EditorWrapper(), BaseEditor(), $isTokenNode(), SerializedTokenNode, TokenNode (+34 more)

### Community 86 - "settingtextfield.tsx"
Cohesion: 0.52
Nodes (3): useErrorStyles, SettingTextField(), SettingTextFieldProps

### Community 87 - "index.tsx"
Cohesion: 0.43
Nodes (4): NodeCollapseToggle(), NodeCollapseToggleProps, useNodeCollapseToggleStyles, nodeButtonInteraction()

### Community 88 - "index.tsx"
Cohesion: 0.08
Nodes (55): ActiveDirectoryAuthentication(), ActiveDirectoryAuthenticationProps, AuthenticationOAuthType, zipDropDownOptions(), AadOAuthCredentials(), AadOAuthCredentialsProps, AuthenticationDropdown(), AuthenticationDropdownProps (+47 more)

### Community 89 - "index.tsx"
Cohesion: 0.48
Nodes (4): Tip(), TipButton, TipProps, useTipStyles

### Community 90 - "tokenpickersection.tsx"
Cohesion: 0.31
Nodes (5): AnnouncedMatches(), AnnouncedMatchesProps, TokenPickerNoDynamicContent(), TokenPickerNoMatches(), TokenPickerSection()

### Community 91 - "index.tsx"
Cohesion: 0.53
Nodes (3): useGraphContainerStyles, GraphContainer(), GraphContainerProps

### Community 92 - "index.tsx"
Cohesion: 0.47
Nodes (3): Peek(), PeekProps, usePeekStyles

### Community 93 - "settingmultiselect.tsx"
Cohesion: 0.53
Nodes (4): MultiSelectOption, MultiSelectSetting(), MultiSelectSettingProps, StatusChangeHandler

### Community 94 - "templatesSectionModel.ts"
Cohesion: 0.05
Nodes (43): KnowledgeConnectionTabProps, KnowledgeTabProps, OnTabNavigation, McpConnectorTabProps, McpCreateAppTabProps, McpPanelTabProps, CustomFieldInput(), FieldSectionItem() (+35 more)

### Community 95 - "index.tsx"
Cohesion: 0.60
Nodes (3): dropdownStyles, IdentityDropdown(), IdentityDropdownProps

### Community 106 - "index.tsx"
Cohesion: 0.11
Nodes (47): addIcon, AddSection(), AddSectionProps, calloutProps, Group(), GroupProps, menuIconProps, MoveOption (+39 more)

### Community 107 - "workflowparameter.tsx"
Cohesion: 0.06
Nodes (42): DotProps, TrafficLightDot(), isHighContrastBlack(), useWorkflowParametersStyles, useWorkflowParameterStyles, CollapseIcon, DeleteIcon, ExpandIcon (+34 more)

### Community 108 - "util.ts"
Cohesion: 0.06
Nodes (47): actionButtonStyles, StaticResultChangeHandler, StaticResultContainer(), StaticResultContainerProps, StaticResultOption, StaticResultRootSchemaType, addItemButtonIconProps, calloutTextFieldStyles (+39 more)

### Community 109 - "settingTokenField.tsx"
Cohesion: 0.08
Nodes (37): useCodeEditorStyles, EditableFileNameProps, CodeEditor(), CodeEditorProps, customCodeIconStyle, FileNameChangeHandler, buildInlineCodeTextFromToken(), formatForCSharp() (+29 more)

### Community 110 - "util.ts"
Cohesion: 0.10
Nodes (40): createEmptyLiteralValueSegment(), isSingleLiteralValueSegment(), isTokenValueSegment(), convertSegmentsToString(), isEmptySegments(), CreateIcon, InitializeVariableEditor(), InitializeVariableEditorProps (+32 more)

### Community 111 - "index.tsx"
Cohesion: 0.07
Nodes (30): getIconForDynamicallyAddedParameterType(), DictionaryCallbackProps, ArrowNavigation(), $isTargetWithinDecorator(), AutoFocus(), AutoLink(), MATCHERS, ClearEditor() (+22 more)

### Community 112 - "index.tsx"
Cohesion: 0.09
Nodes (21): ChatButton(), ChatButtonProps, ChatIcon, CloseIcon, filterTextFieldStyles, navigateForwardIconProps, Overview(), OverviewProps (+13 more)

### Community 113 - "index.tsx"
Cohesion: 0.08
Nodes (21): CardBadgeBar(), CardBadgeBarProps, CardBadgeProps, CardFooter, CardFooterProps, ErrorBanner(), ErrorBannerProps, ICON_MAP (+13 more)

### Community 114 - "panelcontainer.tsx"
Cohesion: 0.10
Nodes (29): PanelContainer(), PanelContainerProps, ChevronRightIcon, DismissIcon, handleOnEscapeDown(), OverflowIcon, PanelHeader(), PanelHeaderProps (+21 more)

### Community 115 - "index.tsx"
Cohesion: 0.09
Nodes (31): CollapsedDictionary(), CollapsedDictionaryProps, ExpandedDictionary(), ExpandedDictionaryEditorType, ExpandedDictionaryProps, isEmpty(), deleteButtonIconProps, DictionaryDeleteButton() (+23 more)

### Community 116 - "conversationItem.ts"
Cohesion: 0.09
Nodes (26): AgentHeader(), AssistantGreeting(), useAssistantGreetingStyles, AdditionalParametersItem, AgentHeaderItem, AgentMessageEntryType, AssistantGreetingItem, AssistantReplyItem (+18 more)

### Community 117 - "index.tsx"
Cohesion: 0.11
Nodes (29): DynamicallyAddedParameterIcon, generateDynamicParameterKey(), getDefaultTitleForDynamicallyAddedParameterType(), getDescriptionForDynamicallyAddedParameterType(), DynamicallyAddedParameter(), DynamicallyAddedParameterProps, DynamicallyAddedParameterType, DynamicallyAddedParameterTypeType (+21 more)

### Community 118 - "parsesegments.ts"
Cohesion: 0.15
Nodes (30): decodeStringSegmentTokensInDomContext(), decodeStringSegmentTokensInLexicalContext(), encodeOrDecodeStringSegmentTokens(), encodeStringSegmentTokensInDomContext(), encodeStringSegmentTokensInLexicalContext(), processStringSegmentTokensInDomAndLexicalContext(), canReplaceSpanWithId(), convertEditorState() (+22 more)

### Community 119 - "searchResult.tsx"
Cohesion: 0.13
Nodes (18): AriaSearchResultsAlert(), AriaSearchResultsAlertProps, useAriaSearchResultsStyles, isBuiltInConnector(), isCustomConnector(), getDefaultRuntimeCategories(), getOperationCardDataFromOperation(), OperationActionDataFromOperation() (+10 more)

### Community 120 - "RichTextToolbar.tsx"
Cohesion: 0.09
Nodes (25): getURL(), parseHtmlSegments(), HtmlViewToggleButton(), HtmlViewToggleButtonProps, RedoButton(), RedoButtonProps, UndoButton(), UndoButtonProps (+17 more)

### Community 121 - "index.tsx"
Cohesion: 0.11
Nodes (27): DropdownControl(), DropdownProps, dropdownStyle, DropdownType, hoursDropdownStyles, timezoneDropdownStyles, Recurrence, ScheduleEditor() (+19 more)

### Community 122 - "createLiteralValueSegment"
Cohesion: 0.12
Nodes (23): BuiltinToolOption, BuiltinToolsEditor(), BuiltinToolsEditorProps, useBuiltinToolsStyles, DropdownEditor(), DropdownEditorProps, DropdownItem, getSelectedKey() (+15 more)

### Community 123 - "nodeErrorCard.tsx"
Cohesion: 0.14
Nodes (18): MessageLevel, NodeMessage, ErrorSubsection(), ErrorSubsectionProps, NodeErrorCard(), NodeErrorCardProps, WorkflowParametersErrorCard(), WorkflowParametersErrorCardProps (+10 more)

### Community 124 - "index.tsx"
Cohesion: 0.21
Nodes (12): BodyLinkValue(), DateTimeValue(), options, DecimalValue(), localizeDecimalNumber(), KeyValuePairs(), NumberValue(), RawValue() (+4 more)

### Community 125 - "statusicon.tsx"
Cohesion: 0.13
Nodes (15): ToolReplyItem, badge, ToolReply(), Aborted(), Cancelled(), Failed(), Handoff(), Skipped() (+7 more)

### Community 126 - "Format.tsx"
Cohesion: 0.14
Nodes (19): buttonStyles, FloatingLinkEditor(), FloatingLinkEditorToolbar(), FormatBoldButton(), FormatBoldButtonProps, FormatButton(), FormatButtonProps, FormatItalicButton() (+11 more)

### Community 127 - "index.ts"
Cohesion: 0.08
Nodes (4): NodeCollapseToggle(), NodeCollapseToggleProps, useNodeCollapseToggleStyles, nodeButtonInteraction()

### Community 128 - "PasswordNode"
Cohesion: 0.10
Nodes (12): $createPasswordNode(), $isPasswordNode(), PasswordNode, SerializedPasswordNode, buttonStyles, CloseEye, EyeIcon, PasswordMaskPlugin() (+4 more)

### Community 129 - "index.tsx"
Cohesion: 0.14
Nodes (11): DocumentationLinkItem(), DocumentationLinkItemProps, calloutContentStyles, FlyoutBalloon(), FlyoutBalloonProps, Flyout2(), Flyout2Props, onDragStartWhenDisabled (+3 more)

### Community 130 - "index.ts"
Cohesion: 0.11
Nodes (19): allCompletions, functionCompletions, keywordCompletions, keywords, workflowCompletion(), functionNames, keywords, workflowHighlighting (+11 more)

### Community 131 - "flowPreview.tsx"
Cohesion: 0.13
Nodes (20): OperationInfo, FlowPreview(), FlowPreviewProps, IFlowDefinition, OperationContract, OperationPreview(), OperationPreviewProps, OperationsPreview() (+12 more)

### Community 132 - "index.tsx"
Cohesion: 0.13
Nodes (15): useConnectorSummaryCardStyles, ConnectorSummaryCard(), ConnectorSummaryCardProps, OperationRuntimeBadges(), OperationRuntimeBadgesProps, mockConnector, mockFavoriteContext, FavoriteButton() (+7 more)

### Community 133 - "CodeMirrorEditorRef"
Cohesion: 0.13
Nodes (9): ButtonOffSet, ButtonProps, TokenPickerButtonLegacy(), TokenPickerButtonProps, CodeMirrorEditor, CodeMirrorEditorRef, CursorPositionChangedEvent, EditorContentChangedEvent (+1 more)

### Community 134 - "progressCardWithStopButton.tsx"
Cohesion: 0.12
Nodes (17): animations, fadeIn, scaleFromLeft, scaleFromRight, slideFromBottom, backgroundMotion, ContainerWithProgressBar(), ContainerWithProgressBarProps (+9 more)

### Community 135 - "index.tsx"
Cohesion: 0.14
Nodes (15): ErrorSection(), ErrorSectionProps, ErrorShape, RetryPanel(), RetryPanelProps, ChevronLeftIcon, ChevronRightIcon, FailedIterationPagerProps (+7 more)

### Community 136 - "designTokens.ts"
Cohesion: 0.15
Nodes (9): useBatchStyles, useGraphContainerStyles, GraphContainer(), GraphContainerProps, useDropdownDarkStyles, useStaticResultStyles, useCommonDarkThemeStyles, useCommonStyles (+1 more)

### Community 137 - "index.tsx"
Cohesion: 0.14
Nodes (13): ChatInput, ChatInputHandle, ChatInputSubmitButtonProps, IChatInputProps, SendIcon, StopIcon, useStyles, ChatSuggestion() (+5 more)

### Community 138 - "index.tsx"
Cohesion: 0.18
Nodes (14): isComboboxItemMatch(), ClearIcon, Combobox(), ComboboxProps, getDisplayValue(), getMode(), getOptions(), getSelectedKey() (+6 more)

### Community 139 - "initialConfig.ts"
Cohesion: 0.13
Nodes (11): $createExtendedTextNode(), ExtendedTextNode, patchStyleConversion(), SerializedExtendedTextNode, theme, defaultInitialConfig, defaultNodes, htmlNodes (+3 more)

### Community 140 - "filepickerPopoverHeader.tsx"
Cohesion: 0.17
Nodes (11): FilePickerPopover(), FilePickerProps, FilePickerPopoverHeader(), FilePickerPopoverHeaderItem(), FilePickerPopoverHeaderProps, useStyles, FilePickerPopoverItem(), FilePickerPopoverItemProps (+3 more)

### Community 141 - "useCardKeyboardInteraction"
Cohesion: 0.21
Nodes (9): useAddActionCardStyles, AddActionCardPropsV2, AddActionCardV2(), useAddActionCardV2Styles, ADD_CARD_TYPE, AddActionCard(), AddActionCardProps, getCardStyle() (+1 more)

### Community 142 - "operationsNeedAttentionMessage.tsx"
Cohesion: 0.12
Nodes (14): OperationsNeedingAttentionItem, OperationsNeedingAttentionOnUserAction, IFlowDiffPreviewProps, OperationInfoItemProps, OperationItem(), OperationItemProps, OperationItemsList(), OperationItemsListProps (+6 more)

### Community 143 - "CopyInputControlWithAgent.tsx"
Cohesion: 0.22
Nodes (11): AgentUrlButton, AgentUrlButtonProps, AgentUrlViewer(), AgentUrlViewerProps, IframeState, CopyInputControlWithAgent, CopyInputControlWithAgentProps, CopyIcon (+3 more)

### Community 144 - "tokenpickeroption.tsx"
Cohesion: 0.19
Nodes (13): ExpressionEditorEvent, TokenPickerProps, TokenPickerFooterProps, SelectAgentParameterProps, getReducedTokenList(), TokenPickerNoDynamicContent(), GetValueSegmentHandler, SearchOutputToken (+5 more)

### Community 145 - "assistantReplyWithFlow.tsx"
Cohesion: 0.16
Nodes (12): AssistantError(), AssistantReplyWithFlow(), AssistantReplyWithFlowProps, changeIconMap, TODO: add check for if isUsingDebugOptions, targetTypeDisplayNameMap, targetTypeIconMap, useStyles (+4 more)

### Community 146 - "index.tsx"
Cohesion: 0.17
Nodes (9): CollapseIcon, ExpandIcon, ValuesPanel(), ValuesPanelProps, ValueDownload(), ValueDownloadProps, ChevronIcon, ValueLink() (+1 more)

### Community 147 - "index.tsx"
Cohesion: 0.16
Nodes (13): ConnectorAvatar(), ConnectorAvatarProps, IApiReference, BaseRecommendationPanelCardProps, isOperationData(), OperationGroupData, OperationsData, RecommendationPanelCard() (+5 more)

### Community 148 - "index.tsx"
Cohesion: 0.23
Nodes (9): DocumentationLinkItem(), DocumentationLinkItemProps, FlyoutBalloon(), FlyoutBalloonProps, Flyout2(), Flyout2Props, onDragStartWhenDisabled, FlyoutSelectedEventArgs (+1 more)

### Community 149 - "index.tsx"
Cohesion: 0.24
Nodes (10): getSignatureAtPosition(), SignatureInfo, templateFunctions, ExpressionEditorSignature(), ExpressionEditorSignatureProps, useStyles, ExpressionEditor(), ExpressionEditorProps (+2 more)

### Community 150 - "index.tsx"
Cohesion: 0.20
Nodes (9): useFlyoutStyles, FlyoutCallout(), FlyoutCalloutProps, focusTrapProps, styles, defaultTooltipHostStyles, Flyout, FlyoutProps (+1 more)

### Community 151 - "index.tsx"
Cohesion: 0.19
Nodes (8): OperationSearchHeader(), OperationSearchHeaderProps, OperationSearchHeaderProps, OperationTypeFilter, OperationTypeFilterProps, DesignerSearchBox(), SearchBoxProps, useSearchBoxStyles

### Community 152 - "index.tsx"
Cohesion: 0.18
Nodes (13): calloutStyles, calloutStylesWithTopMargin, getWindowDimensions(), SearchTextChangedEventHandler, TokenPicker(), pivotStyles, TokenPickerPivot(), TokenPickerPivotProps (+5 more)

### Community 153 - "chatBubble.tsx"
Cohesion: 0.17
Nodes (11): AssistantErrorProps, ChatBubble(), ChatBubbleAction, ChatBubbleProps, ChatEntryReaction, CopyIcon, AssistantErrorItem, TechnicalErrorMessage() (+3 more)

### Community 154 - "CodeMirrorEditor.tsx"
Cohesion: 0.18
Nodes (9): getLanguageExtension(), keybindingsCompartment, languageCompartment, readOnlyCompartment, themeCompartment, workflow(), createFluentTheme(), darkColors (+1 more)

### Community 155 - "index.tsx"
Cohesion: 0.24
Nodes (10): InfoDot(), InfoDotProps, useInfoDotStyles, BuiltInTextProps, LargeText(), MediumText(), SmallText(), TextProps (+2 more)

### Community 156 - "panelcontent.tsx"
Cohesion: 0.17
Nodes (9): MoreHorizontal, OverflowMenuItemProps, OverflowMenuProps, PanelContent(), PanelContentProps, TODO: 12798935 Analytics (event logging), TODO: 13865562 When Tabs get setup, PageActionTelemetryData (+1 more)

### Community 157 - "index.tsx"
Cohesion: 0.24
Nodes (9): useFlyoutStyles, FlyoutCallout(), FlyoutCalloutProps, focusTrapProps, styles, defaultTooltipHostStyles, Flyout, FlyoutProps (+1 more)

### Community 158 - "HTMLChangePlugin.tsx"
Cohesion: 0.24
Nodes (10): canReplaceSpanWithId(), HTMLChangePlugin(), HTMLChangePluginProps, getDomFromHtmlEditorString(), decodeStringSegmentTokensInDomContext(), decodeStringSegmentTokensInLexicalContext(), encodeOrDecodeStringSegmentTokens(), encodeStringSegmentTokensInDomContext() (+2 more)

### Community 159 - "promptGuideContextualMenu.tsx"
Cohesion: 0.19
Nodes (10): PromptGuideCardProps, contextualMenuStyles, headerBackButtonStyles, IPromptGuideContextualMenuProps, menuItemKey(), PromptGuideContextualMenu(), PromptGuideItem, PromptGuideItemKey (+2 more)

### Community 160 - "tokenpickerfooter.tsx"
Cohesion: 0.23
Nodes (10): $createTokenNode(), INSERT_TOKEN_NODE, InsertTokenNode(), PastePlugin(), FxIcon(), IconProps, UPDATE_TOKEN_NODE, TokenPickerFooter() (+2 more)

### Community 161 - "connectionsSetupMessage.tsx"
Cohesion: 0.19
Nodes (11): ConnectionsSetup(), ConnectionsSetupMessage(), ConnectionsSetupMessageProps, ConnectionsSetupProps, TODO: currently just using two filler apis, need to grab connections, ConnectionsLoading(), ConnectionStatusList(), ConnectionStatusListProps (+3 more)

### Community 162 - "xml.tsx"
Cohesion: 0.26
Nodes (9): ClockIcon, Colorizer(), ColorizerProps, CopyIcon, UTCDateTimeProps, isXml(), encoded_atob(), removeByteOrderMark() (+1 more)

### Community 163 - "OpenTokenPicker.tsx"
Cohesion: 0.24
Nodes (10): OPEN_TOKEN_PICKER_PAYLOAD, OpenTokenPicker(), OpenTokenPickerProps, Token, INITIALIZE_TOKENPICKER_AGENT_PARAMETER, TokenPickerAgentParameterHandler(), TokenPickerHandlerProps, INITIALIZE_TOKENPICKER_EXPRESSION (+2 more)

### Community 164 - "DropdownColorPicker.tsx"
Cohesion: 0.22
Nodes (10): Props, TextInput(), DropdownColorPicker(), DropdownColorPickerProps, basicColors, clamp(), keyMoveMap, MoveWrapper() (+2 more)

### Community 165 - "index.tsx"
Cohesion: 0.26
Nodes (8): StatusPill(), StatusPillProps, useStatusPillStyles, calculateDuration(), getDurationString(), getDurationStringFromTimes(), getDurationStringPanelMode(), getStatusString()

### Community 166 - "index.tsx"
Cohesion: 0.29
Nodes (7): SearchableDropdown(), SearchableDropdownOption, SearchableDropdownProps, useSearchableDropdownStyles, SearchableDropdownWithAddAll(), SearchableDropdownWithAddAllProps, useSearchableDropdownWithAddAllStyles

### Community 167 - "generator.ts"
Cohesion: 0.26
Nodes (9): InvalidJsonSchemaTypeException, generateSchemaForObject(), generateSchemaFromArray(), generateSchemaFromJsonString(), generateSchemaFromValue(), getJsonSchemaType(), SchemaObject, tryConvertStringToExpression() (+1 more)

### Community 168 - "index.tsx"
Cohesion: 0.27
Nodes (7): useAboutStyles, About(), AboutProps, BadgeProps, DocLinkClickedEventHandler, DocumentationItem(), DocumentationItemProps

### Community 170 - "index.tsx"
Cohesion: 0.26
Nodes (7): buildFoundryPortalUrl(), FoundryAgentDetails(), FoundryAgentDetailsProps, guidToBase64Url(), useFoundryAgentDetailsStyles, baseAgent, baseModels

### Community 171 - "simpledictionary.tsx"
Cohesion: 0.27
Nodes (8): SimpleDictionary(), SimpleDictionaryProps, useStyles, SimpleDictionaryChangeModel, SimpleDictionaryItem(), SimpleDictionaryItemProps, SimpleDictionaryRowModel, useStyles

### Community 172 - "generator.ts"
Cohesion: 0.27
Nodes (9): InvalidJsonSchemaTypeException, generateSchemaForObject(), generateSchemaFromArray(), generateSchemaFromJsonString(), generateSchemaFromValue(), getJsonSchemaType(), SchemaObject, tryConvertStringToExpression() (+1 more)

### Community 173 - "functions.ts"
Cohesion: 0.25
Nodes (7): getSelectedNode(), processNodeType(), sanitizeUrl(), setFloatingElemPositionForLinkEditor(), SUPPORTED_URL_PROTOCOLS, buttonStyles, FloatingLinkEditor()

### Community 175 - "migrationHelpers.ts"
Cohesion: 0.25
Nodes (10): colorVariableMap, cssToCamelCase(), fontVariableMap, generateImports(), generateStyleHook(), sizeVariableMap, spacingVariableMap, transformRule() (+2 more)

### Community 176 - "TokenTypeahead.tsx"
Cohesion: 0.29
Nodes (7): hideButtonOptions, TokenMenuItem(), TokenOption, TokenTypeAheadPlugin(), TokenTypeAheadPluginProps, TriggerFn, useTokenTypeaheadTriggerMatch()

### Community 177 - "index.tsx"
Cohesion: 0.36
Nodes (4): useActionButtonV2Styles, Plus(), ActionButtonV2(), ActionButtonV2Props

### Community 178 - "index.tsx"
Cohesion: 0.39
Nodes (5): Checkbox(), CheckboxProps, CheckboxState, useCheckboxDescriptionCalloutStyles, useCheckboxStyles

### Community 179 - "CloseTokenPicker.tsx"
Cohesion: 0.25
Nodes (7): CLOSE_TOKENPICKER, CloseTokenPicker(), CloseTokenPickerPaylaod, CloseTokenPickerProps, buttonStyles, TokenPickerHeader(), TokenPickerHeaderProps

### Community 180 - "SelectAgentParameter.tsx"
Cohesion: 0.28
Nodes (6): SINGLE_VALUE_SEGMENT, SingleValueSegment(), NoAgentParameters(), SearchVisual, AddIcon, SelectAgentParameter()

### Community 181 - "index.tsx"
Cohesion: 0.31
Nodes (5): FoundryAgentPicker(), FoundryAgentPickerProps, useFoundryAgentPickerStyles, mockAgents, mockModels

### Community 182 - "assertionField.tsx"
Cohesion: 0.29
Nodes (7): GetConditionExpressionHandler, AssertionField(), AssertionFieldProps, fieldStyles, labelStyles, ParameterFieldDetails, textFieldStyles

### Community 183 - "index.tsx"
Cohesion: 0.29
Nodes (5): AssistedConnectionProps, AzureResourcePickerProps, fuseOptions, GetResourceCallback, ResourceEntryProps

### Community 184 - "index.tsx"
Cohesion: 0.39
Nodes (4): FileDropZone(), FileDropZoneProps, FileHandler, useStyles

### Community 185 - "DeleteNodeModal.tsx"
Cohesion: 0.43
Nodes (3): DeleteNodeModal(), DeleteNodeModalProps, useModalStyles

### Community 186 - "interactionTagList.tsx"
Cohesion: 0.32
Nodes (5): interactionTagDefaultProps, InteractionTagItem, InteractionTagList(), InteractionTagListProps, useInteractionTagListStyles

### Community 187 - "index.tsx"
Cohesion: 0.43
Nodes (4): Tip(), TipButton, TipProps, useTipStyles

### Community 188 - "index.tsx"
Cohesion: 0.38
Nodes (5): useEditorCollapseToggleStyles, calloutProps, EditorCollapseToggle(), EditorCollapseToggleProps, inlineBlockStyle

### Community 189 - "interactionTagList.tsx"
Cohesion: 0.38
Nodes (5): interactionTagDefaultProps, InteractionTagItem, InteractionTagList(), InteractionTagListProps, useInteractionTagListStyles

### Community 190 - "useId"
Cohesion: 0.53
Nodes (3): BaseEditor(), HtmlValue(), useId()

### Community 191 - "index.tsx"
Cohesion: 0.53
Nodes (3): AnnouncedMatches(), AnnouncedMatchesProps, TokenPickerNoMatches()

### Community 194 - "index.tsx"
Cohesion: 0.47
Nodes (3): Peek(), PeekProps, usePeekStyles

### Community 195 - "index.tsx"
Cohesion: 0.47
Nodes (3): dropdownStyles, IdentityDropdown(), IdentityDropdownProps

### Community 196 - "Value"
Cohesion: 0.47
Nodes (3): Value(), ValueList(), ValueListProps

### Community 197 - "utils.ts"
Cohesion: 0.53
Nodes (4): Xml, isContentHash(), isContentLink(), isSecureData()

### Community 198 - "fluent.ts"
Cohesion: 0.47
Nodes (3): createFluentTheme(), darkColors, lightColors

### Community 199 - "DropdownBlockFormat.tsx"
Cohesion: 0.60
Nodes (4): dropDownActiveClass(), BlockFormatDropDown(), BlockFormatDropDownProps, blockTypeToBlockName

### Community 200 - "index.tsx"
Cohesion: 0.60
Nodes (3): ModalDialog(), ModalDialogProps, useModalDialogStyles

### Community 201 - "index.tsx"
Cohesion: 0.60
Nodes (3): ModalDialog(), ModalDialogProps, useModalDialogStyles

### Community 202 - "workflowparametersFooter.tsx"
Cohesion: 0.40
Nodes (3): navigateIconStyle, OnClickHandler, WorkflowParametersFooterProps

## Knowledge Gaps
- **824 isolated node(s):** `cache`, `intl`, `NavigateIcon`, `AgentInstructions`, `AriaSearchResultsAlertProps` (+819 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **22 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `CodeMirrorEditorRef` connect `CodeMirrorEditorRef` to `settingTokenField.tsx`, `tokenpickeroption.tsx`, `index.tsx`, `index.tsx`, `CodeMirrorEditor.tsx`?**
  _High betweenness centrality (0.026) - this node is a cross-community bridge._
- **Why does `useId()` connect `useId` to `index.tsx`, `util.ts`, `index.tsx`, `settingTokenField.tsx`, `simpledictionary.tsx`, `settingTokenField.tsx`, `util.ts`, `index.tsx`, `index.tsx`, `index.tsx`, `ValueSegment`, `EventHandler`, `index.tsx`?**
  _High betweenness centrality (0.015) - this node is a cross-community bridge._
- **Why does `EventHandler` connect `EventHandler` to `workflowparameter.tsx`, `index.tsx`, `simpledictionary.tsx`, `workflowparameter.tsx`, `CodeMirrorEditor.tsx`, `workflowparametersButtons.tsx`, `assertion.tsx`, `index.tsx`, `outputMocks.tsx`?**
  _High betweenness centrality (0.013) - this node is a cross-community bridge._
- **What connects `cache`, `intl`, `NavigateIcon` to the rest of the system?**
  _824 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `index.tsx` be split into smaller, more focused modules?**
  _Cohesion score 0.050883898709985664 - nodes in this community are weakly interconnected._
- **Should `templatesSectionModel.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.052884615384615384 - nodes in this community are weakly interconnected._
- **Should `util.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.08408163265306122 - nodes in this community are weakly interconnected._