# ANTECEDENTES
El 11 de noviembre del 2008, la Comisión Nacional de Banca y de Valores (CNBV), publicó en su boletín de prensa que todas las empresas listadas en la Bolsa Mexicana de Valores (BMV), tenían que adoptar las "Normas Internacionales de Información Financiera" o IFRS, por sus siglas en inglés, menos el sector financiero.  Este proceso terminó en el 2012.  La evolución de esta medida, llevo a que todas las empresas listadas en la BMV, tengan que presentar sus estados financieros en el código __XBRL__.

# XBRL
El XBRL, es un lenguaje abierto, que se está usando para la comunicación electrónica de datos comerciales y financieros. El objetivo de este lenguaje es eliminar los errores en la captura de datos financieros.  Eliminar la incompatibilidad de formatos, al mismo tiempo que permite la verificación y validaciónd de los datos.

En el caso del los reportes XBRL para uso en finanzas, el lenguaje tiene una __taxonomía__ (descripción de los conceptos de un reporte financiero) y siguen las normas de la IFRS, así como los requisitos gubernamentales como lo es la CNBV para la presentación de sus reportes financieros. 

En el punto "TAXONIMIA XBRL PARA LAS EMPRESAS LISTADAS EN LA BMV", se describe cada uno de los 307 conceptos que se tienen dada en la TAXONIMA para México.  

En el punto "CONSTRUCCION DE LOS REPORTES FINANCIEROS", se especifica que conceptos corresponden al "Estado de Resultados", "Balance General", y "Flujos de Efectivo".

# SOBRE EL ARCHIVO "informacion_financiera.json"
El archivo "informacion_financiera.json", contiene todos los reportes XBRL, publicados por las emisoras que cotizan en la BMV.  A la fecha de este documento incluye el periodo del tercer trimestre del 2016 al segundo trimestre del 2019.  Por diferentes razones, no todas las empresas han presentado sus reportes XBRL trimestrales:

* __AUTLAN__: 3er trimestre, 2017
* __BOLSA__: 4to trimestre, 2016
* __CMOCTEZ__:  Empezó a reportarlos a partir del 4to trimestre 2018
* __CUERVO__:  3er trimestre, 2016
* __GCC__:  Empezó a reportarlos a partir del 4to trimestre 2018
* __GEO__:  Dejó de reportar a partir del 3er trimestre 2017. +
* __GFAMSA__:  Empezó a reportarlos a partir del 4to trimestre 2018
* __GMEXICO__:  2do trimestre, 2018
* __KIMBER__: 4to trimestre del 2016, 2017 y 2018 ++
* __LALA__: 3er trimestre, 2016
* __MEGA__:  Empezó a reportarlos a partir del 4to trimestre 2018
* __MEXCHEM__:  1er trimestre, 2018
* __MFRSICO__:  1er trimestre, 2018
* __OHLMEX__:  4to trimestre, 2018, 1ero y 2do del 2019
* __OMA__: 1er trimestre, 2019
* __PAPEL__: 1er y 4to trimestre, 2018
* __PE&OLES__: 4to trimestre del 2016, 2017 y 2018++.  1er trimestre 2018
* __WALMEX__:  4to trimestre del 2016, 2017 y 2018++

*__NOTA__:*
*__+__:  GEO se declarada en bancarrota*
*__++__:  Solo reportaron los estados consolidados, no los trimestrales.*

