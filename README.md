# INDIAN SHAPEFILES

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/datta07/INDIAN-SHAPEFILES?style=for-the-badge&logo=github&color=gold)
![GitHub forks](https://img.shields.io/github/forks/datta07/INDIAN-SHAPEFILES?style=for-the-badge&logo=github&color=blue)
![GitHub issues](https://img.shields.io/github/issues/datta07/INDIAN-SHAPEFILES?style=for-the-badge&logo=github&color=red)

**High-quality and accurate GeoJSON files of India's territory**  
*Providing a comprehensive collection of territorial clusters for developers, researchers, and GIS enthusiasts*

</div>

---

## 🎉 Milestone Achieved: 100+ Stars!

<div align="center">

Thank you to everyone who has supported this project! Your interest and contributions motivate me to expand and improve this repository continuously.

<a href="https://www.buymeacoffee.com/akuladatta" target="_blank">
  <img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;" >
</a>

*Consider supporting this project to help maintain and expand the dataset*

</div>

---

## 📂 Repository Contents

This repository provides comprehensive GeoJSON datasets organized into the following categories:

### 🗺️ **National Level Data**
- **Administrative Boundaries**: States, districts, and political constituencies (PC)
- **Infrastructure Networks**: National highways and railway systems
- **Complete Coverage**: Pan-India territorial mapping

### 🏛️ **State Level Data**
- **Hierarchical Boundaries**: State → District → Sub-district mapping
- **Political Divisions**: Constituency boundaries for each state
- **Administrative Centers**: District and sub-district headquarters with precise coordinates

### 🏙️ **Metropolitan Data**
- **Urban Mapping**: Ward and sub-division boundaries
- **Major Cities**: Comprehensive coverage of metropolitan areas
- **Detailed Granularity**: Street-level administrative divisions

---

## 🚀 Roadmap & Upcoming Features

- [ ] **Village Boundaries**: Complete rural administrative mapping

---

## 📋 Technical Specifications

| **Attribute** | **Details** |
|---------------|-------------|
| **Format** | GeoJSON (RFC 7946 compliant) |
| **Projection** | WGS84 (EPSG:4326) |
| **Data Vintage** | Primarily 2019 (with ongoing updates) |
| **Encoding** | UTF-8 |
| **Quality** | High-precision coordinate data |

---

## 🛠️ Usage & Conversion

### Direct Usage
```javascript
// Example: Loading a state boundary
fetch('path/to/state-boundaries.geojson')
  .then(response => response.json())
  .then(data => {
    // Use with Leaflet, Mapbox, or other mapping libraries
  });
```

### Format Conversion
Need other formats? Convert easily using:
- **[Mapshaper](https://mapshaper.org/)** - Web-based converter
- **GDAL/OGR** - Command-line tools
- **QGIS** - Desktop GIS application

---

## ⚠️ Important Notes

> **Data Currency**: Some datasets reflect 2019 administrative boundaries. Recent territorial changes may not be reflected in all files.

> **Accuracy**: While we strive for high accuracy, please verify boundaries for official or legal purposes.

> **Updates**: We continuously work to incorporate the latest administrative changes.

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

- 🐛 **Report Issues**: Found an error? Open an issue
- 📊 **Submit Data**: Have newer boundary data? Share it
- 💡 **Suggest Features**: Ideas for improvement are always welcome
- 🔧 **Code Contributions**: Help improve the repository structure

---

## 📬 Connect & Support

<div align="center">

**Found this useful?** Give it a ⭐ and help others discover this resource!

[![GitHub](https://img.shields.io/badge/GitHub-Follow-black?style=for-the-badge&logo=github)](https://github.com/datta07)
[![Buy Me A Coffee](https://img.shields.io/badge/Buy%20Me%20A%20Coffee-Support-orange?style=for-the-badge&logo=buy-me-a-coffee)](https://www.buymeacoffee.com/akuladatta)

*Your feedback and suggestions drive continuous improvement*

</div>

---

<div align="center">

**🌟 Thank you for being part of this journey! 🌟**

*Building India's most comprehensive open-source GIS dataset, one boundary at a time.*

</div>
