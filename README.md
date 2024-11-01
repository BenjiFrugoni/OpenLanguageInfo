# 🌍 OpenLanguageInfo: Comprehensive Language Tag Database 🌐

Welcome to OpenLanguageInfo! This project is a comprehensive, curated database of language tags containing rich linguistic data, speaker demographics, and geographical distribution. Built for developers, linguists, and language enthusiasts, this repository provides an extensive look into languages worldwide, including localized information, language families, and RFC 5646-compliant locale tags.

## 📚 Features
  * Detailed Language Profiles: Each language entry includes native speakers (L1) and secondary speakers (L2), up-to-date to the last known census.
  * Country Associations: Know where each language is spoken worldwide, including regions and territories.
  * Locale Tags (With ISO 639-3, 639-2 and RFC 5646): Language codes follow RFC 5646 standards, ensuring compatibility with a wide range of localization systems.
  * Multilingual Language Names: Language names are available in several languages, including:
       * English
       * French
       * Spanish
       * German
       * Russian
       * Chinese
  * Language Family Information: Understand the genealogy of each language with family classifications.
  * Status and Update Information: Includes the year of the last update and total speaker count at that time.

## 🔍 Data Structure

The database is structured to be intuitive and detailed, providing every aspect needed for in-depth linguistic research or robust application development.
Example Language Entry

## 🗂️ Data Fields
```json
"deu": {
        "iso639-3": "deu",
        "iso639-1": "de",
        "iso639-2B": "ger",
        "family": "Indo-European",
        "scope": "Individual",
        "type": "Living",
        "native": "Deutsch",
        "eng": "German",
        "spa": "Alemán",
        "fra": "Allemand",
        "deu": "Deutsch",
        "rus": "Немецкий",
        "zho": "德语",
        "l1": 76000000,
        "l2": 59000000,
        "lastreport": 2019,
        "wikipedia": "https://en.wikipedia.org/wiki/ISO_639:deu",
        "glottolog": "stan1295",
        "linguasphere": "52-ACB–dl",
        "nativeto": "AR|AT|BE|BR|CH|DE|ES|IT|LU|US",
        "locales3": [
            "deu-ar",
            "deu-at",
            "deu-be",
            "deu-br",
            "deu-ch",
            "deu-de",
            "deu-es",
            "deu-it",
            "deu-lu",
            "deu-us"
        ],
        "locales2": [
            "de-ar",
            "de-at",
            "de-be",
            "de-br",
            "de-ch",
            "de-de",
            "de-es",
            "de-it",
            "de-lu",
            "de-us"
        ],
        "rfc5646": [
            "de-ar",
            "de-at",
            "de-be",
            "de-br",
            "de-ch",
            "de-de",
            "de-es",
            "de-it",
            "de-lu",
            "de-us"
        ]
    }
```

## 🛠️ Installation

Clone this repository:

```bash
git clone https://github.com/yourusername/LanguageInfo.git
```
Or add it as a dependency in your project.

## 🚀 Usage

Easily query language data for localization, analytics, or linguistic studies:

   * Localization: Get locale-compliant tags for use in multilingual applications.
   * Linguistic Research: Analyze language families, speaker demographics, and language vitality.
   * Data Analytics: Aggregate speaker data by country or language family.

## 📈 Data Sources & Updates

Data is sourced from linguistic databases, including Wikipedia, Glottolog, SIL, Joshua Project, Ethnologue, ISO 639-3, and the latest censuses. Updates are provided regularly (hopefully by you) to ensure information is accurate and current.

## 🤝 Contributing

We welcome contributions! If you’d like to add languages, update speaker data, or improve localization, please:
  * Fork the repository.
  * Create a new branch.
  * Submit a pull request with detailed comments.

## 🌐 License

This project is licensed under the MIT License.

## 📬 Contact

For questions, feedback, or contributions, please contact us at [benjamin.frugoni@gmail.com].

---

Thank you for exploring OpenLanguageInfo! 🌎 We hope this database empowers your linguistic projects, apps, and research.
