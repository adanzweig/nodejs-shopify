# Shopify Store Management Tool

## Description
This tool is designed to facilitate the management of products in a Shopify store. It allows users to create new products, update inventory levels, retrieve product details, and list all products available in the store. Built using Node.js and the Shopify API Node library, it serves as an efficient way to interact with the Shopify API.

## Features
- Create new products in the Shopify store.
- Update inventory levels for products in specific locations.
- Retrieve detailed information about specific products.
- List all products available in the Shopify store.
- Get a list of all locations associated with the Shopify store.

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/adanzweig/nodejs-shopify.git
   ```
2. Navigate to the project directory:
   ```
   cd nodejs-shopify
   ```
3. Install dependencies:
   ```
   npm install
   ```

## Configuration

Create a `.env` file in the project root and add the following environment variables:
```
SHOP_NAME=your_shop_name
API_KEY=your_api_key
API_SECRET=your_api_secret
```
Replace `your_shop_name`, `your_api_key`, and `your_api_secret` with your Shopify store's details.

## Usage

The script can be run using Node.js. To start the script, use:
```
node index.js
```
Uncomment the specific function calls in the self-invoking function to perform different actions like creating a product, updating stock, etc.

## Contributing
Contributions to improve this tool are welcome. Please fork the repository and submit a pull request with your changes.

## Disclaimer
This tool is not affiliated with Shopify Inc. It uses the Shopify API but is independently developed. Ensure that you comply with Shopify's API terms and conditions while using this tool.
