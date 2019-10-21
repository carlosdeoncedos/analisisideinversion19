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
1.- CashAndCashEquivalents

2.- TradeAndOtherCurrentReceivables

3.- CurrentTaxAssetsCurrent

4.- OtherCurrentFinancialAssets

5.- Inventories

6.- CurrentBiologicalAssets

7.- OtherCurrentNonfinancialAssets

8.- CurrentAssetsOtherThanAssetsOrDisposalGroupsClassifiedAsHeldForSaleOrAsHeldForDistributionToOwners

9.- NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForSaleOrAsHeldForDistributionToOwners

10.- CurrentAssets

11.- NoncurrentReceivables

12.- CurrentTaxAssetsNoncurrent

13.- NoncurrentInventories

14.- NoncurrentBiologicalAssets

15.- OtherNoncurrentFinancialAssets

16.- InvestmentAccountedForUsingEquityMethod

17.- InvestmentsInSubsidiariesJointVenturesAndAssociates

18.- PropertyPlantAndEquipment

19.- InvestmentProperty

20.- RightofuseAssetsThatDoNotMeetDefinitionOfInvestmentProperty

21.- Goodwill

22.- IntangibleAssetsOtherThanGoodwill

23.- DeferredTaxAssets

24.- OtherNoncurrentNonfinancialAssets

25.- NoncurrentAssets

26.- Assets

27.- TradeAndOtherCurrentPayables

28.- CurrentTaxLiabilitiesCurrent

29.- OtherCurrentFinancialLiabilities

30.- CurrentLeaseLiabilities

31.- OtherCurrentNonfinancialLiabilities

32.- CurrentProvisionsForEmployeeBenefits

33.- OtherShorttermProvisions

34.- CurrentProvisions

35.- CurrentLiabilitiesOtherThanLiabilitiesIncludedInDisposalGroupsClassifiedAsHeldForSale

36.- LiabilitiesIncludedInDisposalGroupsClassifiedAsHeldForSale

37.- CurrentLiabilities

38.- NoncurrentPayables

39.- CurrentTaxLiabilitiesNoncurrent

40.- OtherNoncurrentFinancialLiabilities

41.- NoncurrentLeaseLiabilities

42.- OtherNoncurrentNonfinancialLiabilities

43.- NoncurrentProvisionsForEmployeeBenefits

44.- OtherLongtermProvisions

45.- NoncurrentProvisions

46.- DeferredTaxLiabilities

47.- NoncurrentLiabilities

48.- Liabilities

49.- IssuedCapital

50.- SharePremium

51.- TreasuryShares

52.- RetainedEarnings

53.- OtherReserves

54.- EquityAttributableToOwnersOfParent

55.- NoncontrollingInterests

56.- Equity

57.- EquityAndLiabilities

58.- CapitalSocialNominal

59.- CapitalSocialPorActualizacion

60.- FondosParaPensionesYPrimaDeAntiguedad

61.- NumeroDeFuncionarios

62.- NumeroDeEmpleados

63.- NumeroDeObreros

64.- NumeroDeAccionesEnCirculacion

65.- NumeroDeAccionesRecompradas

66.- EfectivoRestringido

67.- DeudaDeAsociadasGarantizada

68.- CashOnHand

69.- BalancesWithBanks

70.- Cash

71.- ShorttermDepositsClassifiedAsCashEquivalents

72.- ShorttermInvestmentsClassifiedAsCashEquivalents

73.- BankingArrangementsClassifiedAsCashEquivalents

74.- CashEquivalents

75.- OtherCashAndCashEquivalents

76.- CurrentTradeReceivables

77.- TradeAndOtherCurrentReceivablesDueFromRelatedParties

78.- CurrentAdvancesToSuppliers

79.- CurrentPrepaidExpenses

80.- CurrentPrepayments

81.- CurrentReceivablesFromTaxesOtherThanIncomeTax

82.- CurrentValueAddedTaxReceivables

83.- CurrentReceivablesFromSaleOfProperties

84.- CurrentReceivablesFromRentalOfProperties

85.- OtherCurrentReceivables

86.- RawMaterials

87.- ProductionSupplies

88.- CurrentRawMaterialsAndCurrentProductionSupplies

89.- Merchandise

90.- WorkInProgress

91.- FinishedGoods

92.- SpareParts

93.- PropertyIntendedForSaleInOrdinaryCourseOfBusiness

94.- OtherInventories

95.- NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForSale

96.- NoncurrentAssetsOrDisposalGroupsClassifiedAsHeldForDistributionToOwners

97.- NoncurrentTradeReceivables

98.- NoncurrentReceivablesDueFromRelatedParties

99.- NoncurrentPrepayments

100.- NoncurrentLeasePrepayments

101.- NoncurrentReceivablesFromTaxesOtherThanIncomeTax

102.- NoncurrentValueAddedTaxReceivables

103.- NoncurrentReceivablesFromSaleOfProperties

104.- NoncurrentReceivablesFromRentalOfProperties

105.- RentasPorFacturar

106.- OtherNoncurrentReceivables

107.- InvestmentsInSubsidiaries

108.- InvestmentsInJointVentures

109.- InvestmentsInAssociates

110.- Land

111.- Buildings

112.- LandAndBuildings

113.- Machinery

114.- Ships

115.- Aircraft

116.- MotorVehicles

117.- Vehicles

118.- FixturesAndFittings

119.- OfficeEquipment

120.- TangibleExplorationAndEvaluationAssets

121.- MiningAssets

122.- OilAndGasAssets

123.- ConstructionInProgress

124.- AnticiposParaConstrucciones

125.- OtherPropertyPlantAndEquipment

126.- InvestmentPropertyCompleted

127.- InvestmentPropertyUnderConstructionOrDevelopment

128.- AnticiposParaLaAdquisicionDePropiedadesDeInversion

129.- BrandNames

130.- IntangibleExplorationAndEvaluationAssets

131.- MastheadsAndPublishingTitles

132.- ComputerSoftware

133.- LicencesAndFranchises

134.- CopyrightsPatentsAndOtherIndustrialPropertyRightsServiceAndOperatingRights

135.- RecipesFormulaeModelsDesignsAndPrototypes

136.- IntangibleAssetsUnderDevelopment

137.- OtherIntangibleAssets

138.- IntangibleAssetsAndGoodwill

139.- TradeAndOtherCurrentPayablesToTradeSuppliers

140.- TradeAndOtherCurrentPayablesToRelatedParties

141.- DeferredIncomeClassifiedAsCurrent

142.- RentDeferredIncomeClassifiedAsCurrent

143.- AccrualsClassifiedAsCurrent

144.- ShorttermEmployeeBenefitsAccruals

145.- AccrualsAndDeferredIncomeClassifiedAsCurrent

146.- CurrentPayablesOnSocialSecurityAndTaxesOtherThanIncomeTax

147.- CurrentValueAddedTaxPayables

148.- CurrentRetentionPayables

149.- OtherCurrentPayables

150.- CreditosBancariosACortoPlazo

151.- CreditosBursatilesACortoPlazo

152.- OtrosCreditosConCostoACortoPlazo

153.- OtrosCreditosSinCostoACortoPlazo

154.- OtrosPasivosFinancierosACortoPlazo

155.- TotalDeOtrosPasivosFinancierosACortoPlazo

156.- NoncurrentPayablesToTradeSuppliers

157.- NoncurrentPayablesToRelatedParties

158.- DeferredIncomeClassifiedAsNoncurrent

159.- RentDeferredIncomeClassifiedAsNoncurrent

160.- AccrualsClassifiedAsNoncurrent

161.- AccrualsAndDeferredIncomeClassifiedAsNoncurrent

162.- NoncurrentPayablesOnSocialSecurityAndTaxesOtherThanIncomeTax

163.- NoncurrentValueAddedTaxPayables

164.- NoncurrentRetentionPayables

165.- OtherNoncurrentPayables

166.- CreditosBancariosALargoPlazo

167.- CreditosBursatilesALargoPlazo

168.- OtrosCreditosConCostoALargoPlazo

169.- OtrosCreditosSinCostoALargoPlazo

170.- OtrosPasivosFinancierosALargoPlazo

171.- TotalDeOtrosPasivosFinancierosALargoPlazo

172.- OtherProvisions

173.- RevaluationSurplus

174.- ReserveOfExchangeDifferencesOnTranslation

175.- ReserveOfCashFlowHedges

176.- ReserveOfGainsAndLossesOnHedgingInstrumentsThatHedgeInvestmentsInEquityInstruments

177.- ReserveOfChangeInValueOfTimeValueOfOptions

178.- ReserveOfChangeInValueOfForwardElementsOfForwardContracts

179.- ReserveOfChangeInValueOfForeignCurrencyBasisSpreads

180.- ReserveOfGainsAndLossesOnFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncome

181.- ReserveOfGainsAndLossesOnRemeasuringAvailableforsaleFinancialAssets

182.- ReserveOfSharebasedPayments

183.- ReserveOfRemeasurementsOfDefinedBenefitPlans

184.- AmountRecognisedInOtherComprehensiveIncomeAndAccumulatedInEquityRelatingToNoncurrentAssetsOrDisposalGroupsHeldForSale

185.- ReserveOfGainsAndLossesFromInvestmentsInEquityInstruments

186.- ReserveOfChangeInFairValueOfFinancialLiabilityAttributableToChangeInCreditRiskOfLiability

187.- ReserveForCatastrophe

188.- ReserveForEqualisation

189.- ReserveOfDiscretionaryParticipationFeatures

190.- ReserveOfEquityComponentOfConvertibleInstruments

191.- CapitalRedemptionReserve

192.- MergerReserve

193.- StatutoryReserve

194.- OtrosResultadosIntegrales

195.- NetAssetsLiabilities

196.- CurrentAssetsLiabilities

197.- ComercioExteriorBancarios

198.- ConGarantiaBancarios

199.- BancaComercial

200.- OtrosBancarios

201.- TotalBancarios

202.- BursatilesListadasEnBolsaQuirografarios

203.- BursatilesListadasEnBolsaConGarantia

204.- ColocacionesPrivadasQuirografarios

205.- ColocacionesPrivadasConGarantia

206.- TotalBursatilesListadasEnBolsaYColocacionesPrivadas

207.- OtrosPasivosCirculantesYNoCirculantesConCosto

208.- TotalOtrosPasivosCirculantesYNoCirculantesConCosto

209.- Proveedores

210.- TotalProveedores

211.- OtrosPasivosCirculantesYNoCirculantesSinCosto

212.- TotalOtrosPasivosCirculantesYNoCirculantesSinCosto

213.- TotalDeCreditos

214.- ActivoMonetarioCirculante

215.- ActivoMonetarioNoCirculante

216.- TotalActivoMonetario

217.- PasivoMonetarioCirculante

218.- PasivoMonetarioNoCirculante

219.- TotalPasivoMonetario

220.- MonetarioActivoPasivoNeto

221.- Revenue

222.- CostOfSales

223.- GrossProfit

224.- DistributionCosts

225.- AdministrativeExpense

226.- OtherIncome

227.- OtherExpenseByFunction

228.- ProfitLossFromOperatingActivities

229.- FinanceIncome

230.- FinanceCosts

231.- ShareOfProfitLossOfAssociatesAndJointVenturesAccountedForUsingEquityMethod

232.- ProfitLossBeforeTax

233.- IncomeTaxExpenseContinuingOperations

234.- ProfitLossFromContinuingOperations

235.- ProfitLossFromDiscontinuedOperations

236.- ProfitLoss

237.- ProfitLossAttributableToOwnersOfParent

238.- ProfitLossAttributableToNoncontrollingInterests

239.- BasicEarningsLossPerShareFromContinuingOperations

240.- BasicEarningsLossPerShareFromDiscontinuedOperations

241.- BasicEarningsLossPerShare

242.- DilutedEarningsLossPerShareFromContinuingOperations

243.- DilutedEarningsLossPerShareFromDiscontinuedOperations

244.- DilutedEarningsLossPerShare

245.- OtherComprehensiveIncomeNetOfTaxGainsLossesFromInvestmentsInEquityInstruments

246.- OtherComprehensiveIncomeNetOfTaxGainsLossesOnRevaluation

247.- OtherComprehensiveIncomeNetOfTaxGainsLossesOnRemeasurementsOfDefinedBenefitPlans

248.- OtherComprehensiveIncomeNetOfTaxChangeInFairValueOfFinancialLiabilityAttributableToChangeInCreditRiskOfLiability

249.- OtherComprehensiveIncomeNetOfTaxGainsLossesOnHedgingInstrumentsThatHedgeInvestmentsInEquityInstruments

250.- ShareOfOtherComprehensiveIncomeOfAssociatesAndJointVenturesAccountedForUsingEquityMethodThatWillNotBeReclassifiedToProfitOrLossNetOfTax

251.- OtherComprehensiveIncomeThatWillNotBeReclassifiedToProfitOrLossNetOfTax

252.- GainsLossesOnExchangeDifferencesOnTranslationNetOfTax

253.- ReclassificationAdjustmentsOnExchangeDifferencesOnTranslationNetOfTax

