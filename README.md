# AMZIMG

Amazon product listing image hosting repository.

## Image Structure

Each product uses one folder:
Product SKU
│
├── 01-main.jpg
├── 02.jpg
├── 03.jpg
├── 04.jpg
├── 05.jpg
├── 06.jpg
├── 07.jpg
├── 08.jpg/png
└── sample.jpg/png

## Image Naming Rules

- 01-main.jpg = Amazon Main Image
- 02-08 = Amazon Alternate Images
- sample = Product Sample Image

## Raw Image URL Format
```
https://raw.githubusercontent.com/chosenfate/AMZIMG/refs/heads/main/{SKU}/{image-name}
```
