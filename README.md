# java8-flags

     intx ActiveProcessorCount                      = -1                                  {product}

    uintx AdaptiveSizeDecrementScaleFactor          = 4                                   {product}

    uintx AdaptiveSizeMajorGCDecayTimeScale         = 10                                  {product}

    uintx AdaptiveSizePausePolicy                   = 0                                   {product}

    uintx AdaptiveSizePolicyCollectionCostMargin    = 50                                  {product}

    uintx AdaptiveSizePolicyInitializingSteps       = 20                                  {product}

    uintx AdaptiveSizePolicyOutputInterval          = 0                                   {product}

    uintx AdaptiveSizePolicyWeight                  = 10                                  {product}

    uintx AdaptiveSizeThroughPutPolicy              = 0                                   {product}

    uintx AdaptiveTimeWeight                        = 25                                  {product}

     bool AdjustConcurrency                         = false                               {product}

     bool AggressiveHeap                            = false                               {product}

     bool AggressiveOpts                            = false                               {product}

     intx AliasLevel                                = 3                                   {C2 product}

     bool AlignVector                               = true                                {C2 product}

     intx AllocateInstancePrefetchLines             = 1                                   {product}

     intx AllocatePrefetchDistance                  = 256                                 {product}

     intx AllocatePrefetchInstr                     = 3                                   {product}

     intx AllocatePrefetchLines                     = 3                                   {product}

     intx AllocatePrefetchStepSize                  = 64                                  {product}

     intx AllocatePrefetchStyle                     = 1                                   {product}

     bool AllowJNIEnvProxy                          = false                               {product}

     bool AllowNonVirtualCalls                      = false                               {product}

     bool AllowParallelDefineClass                  = false                               {product}

     bool AllowUserSignalHandlers                   = false                               {product}

     bool AlwaysActAsServerClassMachine             = false                               {product}

     bool AlwaysCompileLoopMethods                  = false                               {product}

     bool AlwaysLockClassLoader                     = false                               {product}

     bool AlwaysPreTouch                            = false                               {product}

     bool AlwaysRestoreFPU                          = false                               {product}

     bool AlwaysTenure                              = false                               {product}

     bool AssertOnSuspendWaitFailure                = false                               {product}

     bool AssumeMP                                  = false                               {product}

     intx AutoBoxCacheMax                           = 128                                 {C2 product}

    uintx AutoGCSelectPauseMillis                   = 5000                                {product}

     intx BCEATraceLevel                            = 0                                   {product}

     intx BackEdgeThreshold                         = 100000                              {pd product}

     bool BackgroundCompilation                     = true                                {pd product}

    uintx BaseFootPrintEstimate                     = 268435456                           {product}

     intx BiasedLockingBulkRebiasThreshold          = 20                                  {product}

     intx BiasedLockingBulkRevokeThreshold          = 40                                  {product}

     intx BiasedLockingDecayTime                    = 25000                               {product}

     intx BiasedLockingStartupDelay                 = 4000                                {product}

     bool BindCMSThreadToCPU                        = false                               {diagnostic}

     bool BindGCTaskThreadsToCPUs                   = false                               {product}

     bool BlockLayoutByFrequency                    = true                                {C2 product}

     intx BlockLayoutMinDiamondPercentage           = 20                                  {C2 product}

     bool BlockLayoutRotateLoops                    = true                                {C2 product}

     bool BlockOffsetArrayUseUnallocatedBlock       = false                               {diagnostic}

     bool BranchOnRegister                          = false                               {C2 product}

     bool BytecodeVerificationLocal                 = false                               {product}

     bool BytecodeVerificationRemote                = true                                {product}

     bool C1OptimizeVirtualCallProfiling            = true                                {C1 product}

     bool C1PatchInvokeDynamic                      = true                                {C1 diagnostic}

     bool C1ProfileBranches                         = true                                {C1 product}

     bool C1ProfileCalls                            = true                                {C1 product}

     bool C1ProfileCheckcasts                       = true                                {C1 product}

     bool C1ProfileInlinedCalls                     = true                                {C1 product}

     bool C1ProfileVirtualCalls                     = true                                {C1 product}

     bool C1UpdateMethodData                        = true                                {C1 product}

     intx CICompilerCount                          := 3                                   {product}

     bool CICompilerCountPerCPU                     = true                                {product}

     bool CITime                                    = false                               {product}

     bool CMSAbortSemantics                         = false                               {product}

    uintx CMSAbortablePrecleanMinWorkPerIteration   = 100                                 {product}

     intx CMSAbortablePrecleanWaitMillis            = 100                                 {manageable}

    uintx CMSBitMapYieldQuantum                     = 10485760                            {product}

    uintx CMSBootstrapOccupancy                     = 50                                  {product}

     bool CMSClassUnloadingEnabled                  = true                                {product}

    uintx CMSClassUnloadingMaxInterval              = 0                                   {product}

     bool CMSCleanOnEnter                           = true                                {product}

     bool CMSCompactWhenClearAllSoftRefs            = true                                {product}

    uintx CMSConcMarkMultiple                       = 32                                  {product}

     bool CMSConcurrentMTEnabled                    = true                                {product}

    uintx CMSCoordinatorYieldSleepCount             = 10                                  {product}

     bool CMSDumpAtPromotionFailure                 = false                               {product}

     bool CMSEdenChunksRecordAlways                 = true                                {product}

    uintx CMSExpAvgFactor                           = 50                                  {product}

     bool CMSExtrapolateSweep                       = false                               {product}

    uintx CMSFullGCsBeforeCompaction                = 0                                   {product}

    uintx CMSIncrementalDutyCycle                   = 10                                  {product}

    uintx CMSIncrementalDutyCycleMin                = 0                                   {product}

     bool CMSIncrementalMode                        = false                               {product}

    uintx CMSIncrementalOffset                      = 0                                   {product}

     bool CMSIncrementalPacing                      = true                                {product}

    uintx CMSIncrementalSafetyFactor                = 10                                  {product}

    uintx CMSIndexedFreeListReplenish               = 4                                   {product}

     intx CMSInitiatingOccupancyFraction            = -1                                  {product}

    uintx CMSIsTooFullPercentage                    = 98                                  {product}

   double CMSLargeCoalSurplusPercent                = 0.950000                            {product}

   double CMSLargeSplitSurplusPercent               = 1.000000                            {product}

     bool CMSLoopWarn                               = false                               {product}

    uintx CMSMaxAbortablePrecleanLoops              = 0                                   {product}

     intx CMSMaxAbortablePrecleanTime               = 5000                                {product}

    uintx CMSOldPLABMax                             = 1024                                {product}

    uintx CMSOldPLABMin                             = 16                                  {product}

    uintx CMSOldPLABNumRefills                      = 4                                   {product}

    uintx CMSOldPLABReactivityFactor                = 2                                   {product}

     bool CMSOldPLABResizeQuicker                   = false                               {product}

    uintx CMSOldPLABToleranceFactor                 = 4                                   {product}

     bool CMSPLABRecordAlways                       = true                                {product}

    uintx CMSParPromoteBlocksToClaim                = 16                                  {product}

     bool CMSParallelInitialMarkEnabled             = true                                {product}

     bool CMSParallelRemarkEnabled                  = true                                {product}

     bool CMSParallelSurvivorRemarkEnabled          = true                                {product}

    uintx CMSPrecleanDenominator                    = 3                                   {product}

    uintx CMSPrecleanIter                           = 3                                   {product}

    uintx CMSPrecleanNumerator                      = 2                                   {product}

     bool CMSPrecleanRefLists1                      = true                                {product}

     bool CMSPrecleanRefLists2                      = false                               {product}

     bool CMSPrecleanSurvivors1                     = false                               {product}

     bool CMSPrecleanSurvivors2                     = true                                {product}

    uintx CMSPrecleanThreshold                      = 1000                                {product}

     bool CMSPrecleaningEnabled                     = true                                {product}

     bool CMSPrintChunksInDump                      = false                               {product}

     bool CMSPrintEdenSurvivorChunks                = false                               {product}

     bool CMSPrintObjectsInDump                     = false                               {product}

    uintx CMSRemarkVerifyVariant                    = 1                                   {product}

     bool CMSReplenishIntermediate                  = true                                {product}

    uintx CMSRescanMultiple                         = 32                                  {product}

    uintx CMSSamplingGrain                          = 16384                               {product}

     bool CMSScavengeBeforeRemark                   = false                               {product}

    uintx CMSScheduleRemarkEdenPenetration          = 50                                  {product}

    uintx CMSScheduleRemarkEdenSizeThreshold        = 2097152                             {product}

    uintx CMSScheduleRemarkSamplingRatio            = 5                                   {product}

   double CMSSmallCoalSurplusPercent                = 1.050000                            {product}

   double CMSSmallSplitSurplusPercent               = 1.100000                            {product}

     bool CMSSplitIndexedFreeListBlocks             = true                                {product}

     intx CMSTriggerInterval                        = -1                                  {manageable}

    uintx CMSTriggerRatio                           = 80                                  {product}

     intx CMSWaitDuration                           = 2000                                {manageable}

    uintx CMSWorkQueueDrainThreshold                = 10                                  {product}

     bool CMSYield                                  = true                                {product}

    uintx CMSYieldSleepCount                        = 0                                   {product}

    uintx CMSYoungGenPerWorker                      = 67108864                            {pd product}

    uintx CMS_FLSPadding                            = 1                                   {product}

    uintx CMS_FLSWeight                             = 75                                  {product}

    uintx CMS_SweepPadding                          = 1                                   {product}

    uintx CMS_SweepTimerThresholdMillis             = 10                                  {product}

    uintx CMS_SweepWeight                           = 75                                  {product}

    uintx CPUForCMSThread                           = 0                                   {diagnostic}

     bool CheckEndorsedAndExtDirs                   = false                               {product}

     bool CheckJNICalls                             = false                               {product}

     bool ClassUnloading                            = true                                {product}

     bool ClassUnloadingWithConcurrentMark          = true                                {product}

     intx ClearFPUAtPark                            = 0                                   {product}

     bool ClipInlining                              = true                                {product}

    uintx CodeCacheExpansionSize                    = 65536                               {pd product}

    uintx CodeCacheMinimumFreeSpace                 = 512000                              {product}

     bool CollectGen0First                          = false                               {product}

     bool CompactFields                             = true                                {product}

     intx CompilationPolicyChoice                   = 3                                   {product}

