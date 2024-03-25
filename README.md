# Web Scraping for Item Prices

## Description

This script performs web scraping to extract prices of items from various URLs. The prices are fetched from the HTML content of the web pages using BeautifulSoup library in Python.

## Functionality

- The `get_item_price` function takes a URL as input and returns the price of the item found on that URL.
- The script iterates over a list of item URLs and prints the prices of each item.
- It simulates a delay of 4 seconds between each request to avoid overloading the server.

## Item URLs

1. [Yummy Bear - Instant Noodles](https://www.hktvmall.com/hktv/en/main/Yummy-Bear/s/H0956006/%E8%B6%85%E7%B4%9A%E5%B7%BF%E5%A0%B4/%E8%B6%85%E7%B4%9A%E5%B8%82%E5%A0%B4/%E5%8D%B3%E9%A3%9F%E9%BA%B5-%E9%BA%B5-%E6%84%8F%E7%B2%89/%E6%9D%AF%E9%BA%B5/%E6%9D%AF%E9%BA%B5/%E5%85%83%E7%A5%96%E9%9B%9E%E6%B1%81%E6%B3%A1%E9%BA%B5425g-5%E5%8C%85%E8%A3%9D%E5%B9%B3%E8%A1%8C%E9%80%B2%E5%8F%A3%E4%B8%8D%E5%90%8C%E5%8C%85%E8%A3%9D%E9%9A%A8%E6%A9%9F%E5%87%BA/p/H0956006_S_LT10003711)
2. [有機蔬菜動物通粉](https://www.hktvmall.com/hktv/en/main/%E6%9C%89%E6%A9%9F%E8%BE%B2%E7%A4%BE%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8/s/S6061001/%E8%B6%85%E7%B4%9A%E5%B7%BF%E5%A0%B4/%E8%B6%85%E7%B4%9A%E5%B8%82%E5%A0%B4/%E5%8D%B3%E9%A3%9F%E9%BA%B5-%E9%BA%B5-%E6%84%8F%E7%B2%89/%E6%84%8F%E7%B2%89-%E9%80%9A%E5%BF%83%E7%B2%89/%E6%84%8F%E7%B2%89/%E6%9C%89%E6%A9%9F%E8%94%AC%E8%8F%9C%E5%8B%95%E7%89%A9%E9%80%9A%E7%B2%89/p/S6061001_S_92005S)
3. [意大利 - 阿布索 - 煙肉白汁醬](https://www.hktvmall.com/hktv/en/main/%E7%BE%A9%E7%94%9F%E6%B4%8B%E8%A1%8C%E6%9C%89%E9%99%90%E5%85%AC%E5%8F%B8/s/B0424001/%E8%B6%85%E7%B4%9A%E5%B7%BF%E5%A0%B4/%E8%B6%85%E7%B4%9A%E5%B8%82%E5%A0%B4/%E5%8D%B3%E9%A3%9F%E9%BA%B5-%E9%BA%B5-%E6%84%8F%E7%B2%89/%E6%84%8F%E7%B2%89-%E9%80%9A%E5%BF%83%E7%B2%89/%E6%84%8F%E7%B2%89/%E6%84%8F%E5%A4%A7%E5%88%A9-%E9%98%BF%E5%B8%83%E7%B4%A0-%E7%85%99%E8%82%89%E7%99%BD%E6%B1%81%E9%86%AC-270%E5%85%8B-/p/B0424001_S_8009452225384)

## Requirements

- Python 3.x
- BeautifulSoup (bs4)
- urllib

## Usage

- Ensure Python and required libraries are installed.
- Run the script and observe the printed prices of the items.

## Author

Anayed Hossain Eshan

