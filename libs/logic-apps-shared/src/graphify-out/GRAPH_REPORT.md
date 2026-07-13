# Graph Report - src  (2026-07-13)

## Corpus Check
- 351 files · ~635,999 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 4998 nodes · 11037 edges · 205 communities (180 shown, 25 thin omitted)
- Extraction: 100% EXTRACTED · 0% INFERRED · 0% AMBIGUOUS · INFERRED: 14 edges (avg confidence: 0.59)
- Token cost: 0 input · 0 output

## Graph Freshness
- Built from commit: `f4e3a3f2`
- Run `git rev-parse HEAD` and compare to check if the graph is stale.
- Run `graphify update .` after code changes (no API cost).

## Community Hubs (Navigation)
- logicAppsV2.ts
- search.ts
- functions.ts
- copilotWorkflowEditorParsing.ts
- index.ts
- operationmanifest.ts
- BaseException
- operationmanifest.ts
- operation.ts
- openApiV2.ts
- logicApps.ts
- badges.ts
- swagger.ts
- connection.ts
- operationmanifest.ts
- Connector
- connector.ts
- logicAppsV2.ts
- connector.ts
- operationmanifest.ts
- run.ts
- index.ts
- stringFunctions.ts
- Connector
- BaseTemplateService
- run.ts
- connections.ts
- connection.ts
- SchemaProcessor
- keysutility.ts
- connector.ts
- copilotWorkflowEditorTools.ts
- parser.ts
- operationmanifest.ts
- logger.ts
- template.ts
- functions.ts
- index.ts
- resource.ts
- utils.ts
- Action
- operationmanifest.ts
- xml.ts
- index.ts
- parseJson.ts
- index.ts
- RetryableActionInputs
- ResolutionService
- parameterprocessor.ts
- index.ts
- index.ts
- index.ts
- httpClient.ts
- ExpressionScanner
- hooks.ts
- intl.tsx
- BaseException
- logicAppsV2Integration.ts
- index.ts
- equals
- chatbot.ts
- operationmanifest.ts
- oAuth.ts
- index.ts
- connection.ts
- uiInteractionsService.ts
- logicAppsIntegration.ts
- run.ts
- uritemplateparser.ts
- Expression
- color.ts
- dataMap.ts
- experimentation.ts
- dataMapSchema.ts
- getIntl
- equals
- connectors.ts
- openApiV2.ts
- logicApps.ts
- editor.ts
- operation.ts
- index.ts
- keysutility.ts
- operations.ts
- dataoperations.ts
- swagger.ts
- parser.ts
- datetime.spec.ts
- Use Cases
- index.ts
- knowledge.ts
- Action
- TimeoutableAction
- Trigger
- getAzureResourceRecursive
- BaseUserPreferenceService
- operationgroups.ts
- index.ts
- logicAppsV2Expression.ts
- index.ts
- index.ts
- ICognitiveServiceService
- RetryableActionInputs
- Trigger
- control.ts
- datetime.ts
- http.ts
- variables.ts
- IHttpClient
- BaseConnectionService
- version.ts
- run.ts
- utils.ts
- evaluator.ts
- ArmResource
- search.ts
- schedule.ts
- BaseTemplateService
- operationmanifest.ts
- DiscoveryOpArray
- ScopeAction
- outputprocessor.ts
- TestSearchService
- agent.ts
- agent.ts
- agentloop.spec.ts
- inlinecode.ts
- inlineCode.ts
- HttpWebhookInputs
- stringFunctions.ts
- WorkflowRunAction
- Operation
- parameterprocessor.ts
- connections.ts
- index.ts
- index.ts
- SchemaProcessor
- connector.ts
- template.ts
- BaseFunctionService
- Action
- gateway.ts
- StandardRunService
- parseJson.ts
- copilotWorkflowEditorTools.ts
- RetryableActionInputs
- validateRequiredServiceArguments
- BaseApiManagementService
- oAuth.ts
- templateresource.ts
- ExpressionScanner
- hooks.ts
- logicAppsV2Integration.ts
- BaseSearchService
- uritemplateparser.ts
- Trigger
- chatbot.ts
- connectionParameterEditor.ts
- validateRequiredServiceArguments
- uiInteractionsService.ts
- builder.ts
- logicAppsIntegration.ts
- BaseCognitiveServiceService
- experimentation.ts
- parser.ts
- color.ts
- dataMap.ts
- connectors.ts
- tenant.ts
- host.ts
- getHybridAppBaseRelativeUrl
- dataMapSchema.ts
- index.ts
- clone.ts
- dataoperations.ts
- BaseUserPreferenceService
- operations.ts
- ConsumptionOperationManifestService
- datetime.spec.ts
- ExpressionParser
- dereference.ts
- Use Cases
- Action
- TimeoutableAction
- dereference.ts
- knowledge.ts
- logicAppsV2Expression.ts
- guid
- control.ts
- datetime.ts
- http.ts
- RetryableActionInputs
- Trigger
- rosettanet.ts
- customcode.ts
- version.ts
- apiManagement.ts
- dereferenceJsonSchema.ts
- ._fuzzyEvaluate
- parameters.ts
- ScopeAction
- agentloop.spec.ts
- HttpWebhookInputs
- WorkflowRunAction

## God Nodes (most connected - your core abstractions)
1. `equals()` - 95 edges
2. `equals()` - 74 edges
3. `IHttpClient` - 65 edges
4. `Connector` - 60 edges
5. `OperationManifest` - 59 edges
6. `IHttpClient` - 59 edges
7. `OperationManifest` - 58 edges
8. `Connector` - 53 edges
9. `getIntl()` - 38 edges
10. `SwaggerParser` - 38 edges

## Surprising Connections (you probably didn't know these)
- `getTriggerType()` --calls--> `getIntl()`  [EXTRACTED]
  utils/src/lib/helpers/logicapps.ts → intl/src/intl.tsx
- `splitEx()` --calls--> `isNullOrUndefined()`  [EXTRACTED]
  parsers/lib/common/helpers/keysutility.ts → utils/src/lib/helpers/functions.ts
- `getInputByName()` --calls--> `equals()`  [EXTRACTED]
  parsers/lib/manifest/__test__/parser.spec.ts → utils/src/lib/helpers/functions.ts
- `getOutputByName()` --calls--> `equals()`  [EXTRACTED]
  parsers/lib/manifest/__test__/parser.spec.ts → utils/src/lib/helpers/functions.ts
- `isLegacyDynamicValuesTreeExtension()` --calls--> `equals()`  [INFERRED]
  parsers/lib/models/operation.ts → utils/src/lib/helpers/functions.ts

