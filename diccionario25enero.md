# Diccionario de datos - CARDIOMOM
## Las variables con '_pre' se evaluaron antes del parto y '_post' después del parto
Variable | Nombre Propuesto | Tipo | Valores (Codificación)
--- | --- | --- | ---
**ID** | `id` | Integer  

# Antecedentes en el momento de la gestación (verde)
**Estudio inicial** | `estudio_inicial` | Object 

0: Ninguno<br>1: BiSC<br>2: EUROPE<br>3: Angiocor<br>  

**Fecha firma CI CARDIOMOM** | `fecha_firma_ci_cardiomom` | Datetime  

**Fecha firma CI Muestras Biológicas** | `fecha_firma_ci_muestbio` | Datetime  

**Fecha de nacimiento** | `fecha_nac` | Datetime  

**Peso inicio gestación (kg)** | `peso_ini_gest` | Float  

**Peso final en gestación (kg)** | `peso_fin_gest` | Float 

**Aumento de peso durante gestación (kg)** | `aumento_peso_gest` | Float

**Talla (cm)** | `talla` | Float 

**IMC inicio gestación** | `imc_ini_gest` | Float

**Etnia** | `etnia` | Float  

0: Blanca<br>1: Latina (no negra)<br>2: Negra<br>3: Sureste asiático (incluye Pakistan)<br>4: Asia Oriental<br>5: Mixto

**Nivel de estudios completado** | `nivel_estudios` | Float

0: Sin estudios<br>1: Primaria<br>2: Secundaria<br>3: Universidad o superior<br>

**Concepción** | `concepcion` | Object

Espontánea<br>FIV con ovodonación<br>FIV<br>Inseminación

**Parto previo nacido ≥37+0 semanas** | `parto_previo_mayor37_pre` | Object 

Yes<br>No

**Número de partos ≥37+0 semanas** | `num_partos_mayor37_pre` | Float

**Parto previo nacido < 37+0 semanas** | `parto_previo_menor37_pre` | Object

Yes<br>No

**Número de partos < 37+0 semanas** | `num_partos_menor37_pre` | Float

**Abortos espontáneos < 20 semanas** | `aborto_menor20` | Object

Yes<br>No

**Número de abortos espontáneos < 20 semanas** | `num_abortos_menor20_pre` | Float

**Antecedente de CIR** | `ant_cir` | Object

Yes<br>No

**Antecedentde de PEG** | `ant_peg` | Object

Yes<br>No

**Antecedente de óbito** | `ant_obito` | Object

Yes<br>No

**Antecedente de preeclampsia** | `ant_pe` | Object

Yes<br>No

**Tipo de preeclampsia** | `tipo_pe_pre` | Object

Leve<br>Grave

**Antecedente de HELLP** | `ant_hellp` | Object

Yes<br>No

**Antecedente de cesárea** | `ant_cesarea` | Object

Yes<br>No

**Antecedente de diabetes pregestacional** | `ant_diabetes_pregest` | Object

Yes<br>No

**HTA pregestacional** | `hta_pregest` | Object

Yes<br>No

**Síndrome antifosfolípido** | `sindr_antifosfolipido` | Object

Yes<br>No

**Enfermedad autoinmune (que no sea síndrome antifosfolípido)** | `enf_autoinm` | Object

Yes<br>No

**Fumadora** | `fuma` | Object

Yes<br>No

**Alcohol** | `alcohol` | Object

Yes<br>No

**Drogas** | `drogas` | Object

Yes<br>No

**Resultado IBERLIFERISK score hasta los 75 años** | `resultado_iberliferisk_score_hasta_los_75_anos` | Float 

# Gestación (azul) 
**Fecha Última Regla** | `fur_pre` | Datetime

**Edad materna en la gestación** | `edad_materna_gest` | Float 

**TAS 1r trimestre (mmHg)** | `tas_1tri` | Float 

**TAD 1r trimestre (mmHg)** | `tad_1tri` | Float 

**Fecha eco 1r trimestre** | `fecha_eco_1tri` | Datetime 

**Edad gestacional eco 1r trimestre** | `eg_eco_1tri` | Float

**Uterinas >p95 1r trimestre** | `uterinas_p95_1tri` | Object  

Sí<br>No<br>No realizadas<br>

**Se dispone de PlGF 1r trimestre?** | `plgf_1tri` | Object  

Yes<br>No<br>

**Fecha PlGF 1r trimestre** | `fecha_plgf_1tri` | Datetime

**Edad gestacional PlGF 1r trimestre** | `eg_plgf_1tri` | Float

**Unidades PlGF 1r trimestre** | `unidades_plgf_1tri` | Object  

pg/ml<br>MoM

**Valor PlGF 1r trimestre** | `valor_plgf_1tri` | Float 

**Riesgo de PE 1r trimestre** | `riesgo_pe_1tri` | Object 

No realizado<br>Alto riesgo<br>Bajo riesgo<br>

**Tomó alguna durante la gestación?** | `tomo_durante_gest` | Object 

0: Aspirina<br>1: Heparina<br>2: Antihipertensivo<br>3: Ninguna<br>

**Uterinas >p95 eco 2º trimestre** | `uterinas_p95_eco_2tri` | Object