ccstrlist CompileCommand                            =                                     {product}

    ccstr CompileCommandFile                        =                                     {product}

ccstrlist CompileOnly                               =                                     {product}

     intx CompileThreshold                          = 10000                               {pd product}

     bool CompilerThreadHintNoPreempt               = true                                {product}

     intx CompilerThreadPriority                    = -1                                  {product}

     intx CompilerThreadStackSize                   = 0                                   {pd product}

    uintx CompressedClassSpaceSize                  = 1073741824                          {product}

    uintx ConcGCThreads                             = 0                                   {product}

     intx ConditionalMoveLimit                      = 3                                   {C2 pd product}

     intx ContendedPaddingWidth                     = 128                                 {product}

     bool ConvertSleepToYield                       = true                                {pd product}

     bool ConvertYieldToSleep                       = false                               {product}

     bool CrashOnOutOfMemoryError                   = false                               {product}

     bool CreateMinidumpOnCrash                     = false                               {product}

     bool CriticalJNINatives                        = true                                {product}

     bool DTraceAllocProbes                         = false                               {product}

     bool DTraceMethodProbes                        = false                               {product}

     bool DTraceMonitorProbes                       = false                               {product}

     bool DebugInlinedCalls                         = true                                {C2 diagnostic}

     bool DebugNonSafepoints                        = false                               {diagnostic}

     bool Debugging                                 = false                               {product}

    uintx DefaultMaxRAMFraction                     = 4                                   {product}

     intx DefaultThreadPriority                     = -1                                  {product}

     bool DeferInitialCardMark                      = false                               {diagnostic}

     intx DeferPollingPageLoopCount                 = -1                                  {product}

     intx DeferThrSuspendLoopCount                  = 4000                                {product}

     bool DeoptimizeRandom                          = false                               {product}

     bool DisableAttachMechanism                    = false                               {product}

     bool DisableExplicitGC                         = false                               {product}