## Import Cycles
- 3-file cycle: `src/designer-client-services/lib/base/experimentation.ts -> src/designer-client-services/lib/experimentation.ts -> src/designer-client-services/lib/base/index.ts -> src/designer-client-services/lib/base/experimentation.ts`
- 3-file cycle: `designer-client-services/lib/base/experimentation.ts -> designer-client-services/lib/experimentation.ts -> designer-client-services/lib/base/index.ts -> designer-client-services/lib/base/experimentation.ts`
- 3-file cycle: `src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/token.ts -> src/utils/src/index.ts`
- 5-file cycle: `src/utils/src/index.ts -> src/utils/src/lib/helpers/index.ts -> src/utils/src/lib/helpers/connections.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/token.ts -> src/utils/src/index.ts`
- 5-file cycle: `src/utils/src/index.ts -> src/utils/src/lib/helpers/index.ts -> src/utils/src/lib/helpers/connectors.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/token.ts -> src/utils/src/index.ts`
- 5-file cycle: `src/utils/src/index.ts -> src/utils/src/lib/helpers/index.ts -> src/utils/src/lib/helpers/logicapps.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/token.ts -> src/utils/src/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/exceptions/expression.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/exceptions/parser.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/exceptions/scanner.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/helpers/dereferenceJsonSchema.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/helpers/expression.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/helpers/keysutility.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/helpers/utils.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/common/schemaprocessor.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/expression/builder.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/expression/evaluator.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/expression/parser.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/expression/scanner.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/manifest/parser.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`
- 5-file cycle: `src/parsers/index.ts -> src/parsers/lib/manifest/__test__/data/manifests.ts -> src/utils/src/index.ts -> src/utils/src/lib/models/index.ts -> src/utils/src/lib/models/run.ts -> src/parsers/index.ts`

## Communities (205 total, 25 thin omitted)

### Community 0 - "logicAppsV2.ts"
Cohesion: 0.02
Nodes (96): ActionDefinition, Actions, ActionsNode, ActiveDirectoryOAuthAuthentication, AgentChannels, AgentCondition, AgentInputChannelDefinition, AgentMessage (+88 more)

### Community 1 - "search.ts"
Cohesion: 0.07
Nodes (23): AzureOperationsFetchResponse, BaseSearchService, BaseSearchServiceOptions, getClientBuiltInConnectors(), getClientBuiltInOperations(), ContinuationTokenResponse, ConsumptionSearchService, ConsumptionSearchServiceOptions (+15 more)

### Community 2 - "functions.ts"
Cohesion: 0.06
Nodes (55): addPrefix(), arrayEquals(), arrayEqualsOrderInsensitive(), BUILT_IN_AGENT_TOOLS, clone(), combineObjects(), copy(), copyArray() (+47 more)

### Community 3 - "copilotWorkflowEditorParsing.ts"
Cohesion: 0.09
Nodes (36): BaseCopilotWorkflowEditorService, BaseCopilotWorkflowEditorServiceOptions, buildResponseFromParsed(), getParseError(), parseChanges(), parseCopilotResponse(), repairJson(), stripJsonComments() (+28 more)

### Community 4 - "index.ts"
Cohesion: 0.11
Nodes (40): ConnectionAndAppSetting, LocalConnectionModel, buildAgentsUri(), buildAgentUri(), buildProjectEndpointFromResourceId(), buildProxyUri(), buildUpdateBody(), CreateFoundryAgentOptions (+32 more)

### Community 5 - "operationmanifest.ts"
Cohesion: 0.06
Nodes (43): builtInConnectorIds, builtInOperationsMetadata, foreachOperationInfo, getAccessTokenType, supportedBaseManifestObjects, ConnectorManifest, addToTimeManifest, convertTimezoneManifest (+35 more)

### Community 6 - "BaseException"
Cohesion: 0.09
Nodes (17): BaseException, ConnectorServiceErrorCode, ConnectorServiceException, Exception, InvalidFormatException, SerializationErrorCode, SerializationException, UnsupportedExceptionCode (+9 more)

### Community 7 - "operationmanifest.ts"
Cohesion: 0.05
Nodes (41): supportedBaseManifestTypes, supportedConsumptionManifestObjects, supportedConsumptionManifestTypes, apiManagementActionManifest, apiManagementTriggerManifest, connector, appServiceActionManifest, appServiceTriggerManifest (+33 more)

### Community 8 - "operation.ts"
Cohesion: 0.05
Nodes (33): Annotation, DependentParameterInfo, DeserializationType, DynamicList, DynamicParameter, DynamicParameters, DynamicProperties, DynamicPropertiesExtension (+25 more)

### Community 9 - "openApiV2.ts"
Cohesion: 0.06
Nodes (43): ContactObject, DefinitionsObject, Document, ExampleObject, ExternalDocumentationObject, GeneralParameterObject, HeaderObject, HeadersObject (+35 more)

### Community 10 - "logicApps.ts"
Cohesion: 0.05
Nodes (42): ActionDefinition, Actions, ActiveDirectoryOAuthAuthentication, ApiConnectionHeaders, ApiConnectionHost, ApiConnectionHostApi, ApiConnectionHostApiType, ApiConnectionHostConnection (+34 more)

### Community 11 - "badges.ts"
Cohesion: 0.08
Nodes (24): coreBadge, iseBadge, previewBadge, as2DecodeManifest, as2EncodeManifest, connector, connector, selectFunctionManifest (+16 more)

### Community 12 - "swagger.ts"
Cohesion: 0.06
Nodes (37): ApiKeySecurityScheme, BodyParameter, Contact, Definitions, Example, ExternalDocumentation, Header, Headers (+29 more)

### Community 13 - "connection.ts"
Cohesion: 0.08
Nodes (32): ServiceExceptionCode, createCopy(), ConnectionType, AgentConnectionModel, AgentMcpConnectionModel, APIManagementConnectionModel, ConnectionAcl, ConnectionCreationClient (+24 more)

### Community 14 - "operationmanifest.ts"
Cohesion: 0.07
Nodes (12): BaseOperationManifestService, BaseOperationManifestServiceOptions, getBuiltInOperationInfo(), isBuiltInOperation(), ConsumptionOperationManifestService, ConsumptionOperationManifestServiceOptions, IOperationManifestService, OperationInfo (+4 more)

### Community 15 - "Connector"
Cohesion: 0.06
Nodes (26): BaseConnectionService, ConnectionsResponse, ConsentLink, getAccessTokenType, LogicAppConsentResponse, ConsumptionConnectionService, ConsumptionConnectionServiceOptions, HttpResponse (+18 more)

### Community 16 - "connector.ts"
Cohesion: 0.06
Nodes (31): BaseConnectorService, BaseConnectorServiceOptions, GetSchemaFunction, GetValuesFunction, ConsumptionConnectorService, ConsumptionConnectorServiceOptions, getResourceName(), optional() (+23 more)

### Community 17 - "logicAppsV2.ts"
Cohesion: 0.02
Nodes (96): ActionDefinition, Actions, ActionsNode, ActiveDirectoryOAuthAuthentication, AgentChannels, AgentCondition, AgentInputChannelDefinition, AgentMessage (+88 more)

### Community 18 - "connector.ts"
Cohesion: 0.06
Nodes (31): connectionsMock, ConnectorsMock, connectorsSearchResultsMock, MockAzureOperation, MockSearchOperations, MockSearchOperationsBuiltIn, Capabilities, ConnectionAlternativeParameters (+23 more)

### Community 19 - "operationmanifest.ts"
Cohesion: 0.08
Nodes (25): ActionSetting, BindingMode, BuiltInOutput, ConnectionReferenceKeyFormatMapping, CustomSwaggerServiceDetails, CustomSwaggerServiceNames, Documentation, ExecutionOrder (+17 more)

### Community 20 - "run.ts"
Cohesion: 0.05
Nodes (13): CallbackInfo, ConsumptionRunService, IRunService, RunFilterOptions, getRecordEntry(), parseErrorMessage(), mockError, ArmResources (+5 more)

### Community 21 - "index.ts"
Cohesion: 0.06
Nodes (30): flatFileDecodingManifest, flatFileEncodingManifest, integrationAccount, integrationAccountArtifactLookupManifest, api, apiManagementActionOperation, apiManagementGroup, apiManagementTriggerOperation (+22 more)

