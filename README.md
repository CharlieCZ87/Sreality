# 🏠 Sreality.cz Scraper

Czech real estate scraper that sorts apartments by price per m² from cheapest to most expensive.

## 🚀 **Live Demo**

Visit: **[Your GitHub Pages URL will be here]**

## 📋 **What It Does**

- **Scrapes** apartment listings from Sreality.cz
- **Calculates** price per m² for each property
- **Sorts** listings from cheapest to most expensive per m²
- **Exports** results to CSV file with direct links

## 🎯 **Why This Tool**

Sreality.cz doesn't allow sorting by price per m² - only by total price. This tool solves that limitation by:

1. Extracting all property data automatically
2. Computing price per m² for each listing
3. Providing sorted results in an easy-to-use format

## 💻 **How to Use**

1. **Enter a Sreality.cz URL** (e.g., `https://www.sreality.cz/hledani/prodej/byty/brno`)
2. **Click "Scrapovat"** and wait 60-90 seconds
3. **Download** the CSV file with sorted results

## 🔧 **Technical Stack**

- **Frontend**: Vanilla HTML/CSS/JavaScript
- **Backend**: N8N workflow automation
- **Scraping**: Apify web scraper
- **Hosting**: GitHub Pages

## 📊 **CSV Output Columns**

| Column | Description |
|--------|-------------|
| Pořadí | Ranking by price per m² |
| Adresa | Property address |
| Cena (Kč) | Total price in Czech crowns |
| Plocha (m²) | Property size |
| Cena za m² (Kč) | Price per square meter |
| Typ | Apartment type (1+1, 2+1, etc.) |
| Patro | Floor information |
| Odkaz | Direct link to original listing |
| Obrázek | Property image URL |

## 🌟 **Features**

- ✅ **Real-time processing** - Live status updates
- ✅ **Mobile responsive** - Works on all devices
- ✅ **Czech language** - Fully localized interface
- ✅ **Error handling** - Graceful failure recovery
- ✅ **Data validation** - Filters incomplete listings
- ✅ **Direct links** - Click through to original listings

## 🏙️ **Supported Cities**

Currently supports all Czech cities available on Sreality.cz:
- Praha (Prague)
- Brno
- Ostrava
- Plzeň
- And many more...

## 🚦 **Usage Examples**

```
# Brno apartments
https://www.sreality.cz/hledani/prodej/byty/brno

# Prague apartments with filters
https://www.sreality.cz/hledani/prodej/byty/praha?velikost=2%2Bkk

# Ostrava houses
https://www.sreality.cz/hledani/prodej/domy/ostrava
```

## ⚖️ **Legal Notice**

This tool is for educational and research purposes. Please respect:
- Sreality.cz Terms of Service
- Rate limiting (don't overload their servers)
- Use data responsibly for legitimate real estate research

## 🐛 **Issues & Support**

If you encounter any problems:
1. Check that your URL is from Sreality.cz
2. Verify the URL returns search results on the website
3. Try again in a few minutes (rate limiting)
4. Open an issue on GitHub if problems persist

## 📈 **Future Enhancements**

- [ ] Multi-city batch processing
- [ ] Price change tracking over time
- [ ] Advanced filtering options
- [ ] Email alerts for new cheap properties
- [ ] Mobile app version

## 🤝 **Contributing**

Contributions welcome! Please feel free to submit pull requests or open issues.

## 📄 **License**

MIT License - feel free to use and modify for your own projects.

---

**Made with ❤️ for Czech real estate professionals**
