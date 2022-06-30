# KesarNET ![](https://img.shields.io/badge/-Live-brightgreen)
![](https://img.shields.io/badge/Collob-Koyo-green) ![](https://img.shields.io/badge/Domain-Blockchain-blue) ![](https://img.shields.io/badge/Focus-Saffron-yellow) <br/>
![](https://img.shields.io/badge/Blockchain-Ethereum-blue) ![](https://img.shields.io/badge/ML-Image_Processing-blue) ![](https://img.shields.io/badge/Storage-IPFS,_IPNS-blue) ![](https://img.shields.io/badge/Security-SecretSharing-blue) ![](https://img.shields.io/badge/Security-QR_Code-blue) ![](https://img.shields.io/badge/Mobile_App-Yes-green)

Blockchain for Saffron Trading

## Parameters

### Saffron

| Parameter | Description | Datatype | Storage | 
|:---------:|:-----------:|:--------:|:-------:|
| saffronID | Unique ID and saffron Details | Mapping | Blockchain |
| sqCertificateID | Saffron Quality Certificate ID | String | Blockchain |
| susCertificateID | Sustainability Certificate ID | String | Blockchain |

### Sustainability Certificate

| Parameter | Description | Datatype | Storage |
|:---------:|:-----------:|:--------:|:-------:|
| susCertist | Sustainability Certificate ID with Certificate Details | Mapping | Blockchain |
| farmid | Farm ID | int | Blockchain |
| farmeraddress | Farmer Wallet Address/DID | address | Blockchain |

### Saffron Quality Certificate

| Parameter | Description | Datatype | Storage |
|:---------:|:-----------:|:--------:|:-------:|
| sqCertList | Saffron Quality Certificate ID with Certificate Details | Mapping | Blockchain |
| farmid | Farm ID | int | Blockchain |
| farmeraddress | Farmer Wallet Address/DID | address | Blockchain |
| batchID | Batch ID | int | Blockchain |
| GICertID | GI Certificate ID | int | Blockchain |
| grade | Grade | int | Blockchain |

### Batch 

| Parameter | Description | Datatype | Storage |
|:---------:|:-----------:|:--------:|:-------:|
| batchList | Batch ID with Details | Mapping | Blockchain |
| pkg_date | Packaging Date | String | Blockchain |
| batchimage | Batch Images |  Photo | IPFS |
| ipfsHashPhoto | IPFS Hash of batchimage | String  | Blockchain| 

### Farmer

| Parameter | Description | Datatype | Storage |
|:---------:|:-----------:|:--------:|:-------:|
| farmerList | Farmer Wallet Address with Farmer Details | Mapping | Blockchain |
| farmername | Farmer Name | String | Blockchain |
| env_pkg_grade | Environmental - Package Grade | String | Blockchain |
| env_pkg_grade_desc | Environmental Package Grade Description | String | Blockchain |
| lat | Farmer's Latitude | string | Blockchain |
| long | Farmer's Longitude | string | Blockchain |
| state | State | string | Blockchain |

### Farm 

| Parameter | Description | Datatype | Storage |
|:---------:|:-----------:|:--------:|:-------:|    
| env_pest | Environmental - Pesticide | String | Blockchain |
| env_pest_desc | Environmental - Pesticide Description | String | Blockchain |
| env_insect | Environmental - Insectide | String | Blockchain |
| env_insect_desc | Environmental - Insectide Description | String | Blockchain |
| env_fung | Environmental - Fungicide | String | Blockchain |
| env_fung_desc | Environmental - Fungicide Description | String | Blockchain |
| env_pH_nearby | Environmental - pH of NearyBy Area | String | Blockchain |
| env_pH_region | Environmental - Reference pH of the Region | String | Blockchain |
| env_pH_desc | Environmental - pH Description | String | Blockchain |
| env_co2_nearby | Environmental - Carbon Dioxide Emission of NearBy Area | String | Blockchain |
| env_co2_region | Environmental - Reference Carbon Dioxide Emission of Region | String | Blockchain |
| env_co2_desc | Environmental - Carbon Dioxide Emission Description | String | Blockchain |
| env_n2_nearby | Environmental - Nitrogen Emission of NearBy Area | String | Blockchain |
| env_n2_region | Environmental - Nitrogen Emission of Region | String | Blockchain |
| env_n2_desc | Environmental - Nitrogen Emission Description | String | Blockchain |
| water_irrigation | Water - Irrigation Type | int | Blockchain |
| water_irrigation_desc | Water - Irrigation Description | String | Blockchain |
| energy_powsrc | Energy - Power Source | int | Blockchain |
| energy_powsrc_desc | Energy - Power Source Description | String | Blockchain |
| gpi_ww | Gender Parity Index - Working Women Payment Status | int | Blockchain |
| gpi_desc | Gender Parity Index - Payment Description | String | Blockchain |

## SDG 

<p align="center">
    <img src="https://ramagururadhakrishnan.github.io/UN-SDG/Assets/G8.png" width="200"/> 
    <img src="https://ramagururadhakrishnan.github.io/UN-SDG/Assets/G9.png" width="200"/> 
    <img src="https://ramagururadhakrishnan.github.io/UN-SDG/Assets/G10.png" width="200"/> 
</p>   

## Publications
TBD