### Community 22 - "stringFunctions.ts"
Cohesion: 0.10
Nodes (10): areApiIdsEqual(), canStringBeConverted(), capitalizeFirstLetter(), escapeString(), idDisplayCase(), labelCase(), normalizeApiId(), removeIdTag() (+2 more)

### Community 23 - "Connector"
Cohesion: 0.06
Nodes (27): ConnectionCreationInfo, ConnectionParametersMetadata, ConnectorWithSwagger, CreateConnectionResult, IConnectionService, ConsumptionConnectionService, LoggerService(), StandardConnectionService (+19 more)

### Community 24 - "BaseTemplateService"
Cohesion: 0.12
Nodes (4): BaseTemplateService, ConsumptionTemplateService, ConsumptionTemplateServiceOptions, StandardTemplateService

### Community 25 - "run.ts"
Cohesion: 0.06
Nodes (19): ConsumptionRunService, ConsumptionRunServiceOptions, UnsupportedException, isArmResourceId(), getRecordEntry(), parseErrorMessage(), getCallbackUrl(), CallbackInfo (+11 more)

### Community 26 - "connections.ts"
Cohesion: 0.12
Nodes (21): CLIENT_CERTIFICATE_CONSTANTS, connectorContainsAllClientCertificateConnectionParameters(), connectorContainsAllServicePrincipalConnectionParameters(), connectorsShownAsAzure, getAuthRedirect(), _getConnectionParameterSetParametersUsingType(), getConnectionParametersWithType(), getIdentityDropdownOptions() (+13 more)

### Community 27 - "connection.ts"
Cohesion: 0.13
Nodes (21): ConnectionParameterEditorService(), IConnectionCredentialMappingEditorProps, IConnectionCredentialMappingInfo, IConnectionCredentialMappingOptions, IConnectionParameterEditorOptions, IConnectionParameterEditorProps, IConnectionParameterEditorService, IConnectionParameterInfo (+13 more)

### Community 28 - "SchemaProcessor"
Cohesion: 0.22
Nodes (6): SchemaProcessor, getEditorOptionsForParameter(), getParameterDynamicSchema(), getParameterDynamicValues(), SchemaProperty, SchemaObject

### Community 29 - "keysutility.ts"
Cohesion: 0.13
Nodes (19): OutputSource, cleanIndexedValue(), _codeBook, createEx(), decodePropertySegment(), _decodeSegment(), encodePropertySegment(), _encodeSegment() (+11 more)

### Community 30 - "connector.ts"
Cohesion: 0.06
Nodes (30): BaseConnectorService, BaseConnectorServiceOptions, GetSchemaFunction, GetValuesFunction, TestConnectorService, IConnectorService, ListDynamicValue, ManagedIdentityRequestProperties (+22 more)

### Community 31 - "copilotWorkflowEditorTools.ts"
Cohesion: 0.06
Nodes (51): buildResponseFromParsed(), getParseError(), parseChanges(), parseCopilotResponse(), repairJson(), stripJsonComments(), tryExtractJson(), tryJsonParse() (+43 more)

### Community 32 - "parser.ts"
Cohesion: 0.07
Nodes (34): ChunkSizeCapabilities, ExpressionConstants, FILE_PARAMETER_KEYS, Formats, OutputKeys, ParameterLocations, Permissions, PropertyName (+26 more)

### Community 33 - "operationmanifest.ts"
Cohesion: 0.06
Nodes (48): coreBadge, iseBadge, previewBadge, apiManagementActionManifest, apiManagementTriggerManifest, connector, appServiceActionManifest, appServiceTriggerManifest (+40 more)

### Community 34 - "logger.ts"
Cohesion: 0.09
Nodes (19): customLengthGuid(), guid(), hexValues, isAGuid(), InitConnectionService(), ILoggerService, InitLoggerService(), LogEntryWithoutTimestamp (+11 more)

### Community 35 - "template.ts"
Cohesion: 0.10
Nodes (21): Artifact, Connection, ConnectionInfo, ConnectorRuntimeType, ContentInfo, DetailsType, FeaturedConnector, FeaturedConnectorType (+13 more)

### Community 36 - "functions.ts"
Cohesion: 0.07
Nodes (55): addPrefix(), arrayEquals(), arrayEqualsOrderInsensitive(), BUILT_IN_AGENT_TOOLS, clone(), combineObjects(), copyArray(), CopyOptions (+47 more)

### Community 37 - "index.ts"
Cohesion: 0.08
Nodes (43): ICustomCodeService, UploadCustomCodeAppFilePayload, UploadCustomCodePayload, CustomCodeServiceOptions, StandardCustomCodeService, buildAgentsUri(), buildAgentUri(), buildProjectEndpointFromResourceId() (+35 more)

### Community 38 - "resource.ts"
Cohesion: 0.09
Nodes (10): BaseCognitiveServiceService, BaseResourceService, BaseResourceServiceOptions, fetchAppsByQuery(), getResourceNameFromId(), HTTP_METHODS, IResourceService, LogicAppResource (+2 more)

### Community 39 - "utils.ts"
Cohesion: 0.10
Nodes (23): createItem, getEmails, onNewEmail, dereferenceRefSchema(), EmptyRefs, getEditorForParameter(), getKnownTitles(), getKnownTitlesFromKey() (+15 more)

### Community 40 - "Action"
Cohesion: 0.10
Nodes (21): Action, AppendToArrayVariableAction, AppendToStringVariableAction, ComposeAction, ConnectorAction, DecrementVariableAction, HandoffAction, IncrementVariableAction (+13 more)

### Community 41 - "operationmanifest.ts"
Cohesion: 0.05
Nodes (25): BaseOperationManifestService, BaseOperationManifestServiceOptions, getBuiltInOperationInfo(), isBuiltInOperation(), ConsumptionOperationManifestServiceOptions, ChangeHandler, EditorService(), ICustomEditorOptions (+17 more)

### Community 42 - "xml.ts"
Cohesion: 0.25
Nodes (7): settings, xmlTransformManifest, xmlValidationManifest, xmlGroup, api, xmlTransformOperation, xmlValidationOperation

### Community 43 - "index.ts"
Cohesion: 0.06
Nodes (40): ExtensionProperties, isCustomConnectorId(), isManagedConnectorId(), isSharedManagedConnectorId(), isSharedManagedConnectorIdFromPApps(), IStaticResultSchemaService, ManifestParser, SupportedChannels (+32 more)

### Community 44 - "parseJson.ts"
Cohesion: 0.11
Nodes (19): getAllValidationErrorType(), getValidationErrorSchema(), intl, ParseJsonStaticResultSchema, STATIC_RESULT_ERROR_LINE_NUMBER, STATIC_RESULT_ERROR_LINE_POSITION, STATIC_RESULT_HTTP_BODY_TITLE, STATIC_RESULT_OPERATION_OUTPUT_TITLE (+11 more)

### Community 45 - "index.ts"
Cohesion: 0.05
Nodes (43): flatFileDecodingManifest, flatFileEncodingManifest, integrationAccount, settings, xmlTransformManifest, xmlValidationManifest, a2aRequestOperation, agentOperation (+35 more)