## TAXONIMIA XBRL
Para cada reporte trimestral, el archivo contiene los siguientes conceptos:
1.  AccrualsAndDeferredIncomeClassifiedAsCurrent
1.  AccrualsAndDeferredIncomeClassifiedAsNoncurrent
1.  AccrualsClassifiedAsCurrent
1.  AccrualsClassifiedAsNoncurrent
1.  ActivoMonetarioCirculante
1.  ActivoMonetarioNoCirculante
1.  AdjustmentsForAmountsTransferredToInitialCarryingAmountOfHedgedItems
1.  AdministrativeExpense
1.  Aircraft
1.  AmountRecognisedInOtherComprehensiveIncomeAndAccumulatedInEquityRelatingToNoncurrentAssetsOrDisposalGroupsHeldForSale
1.  AmountsRemovedFromEquityAndAdjustedAgainstFairValueOfFinancialAssetsOnReclassificationOutOfFairValueThroughOtherComprehensiveIncomeMeasurementCategoryNetOfTax
1.  AnticiposParaConstrucciones
1.  AnticiposParaLaAdquisicionDePropiedadesDeInversion
1.  Assets
1.  BalancesWithBanks
1.  BancaComercial
1.  BankingArrangementsClassifiedAsCashEquivalents
1.  BasicEarningsLossPerShare
1.  BasicEarningsLossPerShareFromContinuingOperations
1.  BasicEarningsLossPerShareFromDiscontinuedOperations
1.  BrandNames
1.  Buildings
1.  BursatilesListadasEnBolsaConGarantia
1.  BursatilesListadasEnBolsaQuirografarios
1.  CapitalRedemptionReserve
1.  CapitalSocialNominal
1.  CapitalSocialPorActualizacion
1.  Cash
1.  CashAndCashEquivalents
1.  CashEquivalents
1.  CashOnHand
1.  ColocacionesPrivadasConGarantia
1.  ColocacionesPrivadasQuirografarios
1.  ComercioExteriorBancarios
1.  ComprehensiveIncome
1.  ComprehensiveIncomeAttributableToNoncontrollingInterests
1.  ComprehensiveIncomeAttributableToOwnersOfParent
1.  ComputerSoftware
1.  ConGarantiaBancarios
1.  ConstructionInProgress
1.  CopyrightsPatentsAndOtherIndustrialPropertyRightsServiceAndOperatingRights
1.  CostOfSales
1.  CreditosBancariosACortoPlazo
1.  CreditosBancariosALargoPlazo
1.  CreditosBursatilesACortoPlazo
1.  CreditosBursatilesALargoPlazo
1.  CurrentAdvancesToSuppliers
1.  CurrentAssets
1.  CurrentAssetsLiabilities
1.  CurrentAssetsOtherThanAssetsOrDisposalGroupsClassifiedAsHeldForSaleOrAsHeldForDistributionToOwners
1.  CurrentBiologicalAssets
1.  CurrentLeaseLiabilities
1.  CurrentLiabilities
1.  CurrentLiabilitiesOtherThanLiabilitiesIncludedInDisposalGroupsClassifiedAsHeldForSale
1.  CurrentPayablesOnSocialSecurityAndTaxesOtherThanIncomeTax
1.  CurrentPrepaidExpenses
1.  CurrentPrepayments
1.  CurrentProvisions
1.  CurrentProvisionsForEmployeeBenefits
1.  CurrentRawMaterialsAndCurrentProductionSupplies
1.  CurrentReceivablesFromRentalOfProperties
1.  CurrentReceivablesFromSaleOfProperties
1.  CurrentReceivablesFromTaxesOtherThanIncomeTax
1.  CurrentRetentionPayables
1.  CurrentTaxAssetsCurrent
1.  CurrentTaxAssetsNoncurrent
1.  CurrentTaxLiabilitiesCurrent
1.  CurrentTaxLiabilitiesNoncurrent
1.  CurrentTradeReceivables
1.  CurrentValueAddedTaxPayables
1.  CurrentValueAddedTaxReceivables
1.  DeferredIncomeClassifiedAsCurrent
1.  DeferredIncomeClassifiedAsNoncurrent
1.  DeferredTaxAssets
1.  DeferredTaxLiabilities
1.  DepreciacionYAmortizacionOperativa
1.  DeudaDeAsociadasGarantizada
1.  DilutedEarningsLossPerShare
1.  DilutedEarningsLossPerShareFromContinuingOperations
1.  DilutedEarningsLossPerShareFromDiscontinuedOperations
1.  DistributionCosts
1.  EfectivoRestringido
1.  Equity
1.  EquityAndLiabilities
1.  EquityAttributableToOwnersOfParent
1.  FinanceCosts
1.  FinanceIncome
1.  FinishedGoods
1.  FixturesAndFittings
1.  FondosParaPensionesYPrimaDeAntiguedad
1.  GainsLossesOnCashFlowHedgesNetOfTax
1.  GainsLossesOnChangeInValueOfForeignCurrencyBasisSpreadsNetOfTax
1.  GainsLossesOnChangeInValueOfForwardElementsOfForwardContractsNetOfTax
1.  GainsLossesOnChangeInValueOfTimeValueOfOptionsNetOfTax
1.  GainsLossesOnExchangeDifferencesOnTranslationNetOfTax
1.  GainsLossesOnFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncomeNetOfTax
1.  GainsLossesOnHedgesOfNetInvestmentsInForeignOperationsNetOfTax
1.  GainsLossesOnRemeasuringAvailableforsaleFinancialAssetsNetOfTax
1.  GainsOnChangeInFairValueOfDerivatives
1.  Goodwill
1.  GrossProfit
1.  ImpuestoCausado
1.  ImpuestoDiferido
1.  IncomeTaxExpenseContinuingOperations
1.  IntangibleAssetsAndGoodwill
1.  IntangibleAssetsOtherThanGoodwill
1.  IntangibleAssetsUnderDevelopment
1.  IntangibleExplorationAndEvaluationAssets
1.  InteresesDevengadosACargo
1.  InteresesGanados
1.  Inventories
1.  InvestmentAccountedForUsingEquityMethod
1.  InvestmentProperty
1.  InvestmentPropertyCompleted
1.  InvestmentPropertyUnderConstructionOrDevelopment
1.  InvestmentsInAssociates
1.  InvestmentsInJointVentures
1.  InvestmentsInSubsidiaries
1.  InvestmentsInSubsidiariesJointVenturesAndAssociates
1.  IssuedCapital
1.  Land
1.  LandAndBuildings
1.  Liabilities
1.  LiabilitiesIncludedInDisposalGroupsClassifiedAsHeldForSale
1.  LicencesAndFranchises
1.  LossesOnChangeInFairValueOfDerivatives
1.  Machinery
1.  MastheadsAndPublishingTitles
1.  Merchandise
1.  MergerReserve
1.  MiningAssets
1.  MonetarioActivoPasivoNeto
1.  MotorVehicles
1.  NetAssetsLiabilities
1.  NoncontrollingInterests
1.  NoncurrentAssets
1.  NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForDistributionToOwners
1.  NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForSale
1.  NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForSaleOrAsHeldForDistributionToOwners
1.  NoncurrentBiologicalAssets
1.  NoncurrentInventories
1.  NoncurrentLeaseLiabilities
1.  NoncurrentLeasePrepayments
1.  NoncurrentLiabilities
1.  NoncurrentPayables
1.  NoncurrentPayablesOnSocialSecurityAndTaxesOtherThanIncomeTax
1.  NoncurrentPayablesToRelatedParties
1.  NoncurrentPayablesToTradeSuppliers
1.  NoncurrentPrepayments
1.  NoncurrentProvisions
1.  NoncurrentProvisionsForEmployeeBenefits
1.  NoncurrentReceivables
1.  NoncurrentReceivablesDueFromRelatedParties
1.  NoncurrentReceivablesFromRentalOfProperties
1.  NoncurrentReceivablesFromSaleOfProperties
1.  NoncurrentReceivablesFromTaxesOtherThanIncomeTax
1.  NoncurrentRetentionPayables
1.  NoncurrentTradeReceivables
1.  NoncurrentValueAddedTaxPayables
1.  NoncurrentValueAddedTaxReceivables
1.  NumeroDeAccionesEnCirculacion
1.  NumeroDeAccionesRecompradas
1.  NumeroDeEmpleados
1.  NumeroDeFuncionarios
1.  NumeroDeObreros
1.  OfficeEquipment
1.  OilAndGasAssets
1.  OtherCashAndCashEquivalents
1.  OtherComprehensiveIncome
1.  OtherComprehensiveIncomeNetOfTaxAvailableforsaleFinancialAssets
1.  OtherComprehensiveIncomeNetOfTaxCashFlowHedges
1.  OtherComprehensiveIncomeNetOfTaxChangeInFairValueOfFinancialLiabilityAttributableToChangeInCreditRiskOfLiability
1.  OtherComprehensiveIncomeNetOfTaxChangeInValueOfForeignCurrencyBasisSpreads
1.  OtherComprehensiveIncomeNetOfTaxChangeInValueOfForwardElementsOfForwardContracts
1.  OtherComprehensiveIncomeNetOfTaxChangeInValueOfTimeValueOfOptions
1.  OtherComprehensiveIncomeNetOfTaxExchangeDifferencesOnTranslation
1.  OtherComprehensiveIncomeNetOfTaxFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncome
1.  OtherComprehensiveIncomeNetOfTaxGainsLossesFromInvestmentsInEquityInstruments
1.  OtherComprehensiveIncomeNetOfTaxGainsLossesOnHedgingInstrumentsThatHedgeInvestmentsInEquityInstruments
1.  OtherComprehensiveIncomeNetOfTaxGainsLossesOnRemeasurementsOfDefinedBenefitPlans
1.  OtherComprehensiveIncomeNetOfTaxGainsLossesOnRevaluation
1.  OtherComprehensiveIncomeNetOfTaxHedgesOfNetInvestmentsInForeignOperations
1.  OtherComprehensiveIncomeThatWillBeReclassifiedToProfitOrLossNetOfTax
1.  OtherComprehensiveIncomeThatWillNotBeReclassifiedToProfitOrLossNetOfTax
1.  OtherCurrentFinancialAssets
1.  OtherCurrentFinancialLiabilities
1.  OtherCurrentNonfinancialAssets
1.  OtherCurrentNonfinancialLiabilities
1.  OtherCurrentPayables
1.  OtherCurrentReceivables
1.  OtherExpenseByFunction
1.  OtherFinanceCost
1.  OtherFinanceIncome
1.  OtherIncome
1.  OtherIntangibleAssets
1.  OtherInventories
1.  OtherLongtermProvisions
1.  OtherNoncurrentFinancialAssets
1.  OtherNoncurrentFinancialLiabilities
1.  OtherNoncurrentNonfinancialAssets
1.  OtherNoncurrentNonfinancialLiabilities
1.  OtherNoncurrentPayables
1.  OtherNoncurrentReceivables
1.  OtherPropertyPlantAndEquipment
1.  OtherProvisions
1.  OtherReserves
1.  OtherRevenue
1.  OtherShorttermProvisions
1.  OtrosBancarios
1.  OtrosCreditosConCostoACortoPlazo
1.  OtrosCreditosConCostoALargoPlazo
1.  OtrosCreditosSinCostoACortoPlazo
1.  OtrosCreditosSinCostoALargoPlazo
1.  OtrosPasivosCirculantesYNoCirculantesConCosto
1.  OtrosPasivosCirculantesYNoCirculantesSinCosto
1.  OtrosPasivosFinancierosACortoPlazo
1.  OtrosPasivosFinancierosALargoPlazo
1.  OtrosResultadosIntegrales
1.  PasivoMonetarioCirculante
1.  PasivoMonetarioNoCirculante
1.  PerdidaPorCambiosEnValorRazonableDeInstrumentosFinancieros
1.  PerdidaPorFluctuacionCambiaria
1.  ProductionSupplies
1.  ProfitLoss
1.  ProfitLossAttributableToNoncontrollingInterests
1.  ProfitLossAttributableToOwnersOfParent
1.  ProfitLossBeforeTax
1.  ProfitLossFromContinuingOperations
1.  ProfitLossFromDiscontinuedOperations
1.  ProfitLossFromOperatingActivities
1.  PropertyIntendedForSaleInOrdinaryCourseOfBusiness
1.  PropertyPlantAndEquipment
1.  Proveedores
1.  RawMaterials
1.  RecipesFormulaeModelsDesignsAndPrototypes
1.  ReclassificationAdjustmentsOnAvailableforsaleFinancialAssetsNetOfTax
1.  ReclassificationAdjustmentsOnCashFlowHedgesNetOfTax
1.  ReclassificationAdjustmentsOnChangeInValueOfForeignCurrencyBasisSpreadsNetOfTax
1.  ReclassificationAdjustmentsOnChangeInValueOfForwardElementsOfForwardContractsNetOfTax
1.  ReclassificationAdjustmentsOnChangeInValueOfTimeValueOfOptionsNetOfTax
1.  ReclassificationAdjustmentsOnExchangeDifferencesOnTranslationNetOfTax
1.  ReclassificationAdjustmentsOnFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncomeNetOfTax
1.  ReclassificationAdjustmentsOnHedgesOfNetInvestmentsInForeignOperationsNetOfTax
1.  RentalIncome
1.  RentasPorFacturar
1.  RentDeferredIncomeClassifiedAsCurrent
1.  RentDeferredIncomeClassifiedAsNoncurrent
1.  ReserveForCatastrophe
1.  ReserveForEqualisation
1.  ReserveOfCashFlowHedges
1.  ReserveOfChangeInFairValueOfFinancialLiabilityAttributableToChangeInCreditRiskOfLiability
1.  ReserveOfChangeInValueOfForeignCurrencyBasisSpreads
1.  ReserveOfChangeInValueOfForwardElementsOfForwardContracts
1.  ReserveOfChangeInValueOfTimeValueOfOptions
1.  ReserveOfDiscretionaryParticipationFeatures
1.  ReserveOfEquityComponentOfConvertibleInstruments
1.  ReserveOfExchangeDifferencesOnTranslation
1.  ReserveOfGainsAndLossesFromInvestmentsInEquityInstruments
1.  ReserveOfGainsAndLossesOnFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncome
1.  ReserveOfGainsAndLossesOnHedgingInstrumentsThatHedgeInvestmentsInEquityInstruments
1.  ReserveOfGainsAndLossesOnRemeasuringAvailableforsaleFinancialAssets
1.  ReserveOfRemeasurementsOfDefinedBenefitPlans
1.  ReserveOfSharebasedPayments
1.  RetainedEarnings
1.  RevaluationSurplus
1.  Revenue
1.  RevenueFromConstructionContracts
1.  RevenueFromDividends
1.  RevenueFromInterest
1.  RevenueFromRenderingOfServices
1.  RevenueFromRoyalties
1.  RevenueFromSaleOfGoods
1.  RightofuseAssetsThatDoNotMeetDefinitionOfInvestmentProperty
1.  ShareOfOtherComprehensiveIncomeOfAssociatesAndJointVenturesAccountedForUsingEquityMethodThatWillBeReclassifiedToProfitOrLossNetOfTax
1.  ShareOfOtherComprehensiveIncomeOfAssociatesAndJointVenturesAccountedForUsingEquityMethodThatWillNotBeReclassifiedToProfitOrLossNetOfTax
1.  ShareOfProfitLossOfAssociatesAndJointVenturesAccountedForUsingEquityMethod
1.  SharePremium
1.  Ships
1.  ShorttermDepositsClassifiedAsCashEquivalents
1.  ShorttermEmployeeBenefitsAccruals
1.  ShorttermInvestmentsClassifiedAsCashEquivalents
1.  SpareParts
1.  StatutoryReserve
1.  TangibleExplorationAndEvaluationAssets
1.  TotalActivoMonetario
1.  TotalBancarios
1.  TotalBursatilesListadasEnBolsaYColocacionesPrivadas
1.  TotalDeCreditos
1.  TotalDeGastosFinancieros
1.  TotalDeImpuestosALaUtilidad
1.  TotalDeIngresosFinancieros
1.  TotalDeOtrosPasivosFinancierosACortoPlazo
1.  TotalDeOtrosPasivosFinancierosALargoPlazo
1.  TotalOtrosPasivosCirculantesYNoCirculantesConCosto
1.  TotalOtrosPasivosCirculantesYNoCirculantesSinCosto
1.  TotalPasivoMonetario
1.  TotalProveedores
1.  TradeAndOtherCurrentPayables
1.  TradeAndOtherCurrentPayablesToRelatedParties
1.  TradeAndOtherCurrentPayablesToTradeSuppliers
1.  TradeAndOtherCurrentReceivables
1.  TradeAndOtherCurrentReceivablesDueFromRelatedParties
1.  TreasuryShares
1.  UtilidadPorCambiosEnValorRazonableDeInstrumentosFinancieros
1.  UtilidadPorFluctuacionCambiaria
1.  Vehicles
1.  WorkInProgress