Sí<br>No<br>No realizadas<br>

**Fecha ecografía 2º trimestre** | `fecha_eco_2tri` | Datetime 

**Edad gestacional ecografía 2º trimestre** | `eg_eco_2tri` | Float 

**Se realizó determinación de sFlt-1/PlGF en la gestación?** | `deter_sflt1_plgf_gest` | Object

Yes<br>No

**Fecha de la última determinación** | `fecha_ult_deter` | Datetime 

**Edad gestacional de la determinació de sFlt-1/PlGF** | `eg_deter_sflt1_plgf` | Float 

**Valor de sFlt-1 (pg/ml)** | `valor_sflt1` | Float 

**Valor de PlGF (pg/ml)** | `valor_plgf` | Float 

**Ratio sFlt-1/PlGF** | `ratio_sflt1_plgf` | Float

# Parto (naranja)
**Fecha parto** | `fecha_parto` | Datetime

**EG al parto** | `eg_parto` | Float

**Inicio trabajo de parto espontáneo?** | `ini_trabajo_parto_espontaneo` | Object

0: No<br>1: Yes

**Inducción?** | `induccion` | Object

0: No<br>1: Yes

**Motivo inducción** | `motivo_induccion` | Object 

0: CIR o PEG<br>1: Preeclampsia<br>2: GCP<br>3: Patología materna (diabetes, colestasis...<br>4: RPM<br>5: Otras<br>

**Especificar otras** | `especificar_otras_induccion` | Object 

Multitud de valores

**Tipo de parto** | `tipo_parto` | Object
 
Cesárea<br>Eutócico<br>Instrumentado

**Tipo de cesárea** | `tipo_cesarea` | Object 

Electiva<br>Intercurrente

**Motivo cesárea** | `motivo_cesarea` | Object 

Cir<br>Parto estacionado/inducción fallida<br>Patología materna<br>Cirugía uterina previa<br>Pérdida de bienestar fetal<br>Presentación fetal (podálica, transversa)<br>Otras

**Especificar otras.1** | `especificar_otras_cesarea` | Object

placenta previa<br>Deseo materno<br>empeoramiento materno<br>deseo materno<br>vasa previa<br>desig matern<br>prolapso cordon<br>Placenta previa oclusiva

**Peso del RN (g)** | `peso_rn` | Float 

**Sexo del RN** | `sexo_rn` | Object 

Masculino<br>Femenino

**Apgar 1 min** | `apgar_1min` | Float 

**Apgar 5 min** | `apgar_5min` | Float 

**Apgar 10 min** | `apgar_10min` | Float

**pH venoso cordón** | `ph_venoso_cordon` | Float 

**pH arterial cordón** | `ph_arterial_cordon` | Float 

# Complicaciones gestacionales (morado)
**Hemorragia pospartoque requiriera transfusión** | `hemorragia_pospart_transfusion` | Object 

No<br> Yes

**Edema agudo de pulmón** | `edema_agudo_pulmon` | Object

No<br>Yes

**Histerectomía** | `histerectomia` | Object

0: No<br>1: Yes

**Otras** | `otras` | Object

0: No<br>1: Yes

**Especificar** | `especificar` | Float 

**Hipertensión gestacional** | `hipertension_gest` | Object

0: No<br>1: Yes

**Preeclampsia** | `pe` | Object

0: No<br>1: Yes

**Tipo de preeclampsia.1** | `tipo_pe` | Object

Leve<br>Grave

**Fecha de diagnóstico de la PE** | `fecha_diag_pe` | Datetime 

**EG diagnóstico de la PE** | `eg_diag_pe_pre` | Float 

**Sd. HELLP** | `sd_hellp` | Object

0: No<br>1: Yes

**Desprendimiento de placenta** | `desprendimiento_placenta` | Object

0: No<br>1: Yes

**Óbito fetal** | `obito_fetal` | Object

0: No<br>1: Yes

**Fecha óbito** | `fecha_obito` | Datetime 

**EG óbito** | `eg_obito` | Float 

**Hemorragia cerebral/ictus** | `hemocerebral_ictus` | Object

0: No<br>1: Yes

**Embolia/TEP** | `embolia_tep` | Object

No<br>

**Trombosis venosa profunda** | `trombosis_venosa_prof` | Object

0: No<br>1: Yes

**UCI materna/UCOI** | `uci_materna_ucoi` | Object 

0: No<br>1: Yes

**Días ingreso UCI** | `dias_ingreso_uci` | Float 

**COVID** | `covid` | Categórico

No<br>Yes

**CIR** | `cir` | Categórico

0: No<br>1: Yes

**PEG** | `peg` | Categórico

0: No<br>1: Yes

**Diabetes gestacional** | `diabetes_gest` | Categórico 

No<br>Yes

**Insulinizada?** | `insulinizada_1` | Object

0: No<br>1: Yes

**Colestasis intrahepática** | `colestasis_intrahepatica` | Object

0: No<br>1: Yes

**Corioamnionitis** | `corioamnionitis` | Object

0: No<br>1: Yes

# Antecedentes y características basales actuales (Verde oscuro)
**Fecha de la exploración** | `fecha_exploracion` | Datetime 

**Edad actual** | `edad_actual` | Float 

**Peso actual (kg)** | `peso_actual` | Float 

**IMC actual** | `imc_actual` | Float 

**Superficie corporal (m2)** | `superf_corporal` | Float 

**Hijos nacidos ≥37+0 semanas** | `parto_mayor37_post` | Object 

0: No<br>1: Yes

**Número de partos ≥37+0 semanas.1** | `num_partos_mayor37_post` | Float 

**Antecedente familiar de Enfermedad Cardiovascular(solamente considerar HTA, AVC o IAM en familiares de 1er grado (padres/hermanos) cuando el diagnóstico se haya realizado antes de los 60 años)** | `ant_fam_enfcardiovasc` | Object 

No<br>Sí<br>

**¿Cuál de ellas?** | `que_enf` | Object

Hta: 0<br>infarto o enfermedad coronaria: 1<br>ictus o avc: 2


**Parto previo nacido < 37+0 semanas.1** | `parto_menor37_post` | Object 

0: No<br>1: Yes

**Número de partos < 37+0 semanas.1** | `num_partos_menor37_post` | Float 

**Abortos espontáneos < 20 semanas.1** | `aborto_menor20_post` | Object 

0: No<br>1: Yes

**Número de abortos espontáneos < 20 semanas.1** | `num_abortos_menor20_post` | Float 

**Antecedente de CIR .1** | `ant_cir_post` | Object
 
0: No<br>1: Yes

**Antecedentde de PEG.1** | `ant_peg_post` | Object 

0: No<br>1: Yes

**Antecedente de óbito.1** | `ant_obito_post` | Object 

0: No<br>1: Yes

**Antecedente de preeclampsia.1** | `ant_pe_post` | Object 

0: No<br>1: Yes

**¿Cuántas preeclampsias?** | `num_pe` | Float 

**Tipo de preeclampsia.2** | `tipo_pe_post` | Object 

Leve<br>Grave

**Edad gestacional diagnóstico de preeclampsia** | `eg_diag_pe_post` | Float 

**Antecedente de HELLP.1** | `ant_hellp_post` | Object

0: No<br>1: Yes

**¿Antecedente de diabetes gestacional en alguna gestación?** | `ant_diabetes_gest` | Object 

No<br>Yes<br>

**¿Insulinizada?** | `insulinizada_2` | Object
 
0: No<br>1: Yes

**¿Antecedente de colestasis gestacional?** | `ant_colestasis_gest` | Object

0: No<br>1: Yes

**Lactancia materna con algún hijo?** | `lactancia_materna` | Object 

0: No<br>1: Yes

**Cuánto tiempo? (meses)** | `tiempo_lactancia` | Float 

**Está haciendo lactancia materna actualmente?** | `lactancia_materna_actual` | Object 

0: No<br>1: Yes

**Antecedente de cesárea.1** | `ant_cesarea_post` | Object 

0: No<br>1: Yes

**HTA crónica** | `hta_cronica` | Object

0: No<br>1: Yes

**¿Toma medicación para la TA?** | `medicacion_ta` | Object 

No<br>Sí

**Antecedente de infarto o ictus?** | `ant_infarto_ictus` | Object

0: No<br>1: Yes

**Diabetes Mellitus 1 o 2** | `diabetes_mellitus_1_2` | Object

0: No<br>1: Yes

**Tratamiento para la diabetes** | `tratamiento_diabetes` | Object

0: Antidiabéticos orales<br>1: Insulina<br>2: Ambos<br>

**Síndrome antifosfolípido.1** | `sindr_antifosfolipido_post` | Object

0: No<br>1: Yes

**Enfermedad autoinmune (diferente a Sindrome antifosfolipido)** | `enf_autoinm_post` | Object

0: No<br>1: Yes

**Dislipemia** | `dislipemia` | Object
 
0: No<br>1: Yes

**¿Toma medicación hipolipemiante?** | `medicacion_hipolipemiante` | Object 

Sí<br>No

**Menopausia** | `menopausia` | Object 

No<br>Yes

**Edad menopausia** | `edad_menopausia` | Float 

**Fecha última regla** | `fur_post` | Datetime 

**Patrón menstrual** | `patron_menstrual` | Object 

Irregular<br>Regular<br>

**Ha tomado anticonceptivos orales en algún momento?** | `anticonceptivos_orales` | Object 

0: No<br>1: Yes

**Durante cuántos años?** | `tiempo_anticonceptivos_orales` | Float 

**Enfermedad renal crónica** | `enf_renal_cronica` | Object

0: No<br>1: Yes

**¿Qué estadío de enfermedad renal?** | `estadio_enf_renal` | Object

Estadío 1 (FG>90 + proteinuria)<br>Estadío 2 (FG 60-89)<br>Estadío 3 (FG 30-59)<br>

**Consumo de tabaco** | `fuma_post` | Object
 
No<br>Sí<br>Ex-fumadora (>1 año sin fumar)

**¿Qué cantidad?** | `cantidad_fuma_post` | Float

1-10 cig/dia: 1<br>11-20 cig/dia: 2<br>21-30 cig/dia: 3<br>>30 cig/dia: 4

**Alcohol.1** | `alcohol_post` | Object 

0: No<br>1: Yes

**Drogas.1** | `drogas_post` | Object

0: No<br>

# Medidas antroprométricas (rojo) 
**Grasa corporal (%)** | `grasa_corporal` | Float

**Grasa visceral (%)** | `grasa_visceral` | Float
 
**Basal Metabolic Rate (Kcal)** | `basal_metabolic_rate` | Float

**Músculo (%)** | `musculo` | Float

**Edad metabólica** | `edad_metabolica` | Float

**Perímetro de la cintura (cm)** | `perim_cintura` | Float

**Perímetro de la cadera (cm)** | `perim_cadera` | Float

**Ratio cintura/cadera** | `ratio_cintura_cadera` | Float 

# Ecocardiografía (azul oscuro)
**¿Se ha realizado la ecocardio?** | `ecocardio` | Object 

No, Pendiente de recitar : 0<br>No desea realizarla: 1<br>Sí: 2

**Comentaris** | `comentaris` | Object

**Diámetro telediastólico VI (mm)** | `diam_telediastolico` | Float

**DTDVI indexado** | `dtdvi_indexado` | Float 

**Diámetro telesistólico VI (mm)** | `diam_telesistolico` | Float 

**DTSVI indexado** | `dtsvi_indexado` | Float 

**Septo IV DIÁSTOLE (mm)** | `septo_iv_diastole` | Float 

**Pared posterior VI DIÁSTOLE (mm)** | `pared_posterior_vi_diastole` | Float 

**Masa VI Tdiast indexada (g/m2)** | `masa_vi_tdiast_indexada` | Float 

**Diámetro AI (mm)** | `diam_ai` | Float

**Diámetro raíz aórtica (mm)** | `diam_raiz_aortica` | Float 

**Diámetro raiz aórtica indexada (mm)** | `diam_raiz_aortica_indexada` | Float

**Diámetro Ao ascendente (mm)** | `diam_ao_ascendente` | Float

**Diámetro Ao ascendente indexada** | `diam_ao_ascendente_indexada` | Float

**TSVI (mm)** | `tsvi` | Float 

**Válvula aórtica** | `valvula_aortica` | Object

Tricúspide<br>Indeterminada<br>Bicúspide

**Notch pulmonar** | `notch_pulmonar` | Object

No<br>

**Tiempo de hemipresión pulmonar (ms)** | `tiempo_hemipresion_pulmonar` | Float

**AI Volumen (ml)** | `ai_volumen` | Float

**AD Volumen (ml)** | `ad_volumen` | Float

**TAPSE (mm)** | `tapse` | Float 

**Onda S anillo tricuspídeo (cm/s)** | `onda_s_anillo_tricuspideo` | Float

**Díametro basal VD (mm)** | `diam_basal_vd` | Float

**Diámetro longitudinal VD (mm)** | `diam_longitudinal_vd` | Float

**E mitral (cm/s)** | `e_mitral` | Float

**A mitral (cm/s)** | `a_mitral` | Float

**Tiempo deceleración VM (ms)** | `tiempo_deceleracion_vm` | Float

**E' mitral lateral (cm/s)** | `e_mitral_lateral` | Float

**E' mitral medial (cm/s)** | `e_mitral_medial` | Float

**E/e'** | `e_e` | Float

**Gradiente pico IT (mmHg)** | `gradiente_pico_it` | Float 

**Volumen telediastólico VI (ml)** | `vol_telediastolico_vi` | Float 

**Volumen telediastólico VI indexado** | `vol_telediastolico_vi_indexado` | Float

**Volumen telesistólico VI (ml)** | `vol_telesistolico_vi` | Float

**Volumen telesistólico VI indexado** | `vol_telesistolico_vi_indexado` | Float

**FEVI Simpson 4C (%)** | `fevi_simpson_4c` | Float

**Strain longitudinal VI (%)** | `strain_longitudinal_vi` | Float

**Strain auricular izquierdo reservorio (%)** | `strain_auricular_izquierdo_reservorio` | Float

**VTI TSVI (cm)** | `vti_tsvi` | Float

**Presión estimada AD (mmHg)** | `presion_estimada_ad` | Float

**PAP sistólica (mmHg)** | `pap_sistolica` | Float 

**Existe alguna valvulopatía?** | `valvulopatia` | Object

No<br>Sí

**Aórtica** | `aortica` | Object 

No<br>Sí

**Estenosis aórtica** | `estenosis_aortica` | Object 

No<br>Sí

**Insuficiencia aórtica** | `insuficiencia_aortica` | Object 

No<br>Sí

**Mitral** | `mitral` | Object 

No<br>Sí

**Estenosis mitral** | `estenosis_mitral` | Object 

No

**Insuficiencia mitral** | `insuficiencia_mitral` | Object 

No<br>Sí

**Insuficiencia tricuspídea** | `insuficiencia_tricuspidea` | Object 

No<br>Sí

**GC (TSVI) (l/min)** | `gc_tsvi` | Float

**IC (TSVI) (l/min/m2)** | `ic_tsvi` | Float 

**VS (cámara salida VI) (ml)** | `vs_camara_salida_vi` | Float

**VS (cámara salida VI) indexado (ml/m2)** | `vs_camara_salida_vi_indexado` | Float

**Segmentarismos?** | `segmentarismos` | Object
 
0: No

**Localización** | `localizacion` | Object

0: Anteroseptal<br>1: Anterior<br>2: Anterolateral<br>3: Inferoseptal<br>4: Inferior<br>5: Inferolateral<br>

**Cardiopatía estructural?** | `cardiopatia_estructural` | Object

0: No<br>1: Yes

**¿Cuál?** | `tipo_cardiopatia_estructural` | Object

Disfunción ventricular<br>IT ligera<br>VAo bicúspide<br>sospecha de CIA<br>Dilatación VD<br>Dilatación VI y DSVI<br>Derrame pericárdico?

**Calidad del examen** | `calidad_del_examen` | Object
 
Insuficiente<br>Subóptima<br>Adecuada

# TA, carótida y oftálmica (rosa)
**TA sistólica (mmHg)** | `ta_sistolica` | Float 

**TA diastólica (mmHg)** | `ta_diastolica` | Float 

**Frecuencia cardíaca (lpm)** | `frec_cardiaca` | Float 

**RIGHT: 1st peak of systolic velocity (cm/s)** | `right_1peak_systolic_velocity` | Float 

**RIGHT: 2nd peak of systolic velocity (cm/s)** | `right_2peak_systolic_velocity` | Float 

**RIGHT: Pulsatility index** | `right_pulsatility_index` | Float 

**Right PSV ratio** | `right_psv_ratio` | Float 

**LEFT: 1st peak of systolic velocity (cm/s)** | `left_1peak_systolic_velocity` | Float 

**LEFT: 2nd peak of systolic velocity (cm/s)** | `left_2peak_systolic_velocity` | Float 

**LEFT: Pulsatility index** | `left_pulsatility_index` | Float 

**Left PSV ratio** | `left_psv_ratio` | Float 

**RIGHT: Mean** | `right_mean` | Float 

**LEFT: Mean** | `left_mean` | Float 

**Complete?** | `complete` | Object 

Complete<br>Incomplete

**Se ha recogido muestra de pelo?** | `muestra_pelo` | Object

0: No<br>1: Yes

**Se ha separado en dos partes la muestra? (raíz y punta)** | `muestra_pelo_separada` | Object 

0: No<br>1: Yes

**Tiene el pelo teñido?** | `pelo_tenido` | Object

0: No<br>1: Yes

**Se ha hecho algún tratamiento en el pelo en los últimos 3 meses?** | `trat_pelo_ult3meses` | Object 

0: No<br>1: Yes

**Otros comentarios, incidencias o desviación del protocolo** | `otros_comentarios` | Object

Multitud de valores

# Analítica (Gris oscuro)
**Analítica realizada?** | `analitica_realizada` | Object 

0: No<br>1: Yes

**Fecha extracción** | `fecha_extraccion` | Datetime 

**PlGF (pg/mL)** | `plgf_pg` | Float 

**Troponina T (ng/l)** | `troponina_t` | Float 

**NT-proBNP (ng/l)** | `nt_probnp` | Float 

**Hemoglobina (g/l)** | `hemoglobina` | Float 

**Hematocrito (L/L)** | `hematocrito` | Float 

**Leucocitos (U/mcl)** | `leucocitos` | Float 

**Plaquetas (U/mcl)** | `plaquetas` | Float 

**Glucosa (mg/dl)** | `glucosa` | Float 

**Sodio (mmol/L)** | `sodio` | Float 

**Potasio (mmol/L)** | `potasio` | Float 

**Urato o ácido úrico (mg/dl)** | `urato_acidourico` | Float 

**Creatinina (mg/dl)** | `creatinina` | Float 

**Hemoglobina glicada (%)** | `hemoglobina_glicada` | Float 

**AST (U/L)** | `ast` | Float 

**ALT (U/L)** | `alt` | Float 

**Bilirubina total (mg/dl)** | `bilirubina_total` | Float 

**LDH (U/L)** | `ldh` | Float 

**VLDL (mg/dl)** | `vldl` | Float 

**LDL (mg/dl)** | `ldl` | Float 

**HDL (mg/dl)** | `hdl` | Float 

**Colesterol total (mg/dl)** | `colesterol_total` | Float 

**Triglicéridos (mg/dl)** | `trigliceridos` | Float 

**Proteínas totales orina (g/l)** | `prote_totales_orina` | Float 

**Albúmina orina (mg/l)** | `albumina_orina` | Float 

**Ratio albúmina/creatinina (mg/g)** | `ratio_albumina_creatinina` | Float 

**Tirotropina (mUI/L)** | `tirotropina` | Float 

**Prolactina (mUI/L)** | `prolactina` | Float 

# Dieta (Azul claro)
**Pan (1/2 rebanadas)** | `pan` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Verdura o ensalada (1 plato o porción)** | `verdura_ensalada` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Fruta (1 pieza o porción)** | `fruta` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Yogur o leche (1 tarrina o vaso)** | `yogur_leche` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Pasta o arroz (1 plato)** | `pasta_arroz` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Aceite oliva o girasol (una cucharada sopera)** | `aceite_oliva_girasol` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Una bebida alcohólica (un vaso, copa o botella)** | `bebida_alcoholica` | Float

<1/día: 0.5<br>1/día: 1<br>>1/día: 2

**Agua (vasos al día)** | `vasos_agua_dia` | Float

0-1/día: 1.5<br>4-5/día: 4.5<br>>5/día: 6

**Carne (1-2 trozos)** | `carne` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Embutidos (1-3 lonchas)** | `embutidos` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Queso&nbsp;(1 porción)** | `queso_nbsp` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Bollería o pastelería (1-2 piezas)** | `bolleria_pasteleria` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Mantequilla** | `mantequilla` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Bebida azucarada (un vaso o lata)*Excepto gaseosa, tónica y zero o light** | `bebida_azucarada` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Comida rápida** | `comida_rapida` | Float

<4/semana: 2<br>4-6/semana: 5<br>>6/semana: 7

**Pescado** | `pescado` | Float

<2/semana: 1<br>2-3/semana: 2.5<br>>3/semana:4

**Legumbres** | `legumbres` | Float

<2/semana: 1<br>2-3/semana: 2.5<br>>3/semana:4

**Frutos secos (1 puñado)** | `frutos_secos` | Float

<2/semana: 1<br>2-3/semana: 2.5<br>>3/semana:4

**Score total** | `score_dieta` | Float 

# Actividad física (Gris claro)
**Act física LIGERA (MET/semana)** | `act_fisica_ligera` | Float

**Act física MODERADA (MET/semana)** | `act_fisica_moderada` | Float

**Act física INTENSA (MET/semana)** | `act_fisica_intensa` | Float

**Act física TOTAL (MET/semana)** | `act_fisica_total` | Float 

# Estrés (naranja claro) 
**Survey Timestamp** | `survey_timestamp_estres` | Datetime

**1. En el último mes, ¿con qué frecuencia ha estado afectado por algo que ha ocurrido inesperadamente?** | `frec_afectado_inesperadamente` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**2. En el último mes, ¿con qué frecuencia se ha sentido incapaz de controlar las cosas importantes en su vida?** | `frec_incapaz_controlar_cosas_importantes` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**3. En el último mes, ¿con qué frecuencia se ha sentido nervioso o estresado?** | `frec_nervioso_estresado` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**4. En el último mes, ¿con qué frecuencia ha manejado con éxito los pequeños problemas irritantes de la vida?** | `frec_manejado_pequenos_problemas_irritantes` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**5. En el último mes, ¿con qué frecuencia ha sentido que ha afrontado efectivamente los cambios importantes que han estado ocurriendo en su vida?** | `frec_afrontado_cambios_importantes` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**6. En el último mes, ¿con qué frecuencia ha estado seguro sobre su capacidad para manejar sus problemas personales?** | `frec_seguro_capacidad_manejar_problemas_personales` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**7. En el último mes, ¿con qué frecuencia ha sentido que las cosas le van bien?** | `frec_cosas_van_bien` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**8. En el último mes, ¿con qué frecuencia ha sentido que no podía afrontar todas las cosas que tenía que hacer?** | `frec_no_afrontar_todas_cosas` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**9. En el último mes, ¿con qué frecuencia ha podido controlar las dificultades de su vida?** | `frec_controlar_dificultades` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**10. En el ultimo mes, ¿con que frecuencia se ha sentido que tenia todo bajo control?** | `frec_todo_bajo_control` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**11. En el último mes, ¿con qué frecuencia ha estado enfadado porque  las cosas que le han ocurrido estaban fuera de su control?** | `frec_enfadado_cosas_fuera_control` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**12. En el último mes, ¿con qué frecuencia ha  pensado sobre las cosas que le quedan  por hacer?** | `frec_pensado_cosas_por_hacer` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**13. En el último mes, ¿con qué frecuencia ha podido controlar la forma  de  pasar  el tiempo?** | `frec_controlar_forma_pasar_tiempo` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**14. En el último mes, ¿con qué frecuencia ha sentido que las dificultades se acumulan tanto que no puede superarlas?** | `frec_dificultades_acumuladas` | Float

Nunca: 0<br>Casi nunca: 1<br>De vez en cuando: 2<br>A menudo: 3<br>Muy a menudo: 4

**Score** | `score_estres` | Float 

# SCL-90-R (rojo oscuro)
**Survey Timestamp.1** | `survey_timestamp_scl90r` | Datetime

**Dolores de cabeza** | `dolores_cabeza` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Nerviosismo** | `nerviosismo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Pensamientos desagradables que no se iban de mi cabeza** | `pensamientos_desagradables` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sensación de mareo o desmayo** | `sensacion_mareo_desmayo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Falta de interés en relaciones sexuales** | `falta_interes_relsex` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Criticar a los demás** | `criticar` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que otro puede controlar mis pensamientos** | `otro_controla_pensamientos` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que otros son culpables de lo que me pasa** | `otros_culpables` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener dificultad para memorizar cosas** | `dificultad_memorizar` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Estar preocupada por mi falta de ganas para hacer algo** | `preocupada_falta_ganas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme enojada, malhumorada** | `enojada_malhumorada` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Dolores en el pecho** | `dolores_pecho` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Miedo a los espacios abiertos o las calles** | `miedo_espabiertos_calles` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme con muy pocas energías** | `poca_energia` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Pensar en quitarme la vida** | `pensar_quitar_vida` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Escuchar voces que otras personas no oyen** | `escuchar_voces` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Temblores en mi cuerpo** | `temblores_cuerpo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Perder la confianza en la mayoría de las personas** | `perder_confianza_mayoria_personas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**No tener ganas de comer** | `no_ganas_comer` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Llorar por cualquier cosa** | `llorar_cualquier_cosa` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme incómoda con otras personas del otro sexo** | `incomoda_personas_otrosexo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme atrapada o encerrada** | `atrapada_encerrada` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Asustarme de repente sin razón alguna** | `asustarme` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Explotar y no poder controlarme** | `no_controlarme` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener miedo a salir a sola de mi casa** | `miedo_salir_sola` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme culpable por cosas que ocurren** | `sentirme_culpable` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Dolores en la espalda** | `dolores_espalda` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**No poder terminar las cosas que empecé a hacer** | `no_terminar_cosas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme sola** | `sentirme_sola` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme triste** | `sentirme_triste` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Preocuparme demasiado por todo lo que pasa** | `preocuparme_demasiado` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**No tener interés por nada** | `no_tener_interes` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener miedos** | `tener_miedos` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme herido en mis sentimientos** | `herida_sentimientos` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Creer que la gente sabe qué estoy pensando** | `creer_gente_sabe_pensando` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que no me comprenden** | `sentir_no_comprenden` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que no caigo bien a la gente, que no les gusto** | `sentir_no_caigo_bien` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener que hacer las cosas muy despacio para estar seguro/a de que están bien hechas** | `hacer_despacio` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Mi corazón late muy fuerte, se acelera** | `corazon_late_fuerte` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Náuseas o dolor de estómago** | `nauseas_dolorestomago` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme inferior a los demás** | `sentirme_inferior` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Calambres en las manos, brazos o piernas** | `calambres_manos_piernas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que me vigilan o que hablan de mí** | `sentir_vigilan_hablan` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener problemas para dormirme** | `problemas_dormirme` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener que controlar una o más veces lo que hago** | `controlar_veces_hago` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener dificultades para tomar decisiones** | `dificultad_tomar_decisiones` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener miedo de viajar en tren, bus o metro** | `miedo_tren_bus_metro` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener dificultades para respirar bien** | `dificultad_respirar` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Ataques de frío o de calor** | `ataques_frio_calor` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener que evitar acercarme a algunos lugares o actividades porque me dan miedo** | `evitar_lugares_actividades_miedo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que mi mente queda en blanco** | `mente_blanco` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Hormigueos en alguna parte del cuerpo** | `hormigueos_cuerpo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener un nudo en la garganta** | `nudo_garganta` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Perder las esperanzas en el futuro** | `esperanzas_futuro` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Dificultades para concentrarme en lo que estoy haciendo** | `dificultad_concentrarme` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir flojedad, debilidad, en partes de mi cuerpo** | `debilidad_cuerpo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme muy nerviosa, agitada** | `nerviosa_agitada` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir mis brazos y piernas muy pesados** | `pesados_brazos_piernas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Pensar que me estoy por morir** | `pensar_morir` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Comer demasiado** | `comer_demasiado` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme incómoda cuando me miran o hablan de mí** | `incomoda_miran_hablan` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener ideas, pensamientos que no son los míos** | `pensamientos_no_mios` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Necesitar golpear o lastimar a alguien** | `necesitar_golpear_alguien` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Despertarme muy temprano por la mañana sin necesidad** | `madrugar_sin_necesidad` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Repetir muchas veces algo que hago: contar, lavarme, tocar cosas** | `repetir_mucho_algo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Dormir con problemas, muy inquieto/a** | `dormir_inquieta` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Necesitar romper o destrozar cosas** | `necesitar_romper` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener ideas, pensamientos que los demás no entienden** | `pensamientos_noentienden` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Estar muy pendiente de lo que los demás puedan pensar de mí** | `pendiente_piensen` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme incómoda en lugares donde hay mucha gente** | `incomoda_mucha_gente` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que todo me cuesta mucho esfuerzo** | `mucho_esfuerzo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener ataques de mucho miedo o de pánico** | `ataques_miedo_panico` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme mal si estoy comiendo o bebiendo en público** | `sentirme_mal_comiendo_publico` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Meterme muy seguido en discusiones** | `discusiones` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Ponerme nerviosa cuando estoy sola** | `nerviosa_sola` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que los demás no me valoran como merezco** | `no_valorada` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme sola aún estando con gente** | `sola_congente` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Estar inquieta; no poder estar sentada sin moverme** | `inquieta` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme una inútil** | `inutil` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que algo malo me va a pasar** | `malo_pasar` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Gritar o tirar cosas** | `gritar_tirarcosas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Miedo a desmayarme en medio de la gente** | `miedo_desmayarme_gente` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que se aprovechan de mí si les dejo** | `aprovechan_mi` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Pensar cosas sobre el sexo que me molestan** | `pensar_sexo_molesta` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que debo ser castigada por mis pecados** | `sercastigada_pecados` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Tener imágenes y pensamientos que me dan miedo** | `pensamientos_miedo` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentir que algo anda mal en mi cuerpo** | `cuerpo_mal` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme alejada de las demás personas** | `alejada_personas` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Sentirme culpable** | `culpable` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

**Pensar que en mi cabeza hay algo que no funciona bien** | `cabeza_nobien` | Float

Nada: 0<br>Muy poco: 1<br>Poco: 2<br>Bastante:3<br>Mucho: 4

# Fagerström (morado oscuro)
**¿Cuánto tiempo tarda en fumar su primer cigarrillo después de despertarse?** | `tiempo_fumar_cigarrillo_despertar` | Float 

6-30 minutos: 2<br>31-60 minutos: 1<br>>60 minutos: 0

**¿Encuentra dificultad para no fumar en los sitios en que está prohibido?** | `dificultad_nofumar_prohibido` | Object

No<br>Sí

**¿A que cigarrillo le costaría más renunciar?** | `cigarrillo_masdificil_renunciar` | Object

El primero<br>Otros

**¿Cuántos cigarrillos fuma cada día?** | `num_fuma_dia` | Float

1-10 cig/dia: 1<br>11-20 cig/dia: 2<br>21-30 cig/dia: 3<br>>30 cig/dia: 4

**¿Fuma más durante las primeras horas tras levantarse que durante el resto del día?** | `fuma_mas_despertar` | Object

No<br>Sí

**¿Fuma cuando está muy enfermo, incluso estando en la cama la mayor parte del día?** | `fuma_enferma` | Object 

No<br>Sí

**Score Dependencia Tabaco (Fagersxtröm)** | `score_fumar` | Float

# MFE-30 Memoria (marrón)
**Survey Timestamp.2** | `survey_timestamp_memoria` | Datetime

**Los fallos de mi memoria me causan problemas en la vida cotidiana** | `fallos_memoria_problemas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido dónde he puesto alguna cosa. Pierdo cosas por casa** | `olvido_puesto_cosas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido lugares en los que otros me dicen que he estado antes** | `olvido_lugares` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Tengo dificultades para seguir una historia por televisión** | `dificultad_seguir_tele` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**No me adapto a los cambios en mis actividades diarias. Sigo por error antiguas rutinas** | `sigo_antiguas_rutinas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Tengo que volver a comprobar si he hecho alguna cosa que tenía la intención de hacer** | `comprobar_hecho` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido cuándo ocurrieron algunas cosas** | `olvido_cuando_cosas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido llevar conmigo objetos que necesito (llaves, gafas, monedero...) o me los dejo y tengo que volver a buscarlos** | `olvido_llevar_objetos` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido algo que me dijeron ayer o hace pocos días** | `olvido_dijeron` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Empiezo a leer algo sin darme cuenta de que ya lo había leído antes** | `leo_leido_antes` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Divago en las conversaciones y me dejo llevar hacia temas sin importancia** | `divago_conver` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**No reconozco a parientes o amigos cuando me cruzo con ellos por la calle** | `no_reconozco_amigos` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Tengo dificultades para aprender nuevas habilidades o destrezas** | `dificultad_aprender_habilidades` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Tengo una palabra 'en la punta de la lengua'. Sé lo que quiero decir pero no  encuentro la expresión adecuada** | `palabra_punta_lengua` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido cosas que quería hacer o que había planeado hacer. Se me olvidan las citas** | `olvido_cosas_planeado` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido detalles de lo que hice o me ocurrió el día anterior** | `olvido_detalles_ayer` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido el tema de una conversación o tengo que preguntar: ¿de qué estábamos hablando?** | `olvido_tema_conversacion` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Pierdo el hilo cuando leo un periódico, una revista o un libro y tengo que volver a empezar** | `pierdo_hilo_leo` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido dar recados importantes a la gente** | `olvido_recados` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido detalles sobre mi mismo (mi edad, mi teléfono...)** | `olvido_detalles_mi` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Mezclo o confundo detalles de cosas que me han contado otras personas** | `confundo_detalles_otras_personas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido anécdotas o chistes que me han contado anteriormente** | `olvido_anecdotas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido detalles de cosas que hago habitualmente (lo que tengo que hacer o la hora a la que debo hacerlo)** | `olvido_detalles_habituales` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido caras de personas famosas que veo con frecuencia por televisión o en fotografías** | `olvido_famosos` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido dónde guardo las cosas o las busco sitios equivocados** | `olvido_donde_guardo` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Me pierdo o sigo una dirección errónea en viajes, paseos o edificios en los que he estado antes** | `direccion_erronea` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Hago algo dos veces por error cuando sólo había que hacerlo una (p.e. echar sal en la comida)** | `hago_dos_veces` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Repito a alguien lo que acabo de contarle o le hago dos veces la misma pregunta** | `repito_hablando` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido cómo se usa un objeto o aparato nuevo aunque ya lo hubiera usado antes** | `olvido_usar_objeto` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Olvido el nombre de personas conocidas** | `olvido_nombre_personas` | Float

Nunca o casi nunca: 0<br>Pocas veces:1<br>A veces sí y a veces no: 2<br>Muchas veces: 3<br>Siempre o casi siempre: 4

**Score.1** | `score_memoria` | Float 