### Community 46 - "RetryableActionInputs"
Cohesion: 0.11
Nodes (19): ApiConnectionInputs, ApiConnectionNotificationInputs, ApiConnectionWebhookInputs, ApiManagementInputs, AppendToArrayVariableInputs, AppendToStringVariableInputs, ChildWorkflowInputs, DecrementVariableInputs (+11 more)

### Community 47 - "ResolutionService"
Cohesion: 0.20
Nodes (4): isFunction(), isParametersObject(), ParametersObject, ResolutionService

### Community 48 - "parameterprocessor.ts"
Cohesion: 0.25
Nodes (11): aggregate(), create(), getEnum(), toSwaggerSchema(), EnumObject, InputParameter, toInputParameter(), Parameter (+3 more)

### Community 49 - "index.ts"
Cohesion: 0.08
Nodes (17): AgentQueryParams, AgentURL, AGENT_MODEL_CONFIG, SUPPORTED_AGENT_OPENAI_MODELS, SUPPORTED_FOUNDRY_AGENT_MODELS, ApiToGatewayMapping, GatewayProperties, GatewayType (+9 more)

### Community 50 - "index.ts"
Cohesion: 0.06
Nodes (40): IStaticResultSchemaService, StaticResultSchemaService, cleanDynamicSchemaParameters(), getStaticResultSchemaForAPIConnector(), wrapOutputsSchemaToOperationSchema(), intl, STATIC_RESULT_ERROR_OBJECT_CODE_TITLE, STATIC_RESULT_ERROR_OBJECT_MESSAGE_TITLE (+32 more)

### Community 51 - "index.ts"
Cohesion: 0.04
Nodes (47): ApiManagementServiceOptions, BaseAppServiceServiceOptions, connectorIsAppService(), BaseCloneService, BaseCloneServiceOptions, BaseCognitiveServiceServiceOptions, ApiHubServiceDetails, BaseFunctionServiceOptions (+39 more)

### Community 52 - "httpClient.ts"
Cohesion: 0.07
Nodes (25): BladeClosedReason, BladeReference, HelpPaneState, OpenBladeOptions, InitConnectionService(), mockLoggerService, mockLoggerService, BatchHttpMethod (+17 more)

### Community 53 - "ExpressionScanner"
Cohesion: 0.34
Nodes (3): ExpressionScanner, isWhitespace(), ExpressionToken

### Community 54 - "hooks.ts"
Cohesion: 0.15
Nodes (6): getWindowDimensions(), useEdgeIndex(), useWindowDimensions(), EdgeData, useEdgesData(), Size

### Community 55 - "intl.tsx"
Cohesion: 0.29
Nodes (7): cache, IntlGlobalProvider(), IntlGlobalProviderProps, resetIntl(), IntlProvider(), IntlProviderProps, loadLocaleData()

### Community 56 - "BaseException"
Cohesion: 0.08
Nodes (18): ConnectorConnectionErrorCode, ConnectorConnectionException, ServiceException, ServiceExceptionCode, InvalidFormatException, ExpressionEvaluatorException, ArgumentException, BaseException (+10 more)

### Community 57 - "logicAppsV2Integration.ts"
Cohesion: 0.12
Nodes (16): ArtifactInformation, ContentAndSchemaInputs, EmptyNodeGenerationMode, FlatFileDecodingAction, FlatFileEncodingAction, FlatFileEncodingInputs, FunctionInput, IntegrationAccountArtifactLookupAction (+8 more)

### Community 58 - "index.ts"
Cohesion: 0.18
Nodes (8): ExpressionException, ExpressionExceptionCode, ExpressionParserErrorCode, ParserException, ScannerException, dereferenceJsonSchema(), SchemaObject, isNumeric()

### Community 59 - "equals"
Cohesion: 0.21
Nodes (21): ExpressionBuilderErrorCode, TokenToParse, isAppSettingExpression(), isBooleanLiteral(), isLiteralExpression(), isNullLiteral(), isNumberLiteral(), isParameterExpression() (+13 more)

### Community 60 - "chatbot.ts"
Cohesion: 0.20
Nodes (6): BaseChatbotService, ChatbotServiceOptions, IChatbotService, DocumentationMetadataState, OperationMetadata, SummaryMetadata

### Community 61 - "operationmanifest.ts"
Cohesion: 0.07
Nodes (39): addToTimeManifest, convertTimezoneManifest, currentTimeManifest, dateTimeConnector, dateTimeFormats, getFutureTimeManifest, getPastTimeManifest, subtractFromTimeManifest (+31 more)

### Community 62 - "oAuth.ts"
Cohesion: 0.25
Nodes (7): BaseOAuthService, OAuthPopup, IOAuthPopup, IOAuthService, IOAuthServiceOptions, LoginResult, OAuthPopupOptions

### Community 63 - "index.ts"
Cohesion: 0.08
Nodes (7): EditorLanguage, VFSObject, LOCAL_STORAGE_KEYS, canRunBeInvokedWithPayload(), getTriggerFromDefinition(), getTriggerType(), getFrequencyValues()

### Community 64 - "connection.ts"
Cohesion: 0.08
Nodes (38): AgentConnectionModel, AgentMcpConnectionModel, APIManagementConnectionModel, ConnectionAcl, ConnectionAndAppSetting, ConnectionCreationClient, ConnectionsData, convertAgentConnectionDataToConnection() (+30 more)

### Community 65 - "uiInteractionsService.ts"
Cohesion: 0.24
Nodes (6): IDesignerUiInteractionsService, DropdownMenuCustomNode, DropdownMenuItem, DropdownMenuOption, TopLevelDropdownMenuItem, UiInteractionData

### Community 66 - "logicAppsIntegration.ts"
Cohesion: 0.14
Nodes (14): ArtifactInformation, ContentAndSchemaInputs, EmptyNodeGenerationMode, FlatFileDecodingAction, FlatFileEncodingAction, FlatFileEncodingInputs, FunctionInput, IntegrationAccountArtifactLookupAction (+6 more)

### Community 67 - "run.ts"
Cohesion: 0.09
Nodes (24): getIsCallbackUrlSupported(), getRequestTriggerName(), getRunTriggerName(), getTriggerName(), isCallbackInfoWithRelativePath(), AgentMetadata, BindFunction, BoundParameter (+16 more)

### Community 68 - "uritemplateparser.ts"
Cohesion: 0.15
Nodes (7): LiteralSegment, Modes, Segment, Types, UriTemplateGenerator, UriTemplateParser, VariableSegment

### Community 69 - "Expression"
Cohesion: 0.25
Nodes (4): ExpressionBuilder, ExpressionParser, convertToStringLiteral(), Expression

### Community 70 - "color.ts"
Cohesion: 0.21
Nodes (10): Color, hex2rgb(), HSV, hsv2rgb(), lighten(), RGB, rgb2hex(), rgb2hsv() (+2 more)

### Community 71 - "dataMap.ts"
Cohesion: 0.14
Nodes (13): ConnectionAndOrder, emptyCanvasRect, FunctionMetadata, FunctionMetadataV1, FunctionPositionMetadata, IFileSysTreeItem, ITreeDirectory, ITreeFile (+5 more)

### Community 72 - "experimentation.ts"
Cohesion: 0.28
Nodes (6): BaseExperimentationService, ExperimentationService(), IExperimentationService, InitExperimentationServiceService(), enableAPIMGatewayConnection(), EXP_FLAGS