254.- OtherComprehensiveIncomeNetOfTaxExchangeDifferencesOnTranslation

255.- GainsLossesOnRemeasuringAvailableforsaleFinancialAssetsNetOfTax

256.- ReclassificationAdjustmentsOnAvailableforsaleFinancialAssetsNetOfTax

257.- OtherComprehensiveIncomeNetOfTaxAvailableforsaleFinancialAssets

258.- GainsLossesOnCashFlowHedgesNetOfTax

259.- ReclassificationAdjustmentsOnCashFlowHedgesNetOfTax

260.- AdjustmentsForAmountsTransferredToInitialCarryingAmountOfHedgedItems

261.- OtherComprehensiveIncomeNetOfTaxCashFlowHedges

262.- GainsLossesOnHedgesOfNetInvestmentsInForeignOperationsNetOfTax

263.- ReclassificationAdjustmentsOnHedgesOfNetInvestmentsInForeignOperationsNetOfTax

264.- OtherComprehensiveIncomeNetOfTaxHedgesOfNetInvestmentsInForeignOperations

265.- GainsLossesOnChangeInValueOfTimeValueOfOptionsNetOfTax

266.- ReclassificationAdjustmentsOnChangeInValueOfTimeValueOfOptionsNetOfTax

267.- OtherComprehensiveIncomeNetOfTaxChangeInValueOfTimeValueOfOptions

268.- GainsLossesOnChangeInValueOfForwardElementsOfForwardContractsNetOfTax

269.- ReclassificationAdjustmentsOnChangeInValueOfForwardElementsOfForwardContractsNetOfTax

270.- OtherComprehensiveIncomeNetOfTaxChangeInValueOfForwardElementsOfForwardContracts

271.- GainsLossesOnChangeInValueOfForeignCurrencyBasisSpreadsNetOfTax

272.- ReclassificationAdjustmentsOnChangeInValueOfForeignCurrencyBasisSpreadsNetOfTax

273.- OtherComprehensiveIncomeNetOfTaxChangeInValueOfForeignCurrencyBasisSpreads

274.- GainsLossesOnFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncomeNetOfTax

275.- ReclassificationAdjustmentsOnFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncomeNetOfTax

276.- AmountsRemovedFromEquityAndAdjustedAgainstFairValueOfFinancialAssetsOnReclassificationOutOfFairValueThroughOtherComprehensiveIncomeMeasurementCategoryNetOfTax

277.- OtherComprehensiveIncomeNetOfTaxFinancialAssetsMeasuredAtFairValueThroughOtherComprehensiveIncome

278.- ShareOfOtherComprehensiveIncomeOfAssociatesAndJointVenturesAccountedForUsingEquityMethodThatWillBeReclassifiedToProfitOrLossNetOfTax

279.- OtherComprehensiveIncomeThatWillBeReclassifiedToProfitOrLossNetOfTax

280.- OtherComprehensiveIncome

281.- ComprehensiveIncome

282.- ComprehensiveIncomeAttributableToOwnersOfParent

283.- ComprehensiveIncomeAttributableToNoncontrollingInterests

284.- DepreciacionYAmortizacionOperativa

285.- RevenueFromRenderingOfServices

286.- RevenueFromSaleOfGoods

287.- RevenueFromInterest

288.- RevenueFromRoyalties

289.- RevenueFromDividends

290.- RentalIncome

291.- RevenueFromConstructionContracts

292.- OtherRevenue

293.- InteresesGanados

294.- UtilidadPorFluctuacionCambiaria

295.- GainsOnChangeInFairValueOfDerivatives

296.- UtilidadPorCambiosEnValorRazonableDeInstrumentosFinancieros

297.- OtherFinanceIncome

298.- TotalDeIngresosFinancieros

299.- InteresesDevengadosACargo

300.- PerdidaPorFluctuacionCambiaria

301.- LossesOnChangeInFairValueOfDerivatives

302.- PerdidaPorCambiosEnValorRazonableDeInstrumentosFinancieros

303.- OtherFinanceCost

304.- TotalDeGastosFinancieros

305.- ImpuestoCausado

306.- ImpuestoDiferido

307.- TotalDeImpuestosALaUtilidad


## CONCEPTOS DEL ESTADO DE RESULTADOS
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


## CONCEPTOS DEL BALANCE GENERAL




## CONCEPTOS DE LOS ESTADOS DE FLUJOS DE EFECTIVO
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
