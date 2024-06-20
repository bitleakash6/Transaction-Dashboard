# 📊 Welcome to the MERN Stack Transaction Dashboard! 🛠️

[**Live**](https://akash-bitle-transaction-dashboard1.onrender.com/) : https://akash-bitle-transaction-dashboard1.onrender.com/

## Objective

This project is a MERN stack application designed to manage and query product transactions fetched from a third-party API. The backend initializes the database with data from the API and provides endpoints for querying and statistics. The frontend displays this data in a table and charts, with functionalities for search, pagination, and filtering by month.


## Tech Stack

**Client:** React.Js, components, Axios

**Server:** Node.Js, Express.Js ,Mongodb, Mongoose, Axios

## Features Implemented

## Backend
### Database Initialization

- Fetch data from a third-party API and seed the MongoDB database.
- Efficient schema design for storing transaction data.

### API Endpoints

**Initialize Database**: Fetch data and initialize the database.
**List Transactions**: List transactions with search and pagination.
**Statistics**: Provide total sale amount, total sold items, and total not sold items for the selected month.
**Bar Chart Data**: Provide price ranges and the number of items in each range for the selected month.
**Pie Chart Data**: Provide unique categories and the number of items in each category for the selected month.
**Combined Data**: Fetch and combine data from all the above APIs and send a final combined JSON response.

## Frontend
**Transaction Table**

- Display transactions for the selected month.
- Support search by title, description, or price.
- Implement pagination.
- Navigate between pages using "Next" and "Previous" buttons.

**Transaction Statistics**

- Display total sale amount, total sold items, and total not sold items for the selected month.

**Bar Chart**
- Display price ranges and the number of items in each range for the selected month.
  
**Pie Chart**

- Display unique categories and the number of items in each category for the selected month.

## Required Software

- Node Js must be installed before running project
- MongoDB compass is helpful for view database collection

## Run Locally

Clone the project

```bash
  git clone https://github.com/bitleakash6/Transaction-Dashboard
```

Move into Project folder

```bash
cd roxiler
```

Move into server and install node dependencies for server side

```bash
cd server
npm i
```

Install react dependencies in client folder

```bash
cd ..
cd client
npm i
```

Run node backend in other shell

```bash
npm start
```

Run react frontend in third shell

```bash
cd ..
cd client
npm start
```

# ScreenShot of Project :

- <img src="https://github.com/bitleakash6/Transaction-Dashboard/blob/main/Images/frontend.png">

- <img src="">


## Authors

- [@AkashBitle](https://github.com/bitleakash6)

## Feedback

If you have any feedback, please reach out to us at akashbitle3@gmail.com