### Community 73 - "dataMapSchema.ts"
Cohesion: 0.18
Nodes (12): DataMapSchema, InputFormat, NamespaceDictionary, NormalizedDataType, PathItem, SchemaExtended, SchemaFileFormat, SchemaNode (+4 more)

### Community 74 - "getIntl"
Cohesion: 0.10
Nodes (4): BaseApiManagementService, BaseAppServiceService, BaseFunctionService, getIntl()

### Community 75 - "equals"
Cohesion: 0.13
Nodes (25): isAppSettingExpression(), isBooleanLiteral(), isFunction(), isLiteralExpression(), isNullLiteral(), isNumberLiteral(), isParameterExpression(), isParameterOrAppSettingExpression() (+17 more)

### Community 76 - "connectors.ts"
Cohesion: 0.17
Nodes (13): fallbackConnectorIconUrl(), getAllConnectorProperties(), getBrandColorFromConnector(), getDescriptionFromConnector(), getDisplayNameFromConnector(), getIconUriFromConnector(), isIndependentPublisherConnector(), normalizeConnectorId() (+5 more)

### Community 77 - "openApiV2.ts"
Cohesion: 0.06
Nodes (43): ContactObject, DefinitionsObject, Document, ExampleObject, ExternalDocumentationObject, GeneralParameterObject, HeaderObject, HeadersObject (+35 more)

### Community 78 - "logicApps.ts"
Cohesion: 0.05
Nodes (42): ActionDefinition, Actions, ActiveDirectoryOAuthAuthentication, ApiConnectionHeaders, ApiConnectionHost, ApiConnectionHostApi, ApiConnectionHostApiType, ApiConnectionHostConnection (+34 more)

### Community 79 - "editor.ts"
Cohesion: 0.21
Nodes (10): ChangeHandler, EditorService(), ICustomEditorOptions, IEditorParameterInfo, IEditorProps, IEditorService, InitEditorService(), IRenderDefaultEditorParams (+2 more)

### Community 80 - "operation.ts"
Cohesion: 0.06
Nodes (34): createItem, getEmails, onNewEmail, getInputByName(), getOutputByName(), DependentParameterInfo, DeserializationType, DynamicList (+26 more)

### Community 81 - "index.ts"
Cohesion: 0.13
Nodes (8): ConnectorManifest, inlineCSharpManifest, inlinePowershellManifest, inlinePythonManifest, OperationManifest, OperationOptions, OutputSecureDataMode, SettingScope

### Community 82 - "keysutility.ts"
Cohesion: 0.08
Nodes (34): ChunkSizeCapabilities, ExpressionConstants, FILE_PARAMETER_KEYS, Formats, OutputKeys, OutputSource, Permissions, PropertyName (+26 more)

### Community 83 - "operations.ts"
Cohesion: 0.25
Nodes (6): normalizeTemplate(), replaceTemplatePlaceholders(), WORKFLOW_EDGE_TYPES, WORKFLOW_NODE_TYPES, WorkflowEdgeType, WorkflowNodeType

### Community 84 - "dataoperations.ts"
Cohesion: 0.18
Nodes (10): chunktext, composeOperation, csvTableOperation, htmlTableOperation, joinOperation, parsedocument, parsedocumentwithmetadata, parseJsonOperation (+2 more)

### Community 85 - "swagger.ts"
Cohesion: 0.06
Nodes (37): ApiKeySecurityScheme, BodyParameter, Contact, Definitions, Example, ExternalDocumentation, Header, Headers (+29 more)

### Community 86 - "parser.ts"
Cohesion: 0.10
Nodes (17): Annotation, InputParameters, LAOperation, Operations, OutputParameters, ApiNotificationConstants, GetInputParametersOptions, GetOperationsOptions (+9 more)

### Community 87 - "datetime.spec.ts"
Cohesion: 0.31
Nodes (7): getDuration(), TimeUnit, toFriendlyDurationString(), cache, getTestIntl(), intl, mockUseIntl()

### Community 88 - "Use Cases"
Cohesion: 0.20
Nodes (9): API, Feature Flags Based on Version, `isMultiVariableSupport(version?)` (deprecated), `isVersionSupported(currentVersion, requiredVersion, exactMatch?)`, Migration Path, Use Cases, Version Format, Version Gating in Service Configuration (+1 more)

### Community 89 - "index.ts"
Cohesion: 0.05
Nodes (19): FavoriteContext, FavoriteContextType, AssertionErrorCode, AssertionException, IApiManagementService, IAppServiceService, IFunctionService, CustomTemplateResource (+11 more)

### Community 90 - "knowledge.ts"
Cohesion: 0.22
Nodes (9): ArtifactCreationStatus, ArtifactType, ContentKind, KnowledgeHub, KnowledgeHubArtifact, KnowledgeHubExtended, ProgressStatus, UploadFile (+1 more)

### Community 91 - "Action"
Cohesion: 0.20
Nodes (10): Action, ApiConnectionAction, ApiConnectionWebhookAction, ChildWorkflow, ComposeAction, FunctionAction, HttpAction, HttpWebhookAction (+2 more)

### Community 92 - "TimeoutableAction"
Cohesion: 0.20
Nodes (10): AgentAction, ApiConnectionAction, ApiConnectionWebhookAction, ApiManagementAction, ChildWorkflow, FunctionAction, HttpAction, HttpWebhookAction (+2 more)

### Community 93 - "Trigger"
Cohesion: 0.12
Nodes (16): ApiConnectionNotificationTrigger, ApiConnectionTrigger, ApiConnectionWebhookTrigger, ApiManagementTrigger, BatchTrigger, GeofenceTrigger, HttpTrigger, HttpWebhookTrigger (+8 more)

### Community 94 - "getAzureResourceRecursive"
Cohesion: 0.10
Nodes (12): BaseResourceService, BaseResourceServiceOptions, getAzureResourceRecursive(), IResourceService, LogicAppResource, Resource, WorkflowResource, getResourceNameFromId() (+4 more)

### Community 96 - "operationgroups.ts"
Cohesion: 0.22
Nodes (8): agentGroup, controlGroup, dataOperationsGroup, dateTimeGroup, httpGroup, requestGroup, scheduleGroup, variableGroup

### Community 98 - "index.ts"
Cohesion: 0.06
Nodes (24): a2aRequestOperation, agentOperation, handoffOperation, inlinePythonCodeOperation, agentGroup, controlGroup, dataOperationsGroup, dateTimeGroup (+16 more)

### Community 99 - "logicAppsV2Expression.ts"
Cohesion: 0.22
Nodes (8): AddSubtractTimeInputs, AddSubtractTimeInputsType, ConvertTimeZoneInputs, ConvertTimeZoneInputsType, CurrentTimeInputs, ExpressionAction, OffsetTimeInputs, OffsetTimeInputsType

### Community 100 - "index.ts"
Cohesion: 0.25
Nodes (3): handoffOperation, requestOperation, responseOperation

### Community 101 - "index.ts"
Cohesion: 0.10
Nodes (14): IAppServiceService, ApiManagementServiceOptions, BaseAppServiceService, BaseAppServiceServiceOptions, connectorIsAppService(), CONSUMPTION_SYSTEM_PROMPT, DEFAULT_SYSTEM_PROMPT, LogicAppsSku (+6 more)

### Community 102 - "ICognitiveServiceService"
Cohesion: 0.06
Nodes (7): BaseCognitiveServiceServiceOptions, ICognitiveServiceService, IWorkflowService, AgentURL, UploadFile, ManagedIdentity, ManagedIdentityData