## TAXONOMIA DEL ESTADO DE RESULTADOS
1. Revenue
1. CostOfSales
1. GrossProfit
1. DistributionCosts
1. AdministrativeExpense
1. OtherIncome
1. OtherExpenseByFunction
1. ProfitLossFromOperatingActivities
1. FinanceIncome
1. FinanceCosts
1. ShareOfProfitLossOfAssociatesAndJointVenturesAccountedForUsingEquityMethod
1. ProfitLossBeforeTax
1. IncomeTaxExpenseContinuingOperations
1. ProfitLossFromContinuingOperations
1. ProfitLossFromDiscontinuedOperations
1. ProfitLoss


## TAXONOMIA BALANCE GENERAL

**ACTIVOS:**
1. Assets

**Activos circulantes:**
    1. CashAndCashEquivalents
    1. TradeAndOtherCurrentReceivables
    1. CurrentTaxAssetsCurrent
    1. OtherCurrentFinancialAssets
    1. Inventories
    1. CurrentBiologicalAssets
    1. OtherCurrentNonfinancialAssets
    1. CurrentAssetsOtherThanAssetsOrDisposalGroupsClassifiedAsHeldForSaleOrAsHeldForDistributionToOwners
    1. NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForSaleOrAsHeldForDistributionToOwners
    1. CurrentAssets
  
  
**Activos no circulantes:**
    1. NoncurrentReceivables
    1. CurrentTaxAssetsNoncurrent
    1. NoncurrentInventories
    1. NoncurrentBiologicalAssets
    1. OtherNoncurrentFinancialAssets
    1. InvestmentAccountedForUsingEquityMethod
    1. InvestmentsInSubsidiariesJointVenturesAndAssociates
    1. PropertyPlantAndEquipment
    1. InvestmentProperty
    1. RightofuseAssetsThatDoNotMeetDefinitionOfInvestmentProperty
    1. Goodwill
    1. IntangibleAssetsOtherThanGoodwill
    1. DeferredTaxAssets
    1. OtherNoncurrentNonfinancialAssets
    1. NoncurrentAssets




## CONCEPTOS DE LOS ESTADOS DE FLUJOS DE EFECTIVO
