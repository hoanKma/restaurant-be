# Restaurant Backend

This project is the backend for a restaurant application built with Node.js, TRPC, Prisma, and PostgreSQL.

## Getting Started

### Prerequisites

- Node.js (v18 or higher)
- PostgreSQL
- Yarn

### Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd restaurant-backend

   ```

2. Install dependencies:

   yarn install

3. Set up your .env file with the necessary database credentials:

   DATABASE_URL=postgresql://USER:PASSWORD@HOST:PORT/DATABASE

4. Run the Prisma migrations:

   yarn prisma migrate dev

5. Seed the database

   yarn prisma db seed

--> To start the server, run: yarn dev

API Endpoints

GET /trpc/getRestaurants: Retrieves all restaurants.
POST /trpc/addFavorite: Marks a restaurant as a favorite.