### Community 103 - "RetryableActionInputs"
Cohesion: 0.29
Nodes (7): ApiConnectionInputs, ApiConnectionWebhookInputs, ChildWorkflowInputs, FunctionInputs, HttpInputs, HttpInputsOptional, RetryableActionInputs

### Community 104 - "Trigger"
Cohesion: 0.29
Nodes (7): ApiConnectionTrigger, ApiConnectionWebhookTrigger, HttpTrigger, HttpWebhookTrigger, ManualTrigger, RecurrenceTrigger, Trigger

### Community 105 - "control.ts"
Cohesion: 0.29
Nodes (6): foreachOperation, ifOperation, scopeOperation, switchOperation, terminateOperation, untilOperation

### Community 106 - "datetime.ts"
Cohesion: 0.29
Nodes (6): addToTimeOperation, convertTimezoneOperation, currentTimeOperation, getFutureTimeOperation, getPastTimeOperation, subtractFromTimeOperation

### Community 107 - "http.ts"
Cohesion: 0.29
Nodes (6): httpActionOperation, httpSwaggerActionOperation, httpSwaggerTriggerOperation, httpTriggerOperation, httpWebhookActionOperation, httpWebhookTriggerOperation

### Community 108 - "variables.ts"
Cohesion: 0.29
Nodes (6): appendArrayVariableOperation, appendStringVariableOperation, decrementVariableOperation, incrementVariableOperation, initializeVariableOperation, setVariableOperation

### Community 109 - "IHttpClient"
Cohesion: 0.09
Nodes (16): ApiHubServiceDetails, ConnectionsResponse, ConsentLink, getAccessTokenType, LogicAppConsentResponse, TestSearchService, ConsumptionConnectionServiceOptions, ConsumptionRunServiceOptions (+8 more)

### Community 110 - "BaseConnectionService"
Cohesion: 0.11
Nodes (4): BaseConnectionService, HttpResponse, getUniqueName(), TestConnectionObject

### Community 111 - "version.ts"
Cohesion: 0.53
Nodes (4): BundleVersionRequirements, compareVersions(), isVersionSupported(), parseVersion()

### Community 112 - "run.ts"
Cohesion: 0.10
Nodes (25): deepCompareObjects(), isObject(), getCallbackUrl(), getIsCallbackUrlSupported(), getRequestTriggerName(), getRunTriggerName(), getTriggerName(), isCallbackInfoWithRelativePath() (+17 more)

### Community 113 - "utils.ts"
Cohesion: 0.12
Nodes (24): getIntl(), SchemaObject, dereferenceRefSchema(), EmptyRefs, getEditorOptionsForParameter(), getKnownTitles(), getKnownTitlesFromKey(), getParameterDynamicSchema() (+16 more)

### Community 114 - "evaluator.ts"
Cohesion: 0.24
Nodes (5): ExpressionEvaluator, ExpressionEvaluatorErrorCode, ExpressionEvaluatorException, ExpressionEvaluatorOptions, ExpressionEvaluationContext

### Community 115 - "ArmResource"
Cohesion: 0.14
Nodes (9): BaseRoleService, BaseRoleServiceOptions, IRoleService, RoleAssignment, RoleAssignmentPayload, RoleDefinition, ArmResource, DiscoveryWorkflow (+1 more)

### Community 116 - "search.ts"
Cohesion: 0.15
Nodes (19): AzureOperationsFetchResponse, BaseSearchServiceOptions, getClientBuiltInConnectors(), getClientBuiltInOperations(), NOTE: temporary workaround to filter out the mcp server until backend does the p, ContinuationTokenResponse, ConsumptionSearchServiceOptions, getBuiltInConnectorsInConsumption() (+11 more)

### Community 117 - "schedule.ts"
Cohesion: 0.40
Nodes (4): delayOperation, delayUntilOperation, recurrenceOperation, slidingWindowOperation

### Community 118 - "BaseTemplateService"
Cohesion: 0.11
Nodes (8): BaseTemplateService, BaseTemplateServiceOptions, ConsumptionTemplateService, ConsumptionTemplateServiceOptions, StandardTemplateService, StandardTemplateServiceOptions, CustomTemplateResource, ITemplateService

### Community 119 - "operationmanifest.ts"
Cohesion: 0.07
Nodes (26): ActionSetting, BindingMode, BuiltInOutput, ConnectionReferenceKeyFormatMapping, CustomSwaggerServiceDetails, CustomSwaggerServiceNames, Documentation, ExecutionOrder (+18 more)

### Community 120 - "DiscoveryOpArray"
Cohesion: 0.14
Nodes (5): ConsumptionSearchService, ISearchService, OperationRuntimeCategory, SearchResult, DiscoveryOpArray

### Community 121 - "ScopeAction"
Cohesion: 0.50
Nodes (4): ForEachAction, IfAction, ScopeAction, UntilAction

### Community 122 - "outputprocessor.ts"
Cohesion: 0.12
Nodes (14): ParameterLocations, getArrayOutputMetadata(), OutputsProcessor, TODO: this method should move to some utility class., NOTE: If only one response is defined in the swagger and if it is any of the ass, Responses, InternalSchemaProcessorOptions, SchemaProcessorOptions (+6 more)

### Community 130 - "stringFunctions.ts"
Cohesion: 0.10
Nodes (9): areApiIdsEqual(), canStringBeConverted(), escapeString(), idDisplayCase(), labelCase(), normalizeApiId(), removeIdTag(), toPascalCase() (+1 more)

### Community 133 - "parameterprocessor.ts"
Cohesion: 0.19
Nodes (15): create(), getEnum(), toSwaggerSchema(), EnumObject, InputParameter, toInputParameter(), Parameter, ParametersProcessor (+7 more)

### Community 134 - "connections.ts"
Cohesion: 0.13
Nodes (20): CLIENT_CERTIFICATE_CONSTANTS, connectorContainsAllClientCertificateConnectionParameters(), connectorContainsAllServicePrincipalConnectionParameters(), connectorsShownAsAzure, getAuthRedirect(), _getConnectionParameterSetParametersUsingType(), getConnectionParametersWithType(), getIdentityDropdownOptions() (+12 more)

### Community 135 - "index.ts"
Cohesion: 0.08
Nodes (15): AgentQueryParams, AGENT_MODEL_CONFIG, SUPPORTED_AGENT_OPENAI_MODELS, SUPPORTED_FOUNDRY_AGENT_MODELS, ApiToGatewayMapping, GatewayProperties, GatewayType, DeepPartial (+7 more)

### Community 137 - "SchemaProcessor"
Cohesion: 0.27
Nodes (4): getEditorForParameter(), SchemaProcessor, ParameterBase, SchemaProperty

### Community 138 - "connector.ts"
Cohesion: 0.10
Nodes (21): Capabilities, ConnectionAlternativeParameters, ConnectionParameterAllowedValue, ConnectionParameterMetadata, ConnectionParameterSchemaFormat, ConnectionParameterSchemaType, ConnectionParameterSetParameterUIDefinition, ConnectionParameterSets (+13 more)

### Community 139 - "template.ts"
Cohesion: 0.10
Nodes (21): Artifact, Connection, ConnectionInfo, ConnectorRuntimeType, ContentInfo, DetailsType, FeaturedConnector, FeaturedConnectorType (+13 more)

