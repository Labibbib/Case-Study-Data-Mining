# Mencari Insight dan Membandingkan Machine Learning Model (LR, RF, kNN, dan DT) pada Dataset Rata-Rata Penggunaan Energi Listrik (Case-Study-03-Group-F)

## Deskripsi
Studi kasus ini diambil dari https://www.kaggle.com/competitions/ashrae-energy-prediction/data dengan permasalahan dan data understanding yang sama, tetapi menggunakan dataset yang sudah dimodifikasi menjadi "rata-rata" penggunaan energi listrik dari berbagai gedung. Goal pada studi kasus ini kami berperan sebagai data miner yang memiliki tugas utama mencari insight sebanyak banyaknya dari data energi listrik dengan EDA (Exploratory Data Analysis) dan menggunakan model. Di sini kami membandingkan empat model, diantaranya Linear Regression (LR), Random Forest (RF), k-Nearest Neighbors (kNN), dan Decision Tree (DT). Kemudian keempat model ini dipilih sebagai tools untuk mendapatkan insight.


## Data Understanding
- building_id - Foreign key for the building metadata.
- meter_reading - The target variable. Energy consumption in kWh (or equivalent). Note that this is real data with measurement error, which we expect will impose a baseline level of modeling error. UPDATE: as discussed here, the site 0 electric meter readings are in kBTU.
- primary_use - Indicator of the primary category of activities for the building based on EnergyStar property type definitions
- square_feet - Gross floor area of the building
- year_built - Year building was opened
- floor_count - Number of floors of the building
- air_temperature - Degrees Celsius
- cloud_coverage - Portion of the sky covered in clouds, in oktas
- dew_temperature - Degrees Celsius
- precip_depth_1_hr - Millimeters
- sea_level_pressure - Millibar/hectopascals
- wind_direction - Compass direction (0-360)
- wind_speed - Meters per second Beberapa variabel dan observasi dari data asal hilang karena tidak lagi relevant setelah proses wrangling.

Baca lebih lanjut disini: https://www.kaggle.com/competitions/ashrae-energy-prediction/overview
