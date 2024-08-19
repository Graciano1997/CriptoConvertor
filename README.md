# Ether2Dollar

**Ether2Dollar** is a lightweight web application that allows users to convert the value of Ethereum (ETH) to United States Dollars (USD) using real-time market data. The application fetches the latest exchange rate from a cryptocurrency pricing API and performs the conversion instantly.

## Table of Contents
- [Motivation](#Motivation)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [API Integration](#api-integration)
- [Project Structure](#project-structure)
- [Future Enhancements](#future-enhancements)
- [License](#license)
- [Author](#author)

## Motivation

The rapid growth of cryptocurrencies like Ethereum has made it increasingly important for users to easily understand the value of their holdings in traditional fiat currencies like the US Dollar. However, accessing up-to-date exchange rates and performing conversions manually can be time-consuming and error-prone. **Ether2Dollar** was created to simplify this process, providing users with a quick and reliable way to convert Ethereum to USD in real-time.

By offering a straightforward interface and leveraging real-time data, Ether2Dollar aims to make cryptocurrency more accessible to everyone, whether you're a seasoned trader or just starting out. The project was also developed to enhance my skills in Web3.js and cryptocurrency API integration, and to contribute to the growing ecosystem of decentralized finance (DeFi) tools.


## Features

- **Real-time Conversion**: Convert ETH to USD instantly based on live market rates.
- **Simple Interface**: User-friendly interface for easy conversion.
- **Expandable**: Designed to easily add support for other cryptocurrencies and fiat currencies.

## Technologies Used
- **ReactJs**: To create the SPA .
- **Web3.js**: Interface for interacting with Ethereum blockchain.

- **API**: Fetches real-time ETH to USD exchange rates using CoinGecko API.

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed to run the local development server.

## Author

 ## Graciano Henrique
**Email**: gracianomanuelhenrique@email.com

**GitHub**: github.com/yourusername

**LinkedIn**: [Graciano Henrique](https://www.linkedin.com/in/gracianohenrique/)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/Graciano1997/Ether2Dollar.git
   cd Ether2Dollar

## Installation

### Install Dependencies:

``` bash
npm install

## Features

    Enter the amount of Ethereum (ETH) you wish to convert.
    Click the "Convert" button.
    The equivalent value in USD will be displayed instantly.

API Integration

Ether2Dollar fetches the latest ETH to USD exchange rate using the CoinGecko API.

    Endpoint Used:
        https://api.coingecko.com/api/v3/simple/price?ids=ethereum&vs_currencies=usd

This endpoint provides the latest market price of Ethereum in USD.
