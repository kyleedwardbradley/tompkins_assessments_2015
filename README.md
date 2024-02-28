Tompkins County, NY Tax assessments and arms-length transactions, 2015-2023

Interactive map at: https://kyleedwardbradley.github.io/tompkins_assessments_2015/

Data files:

----------------------------------------------------------
Filename: final_data_csv.csv
Format: CSV
Contains: Property assessment data for Tompkins County, 2015-2013, extracted from yearly data provided by the Tompkins County Department of Assessment

Example entry:
500700_1.-1-15,-76.5,42.4635,8,650,2.9,1950000,1 James L Gibbs Dr,1950000,1950000,1950000,1950000,1950000,1950000,1950000,1950000,0,0,0,0,0,0,0,0,0


Columns: key,lon,lat,roll_section,prop_class,asmt_acres,total_av_2015,parcel_location_address,total_av_2016,total_av_2017,total_av_2018,total_av_2019,total_av_2020,total_av_2021,total_av_2022,total_av_2023,pct_2016,pct_2017,pct_2018,pct_2019,pct_2020,pct_2021,pct_2022,pct_2023,pct_2020_2023

key: property identification code
lon/lat: location (decimal degrees)
roll_section: tax roll section
prop_class: tax property class
asmt_acres: assessment acreage (acres)
total_av_YYYY: assessed value in year YYYY (USD)
parcel_location_address: address
pct_YYYY: (total_av_YYYY - total_av_2015)/total_av_2015 * 100  (percent)

----------------------------------------------------------

Filename: ithaca_geocoded_transactions.csv
Format: CSV
Contains: Arms-length property transactions since 2015, City of Ithaca, fairly poorly geocoded using US Census Bureau online tool

Example entry:
Ithaca,821 CLIFF ST,(Ithaca None),None,945000,Feb. 16 2015,PRIMARY DEVELOPERS INC,AMER.BLUE SKY HOLD.LLC,Standard (arms length),-76.51797132899998,42.450144918000035

Columns: City,Address,IDZip,Zip,Price,Date,Seller,Buyer,Transaction,Longitude,Latitude

----------------------------------------------------------

Filename: ithaca_geocoded_transactions_2020.csv
Format: CSV
Contains: Same information as ithaca_geocoded_transactions.csv, beginning in 2020
