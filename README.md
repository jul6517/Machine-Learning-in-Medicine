# Machine-Learning-in-Medicine
Examples of utilizing machine learning techniques in medicine

## Parkinson.csv file
  - columns ‘ID’ and ‘Recording’ can not be considered as the features
  - Description of acoustic parameter families derived from the voice records in HC and PD subject groups.
    
| Parameter Family| Abbreviation | Parameter Description |
| :---         |     :---:      | :--- |
| Jitter   | Jitter-Rel	        |Relative jitter|
|          |Jitter-Abs	|Absolute jitter|
|   |Jitter-RAP	| Relative average perturbation|
|   |Jitter-PPQ	|Pitch perturbation quotient|
| Shimmer     | Shim-Loc       | Local shimmer      |
|          |Shim-dB	|Shimmer in dB|
|   |Shim-APQ3	| 3-point amplitude perturbation quotient|
|   |Shim-APQ5	|5-point amplitude perturbation quotient|		
|          |Shim-APQ11	|11-point amplitude perturbation quotient|	
| Harmonic-to-noise    | HNR05       | Harmonic-to-noise ratio in 0–500 Hz|		
|          |HNR15	|Harmonic-to-noise ratio in 0–1500 Hz|
|   |HNR25	|Harmonic-to-noise ratio in 0–2500 Hz|
|   |HNR35|Harmonic-to-noise ratio in 0–3500 Hz|		
|          |HNR38|Harmonic-to-noise ratio in 0–3800 Hz|		
| Nonlinear	| RPDE    | Recurrence period density entropy|		
|          |DFA|Detrended fluctuation analysis|
|   |PPE|Pitch period entropy|
|   |GNE|Glottal-to-noise excitation ratio|		
|Frequency |MFCC 0 to 12|Mel-frequency cepstral coefficient-based spectral measures of order 0–12|			
|   |Delta 0 to 12|The derivatives of mel-frequency cepstral coefficient measures of order 0–12|		     
	
## ILPD.csv	
  - provides the age, gender, total Bilirubin, direct Bilirubin, total proteins, albumin, A/G ratio, SGPT, SGOT and Alkphos of patients

| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
| Age | Jitter-Rel	        |Relative jitter|
|Gender |Jitter-Abs	|Absolute jitter|
| total Bilirubin |Jitter-RAP	| Relative average perturbation|
|direct Bilirubin|Jitter-PPQ	|Pitch perturbation quotient|
|total proteins | Shim-Loc       | Local shimmer      |
|albumin|Shim-dB	|Shimmer in dB|
|A/G ratio|Shim-APQ3	| 3-point amplitude perturbation quotient|
|SGPT |Shim-APQ5	|5-point amplitude perturbation quotient|	
|SGOT|Shim-dB	|Shimmer in dB|
|Alkphos  |Shim-APQ3	| 3-point amplitude perturbation quotient|
|Class|Shim-APQ5	|5-point amplitude perturbation quotient|	
      		
## Frogs_MFCCs.csv
| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
| MFCCs_ 1', 'MFCCs_ 2', 'MFCCs_ 3', 'MFCCs_ 4', 'MFCCs_ 5', 'MFCCs_ 6', 'MFCCs_ 7', 'MFCCs_ 8', 'MFCCs_ 9', 'MFCCs_10', 'MFCCs_11', 'MFCCs_12', 'MFCCs_13', 'MFCCs_14', 'MFCCs_15', 'MFCCs_16', 'MFCCs_17', 'MFCCs_18','MFCCs_19', 'MFCCs_20', 'MFCCs_21', 'MFCCs_22'| float |characteristics|
|Species|str	|name of specifies|

## 3_episode1_timeseries.csv

| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
|Hours| float   |hours in the hospital|
|Capillary refill rate|float|feature|
|Diastolic blood pressure|float| feature|
|direct Bilirubin|float|feature|
|Fraction inspired oxygen|float |feature|
|Glascow coma scale total|float|feature|
|Glucose|float|feature|
|Heart Rate|float|feature|
|Height|float|feature|
|Mean blood pressure|float  |feature |
|Oxygen saturation|float|feature|
|Respiratory rate|float|feature|
|Systolic blood pressure| float  |feature |
|Temperature|float|feature|
|Weight|float|feature|
|pH|float|feature|
|label|float|0: controls (alive, discharge); 1: cases (death) |

## label.csv

| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
| Subj | complex        |unique patient|
|label|float|0: controls (alive, discharge); 1: cases (death) |

## in_hospital_mortality_48_day_chunk_6.csv

| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
| Subj | complex        |unique patient|
|Capillary refill rate_max/min_days|float|feature|
|Diastolic blood pressure_max/min_days|float| feature|
|direct Bilirubin_max/min_days|float|feature|
|Fraction inspired oxygen_max/min_days|float |feature|
|Glascow coma scale total_max/min_days|float|feature|
|Glucose_max/min_days|float|feature|
|Heart Rate_max/min_days|float|feature|
|Height_max/min_days|float|feature|
|Mean blood pressure_max/min_days|float  |feature |
|Oxygen saturation_max/min_days|float|feature|
|Respiratory rate_max/min_days|float|feature|
|Systolic blood pressure_max/min_days| float  |feature |
|Temperature_max/min_days|float|feature|
|Weight_max/min_days|float|feature|
|pH_max/min_days|float|feature|
|label|float|0: controls (alive, discharge); 1: cases (death) |

## all_addressed_data.csv

| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
| Subj | complex        |unique patient|
|Capillary refill rate|float|feature|
|Diastolic blood pressure|float| feature|
|direct Bilirubin|float|feature|
|Fraction inspired oxygen|float |feature|
|Glascow coma scale total|float|feature|
|Glucose|float|feature|
|Heart Rate|float|feature|
|Height|float|feature|
|Mean blood pressure|float  |feature |
|Oxygen saturation|float|feature|
|Respiratory rate|float|feature|
|Systolic blood pressure| float  |feature |
|Temperature|float|feature|
|Weight|float|feature|
|pH|float|feature|
|label|float|0: controls (alive, discharge); 1: cases (death) |

## listfile.csv

| Parameter Family| type| Parameter Description |
| :---         |     :---:      | :--- |
|stay| complex  | unique subject|
|y_true|float|yes/no|

