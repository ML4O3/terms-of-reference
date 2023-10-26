# TOAR ML4O3 Terms of Reference

## at the time of creation

In recent years machine learning and especially deep learning has gained enormous momentum through its fundamental breakthroughs in image recognition and language processing. Even though the underlying data properties of those applications differ from tropospheric ozone time-series or satellite data, the methods and concepts of such systems can help to distil information from existing data. This information will allow the TOAR-II community and others to enhance their understanding of tropospheric ozone. Within this working group (WG), we will focus on knowledge that can be derived from the TOAR database, in conjunction with other data, to shed light on existing scientific problems and questions.

Ozone formation and loss processes are highly nonlinear and heavily depend on other chemical variables and meteorological properties. Air pollutant concentrations are controlled by four main types of processes: emissions, transport, (chemical and physical) transformations, and loss processes such as deposition and washout. These processes that affect production and removal of ozone are of a complexity where high-quality interpolation, forecasting, and quality assurance would benefit from ML approaches. This WG will bring together ozone and machine learning experts, allowing us to develop best practice guidelines on data preprocessing and model evaluation with respect to AI applications.

Key objectives of the WG include:

1. The interpolation of missing values in the TOAR database in two ways: (a) derive reliable information on air quality at stations where incomplete or no measurements exist (spatial interpolation to "new" or "unknown" station locations; (b) fill temporal gaps in the measurement time series at individual station locations by identifying a transfer function

1. The detection of potentially "suspicious" or "wrong" values in the ingestion phase of the TOAR database

1. Detection of ozone regimes, e.g. high photochemical production vs transport dominated areas (classification task), based on station proxy or meteorological data.

1. Transfer properties of regional ML-models to a global scale and demonstrate how well this approach is suited for tropospheric ozone. What areas show good/bad performances, and can we identify (chemical/physical) causes related to the performance?

1. Documenting and developing best practices for handling TOAR data for use with machine learning applications