### Community 141 - "Action"
Cohesion: 0.10
Nodes (21): Action, AppendToArrayVariableAction, AppendToStringVariableAction, ComposeAction, ConnectorAction, DecrementVariableAction, HandoffAction, IncrementVariableAction (+13 more)

### Community 142 - "gateway.ts"
Cohesion: 0.15
Nodes (7): BaseGatewayService, BaseGatewayServiceOptions, GatewayServiceConfig, IGatewayService, Gateway, Subscription, SubscriptionFilter

### Community 144 - "parseJson.ts"
Cohesion: 0.11
Nodes (19): getAllValidationErrorType(), getValidationErrorSchema(), intl, ParseJsonStaticResultSchema, STATIC_RESULT_ERROR_LINE_NUMBER, STATIC_RESULT_ERROR_LINE_POSITION, STATIC_RESULT_HTTP_BODY_TITLE, STATIC_RESULT_OPERATION_OUTPUT_TITLE (+11 more)

### Community 145 - "copilotWorkflowEditorTools.ts"
Cohesion: 0.16
Nodes (13): ActionTemplate, buildActionTemplate(), COPILOT_WORKFLOW_TOOLS, CopilotToolDefinition, deriveReferenceName(), discoverConnectors(), executeCopilotTool(), getConnectorOperations() (+5 more)

### Community 146 - "RetryableActionInputs"
Cohesion: 0.11
Nodes (19): ApiConnectionInputs, ApiConnectionNotificationInputs, ApiConnectionWebhookInputs, ApiManagementInputs, AppendToArrayVariableInputs, AppendToStringVariableInputs, ChildWorkflowInputs, DecrementVariableInputs (+11 more)

### Community 147 - "validateRequiredServiceArguments"
Cohesion: 0.16
Nodes (6): validateRequiredServiceArguments(), ICustomCodeService, UploadCustomCodeAppFilePayload, UploadCustomCodePayload, CustomCodeServiceOptions, StandardCustomCodeService

### Community 149 - "oAuth.ts"
Cohesion: 0.21
Nodes (8): BaseOAuthService, OAuthPopup, IOAuthPopup, IOAuthService, IOAuthServiceOptions, LoginResult, OAuthPopupOptions, OAuthService()

### Community 150 - "templateresource.ts"
Cohesion: 0.15
Nodes (5): BaseTemplateResourceService, ITemplateResourceServiceOptions, getTemplateManifestFromResourceManifest(), ITemplateResourceService, WorkflowData

### Community 151 - "ExpressionScanner"
Cohesion: 0.34
Nodes (4): isNumeric(), isWhitespace(), ExpressionScanner, ExpressionToken

### Community 152 - "hooks.ts"
Cohesion: 0.15
Nodes (7): getWindowDimensions(), useEdgeIndex(), useWindowDimensions(), EdgeData, shallowEdgeData(), useEdgesData(), Size

### Community 153 - "logicAppsV2Integration.ts"
Cohesion: 0.12
Nodes (16): ArtifactInformation, ContentAndSchemaInputs, EmptyNodeGenerationMode, FlatFileDecodingAction, FlatFileEncodingAction, FlatFileEncodingInputs, FunctionInput, IntegrationAccountArtifactLookupAction (+8 more)

### Community 155 - "uritemplateparser.ts"
Cohesion: 0.16
Nodes (9): RFC-6570, isLiteralSegment(), LiteralSegment, Modes, Segment, Types, UriTemplateGenerator, UriTemplateParser (+1 more)

### Community 156 - "Trigger"
Cohesion: 0.12
Nodes (16): ApiConnectionNotificationTrigger, ApiConnectionTrigger, ApiConnectionWebhookTrigger, ApiManagementTrigger, BatchTrigger, GeofenceTrigger, HttpTrigger, HttpWebhookTrigger (+8 more)

### Community 157 - "chatbot.ts"
Cohesion: 0.20
Nodes (6): BaseChatbotService, ChatbotServiceOptions, IChatbotService, DocumentationMetadataState, OperationMetadata, SummaryMetadata

### Community 158 - "connectionParameterEditor.ts"
Cohesion: 0.23
Nodes (11): ConnectionParameterEditorService(), IConnectionCredentialMappingEditorProps, IConnectionCredentialMappingInfo, IConnectionCredentialMappingOptions, IConnectionParameterEditorOptions, IConnectionParameterEditorProps, IConnectionParameterEditorService, IConnectionParameterInfo (+3 more)

### Community 160 - "uiInteractionsService.ts"
Cohesion: 0.24
Nodes (6): IDesignerUiInteractionsService, DropdownMenuCustomNode, DropdownMenuItem, DropdownMenuOption, TopLevelDropdownMenuItem, UiInteractionData

### Community 161 - "builder.ts"
Cohesion: 0.28
Nodes (6): convertToStringLiteral(), ExpressionBuilder, ExpressionBuilderErrorCode, ExpressionBuilderException, Dereference, Expression

### Community 162 - "logicAppsIntegration.ts"
Cohesion: 0.14
Nodes (14): ArtifactInformation, ContentAndSchemaInputs, EmptyNodeGenerationMode, FlatFileDecodingAction, FlatFileEncodingAction, FlatFileEncodingInputs, FunctionInput, IntegrationAccountArtifactLookupAction (+6 more)

### Community 164 - "experimentation.ts"
Cohesion: 0.27
Nodes (7): BaseExperimentationService, ExperimentationService(), IExperimentationService, InitExperimentationServiceService(), enableAPIMGatewayConnection(), enableOperationSettingDefaults(), EXP_FLAGS

### Community 165 - "parser.ts"
Cohesion: 0.26
Nodes (6): ExpressionException, ExpressionExceptionCode, ExpressionParserErrorCode, ParserException, ScannerException, TODO: This might require to support string interpolation as well.

### Community 166 - "color.ts"
Cohesion: 0.21
Nodes (10): Color, hex2rgb(), HSV, hsv2rgb(), lighten(), RGB, rgb2hex(), rgb2hsv() (+2 more)

### Community 167 - "dataMap.ts"
Cohesion: 0.14
Nodes (13): ConnectionAndOrder, emptyCanvasRect, FunctionMetadata, FunctionMetadataV1, FunctionPositionMetadata, IFileSysTreeItem, ITreeDirectory, ITreeFile (+5 more)

### Community 168 - "connectors.ts"
Cohesion: 0.33
Nodes (10): fallbackConnectorIconUrl(), getAllConnectorProperties(), getBrandColorFromConnector(), getDescriptionFromConnector(), getDisplayNameFromConnector(), getIconUriFromConnector(), isIndependentPublisherConnector(), normalizeConnectorId() (+2 more)

### Community 169 - "tenant.ts"
Cohesion: 0.22
Nodes (4): BaseTenantService, BaseTenantServiceOptions, Tenant, ITenantService

### Community 170 - "host.ts"
Cohesion: 0.15
Nodes (4): ContentType, IHostService, IsConnectorFn, ConnectorProperty

### Community 171 - "getHybridAppBaseRelativeUrl"
Cohesion: 0.22
Nodes (5): getHybridAppBaseRelativeUrl(), filterAzureConnection(), filterStateful(), needsAzureConnection(), StandardSearchService

### Community 172 - "dataMapSchema.ts"
Cohesion: 0.18
Nodes (12): DataMapSchema, InputFormat, NamespaceDictionary, NormalizedDataType, PathItem, SchemaExtended, SchemaFileFormat, SchemaNode (+4 more)