ccstrlist DisableIntrinsic                          =                                     {C2 diagnostic}

     bool DisplayVMOutput                           = true                                {diagnostic}

     bool DisplayVMOutputToStderr                   = false                               {product}

     bool DisplayVMOutputToStdout                   = false                               {product}

     bool DoEscapeAnalysis                          = true                                {C2 product}

     intx DominatorSearchLimit                      = 1000                                {C2 diagnostic}

     bool DontCompileHugeMethods                    = true                                {product}

     bool DontYieldALot                             = false                               {pd product}

    ccstr DumpLoadedClassList                       =                                     {product}

     bool DumpReplayDataOnError                     = true                                {product}

     bool DumpSharedSpaces                          = false                               {product}

     bool EagerXrunInit                             = false                               {product}

     intx EliminateAllocationArraySizeLimit         = 64                                  {C2 product}

     bool EliminateAllocations                      = true                                {C2 product}

     bool EliminateAutoBox                          = true                                {C2 product}

     bool EliminateLocks                            = true                                {C2 product}

     bool EliminateNestedLocks                      = true                                {C2 product}

     intx EmitSync                                  = 0                                   {product}

     bool EnableContended                           = true                                {product}

     bool EnableInvokeDynamic                       = true                                {diagnostic}

     bool EnableResourceManagementTLABCache         = true                                {product}

     bool EnableSharedLookupCache                   = true                                {product}

     bool EnableTracing                             = false                               {product}

    uintx ErgoHeapSizeLimit                         = 0                                   {product}

    ccstr ErrorFile                                 =                                     {product}

    ccstr ErrorReportServer                         =                                     {product}

   double EscapeAnalysisTimeout                     = 20.000000                           {C2 product}

     bool EstimateArgEscape                         = true                                {product}

     bool ExitOnOutOfMemoryError                    = false                               {product}

     bool ExplicitGCInvokesConcurrent               = false                               {product}

     bool ExplicitGCInvokesConcurrentAndUnloadsClasses  = false                               {product}

     bool ExtendedDTraceProbes                      = false                               {product}

    ccstr ExtraSharedClassListFile                  =                                     {product}

     bool FLSAlwaysCoalesceLarge                    = false                               {product}

    uintx FLSCoalescePolicy                         = 2                                   {product}

   double FLSLargestBlockCoalesceProximity          = 0.990000                            {product}

     bool FLSVerifyAllHeapReferences                = false                               {diagnostic}

     bool FLSVerifyIndexTable                       = false                               {diagnostic}

     bool FLSVerifyLists                            = false                               {diagnostic}

     bool FailOverToOldVerifier                     = true                                {product}

     bool FastTLABRefill                            = true                                {product}

     intx FenceInstruction                          = 0                                   {ARCH product}

     intx FieldsAllocationStyle                     = 1                                   {product}

     bool FilterSpuriousWakeups                     = true                                {product}

    ccstr FlightRecorderOptions                     =                                     {product}

     bool FoldStableValues                          = true                                {diagnostic}

     bool ForceDynamicNumberOfGCThreads             = false                               {diagnostic}

     bool ForceNUMA                                 = false                               {product}

     bool ForceTimeHighResolution                   = false                               {product}

     bool ForceUnreachable                          = false                               {diagnostic}

     intx FreqInlineSize                            = 325                                 {pd product}

   double G1ConcMarkStepDurationMillis              = 10.000000                           {product}

    uintx G1ConcRSHotCardLimit                      = 4                                   {product}

    uintx G1ConcRSLogCacheSize                      = 10                                  {product}

     intx G1ConcRefinementGreenZone                 = 0                                   {product}

     intx G1ConcRefinementRedZone                   = 0                                   {product}

     intx G1ConcRefinementServiceIntervalMillis     = 300                                 {product}

    uintx G1ConcRefinementThreads                   = 0                                   {product}

     intx G1ConcRefinementThresholdStep             = 0                                   {product}

     intx G1ConcRefinementYellowZone                = 0                                   {product}

    uintx G1ConfidencePercent                       = 50                                  {product}

    uintx G1HeapRegionSize                          = 0                                   {product}

    uintx G1HeapWastePercent                        = 5                                   {product}

    uintx G1MixedGCCountTarget                      = 8                                   {product}

     bool G1PrintHeapRegions                        = false                               {diagnostic}

     bool G1PrintRegionLivenessInfo                 = false                               {diagnostic}

     intx G1RSetRegionEntries                       = 0                                   {product}

    uintx G1RSetScanBlockSize                       = 64                                  {product}

     intx G1RSetSparseRegionEntries                 = 0                                   {product}

     intx G1RSetUpdatingPauseTimePercent            = 10                                  {product}

     intx G1RefProcDrainInterval                    = 10                                  {product}

    uintx G1ReservePercent                          = 10                                  {product}

    uintx G1SATBBufferEnqueueingThresholdPercent    = 60                                  {product}

     intx G1SATBBufferSize                          = 1024                                {product}

     bool G1SummarizeConcMark                       = false                               {diagnostic}

     bool G1SummarizeRSetStats                      = false                               {diagnostic}

     intx G1SummarizeRSetStatsPeriod                = 0                                   {diagnostic}

     bool G1TraceConcRefinement                     = false                               {diagnostic}

     intx G1UpdateBufferSize                        = 256                                 {product}

     bool G1UseAdaptiveConcRefinement               = true                                {product}

     bool G1VerifyHeapRegionCodeRoots               = false                               {diagnostic}

     bool G1VerifyRSetsDuringFullGC                 = false                               {diagnostic}

    uintx GCDrainStackTargetSize                    = 64                                  {product}

    uintx GCHeapFreeLimit                           = 2                                   {product}

    uintx GCLockerEdenExpansionPercent              = 5                                   {product}

     bool GCLockerInvokesConcurrent                 = false                               {product}

    uintx GCLockerRetryAllocationCount              = 2                                   {diagnostic}

    uintx GCLogFileSize                             = 8192                                {product}

     bool GCParallelVerificationEnabled             = true                                {diagnostic}

    uintx GCPauseIntervalMillis                     = 0                                   {product}

    uintx GCTaskTimeStampEntries                    = 200                                 {product}

    uintx GCTimeLimit                               = 98                                  {product}

    uintx GCTimeRatio                               = 99                                  {product}

     intx GuaranteedSafepointInterval               = 1000                                {diagnostic}

    uintx HeapBaseMinAddress                        = 2147483648                          {pd product}

     bool HeapDumpAfterFullGC                       = false                               {manageable}

     bool HeapDumpBeforeFullGC                      = false                               {manageable}

     bool HeapDumpOnOutOfMemoryError                = false                               {manageable}

    ccstr HeapDumpPath                              =                                     {manageable}

    uintx HeapFirstMaximumCompactionCount           = 3                                   {product}

    uintx HeapMaximumCompactionInterval             = 20                                  {product}

    uintx HeapSizePerGCThread                       = 87241520                            {product}

     bool IgnoreEmptyClassPaths                     = false                               {product}

     bool IgnoreUnrecognizedVMOptions               = false                               {product}

     bool IgnoreUnverifiableClassesDuringDump       = false                               {diagnostic}

    uintx IncreaseFirstTierCompileThresholdAt       = 50                                  {product}

     bool IncrementalInline                         = true                                {C2 product}

    uintx InitialBootClassLoaderMetaspaceSize       = 4194304                             {product}

    uintx InitialCodeCacheSize                      = 2555904                             {pd product}

    uintx InitialHeapSize                          := 268435456                           {product}

    uintx InitialRAMFraction                        = 64                                  {product}

   double InitialRAMPercentage                      = 1.562500                            {product}

    uintx InitialSurvivorRatio                      = 8                                   {product}

    uintx InitialTenuringThreshold                  = 7                                   {product}

    uintx InitiatingHeapOccupancyPercent            = 45                                  {product}

     bool Inline                                    = true                                {product}

    ccstr InlineDataFile                            =                                     {product}

     intx InlineSmallCode                           = 2000                                {pd product}

     bool InlineSynchronizedMethods                 = true                                {C1 product}

     bool InsertMemBarAfterArraycopy                = true                                {C2 product}

     intx InteriorEntryAlignment                    = 16                                  {C2 pd product}

     intx InterpreterProfilePercentage              = 33                                  {product}

     bool JNIDetachReleasesMonitors                 = true                                {product}

     bool JavaMonitorsInStackTrace                  = true                                {product}

     intx JavaPriority10_To_OSPriority              = -1                                  {product}

     intx JavaPriority1_To_OSPriority               = -1                                  {product}

     intx JavaPriority2_To_OSPriority               = -1                                  {product}

     intx JavaPriority3_To_OSPriority               = -1                                  {product}

     intx JavaPriority4_To_OSPriority               = -1                                  {product}

     intx JavaPriority5_To_OSPriority               = -1                                  {product}

     intx JavaPriority6_To_OSPriority               = -1                                  {product}

     intx JavaPriority7_To_OSPriority               = -1                                  {product}

     intx JavaPriority8_To_OSPriority               = -1                                  {product}

     intx JavaPriority9_To_OSPriority               = -1                                  {product}

     bool LIRFillDelaySlots                         = false                               {C1 pd product}

    uintx LargePageHeapSizeThreshold                = 134217728                           {product}

    uintx LargePageSizeInBytes                      = 0                                   {product}

     bool LazyBootClassLoader                       = true                                {product}

     intx LiveNodeCountInliningCutoff               = 40000                               {C2 product}

     bool LogCommercialFeatures                     = false                               {product}

     bool LogCompilation                            = false                               {diagnostic}

     bool LogEvents                                 = true                                {diagnostic}

    uintx LogEventsBufferEntries                    = 10                                  {diagnostic}

    ccstr LogFile                                   =                                     {diagnostic}

     bool LogVMOutput                               = false                               {diagnostic}

     bool LoopLimitCheck                            = true                                {C2 diagnostic}

     intx LoopMaxUnroll                             = 16                                  {C2 product}

     intx LoopOptsCount                             = 43                                  {C2 product}

     intx LoopUnrollLimit                           = 60                                  {C2 pd product}

     intx LoopUnrollMin                             = 4                                   {C2 product}

     bool LoopUnswitching                           = true                                {C2 product}

    uintx MallocMaxTestWords                        = 0                                   {diagnostic}

     intx MallocVerifyInterval                      = 0                                   {diagnostic}

     intx MallocVerifyStart                         = 0                                   {diagnostic}

     bool ManagementServer                          = false                               {product}

    uintx MarkStackSize                             = 4194304                             {product}

    uintx MarkStackSizeMax                          = 536870912                           {product}

    uintx MarkSweepAlwaysCompactCount               = 4                                   {product}

    uintx MarkSweepDeadRatio                        = 1                                   {product}

     intx MaxBCEAEstimateLevel                      = 5                                   {product}

     intx MaxBCEAEstimateSize                       = 150                                 {product}

    uintx MaxDirectMemorySize                       = 0                                   {product}

     bool MaxFDLimit                                = true                                {product}

    uintx MaxGCMinorPauseMillis                     = 4294967295                          {product}

    uintx MaxGCPauseMillis                          = 4294967295                          {product}

    uintx MaxHeapFreeRatio                          = 100                                 {manageable}

    uintx MaxHeapSize                              := 4278190080                          {product}

     intx MaxInlineLevel                            = 9                                   {product}

     intx MaxInlineSize                             = 35                                  {product}

     intx MaxJNILocalCapacity                       = 65536                               {product}

     intx MaxJavaStackTraceDepth                    = 1024                                {product}

     intx MaxJumpTableSize                          = 65000                               {C2 product}

     intx MaxJumpTableSparseness                    = 5                                   {C2 product}

     intx MaxLabelRootDepth                         = 1100                                {C2 product}

     intx MaxLoopPad                                = 11                                  {C2 product}

    uintx MaxMetaspaceExpansion                     = 5451776                             {product}

    uintx MaxMetaspaceFreeRatio                     = 70                                  {product}

    uintx MaxMetaspaceSize                          = 4294901760                          {product}

    uintx MaxNewSize                               := 1426063360                          {product}

     intx MaxNodeLimit                              = 75000                               {C2 product}

 uint64_t MaxRAM                                    = 0                                   {pd product}

    uintx MaxRAMFraction                            = 4                                   {product}

   double MaxRAMPercentage                          = 25.000000                           {product}

     intx MaxRecursiveInlineLevel                   = 1                                   {product}

    uintx MaxTenuringThreshold                      = 15                                  {product}

     intx MaxTrivialSize                            = 6                                   {product}

     intx MaxVectorSize                             = 32                                  {C2 product}

    uintx MetaspaceSize                             = 21807104                            {pd product}

     bool MethodFlushing                            = true                                {product}

    uintx MinHeapDeltaBytes                        := 524288                              {product}

    uintx MinHeapFreeRatio                          = 0                                   {manageable}

     intx MinInliningThreshold                      = 250                                 {product}

     intx MinJumpTableSize                          = 10                                  {C2 pd product}

    uintx MinMetaspaceExpansion                     = 339968                              {product}

    uintx MinMetaspaceFreeRatio                     = 40                                  {product}

    uintx MinRAMFraction                            = 2                                   {product}

   double MinRAMPercentage                          = 50.000000                           {product}

    uintx MinSurvivorRatio                          = 3                                   {product}

    uintx MinTLABSize                               = 2048                                {product}

     intx MonitorBound                              = 0                                   {product}

     bool MonitorInUseLists                         = false                               {product}

     intx MultiArrayExpandLimit                     = 6                                   {C2 product}

     bool MustCallLoadClassInternal                 = false                               {product}

    uintx NUMAChunkResizeWeight                     = 20                                  {product}

    uintx NUMAInterleaveGranularity                 = 2097152                             {product}

    uintx NUMAPageScanRate                          = 256                                 {product}

    uintx NUMASpaceResizeRate                       = 1073741824                          {product}

     bool NUMAStats                                 = false                               {product}

    ccstr NativeMemoryTracking                      = off                                 {product}

     bool NeedsDeoptSuspend                         = false                               {pd product}

     bool NeverActAsServerClassMachine              = false                               {pd product}

     bool NeverTenure                               = false                               {product}

    uintx NewRatio                                  = 2                                   {product}

    uintx NewSize                                  := 89128960                            {product}

    uintx NewSizeThreadIncrease                     = 5320                                {pd product}

     intx NmethodSweepActivity                      = 10                                  {product}

     intx NmethodSweepCheckInterval                 = 5                                   {product}

     intx NmethodSweepFraction                      = 16                                  {product}

     intx NodeLimitFudgeFactor                      = 2000                                {C2 product}

    uintx NumberOfGCLogFiles                        = 0                                   {product}

     intx NumberOfLoopInstrToAlign                  = 4                                   {C2 product}

     intx ObjectAlignmentInBytes                    = 8                                   {lp64_product}

    uintx OldPLABSize                               = 1024                                {product}

    uintx OldPLABWeight                             = 50                                  {product}

    uintx OldSize                                  := 179306496                           {product}

     bool OmitStackTraceInFastThrow                 = true                                {product}

