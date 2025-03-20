**Cloning the TRMS Project and Running Locally**

### `git clone https://github.com/Raju7250/TRMS.git`
### `cd TRMS`

**Look at the files and folders of the project**
**Delete the `node_modules` folder and `package-lock.json` file if they exist**

**Run the following commands**
### `npm install`
This will create the `node_modules` folder and `package-lock.json` file.

### `npm start`
This will start your React app.

Now go to http://localhost:3000/ to visit your app.

### Setting up MongoDB
Visit `mongodb://localhost:27017/User` in MongoDB Compass.

Create an admin entry in the database to log in to the portal using the following credentials:
```json
{
    "usertype": "admin",
    "loginid": "admin123",
    "password": "password123"
}
```

**Description**
TRMS

TRMS website is made with a motive to reduce the paperwork required to book auditoriums and other activity rooms in colleges. One can book a room, view their bookings, and cancel their bookings as per their comfort.
There would be two categories of users:

1. User

2. Admin

Options for Admin:

1. Create new IDs

2. Delete any ID

3. Book a room

4. View all bookings of all users specific to a room or date, etc.

5. View his/her bookings

6. Cancel booking

Options for User:

1. Book a room

2. View bookings

3. Cancel booking

While booking a room, a user would be required to enter the details regarding their requirements, date and time of booking, and purpose of booking. Then they would be shown blocks and buildings where such rooms are available. On selecting the blocks, they can select the room number and get a confirmation about room booking. A similar procedure would be followed for other tasks.