### Community 173 - "index.ts"
Cohesion: 0.30
Nodes (7): cache, IntlGlobalProvider(), IntlGlobalProviderProps, resetIntl(), IntlProvider(), IntlProviderProps, loadLocaleData()

### Community 174 - "clone.ts"
Cohesion: 0.24
Nodes (3): BaseCloneService, BaseCloneServiceOptions, ICloneService

### Community 175 - "dataoperations.ts"
Cohesion: 0.18
Nodes (10): chunktext, composeOperation, csvTableOperation, htmlTableOperation, joinOperation, parsedocument, parsedocumentwithmetadata, parseJsonOperation (+2 more)

### Community 177 - "operations.ts"
Cohesion: 0.27
Nodes (7): isScopeOperation(), normalizeTemplate(), replaceTemplatePlaceholders(), WORKFLOW_EDGE_TYPES, WORKFLOW_NODE_TYPES, WorkflowEdgeType, WorkflowNodeType

### Community 179 - "datetime.spec.ts"
Cohesion: 0.31
Nodes (7): cache, getTestIntl(), intl, mockUseIntl(), getDuration(), TimeUnit, toFriendlyDurationString()

### Community 180 - "ExpressionParser"
Cohesion: 0.42
Nodes (3): ExpressionParser, TokenToParse, ExpressionTokenType

### Community 181 - "dereference.ts"
Cohesion: 0.27
Nodes (5): CyclicalRefMetadata, DereferencedDocument, dereferenceSwagger(), RFC-6901, Outlook

### Community 182 - "Use Cases"
Cohesion: 0.20
Nodes (9): API, Feature Flags Based on Version, `isMultiVariableSupport(version?)` (deprecated), `isVersionSupported(currentVersion, requiredVersion, exactMatch?)`, Migration Path, Use Cases, Version Format, Version Gating in Service Configuration (+1 more)

### Community 183 - "Action"
Cohesion: 0.20
Nodes (10): Action, ApiConnectionAction, ApiConnectionWebhookAction, ChildWorkflow, ComposeAction, FunctionAction, HttpAction, HttpWebhookAction (+2 more)

### Community 184 - "TimeoutableAction"
Cohesion: 0.20
Nodes (10): AgentAction, ApiConnectionAction, ApiConnectionWebhookAction, ApiManagementAction, ChildWorkflow, FunctionAction, HttpAction, HttpWebhookAction (+2 more)

### Community 185 - "dereference.ts"
Cohesion: 0.31
Nodes (4): Outlook, CyclicalRefMetadata, DereferencedDocument, dereferenceSwagger()

### Community 186 - "knowledge.ts"
Cohesion: 0.25
Nodes (8): ArtifactCreationStatus, ArtifactType, ContentKind, KnowledgeHub, KnowledgeHubArtifact, KnowledgeHubExtended, ProgressStatus, UploadFileHandler

### Community 187 - "logicAppsV2Expression.ts"
Cohesion: 0.22
Nodes (8): AddSubtractTimeInputs, AddSubtractTimeInputsType, ConvertTimeZoneInputs, ConvertTimeZoneInputsType, CurrentTimeInputs, ExpressionAction, OffsetTimeInputs, OffsetTimeInputsType

### Community 188 - "guid"
Cohesion: 0.39
Nodes (6): RFC-4122, customLengthGuid(), guid(), hexValues, isAGuid(), useGuid()

### Community 189 - "control.ts"
Cohesion: 0.29
Nodes (6): foreachOperation, ifOperation, scopeOperation, switchOperation, terminateOperation, untilOperation

### Community 190 - "datetime.ts"
Cohesion: 0.29
Nodes (6): addToTimeOperation, convertTimezoneOperation, currentTimeOperation, getFutureTimeOperation, getPastTimeOperation, subtractFromTimeOperation

### Community 191 - "http.ts"
Cohesion: 0.29
Nodes (6): httpActionOperation, httpSwaggerActionOperation, httpSwaggerTriggerOperation, httpTriggerOperation, httpWebhookActionOperation, httpWebhookTriggerOperation

### Community 192 - "RetryableActionInputs"
Cohesion: 0.29
Nodes (7): ApiConnectionInputs, ApiConnectionWebhookInputs, ChildWorkflowInputs, FunctionInputs, HttpInputs, HttpInputsOptional, RetryableActionInputs

### Community 193 - "Trigger"
Cohesion: 0.29
Nodes (7): ApiConnectionTrigger, ApiConnectionWebhookTrigger, HttpTrigger, HttpWebhookTrigger, ManualTrigger, RecurrenceTrigger, Trigger

### Community 194 - "rosettanet.ts"
Cohesion: 0.33
Nodes (5): api, rosettaNetDecodeOperation, rosettaNetEncodeOperation, rosettaNetGroup, rosettaNetWairForResponseOperation

### Community 196 - "version.ts"
Cohesion: 0.53
Nodes (4): BundleVersionRequirements, compareVersions(), isVersionSupported(), parseVersion()

### Community 197 - "apiManagement.ts"
Cohesion: 0.40
Nodes (4): api, apiManagementActionOperation, apiManagementGroup, apiManagementTriggerOperation

### Community 198 - "dereferenceJsonSchema.ts"
Cohesion: 0.50
Nodes (3): dereferenceJsonSchema(), SchemaObject, RFC-6901

### Community 201 - "ScopeAction"
Cohesion: 0.50
Nodes (4): ForEachAction, IfAction, ScopeAction, UntilAction

## Knowledge Gaps
- **1381 isolated node(s):** `iseBadge`, `mockAxiosPost`, `mockGetAccessToken`, `defaultOptions`, `simpleWorkflow` (+1376 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **25 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `equals()` connect `equals` to `search.ts`, `functions.ts`, `operationmanifest.ts`, `operation.ts`, `connection.ts`, `operationmanifest.ts`, `Connector`, `connector.ts`, `connections.ts`, `SchemaProcessor`, `parser.ts`, `utils.ts`, `index.ts`, `ResolutionService`, `parameterprocessor.ts`, `index.ts`, `ExpressionScanner`, `index.ts`, `index.ts`, `Expression`?**
  _High betweenness centrality (0.032) - this node is a cross-community bridge._
- **Why does `OperationManifest` connect `operationmanifest.ts` to `parser.ts`, `utils.ts`, `operationmanifest.ts`, `xml.ts`, `badges.ts`, `index.ts`, `operationmanifest.ts`, `connector.ts`, `operationmanifest.ts`, `index.ts`?**
  _High betweenness centrality (0.031) - this node is a cross-community bridge._
- **Why does `Connector` connect `Connector` to `search.ts`, `operationmanifest.ts`, `connectors.ts`, `connection.ts`, `operationmanifest.ts`, `connector.ts`, `connector.ts`, `operationmanifest.ts`, `connections.ts`?**
  _High betweenness centrality (0.028) - this node is a cross-community bridge._
- **What connects `iseBadge`, `mockAxiosPost`, `mockGetAccessToken` to the rest of the system?**
  _1381 weakly-connected nodes found - possible documentation gaps or missing edges._
- **Should `logicAppsV2.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.020833333333333332 - nodes in this community are weakly interconnected._
- **Should `search.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.06905370843989769 - nodes in this community are weakly interconnected._
- **Should `functions.ts` be split into smaller, more focused modules?**
  _Cohesion score 0.06498015873015874 - nodes in this community are weakly interconnected._