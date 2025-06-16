markdown
# FatSecret4 MCP Server

## Overview

FatSecret4 is a robust MCP server designed to provide accurate food and nutrition data globally. It serves as a vital tool for developers, nutritionists, dietitians, and organizations looking to integrate detailed nutrition information into their applications, websites, and devices. With over 15 years of industry experience, the platform is utilized by more than 40,000 developers across 56 countries, contributing to over 700 million API calls every month.

## Key Features

- **Comprehensive Database**: Access a curated database of nutritional and calorie data across generic foods, branded products, and restaurant items.
- **Global Reach**: Provides verified local food and nutrition data for 55+ countries and supports 24 languages.
- **Advanced Search Capabilities**: Features high-quality auto-complete search algorithms and barcode scanning capabilities.
- **Extensive Data Coverage**: Offers data on more than 1.9 million food items, ensuring language agnostic results across different regions.
- **Premier Free Tier**: Available for start-ups, non-profits, students, and research organizations, providing unlimited access to the US dataset and premium features with required attribution.

## Authentication

FatSecret4 MCP Server supports multiple authentication methods, including OAuth1.0 and OAuth2.0, to ensure secure access to its tools and data.

## Tools and Usage

FatSecret4 offers a range of tools divided into different groups, mainly focusing on food and recipe data:

### Foods

- **Food Search v1**: Conducts a search in the food database using specified search expressions. Returns detailed nutritional information for the queried food.
- **Food Get**: Retrieves food elements best matching the search expression, ordered by relevancy.
- **Food Autocomplete Search (Premier Only)**: Provides food elements matching the search expression with enhanced relevancy.
- **Find ID For Barcode (Premier Only)**: Returns the food ID matching a specified barcode, supporting various barcode formats.
- **Food Search v2 (Premier Only)**: Similar to Food Search v1 but with additional features for premium users.

### Recipes

- **Recipe Search**: Searches the recipe database using specified search expressions, returning detailed nutritional information, ingredients, and cooking directions.
- **Recipe Get**: Provides detailed information for a specified recipe, including nutrition values for standard servings.

## Localization

FatSecret4 supports extensive localization capabilities, allowing access to more than 55 unique country datasets. By default, the server returns US food data in English, but it can be customized to provide data in different languages and regions.

This MCP server is ideal for developers and organizations aiming to integrate detailed food and nutrition data into their platforms, ensuring a global reach with localized, accurate information.