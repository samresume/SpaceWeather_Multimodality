# X5.4 Solar Flare Event - March 7, 2012

## Overview
On March 7, 2012, active region **11429** produced an **X5.4 flare** (00:02 UTC), followed by:
- Two fast **Coronal Mass Ejections (CMEs)**:
  - **00:36 UTC** (2200 km/s)
  - **01:25 UTC** (1800 km/s)
- Two high-energy **Solar Energetic Particle (SEP) events**:
  - **01:44 UTC** (13-100 MeV)
  - **04:05 UTC** (>100 MeV)

![Flare Image](https://github.com/samresume/SpaceWeather_Multimodality/blob/main/DONKI.png)

## Google Colab Notebook
This repository includes a **Google Colab Notebook** to help process and analyze data related to this solar flare event.

### 🔗 [Open in Google Colab](https://colab.research.google.com/drive/1uqD5df9b1_sD_mYvG3581aYn43Cc-ps1?usp=sharing)

## Repository Contents
This repository includes the following data sources related to this flare event:

### 1. **SWAN-SF MVTSs (Multivariate Time Series)**
- Data collected and attached as a ZIP archive (**Partition 1**).
- Use these files to extract **24 magnetic field time series** (Bobra’s parameters).
- Steps for processing:
  1. Compute the **average magnetic field** from the time series.
  2. Normalize columns.
  3. Visualize as multivariate time series using Python libraries such as `tsfresh`, `matplotlib`, etc.

### 2. **SDO/AIA and HMI Data**
- **Wavelengths:** 94, 193, 304 Ångström.
- **HMI Vector Magnetogram**: Download from [SDO Data](https://sdo.gsfc.nasa.gov/data/aiahmi/).
- Please provide at least one image for each wavelength that shows the flare clearly.

### 3. **SHARP Magnetic Field Data**
- Relevant data includes **B_x, B_y, B_z**.
- Query and download from:
  - [Github Code](https://github.com/Luchomerenda3/SHARPs/blob/master/hedgehog.ipynb)
  - [SHARP Data Documentation](http://jsoc.stanford.edu/doc/data/hmi/sharp/sharp.htm)
  - [HMI Look Data](http://jsoc.stanford.edu/ajax/lookdata.html)
  - [HMI Record Set Help](http://jsoc.stanford.edu/ajax/RecordSetHelp.html)

### 4. **Solar Wind Data (ACE/WIND)**
- For each day, four .txt files containing solar wind data can be easily downloaded from [SolarSoft](https://sohoftp.nascom.nasa.gov/sdb/goes/ace/daily/).
- Other websites providing real-time solar wind data:
  - [ACE Real-Time Solar Wind](https://www.swpc.noaa.gov/products/ace-real-time-solar-wind)
  - [ACE RTSW Data](https://izw1.caltech.edu/ACE/ASC/rtsw.html)
  - [NOAA SWPC](https://www.swpc.noaa.gov/)

### 5. **Coronagraph Images (SOHO/LASCO & STEREO)**
- One coronagraph image (**Attachment 2**) is included.
- Searching for **higher-resolution images** from SOHO/STEREO.
- Refer to **Paper 1** (attached) for additional imagery.

### 6. **Sunspot Data**
- Data sources:
  - [SpaceWeatherLive Archive](https://www.spaceweatherlive.com/en/archive/2012/03/07/dayobs.html)
  - [NOAA SWPC](https://www.swpc.noaa.gov/)
- Searching for **time series or feature vector data**.

### 7. **Radio Data**
- Refer to **Paper 2** (attached) for initial analysis.
- Potential sources:
  - [NOAA Solar Radio Data](https://www.ncei.noaa.gov/products/space-weather/legacy-data/solar-radio-datasets)
- Searching for **time series or feature vector data**.

### 8. **GOES X-ray, Proton, Electron, and Heavy Ion Data**
- Possible source: [NOAA SWPC](https://www.swpc.noaa.gov/)

## License
This repository is licensed under the **Harvard License**.

## Contribute
If you find better sources or additional data, feel free to submit a pull request.

## Contact
For any questions or collaborations, feel free to open an issue or contact me at **sameskandarinasab@gmail.com**.

---
*Note:
