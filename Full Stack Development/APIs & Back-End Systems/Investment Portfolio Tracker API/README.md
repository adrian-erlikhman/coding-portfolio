# Investment Portfolio Tracker API

## Project Description
Build an API that allows investors to manage their portfolios, track performance over time, and integrate market data feeds. The API will serve as the foundation for web or mobile portfolio tracking applications.

## Technologies and Tools Used
- Python with FastAPI for high performance
- PostgreSQL database accessed via SQLAlchemy
- JWT-based authentication with OAuth support
- Docker for containerized development

## Setup & Installation Steps
1. Clone this repository and navigate to this folder.
2. Install dependencies using `pip install -r requirements.txt`.
3. Copy `.env.example` to `.env` and configure database credentials.
4. Run the application with `uvicorn main:app --reload`.

## Core Features & Functionalities
- Create, update, and delete portfolios and holdings
- Retrieve portfolio valuations and performance metrics
- Secure user registration and authentication
- Optional integration with external market price APIs

## Implementation Roadmap & Milestones
1. Define database schema for users, portfolios, and transactions
2. Implement REST endpoints with FastAPI and JWT auth
3. Add performance calculation utilities and tests
4. Containerize the app with Docker and deploy to the cloud

## Expected Outcome & Results
An easy-to-use API providing portfolio management features that can power a variety of investment tracking clients.

## Suggestions for Extensions & Research
- Real-time price streaming via websockets
- Support for digital assets such as crypto portfolios
- Machine learning to forecast portfolio growth