ccstrlist OnError                                   =                                     {product}

ccstrlist OnOutOfMemoryError                        =                                     {product}

     intx OnStackReplacePercentage                  = 140                                 {pd product}

     bool OptimizeExpensiveOps                      = true                                {C2 diagnostic}

     bool OptimizeFill                              = true                                {C2 product}

     bool OptimizePtrCompare                        = true                                {C2 product}

     bool OptimizeStringConcat                      = true                                {C2 product}

     bool OptoBundling                              = false                               {C2 pd product}

     intx OptoLoopAlignment                         = 16                                  {pd product}

     bool OptoScheduling                            = false                               {C2 pd product}

    uintx PLABWeight                                = 75                                  {product}

     bool PSChunkLargeArrays                        = true                                {product}

     intx ParGCArrayScanChunk                       = 50                                  {product}

     intx ParGCCardsPerStrideChunk                  = 256                                 {diagnostic}

    uintx ParGCDesiredObjsFromOverflowList          = 20                                  {product}

    uintx ParGCStridesPerThread                     = 2                                   {diagnostic}

     bool ParGCTrimOverflow                         = true                                {product}

     bool ParGCUseLocalOverflow                     = false                               {product}

    uintx ParallelGCBufferWastePct                  = 10                                  {product}

     bool ParallelGCRetainPLAB                      = false                               {diagnostic}

    uintx ParallelGCThreads                         = 6                                   {product}

     bool ParallelGCVerbose                         = false                               {product}

    uintx ParallelOldDeadWoodLimiterMean            = 50                                  {product}

    uintx ParallelOldDeadWoodLimiterStdDev          = 80                                  {product}

     bool ParallelRefProcBalancingEnabled           = true                                {product}

     bool ParallelRefProcEnabled                    = false                               {product}

     bool PartialPeelAtUnsignedTests                = true                                {C2 product}

     bool PartialPeelLoop                           = true                                {C2 product}

     intx PartialPeelNewPhiDelta                    = 0                                   {C2 product}

     bool PauseAtExit                               = false                               {diagnostic}

     bool PauseAtStartup                            = false                               {diagnostic}

    ccstr PauseAtStartupFile                        =                                     {diagnostic}

    uintx PausePadding                              = 1                                   {product}

     intx PerBytecodeRecompilationCutoff            = 200                                 {product}

     intx PerBytecodeTrapLimit                      = 4                                   {product}

     intx PerMethodRecompilationCutoff              = 400                                 {product}

     intx PerMethodTrapLimit                        = 100                                 {product}

     bool PerfAllowAtExitRegistration               = false                               {product}

     bool PerfBypassFileSystemCheck                 = false                               {product}

     intx PerfDataMemorySize                        = 32768                               {product}

     intx PerfDataSamplingInterval                  = 50                                  {product}

    ccstr PerfDataSaveFile                          =                                     {product}

     bool PerfDataSaveToFile                        = false                               {product}

     bool PerfDisableSharedMem                      = false                               {product}

     intx PerfMaxStringConstLength                  = 1024                                {product}

     intx PreInflateSpin                            = 10                                  {pd product}

     bool PreferInterpreterNativeStubs              = false                               {pd product}

     intx PrefetchCopyIntervalInBytes               = 576                                 {product}

     intx PrefetchFieldsAhead                       = 1                                   {product}

     intx PrefetchScanIntervalInBytes               = 576                                 {product}

     bool PreserveAllAnnotations                    = false                               {product}

     bool PreserveFramePointer                      = false                               {pd product}

    uintx PretenureSizeThreshold                    = 0                                   {product}

     bool PrintActiveCpus                           = false                               {diagnostic}

     bool PrintAdapterHandlers                      = false                               {diagnostic}

     bool PrintAdaptiveSizePolicy                   = false                               {product}

     bool PrintAssembly                             = false                               {diagnostic}

    ccstr PrintAssemblyOptions                      =                                     {diagnostic}

     bool PrintBiasedLockingStatistics              = false                               {diagnostic}

     bool PrintCMSInitiationStatistics              = false                               {product}

     intx PrintCMSStatistics                        = 0                                   {product}

     bool PrintClassHistogram                       = false                               {manageable}

     bool PrintClassHistogramAfterFullGC            = false                               {manageable}

     bool PrintClassHistogramBeforeFullGC           = false                               {manageable}

     bool PrintCodeCache                            = false                               {product}

     bool PrintCodeCacheOnCompilation               = false                               {product}

     bool PrintCommandLineFlags                     = false                               {product}

     bool PrintCompilation                          = false                               {product}

     bool PrintCompilation2                         = false                               {diagnostic}

     bool PrintCompressedOopsMode                   = false                               {diagnostic}

     bool PrintConcurrentLocks                      = false                               {manageable}

     bool PrintContainerInfo                        = false                               {diagnostic}

     bool PrintDTraceDOF                            = false                               {diagnostic}

     intx PrintFLSCensus                            = 0                                   {product}

     intx PrintFLSStatistics                        = 0                                   {product}

     bool PrintFlagsFinal                          := true                                {product}

     bool PrintFlagsInitial                         = false                               {product}

     bool PrintGC                                   = false                               {manageable}

     bool PrintGCApplicationConcurrentTime          = false                               {product}

     bool PrintGCApplicationStoppedTime             = false                               {product}

     bool PrintGCCause                              = true                                {product}

     bool PrintGCDateStamps                         = false                               {manageable}

     bool PrintGCDetails                            = false                               {manageable}

     bool PrintGCID                                 = false                               {manageable}

     bool PrintGCTaskTimeStamps                     = false                               {product}

     bool PrintGCTimeStamps                         = false                               {manageable}

     bool PrintHeapAtGC                             = false                               {product rw}

     bool PrintHeapAtGCExtended                     = false                               {product rw}

     bool PrintHeapAtSIGBREAK                       = true                                {product}

     bool PrintInlining                             = false                               {diagnostic}

     bool PrintInterpreter                          = false                               {diagnostic}

     bool PrintIntrinsics                           = false                               {C2 diagnostic}

     bool PrintJNIGCStalls                          = false                               {product}

     bool PrintJNIResolving                         = false                               {product}

     bool PrintMethodFlushingStatistics             = false                               {diagnostic}

     bool PrintMethodHandleStubs                    = false                               {diagnostic}

     bool PrintNMTStatistics                        = false                               {diagnostic}

     bool PrintNMethods                             = false                               {diagnostic}

     bool PrintNativeNMethods                       = false                               {diagnostic}

     bool PrintOldPLAB                              = false                               {product}

     bool PrintOopAddress                           = false                               {product}

     bool PrintPLAB                                 = false                               {product}

     bool PrintParallelOldGCPhaseTimes              = false                               {product}

     bool PrintPreciseBiasedLockingStatistics       = false                               {C2 diagnostic}

     bool PrintPreciseRTMLockingStatistics          = false                               {C2 diagnostic}

     bool PrintPromotionFailure                     = false                               {product}

     bool PrintReferenceGC                          = false                               {product}

     bool PrintSafepointStatistics                  = false                               {product}

     intx PrintSafepointStatisticsCount             = 300                                 {product}

     intx PrintSafepointStatisticsTimeout           = -1                                  {product}

     bool PrintSharedArchiveAndExit                 = false                               {product}

     bool PrintSharedDictionary                     = false                               {product}

     bool PrintSharedSpaces                         = false                               {product}

     bool PrintSignatureHandlers                    = false                               {diagnostic}

     bool PrintStringDeduplicationStatistics        = false                               {product}

     bool PrintStringTableStatistics                = false                               {product}

     bool PrintStubCode                             = false                               {diagnostic}

     bool PrintTLAB                                 = false                               {product}

     bool PrintTenuringDistribution                 = false                               {product}

     bool PrintTieredEvents                         = false                               {product}

     bool PrintVMOptions                            = false                               {product}

     bool PrintVMQWaitTime                          = false                               {product}

     bool PrintWarnings                             = true                                {product}

    uintx ProcessDistributionStride                 = 4                                   {product}

     bool ProfileDynamicTypes                       = true                                {C2 diagnostic}

     bool ProfileInterpreter                        = true                                {pd product}

     bool ProfileIntervals                          = false                               {product}

     intx ProfileIntervalsTicks                     = 100                                 {product}

     intx ProfileMaturityPercentage                 = 20                                  {product}

     bool ProfileVM                                 = false                               {product}

     bool ProfilerPrintByteCodeStatistics           = false                               {product}

     bool ProfilerRecordPC                          = false                               {product}

    uintx PromotedPadding                           = 3                                   {product}

    uintx QueuedAllocationWarningCount              = 0                                   {product}

    uintx RTMRetryCount                             = 5                                   {ARCH product}

     bool RangeCheckElimination                     = true                                {product}

     bool RangeLimitCheck                           = true                                {C2 diagnostic}

     intx ReadPrefetchInstr                         = 0                                   {ARCH product}

     bool ReassociateInvariants                     = true                                {C2 product}

     bool ReduceBulkZeroing                         = true                                {C2 product}

     bool ReduceFieldZeroing                        = true                                {C2 product}

     bool ReduceInitialCardMarks                    = true                                {C2 product}

     bool ReduceSignalUsage                         = false                               {product}

     intx RefDiscoveryPolicy                        = 0                                   {product}

     bool ReflectionWrapResolutionErrors            = true                                {product}

     bool RegisterFinalizersAtInit                  = true                                {product}

     bool RelaxAccessControlCheck                   = false                               {product}

    ccstr ReplayDataFile                            =                                     {product}

     bool RequireSharedSpaces                       = false                               {product}

    uintx ReservedCodeCacheSize                     = 251658240                           {pd product}

     bool ResizeOldPLAB                             = true                                {product}

     bool ResizePLAB                                = true                                {product}

     bool ResizeTLAB                                = true                                {pd product}

     bool RestoreMXCSROnJNICalls                    = false                               {product}

     bool RestrictContended                         = true                                {product}

     bool RewriteBytecodes                          = true                                {pd product}

     bool RewriteFrequentPairs                      = true                                {pd product}

     intx SafepointPollOffset                       = 256                                 {C1 pd product}

     intx SafepointSpinBeforeYield                  = 2000                                {product}

     bool SafepointTimeout                          = false                               {product}

     intx SafepointTimeoutDelay                     = 10000                               {product}

     bool ScavengeBeforeFullGC                      = true                                {product}

     intx ScavengeRootsInCode                       = 2                                   {diagnostic}

     intx SelfDestructTimer                         = 0                                   {product}

     bool SerializeVMOutput                         = true                                {diagnostic}

    ccstr SharedArchiveFile                         =                                     {diagnostic}

    uintx SharedBaseAddress                         = 0                                   {product}

    ccstr SharedClassListFile                       =                                     {product}

    uintx SharedMiscCodeSize                        = 122880                              {product}

    uintx SharedMiscDataSize                        = 4194304                             {product}

    uintx SharedReadOnlySize                        = 16777216                            {product}

    uintx SharedReadWriteSize                       = 16777216                            {product}

     bool ShowHiddenFrames                          = false                               {diagnostic}

     bool ShowMessageBoxOnError                     = false                               {product}

     intx SoftRefLRUPolicyMSPerMB                   = 1000                                {product}

     bool SpecialEncodeISOArray                     = true                                {C2 product}

     bool SplitIfBlocks                             = true                                {C2 product}

     intx StackRedPages                             = 1                                   {pd product}

     intx StackShadowPages                          = 6                                   {pd product}

     bool StackTraceInThrowable                     = true                                {product}

     intx StackYellowPages                          = 3                                   {pd product}

     bool StartAttachListener                       = false                               {product}

     intx StarvationMonitorInterval                 = 200                                 {product}

     bool StressLdcRewrite                          = false                               {product}

    uintx StringDeduplicationAgeThreshold           = 3                                   {product}

     bool StringDeduplicationRehashALot             = false                               {diagnostic}

     bool StringDeduplicationResizeALot             = false                               {diagnostic}

    uintx StringTableSize                           = 60013                               {product}

     bool SuppressFatalErrorMessage                 = false                               {product}

    uintx SurvivorPadding                           = 3                                   {product}

    uintx SurvivorRatio                             = 8                                   {product}

     intx SuspendRetryCount                         = 50                                  {product}

     intx SuspendRetryDelay                         = 5                                   {product}

     intx SyncFlags                                 = 0                                   {product}

    ccstr SyncKnobs                                 =                                     {product}

     intx SyncVerbose                               = 0                                   {product}

    uintx TLABAllocationWeight                      = 35                                  {product}

    uintx TLABRefillWasteFraction                   = 64                                  {product}

    uintx TLABSize                                  = 0                                   {product}

     bool TLABStats                                 = true                                {product}

    uintx TLABWasteIncrement                        = 4                                   {product}

    uintx TLABWasteTargetPercent                    = 1                                   {product}

    uintx TargetPLABWastePct                        = 10                                  {product}

    uintx TargetSurvivorRatio                       = 50                                  {product}

    uintx TenuredGenerationSizeIncrement            = 20                                  {product}

    uintx TenuredGenerationSizeSupplement           = 80                                  {product}

    uintx TenuredGenerationSizeSupplementDecay      = 2                                   {product}

     intx ThreadPriorityPolicy                      = 0                                   {product}

     bool ThreadPriorityVerbose                     = false                               {product}

    uintx ThreadSafetyMargin                        = 52428800                            {product}

     intx ThreadStackSize                           = 0                                   {pd product}

    uintx ThresholdTolerance                        = 10                                  {product}

     intx Tier0BackedgeNotifyFreqLog                = 10                                  {product}

     intx Tier0InvokeNotifyFreqLog                  = 7                                   {product}

     intx Tier0ProfilingStartPercentage             = 200                                 {product}

     intx Tier23InlineeNotifyFreqLog                = 20                                  {product}

     intx Tier2BackEdgeThreshold                    = 0                                   {product}

     intx Tier2BackedgeNotifyFreqLog                = 14                                  {product}

     intx Tier2CompileThreshold                     = 0                                   {product}

     intx Tier2InvokeNotifyFreqLog                  = 11                                  {product}

     intx Tier3BackEdgeThreshold                    = 60000                               {product}

     intx Tier3BackedgeNotifyFreqLog                = 13                                  {product}

     intx Tier3CompileThreshold                     = 2000                                {product}

     intx Tier3DelayOff                             = 2                                   {product}

     intx Tier3DelayOn                              = 5                                   {product}

     intx Tier3InvocationThreshold                  = 200                                 {product}

     intx Tier3InvokeNotifyFreqLog                  = 10                                  {product}

     intx Tier3LoadFeedback                         = 5                                   {product}

     intx Tier3MinInvocationThreshold               = 100                                 {product}

     intx Tier4BackEdgeThreshold                    = 40000                               {product}

     intx Tier4CompileThreshold                     = 15000                               {product}

     intx Tier4InvocationThreshold                  = 5000                                {product}

     intx Tier4LoadFeedback                         = 3                                   {product}

     intx Tier4MinInvocationThreshold               = 600                                 {product}

     bool TieredCompilation                         = true                                {pd product}

     intx TieredCompileTaskTimeout                  = 50                                  {product}

     intx TieredRateUpdateMaxTime                   = 25                                  {product}

     intx TieredRateUpdateMinTime                   = 1                                   {product}

     intx TieredStopAtLevel                         = 4                                   {product}

     bool TimeLinearScan                            = false                               {C1 product}

     bool TraceBiasedLocking                        = false                               {product}

     bool TraceClassLoading                         = false                               {product rw}

     bool TraceClassLoadingPreorder                 = false                               {product}

     bool TraceClassPaths                           = false                               {product}

     bool TraceClassResolution                      = false                               {product}

     bool TraceClassUnloading                       = false                               {product rw}

     bool TraceDynamicGCThreads                     = false                               {product}

     bool TraceGCTaskThread                         = false                               {diagnostic}

     bool TraceGen0Time                             = false                               {product}

     bool TraceGen1Time                             = false                               {product}

    ccstr TraceJVMTI                                =                                     {product}

     bool TraceJVMTIObjectTagging                   = false                               {diagnostic}

     bool TraceLoaderConstraints                    = false                               {product rw}

     bool TraceMetadataHumongousAllocation          = false                               {product}

     bool TraceMonitorInflation                     = false                               {product}

     bool TraceNMethodInstalls                      = false                               {diagnostic}

     bool TraceParallelOldGCTasks                   = false                               {product}

     intx TraceRedefineClasses                      = 0                                   {product}

     bool TraceSafepointCleanupTime                 = false                               {product}

     bool TraceSharedLookupCache                    = false                               {product}

     bool TraceSuspendWaitFailures                  = false                               {product}

     bool TraceTypeProfile                          = false                               {C2 diagnostic}

     intx TrackedInitializationLimit                = 50                                  {C2 product}

     bool TransmitErrorReport                       = false                               {product}

     bool TrapBasedNullChecks                       = false                               {pd product}

     bool TrapBasedRangeChecks                      = false                               {C2 pd product}

     intx TypeProfileArgsLimit                      = 2                                   {product}

    uintx TypeProfileLevel                          = 111                                 {pd product}

     intx TypeProfileMajorReceiverPercent           = 90                                  {C2 product}

     intx TypeProfileParmsLimit                     = 2                                   {product}

     intx TypeProfileWidth                          = 2                                   {product}

     intx UnguardOnExecutionViolation               = 0                                   {product}

     bool UnlinkSymbolsALot                         = false                               {product}

     bool UnlockDiagnosticVMOptions                := true                                {diagnostic}

     bool UnrollLimitCheck                          = true                                {C2 diagnostic}

     bool UnsyncloadClass                           = false                               {diagnostic}

     bool Use486InstrsOnly                          = false                               {ARCH product}

     bool UseAES                                    = true                                {product}

     bool UseAESCTRIntrinsics                       = true                                {product}

     bool UseAESIntrinsics                          = true                                {product}

     intx UseAVX                                    = 2                                   {ARCH product}

     bool UseAdaptiveGCBoundary                     = false                               {product}

     bool UseAdaptiveGenerationSizePolicyAtMajorCollection  = true                                {product}

     bool UseAdaptiveGenerationSizePolicyAtMinorCollection  = true                                {product}

     bool UseAdaptiveNUMAChunkSizing                = true                                {product}

     bool UseAdaptiveSizeDecayMajorGCCost           = true                                {product}

     bool UseAdaptiveSizePolicy                     = true                                {product}

     bool UseAdaptiveSizePolicyFootprintGoal        = true                                {product}

     bool UseAdaptiveSizePolicyWithSystemGC         = false                               {product}

     bool UseAddressNop                             = true                                {ARCH product}

     bool UseAltSigs                                = false                               {product}

     bool UseAutoGCSelectPolicy                     = false                               {product}

     bool UseBMI1Instructions                       = true                                {ARCH product}

     bool UseBMI2Instructions                       = true                                {ARCH product}

     bool UseBiasedLocking                          = true                                {product}

     bool UseBimorphicInlining                      = true                                {C2 product}

     bool UseBoundThreads                           = true                                {product}

     bool UseCLMUL                                  = true                                {ARCH product}

     bool UseCMSBestFit                             = true                                {product}

     bool UseCMSCollectionPassing                   = true                                {product}

     bool UseCMSCompactAtFullCollection             = true                                {product}

     bool UseCMSInitiatingOccupancyOnly             = false                               {product}

     bool UseCRC32Intrinsics                        = true                                {product}

     bool UseCodeCacheFlushing                      = true                                {product}

     bool UseCompiler                               = true                                {product}

     bool UseCompilerSafepoints                     = true                                {product}

     bool UseCompressedClassPointers               := true                                {lp64_product}

     bool UseCompressedOops                        := true                                {lp64_product}

     bool UseConcMarkSweepGC                        = false                               {product}

     bool UseCondCardMark                           = false                               {C2 product}

     bool UseCountLeadingZerosInstruction           = true                                {ARCH product}

     bool UseCountTrailingZerosInstruction          = true                                {ARCH product}

     bool UseCountedLoopSafepoints                  = false                               {C2 product}

     bool UseCounterDecay                           = true                                {product}

     bool UseDivMod                                 = true                                {C2 product}

     bool UseDynamicNumberOfGCThreads               = false                               {product}

     bool UseFPUForSpilling                         = true                                {C2 product}

     bool UseFastAccessorMethods                    = false                               {product}

     bool UseFastEmptyMethods                       = false                               {product}

     bool UseFastJNIAccessors                       = true                                {product}

     bool UseFastStosb                              = true                                {ARCH product}

     bool UseG1GC                                   = false                               {product}

     bool UseGCLogFileRotation                      = false                               {product}

     bool UseGCOverheadLimit                        = true                                {product}

     bool UseGCTaskAffinity                         = false                               {product}

     bool UseGHASHIntrinsics                        = true                                {product}

     bool UseHeavyMonitors                          = false                               {product}

     bool UseImplicitStableValues                   = true                                {C2 diagnostic}

     bool UseIncDec                                 = true                                {ARCH diagnostic}

     bool UseInlineCaches                           = true                                {product}

     bool UseInlineDepthForSpeculativeTypes         = true                                {C2 diagnostic}

     bool UseInterpreter                            = true                                {product}

     bool UseJumpTables                             = true                                {C2 product}

     bool UseLWPSynchronization                     = true                                {product}

     bool UseLargePages                             = false                               {pd product}

     bool UseLargePagesInMetaspace                  = false                               {product}

     bool UseLargePagesIndividualAllocation        := false                               {pd product}

     bool UseLockedTracing                          = false                               {product}

     bool UseLoopCounter                            = true                                {product}

     bool UseLoopInvariantCodeMotion                = true                                {C1 product}

     bool UseLoopPredicate                          = true                                {C2 product}

     bool UseMathExactIntrinsics                    = true                                {C2 product}

     bool UseMaximumCompactionOnSystemGC            = true                                {product}

     bool UseMembar                                 = false                               {pd product}

     bool UseMontgomeryMultiplyIntrinsic            = true                                {C2 product}

     bool UseMontgomerySquareIntrinsic              = true                                {C2 product}

     bool UseMulAddIntrinsic                        = true                                {C2 product}

     bool UseMultiplyToLenIntrinsic                 = true                                {C2 product}

     bool UseNUMA                                   = false                               {product}

     bool UseNUMAInterleaving                       = false                               {product}

     bool UseNewCode                                = false                               {diagnostic}

     bool UseNewCode2                               = false                               {diagnostic}

     bool UseNewCode3                               = false                               {diagnostic}

     bool UseNewLongLShift                          = false                               {ARCH product}

     bool UseOSErrorReporting                       = false                               {pd product}

     bool UseOldInlining                            = true                                {C2 product}

     bool UseOnStackReplacement                     = true                                {pd product}

     bool UseOnlyInlinedBimorphic                   = true                                {C2 product}

     bool UseOptoBiasInlining                       = true                                {C2 product}

     bool UsePSAdaptiveSurvivorSizePolicy           = true                                {product}

     bool UseParNewGC                               = false                               {product}

     bool UseParallelGC                            := true                                {product}

     bool UseParallelOldGC                          = true                                {product}

     bool UsePerfData                               = true                                {product}

     bool UsePopCountInstruction                    = true                                {product}

     bool UseRDPCForConstantTableBase               = false                               {C2 product}

     bool UseRTMDeopt                               = false                               {ARCH product}

     bool UseRTMLocking                             = false                               {ARCH product}

     bool UseSHA                                    = false                               {product}

     bool UseSHA1Intrinsics                         = false                               {product}

     bool UseSHA256Intrinsics                       = false                               {product}

     bool UseSHA512Intrinsics                       = false                               {product}

     intx UseSSE                                    = 4                                   {product}

     bool UseSSE42Intrinsics                        = true                                {product}

     bool UseSerialGC                               = false                               {product}

     bool UseSharedSpaces                           = false                               {product}

     bool UseSignalChaining                         = true                                {product}

     bool UseSquareToLenIntrinsic                   = true                                {C2 product}

     bool UseStoreImmI16                            = false                               {ARCH product}

     bool UseStringDeduplication                    = false                               {product}

     bool UseSuperWord                              = true                                {C2 product}

     bool UseTLAB                                   = true                                {pd product}

     bool UseThreadPriorities                       = true                                {pd product}

     bool UseTypeProfile                            = true                                {product}

     bool UseTypeSpeculation                        = true                                {C2 product}

     bool UseUTCFileTimestamp                       = true                                {product}

     bool UseUnalignedLoadStores                    = false                               {ARCH product}

     bool UseVMInterruptibleIO                      = false                               {product}

     bool UseXMMForArrayCopy                        = true                                {product}

     bool UseXmmI2D                                 = false                               {ARCH product}

     bool UseXmmI2F                                 = false                               {ARCH product}

     bool UseXmmLoadAndClearUpper                   = true                                {ARCH product}

     bool UseXmmRegToRegMoveAll                     = true                                {ARCH product}

     bool VMThreadHintNoPreempt                     = false                               {product}

     intx VMThreadPriority                          = -1                                  {product}

     intx VMThreadStackSize                         = 0                                   {pd product}

     intx ValueMapInitialSize                       = 11                                  {C1 product}

     intx ValueMapMaxLoopSize                       = 8                                   {C1 product}

     intx ValueSearchLimit                          = 1000                                {C2 product}

     bool VerboseVerification                       = false                               {diagnostic}

     bool VerifyAdapterCalls                        = false                               {diagnostic}

     bool VerifyAfterGC                             = false                               {diagnostic}

     bool VerifyBeforeExit                          = false                               {diagnostic}

     bool VerifyBeforeGC                            = false                               {diagnostic}

     bool VerifyBeforeIteration                     = false                               {diagnostic}

     bool VerifyDuringGC                            = false                               {diagnostic}

     bool VerifyDuringStartup                       = false                               {diagnostic}

     intx VerifyGCLevel                             = 0                                   {diagnostic}

    uintx VerifyGCStartAt                           = 0                                   {diagnostic}

     bool VerifyMergedCPBytecodes                   = true                                {product}

     bool VerifyMethodHandles                       = false                               {diagnostic}

     bool VerifyObjectStartArray                    = true                                {diagnostic}

     bool VerifyRememberedSets                      = false                               {diagnostic}

     bool VerifySharedSpaces                        = false                               {product}

     bool VerifySilently                            = false                               {diagnostic}

     bool VerifyStringTableAtExit                   = false                               {diagnostic}

ccstrlist VerifySubSet                              =                                     {diagnostic}

     bool WhiteBoxAPI                               = false                               {diagnostic}

     intx WorkAroundNPTLTimedWaitHang               = 1                                   {product}

    uintx YoungGenerationSizeIncrement              = 20                                  {product}

    uintx YoungGenerationSizeSupplement             = 80                                  {product}

    uintx YoungGenerationSizeSupplementDecay        = 8                                   {product}

    uintx YoungPLABSize                             = 4096                                {product}

     bool ZeroTLAB                                  = false                               {product}

     intx hashCode                                  = 5                                   {product}
